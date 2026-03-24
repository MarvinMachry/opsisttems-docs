# Visualizador de Lote

## Descrição
*Data de edição: 03/05/2023*

Descrição do módulo **Visualizador de Lote**.

!!! info "Funcionamento do módulo"

    ### Ordenação dos itens
    O visualizador mostra os itens em ordem de **maior necessidade**, utilizando o campo **Saldo**.

    Ou seja, itens com **saldo menor aparecem primeiro**, indicando maior urgência de produção ou reposição.

    ### Saldo Atual
    Representa a conta:

    **Estoque (NOG + CAS)  
    + Produtos ainda não montados  
    - Itens da Programação  
    - Itens sem lote no Promob**

    ### Pedido de Reposição
    Representa a média entre:

    - Média dos **últimos 3 meses**
    - Média dos **3 meses à frente do mesmo período do ano passado**

    ### Tempo de Reposição
    Tempo necessário para concluir um lote completo do produto entre:

    - **Corte**
    - **CNC**

    ### Média Mensal
    Média da soma dos últimos meses, considerando a **margem selecionada**.

    ### Estoque Mínimo
    Representa a conta:

    `(Média de dias corridos do produto / (30 × margem)) × (soma das médias)`

    ### Ponto de Reposição
    Representa a conta:

    `(soma das médias × (dias corridos / 30)) + estoque mínimo`

    ### Previsão de Pedido
    Data estimada em que será necessário **gerar um novo lote** do produto.

    ### Previsão Emin
    Data estimada em que o **estoque atingirá o mínimo permitido**.

    ### Remoção de itens fora de linha
    Para remover itens da visualização, acessar o módulo **Ficha Filial** e marcar o item como fora de linha.

    ### Origem do nome dos itens
    O nome dos produtos vem das tabelas:

    - **TEMPOS → campo "CONTROLE ESTOQUE"**
    - **CONTROLE_ESTOQUE → campo "PRODUTO"**

---

## Legenda de Status

!!! warning "Cores de status do estoque"

    **🔴 Vermelho**

    Estoque **Nogueira ≤ Estoque Mínimo**

    **🟡 Amarelo**

    Estoque **Nogueira ≤ (Ponto de Reposição × 1,2)**

    **🔵 Azul**

    Estoque **Nogueira > (Ponto de Reposição × 1,2)**

---

## Funcionalidades
*Data de edição: 03/05/2023*

!!! tip "Ações do módulo"

    ### 2 cliques no campo Status

    Permite adicionar um **novo lote** para o produto.

    Existem duas formas:

    **Automática**
    - Utiliza os valores sugeridos pelo sistema.

    **Manual**
    - Permite definir manualmente:
        - tamanho do lote
        - data do lote

    ### Botão Atualizar

    Atualiza completamente o módulo:

    1. Remove as informações existentes
    2. Reconsulta os dados atualizados do banco

    Após isso, o sistema calcula o campo **"Atende Até"**.

    O cálculo funciona da seguinte forma:

    - Obtém o estoque **Nogueira** do item
    - Percorre a tabela **programacao**
    - Vai descontando a quantidade necessária
    - Quando o saldo fica **negativo**, a consulta para
    - A data daquele ponto é salva como **"Atende Até"**
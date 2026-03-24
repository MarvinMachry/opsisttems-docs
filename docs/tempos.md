# Tempos de Processo

## Descrição
*Data de edição: 07/08/2025*

Descrição da utilização do módulo **Tempos**.

!!! info "Regras e funcionamento do módulo"

    ### Criação automática do controle de estoque
    Ao criar um produto novo, após a inserção, o campo **CONTROLE ESTOQUE** será preenchido automaticamente utilizando apenas a **parte numérica do código do produto**.

    Caso seja necessário alterar, primeiro insira o item e depois realize a edição manual.

    ### Nome Utilitário
    O campo **NOME UTILITÁRIO** é utilizado para **impressão de etiquetas**.

    ### Controle Estoque
    O campo **CONTROLE ESTOQUE** é utilizado para:

    - Verificar nomes de itens para inserção no estoque
    - Acrescentar novos itens ao controle de estoque

    ### Marcação de tempos genéricos
    Ao dar **duplo clique no campo Descrição** com usuário **admin**, o campo será pintado de **amarelo**.

    Isso indica que o produto possui **dados genéricos de tempos**.

    ### Campo Ativo
    O campo **Ativo** define se o produto aparecerá na consulta do **Visualizador de Lotes**.

    - Marcado → produto aparece
    - Desmarcado → produto oculto

    *(PCP / Admin)*


---

## Funcionalidades

!!! tip "Botões do módulo"

    ### Liberar
    Libera a tabela para:

    - edição
    - exclusão
    - inclusão de registros

    O botão possui indicador visual:

    - 🔴 Círculo vermelho → tabela bloqueada  
    - 🟢 Círculo verde → tabela liberada

    Esse botão aparece somente para **Admin e Leonardo**.

    ### Salva Histórico
    Salva o estado atual da tabela **Tempos** em uma tabela de **histórico**, utilizando a data atual do sistema.

    Caso já exista registro para aquela data, o sistema exibirá um aviso informando que o registro já foi criado.

    ### Auditoria
    Abre o módulo de **histórico de alterações** da tabela **Tempos**.

    ### Gerar
    Gera um arquivo contendo todos os registros da tabela **Tempos**.

    O arquivo será criado em:

    `C:\Tempos de processo.xls`


---

# Cadastro de Itens

## Cadastro de itens - Matriz
*Data de edição: 14/04/2023*

!!! example "Processo de cadastro"

    1. Criar componentes na **Ficha Técnica**
    
    2. Criar cadastro do item no formulário **Tempos**

       Exemplo:

       - CADXXX CADEIRA LUNA TEX  
       - CADXXX CADEIRA LUNA LEE

    3. Criar cadastro do item no formulário **Componentes**

       Exemplo:

       - CADXXX CADEIRA LUNA TEX  
       - CADXXX CADEIRA LUNA LEE

    4. Criar cadastro no formulário **TemposCNC**

    5. Criar cadastro do item no formulário **Ficha Técnica Filial**

    6. Adicionar item no formulário **Controle Estoque**

    7. Adicionar ou remover **Assento** ou **Encosto**

    8. No módulo **Ficha Técnica**, marcar o campo **Filial**  
       para que o produto saia do corte e seja enviado ao **Registro Filial**.


---

## Cadastro de itens - Filial

!!! example "Processo de cadastro"

    1. Criar cadastro do item na **Ficha Técnica Filial**

    2. Criar cadastro do item no formulário **Tempos**

       Exemplo:

       - MESA TALES 200X110

    3. Criar cadastro do item no formulário **Componentes**

       Exemplo:

       - MESA TALES 200X110

    4. Criar componentes na **Ficha Técnica**

       O nome deve ser **igual ao utilizado no módulo Tempos → ITEM ESTOQUE FILIAL**.

    5. Criar cadastro no formulário **TemposCNC**
# Corte Filial

## Funcionalidades
*Data de edição: 12/03/2026*

Descrição da utilização do módulo **Corte Filial**.

!!! tip "Botões do módulo"

    ### Criar
    Abre o módulo para criar um **pedido de corte**.

    ### ~~Ad. Corte~~
    (Função descontinuada)  
    Adicionava os itens selecionados à lista **"pronto para gerar corte certo"**.

    ### ~~Gerar~~
    (Função descontinuada)  
    Gerava o arquivo para o **Corte Certo**.

    ### Concluir
    Conclui apenas o **produto em foco**, removendo-o da lista.

    ### Excluir esquerdo
    Exclui o **item em foco** com um clique.

    ### Voltar
    Retorna uma etapa na sequência.  
    Funciona apenas para itens com **flag marcada** e **componentes não concluídos**.

    ### Avançar
    Avança uma etapa na sequência.  
    Funciona apenas para itens com **flag marcada** e **componentes não concluídos**.

    ### Marcar / Desmarcar
    Inverte a seleção atual dos componentes.  
    Se estiver marcado, **desmarca**, e vice-versa.

    ### IMP. PEÇAS
    Abre as etiquetas como **PEÇAS** e marca o item como **impresso** na lista e na programação.

    ### IMP. MONTAGEM
    Abre as etiquetas como **MONTAGEM** e marca o item como **impresso** na lista.

    ### Etiq. Cad
    Abre etiquetas de componentes da **cadeira**, selecionados pelo campo de seleção.

    ### Concluídos
    Abre o módulo de **itens concluídos**.

    ### Excluir direito
    Exclui os **componentes selecionados**.

    ### Chaparia
    Abre um módulo para consulta de **chaparia por data limite**.


---

## Regras e Observações
*Data de edição: 03/07/2025*

!!! warning "Regras do módulo"

    ### Itens criados manualmente
    Itens gerados manualmente **não funcionam** nos botões **Avançar** e **Voltar**.

    ### Limite da consulta
    A consulta mostra apenas componentes com:

    `Data > (DataAtual - 50 dias)`


---

## Regras para geração de lotes de chaparia

!!! info "Condições para gerar lotes"

    - A **categoria** deve ser diferente de **88 (UNIFICADA)**.
    - A coluna **Ativo** deve estar **desmarcada**.
    - A **unidade** deve ser **FILIAL**.
    - O **material** deve iniciar com o código **MP02**.
    - O **item** deve iniciar com o código **CAD**.
    - Os itens **PUFF**, **BANCO** e **CHAISE** **não geram lotes**.

    ### Nome dos itens

    Os itens são nomeados usando o campo:

    `item_estoque` do módulo **Tempos**.

    O campo **nome_generico** é utilizado para o **controle de estoque** do item.
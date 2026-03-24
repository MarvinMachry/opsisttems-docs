# Manutenção

## Funcionalidades
*Data de edição: 12/03/2026*

Descrição da utilização do módulo **Manutenção**.

!!! tip "Botões do módulo"

    ### Novo
    Adiciona uma nova linha em branco para criação de um **novo registro de manutenção**.

    ### Manutentor
    Permite inserir **uma lista de manutentores** dentro de um único registro.  
    Deve ser utilizado **após a inserção da manutenção**.

    ### Histórico
    Abre o módulo contendo o **histórico das manutenções registradas**.

    ### Excluir
    Exclui a **linha atualmente selecionada**.

    ### Start
    Inicia a manutenção.

    O sistema:
    - Marca o registro como **INICIADO**
    - Abre o módulo para inserir os **manutentores que irão trabalhar**

    ### Pause
    Pausa a manutenção.

    O sistema:
    - Marca o registro como **PARADO**
    - Abre o módulo para registrar os **manutentores que interromperam o trabalho**

    Esse botão só funciona se a tarefa **já estiver iniciada**.

    ### Concluir
    Abre o módulo para **conclusão da tarefa**.

    Os manutentores restantes (que não foram registrados em **Pause**) serão **adicionados automaticamente** ao encerramento.


---

## Regras e Observações
*Data de edição: 13/03/2026*

!!! warning "Regras de utilização"

    ### Inserção de manutentores
    A inserção de manutentores **só pode ser feita em registros já existentes**.

    Sempre verifique se **o símbolo de lápis NÃO está aparecendo no canto esquerdo da linha**,  
    pois isso indica que o registro ainda está em edição.

    ### Uso do Pause
    O botão **Pause** só pode ser utilizado se existir **algum registro de Start ativo**.

---

## Ordenação da lista

!!! info "Critério de ordenação"

    A lista de manutenções é ordenada da seguinte forma:

    1. **Status (estado_atual)**
    2. **Ordem**
    3. **Prioridade (status)**
    4. **Data da Solicitação**
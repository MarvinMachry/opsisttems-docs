# Programação PCP Simplificada

## Descrição
*Data de edição: 03/05/2023*

Descrição do módulo **Programação PCP Simplificada**.

!!! info "Campos e cálculos do módulo"

    ### Valor Total / Qtd Total / Dias Úteis
    Baseados em valores a partir do **dia atual**, utilizados para estimar a quantidade de produção existente à frente.

    ### Qtde Disp. Matriz
    Quantidade disponível separada por dia.

    O cálculo é feito da seguinte forma:

    **Quantidade estimada de produção - Quantidade solicitada**

    A quantidade estimada de produção é derivada da:

    - Quantidade de funcionários no setor **ESTOFARIA**
    - Subtraindo a soma dos **tempos dos itens**

    ### Qtde Disp. Filial
    Quantidade disponível separada por dia.

    O cálculo é feito da seguinte forma:

    **Quantidade configurada no campo numérico sublinhado - Quantidade solicitada**

    ### Saldo
    Representa a quantidade considerando:

    - itens **atrasados**
    - soma do saldo atual

    O cálculo sempre parte **do dia atual em diante**.

    ### Campo numérico sublinhado
    Permite alterar manualmente a **meta de produção por unidade**.

    Esse campo também é utilizado para **colorir a coluna Qtde**, auxiliando na visualização da programação.


---

## Funcionalidades
*Data de edição: 03/05/2023*

Descrição das funcionalidades do módulo.

!!! tip "Botões do módulo"

    ### Atualizar
    Atualiza as tabelas do módulo.

    O processo:
    - Exclui os dados existentes
    - Reconsulta os dados no banco de dados
    - Recarrega a programação atualizada

    ### Rel. p/ Data
    Abre um relatório utilizado pelo **PCP** para confirmar as **datas dos pedidos que ainda não possuem lote no Promob**.
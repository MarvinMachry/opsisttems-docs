# Ficha Técnica

## Descrição
*Data de edição: 05/12/2025*

Descrição do módulo **Ficha Técnica** e regras de utilização.

!!! warning "Regras de geração de lotes"

    ### Itens que não devem gerar lotes

    - Itens marcados como **Controle = FILIAL** não devem ser incluídos na geração de lotes.
    - Alguns itens, como **APOIO KIM**, podem possuir sequência de pé mesmo sem Controle MATRIZ, permitindo gerar lote futuramente para operação no torno.
    - Para organização, o **pé do APOIO KIM não deve possuir controle de estoque**, sendo o controle realizado pelo **tampo**.
    - A **MESA MILA** será controlada pela **MATRIZ**, pois seus lotes de torno são gerados em outra cidade.


---

## Regras de funcionamento

!!! info "Campos e comportamentos do sistema"

    ### Tempo de Máquina
    Ao dar **duplo clique na descrição do componente**, caso a máquina possua **“não” no campo Acabamento**,  
    a conclusão de itens no **centro de usinagem** contendo **ASSENTO** ou **ENCOSTO** irá adicionar automaticamente a quantidade correspondente ao estoque.

    ### Categoria – UNIFICADA_VA
    Utilizado para itens compostos por **mais de um componente**.  
    Esses itens **não serão enviados ao Corte Filial** ao gerar lote.

    ### Categoria – UNIFICADA_ML
    Utilizado para itens compostos por **mais de um componente**.  
    Esses itens **não irão para a Programação Matriz** ao gerar lote.

    ### Campo Unidade
    Se **FILIAL** não estiver marcado, o item **não participará do controle de estoque** via Registro MATRIZ → FILIAL.

    Caso o campo esteja vazio, ao concluir no corte o item **não será enviado ao estoque**.

    ### Campo Controle nos componentes
    Indica se o item deve ou não ir para o **corte via Análise PCP**.

    Se estiver vazio, o item **não irá para o corte**, servindo como filtro de controle do fluxo produtivo.

    ### Controle = FILIAL
    Itens que possuem **chaparia** e dependem de lotes gerados pelo **Gerador de Chaparia** serão enviados para o **Corte Filial**.


---

## Regras para itens M.L.

!!! info "Itens genéricos (prefixo M.L.)"

    ### Identificação
    IDs com prefixo **M.L.** representam itens genéricos **cortados exclusivamente na matriz**,  
    que não passam por outros processos e são controlados pelo **Almoxarifado**.

    Todos os componentes **M.L.** devem permanecer agrupados dentro do mesmo item.

    ### Nome do item
    O nome do item e do componente deve seguir o formato:

    `APARADOR THEO - SARRAFO`

    Ou seja, **nome principal + componente**, separados por **“-”**.

    ### Usinagem
    Caso exista peça de **centro de usinagem**, desmarcar o campo **Somente Corte**.

    O nome antes do hífen deve coincidir com o cadastro na tabela **temposCNC**.

    ### Restrições
    O nome do item **não pode conter**:

    - `\`
    - `/`

    pois isso impede a busca correta no sistema.


---

## Regras gerais do módulo

!!! info "Campos e comportamentos"

    ### Seleção de Status
    Inativa o item, removendo-o da ficha técnica.  
    Ele permanecerá acessível apenas pela opção **Inativos**.

    ### Dimensões
    Devem ser preenchidas **somente com números** ou no formato:

    `45X21`

    Não é permitido inserir **apenas texto** nesses campos.

    ### Controle de estoque
    Para que o item seja controlado corretamente ao gerar lotes,  
    o nome da **Ficha Técnica deve ser diferente** do nome utilizado nas tabelas **Tempos** e **Controle de Estoque**.

    Exemplo:

    Ficha Técnica  
    `BISTRO MILA REDONDA 80`

    Tempos / Controle  
    `BISTRO MILA 80`

    ### É Par
    Quando marcado, o item passa a contabilizar **dois lados distintos** no **Estoque Montagem**.

    ### Conta Estoque
    Quando marcado, o item fica disponível para inserção e será contabilizado no **Estoque Montagem**.

    ### Geração de lotes com chaparia
    Quando o item possuir **chapas**, o lote enviado ao **Corte Filial** passa a utilizar o **nome da Ficha Técnica**.

    Exemplo:

    `APOIO LURI`

    Isso evita acréscimos indevidos ao estoque após a conclusão.


---

## Funcionalidades
*Data de edição: 26/06/2025*

Descrição da utilização dos botões do módulo **Ficha Técnica**.

!!! tip "Botões do módulo"

    ### Gerar Lote
    Gera um lote para o **PCP**.

    Caso a seleção **Somente Corte** esteja marcada, gera lote **apenas para corte**.

    ### Desmarcar
    Desmarca todos os componentes marcados.  
    A consulta é realizada na **tabela inteira**, independentemente do filtro aplicado.

    ### Registrar
    Insere o item manualmente no **Registro MATRIZ → FILIAL**.

    Utilizado principalmente no produto **MILA**.

    ### Add. Material
    Abre o módulo para adicionar **novos materiais**.

    ### Add. Categoria
    Abre o módulo para adicionar **categorias**.

    ### Add. Embalagem
    Abre o módulo para adicionar **tipos de embalagem**.

    ### Inativos
    Abre o módulo que mostra os **produtos inativos**, permitindo reativá-los.

    ### Excluir
    Exclui o **produto em foco**.

    ### Importar
    Importa os componentes através de um arquivo:

    `C:\Ficha.xls`

    ### Sequência
    Abre o módulo para **copiar sequência** para o item em foco.

    ### Duplicar
    Duplica o produto, solicitando um **novo nome**.

    ### Rel. Est. Filial
    Abre relatório de componentes com **controle de estoque**, produzidos na **Matriz**.
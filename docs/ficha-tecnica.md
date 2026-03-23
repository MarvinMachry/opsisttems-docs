
<body>
    <div class="container">
        <h1>Ficha Técnica</h1>
        <ul class="version-list">
            <li>
                <div>
                    <strong class="version">Descrição</strong>
                    <span class="date">Data de edição: 05/12/2025</span>
                    <p><b>Descrição do módulo e regras de utilização.</b></p>

                    <ul>

                        <li><b>Itens que não devem gerar lotes:</b><br>
                            - Itens marcados como Controle “FILIAL” não devem ser incluídos na geração de lotes.<br>
                            - Alguns itens, como o “APOIO KIM”, podem ter sequência de pé mesmo sem Controle MATRIZ, permitindo gerar lote futuramente para operação no torno.<br>
                            - Para organização, o pé do APOIO KIM não deve ter controle de estoque; o controle deve ser feito pelo tampo.<br>
                            - A MESA MILA será controlada pela MATRIZ, pois seus lotes de torno são gerados em outra cidade.
                        </li>

                        <li><b>Tempo de Máquina:</b> Ao dar dois cliques na descrição do componente, caso a máquina possua “não” no campo *Acabamento*, a conclusão de itens no centro de usinagem contendo ASSENTO ou ENCOSTO irá adicionar automaticamente a quantidade correspondente ao estoque.</li>

                        <li><b>Campo Categoria – UNIFICADA_VA:</b> Usado para itens compostos por mais de um componente. Esses itens não serão enviados ao Corte Filial ao gerar lote.</li>

                        <li><b>Campo Categoria – UNIFICADA_ML:</b> Usado para itens compostos por mais de um componente. Esses itens não irão para a Programação Matriz ao gerar lote.</li>

                        <li><b>Campo Unidade:</b> Se FILIAL não estiver marcado, o item não participará do controle de estoque via Registro MATRIZ → FILIAL.  
                            Caso o campo esteja vazio, ao concluir no corte o item **não** será enviado ao estoque. (Admin – PCP)
                        </li>

                        <li><b>Campo Controle nos componentes:</b> Indica se o item deve ou não ir para o corte via Análise PCP.  
                            Se estiver vazio, o item **não irá para o corte**, servindo como filtro de controle do fluxo produtivo.</li>

                        <li><b>Campo Controle = FILIAL:</b> Itens que possuem chaparia e dependem de lotes gerados pelo Gerador de Chaparia serão enviados para o Corte Filial.</li>

                        <li><b>ID com prefixo M.L.:</b> Representam itens “genéricos” (M.L-) cortados exclusivamente na matriz e que não passam por outros processos, sendo armazenados e controlados pelo Almoxarifado. Todos os componentes M.L- devem permanecer dentro deste mesmo item agrupador.</li>

                        <li><b>ID com prefixo M.L. – Nome do item:</b> O nome do item e do componente devem estar na descrição no formato:<br>
                            <code>“APARADOR THEO - SARRAFO”</code><br>
                            Ou seja, o nome principal seguido do componente, separados por “-”.
                        </li>

                        <li><b>ID com prefixo M.L. – Usinagem:</b> Caso exista peça de centro de usinagem, desmarcar o campo “Somente Corte”.  
                            O nome antes do hífen (“-”) deve coincidir com o cadastrado em <b>temposCNC</b>. (Admin – PCP)
                        </li>

                        <li><b>ID com prefixo M.L. – Restrições:</b> Os itens não podem conter “\” ou “/” no nome, pois isso impede a busca correta. (Admin – PCP)</li>

                        <li><b>Seleção de Status:</b> Inativa o item, removendo-o da ficha técnica. Ele permanecerá acessível apenas pela opção “Inativos”.</li>

                        <li><b>Dimensões:</b> Devem ser preenchidas apenas com valores numéricos ou com um formato contendo “X”, como “45X21”.  
                            Não é permitido inserir somente texto nesses campos. (Admin – Todos)
                        </li>

                        <li><b>Estoque:</b> Para que o item seja controlado corretamente ao gerar lotes, o nome na ficha técnica deve ser diferente do nome utilizado na tabela Tempos e no Controle de Estoque.  
                            Exemplo:<br>
                            Ficha Técnica: <code>“BISTRO MILA REDONDA 80”</code><br>
                            Tempos/Controle: <code>“BISTRO MILA 80”</code><br>
                            (Todos)
                        </li>

                        <li><b>É Par:</b> Quando marcado, o item passa a contabilizar dois lados distintos no Estoque Montagem. (Admin – Todos)</li>

                        <li><b>Conta Estoque:</b> Quando marcado, o item fica disponível para inserção e será contabilizado no Estoque Montagem. (Admin – Todos)</li>

                        <li><b>Ao gerar lotes:</b> Agora, quando o item possuir CHAPAS, o lote enviado ao Corte Filial utiliza o nome da FICHA, e não mais o nome do TEMPOS.  
                            Exemplo: APOIO LURI — ao gerar lote, o nome da FICHA será usado, impedindo acréscimo indevido ao estoque após a conclusão.
                        </li>

                    </ul>
                </div>
            </li>

            <li>
                <div>
                    <strong class="version">Funcionalidades</strong>
                    <span class="date">Data de edição: 26/06/2025</span>
                    <p><b>Descrição da utilização do módulo Programação.</b></p>
                    <ul>
                      <li><b>Botão Gerar Lote:</b> Gera um lote para o PCP caso a seleção "Somente Corte" estiver desmarcada, gera um lote somente para corte se estiver com a seleção marcada.</li>
                      <li><b>Botão Desmarcar:</b> Desmarca todos os componentes ja marcados, faz a consulta na tabela inteira, independente do filtro aplicado.</li>
                      <li><b>Botão Registrar:</b> Insere o item manualmente no Registro de itens entre MATRIZ -> FILIAL, utilizado no produto MILA.</li>
                      <li><b>Botão Add. Material:</b> Abre módulo para acrescentar materiais.</li>
                      <li><b>Botão Add. Categ.:</b> Abre módulo para acrescentar categorias.</li>
                      <li><b>Botão Add. Embalagem:</b> Abre módulo para acrescentar tipos de embalagens.</li>
                      <li><b>Botão Inativos:</b> Abre módulo que mostra os produtos inativos, podendo reativá-los.</li>
                      <li><b>Botão Excluir:</b> Exclui o produto em foco.</li>
                      <li><b>Botão Importar:</b> Importa os componentes atravéz de um arquivo .xls no disco local C:\Ficha.xls.</li>
                      <li><b>Botão Sequência:</b> Abre modulo para a copia de sequencia para o item em foco.</li>
                      <li><b>Botão Duplicar:</b> Irá duplicar o produto, pedindo um novo nome.</li>
                      <li><b>Botão Rel. Est. Filial:</b> Abre relatório de componentes de itens com controle de estoque, produzidos na MATRIZ.</li>
                    </ul>
                </div>
            </li>
        </ul>
    </div>
</body>

    
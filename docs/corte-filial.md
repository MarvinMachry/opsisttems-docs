
<body>
    <div class="container">
        <h1>Corte Filial</h1>
        <ul class="version-list">
            <li>
                <div>
                    <strong class="version">Funcionalidades</strong>
                    <span class="date">Data de edição: 12/03/2026</span>
                    <p><b>Descrição da utilização do módulo Corte Filial.</b></p>
                    <ul>
                      <li><b>Botão Criar:</b> Abre modulo para criar um pedido de corte.</li>
                      <li><b><del>Botão Ad.Corte:</del></b> Adiciona os itens selecionados na lista para adiciona-lo a lista de "pronto para gerar corte certo".</li>
                      <li><b><del>Botão Gerar:</del></b> Gera o arquivo para o corte certo.</li>
                      <li><b>Botão Concluir:</b> Conclui apenas o produto em foco. Fazendo-o sair da lista.</li>
                      <li><b>Botão Excluir esquerdo:</b> Exclui o item em foco com click.</li>
                      <li><b>Botão Voltar:</b> Volta uma etapa na sequência, apenas itens com 'flag' marcada e somente componentes não concluídos.</li>
                      <li><b>Botão Avançar:</b> Avança uma etapa na sequência, apenas itens com 'flag' marcada e somente componentes não concluídos.</li>
                      <li><b>Botão Marcar/Desm.:</b> Inverte a seleção atual dos componentes, ou seja, se estiver marcado ele desmarca e vice-versa.</li>
                      <li><b>Botão IMP. PEÇAS:</b> Abre as etiquetas como PEÇAS e marca como impresso na lista e na programação.</li>
                      <li><b>Botão IMP. MONTAGEM:</b> Abre as etiquetas como MONTAGEM e marca como impresso na lista.</li>
                      <li><b>Botão Etiq.Cad:</b> Abre etiquetas de componentes da cadeira, selecionados pelo campo de seleção.</li>
                      <li><b>Botão Concluidos:</b> Abre modulo de itens concluidos.</li>
                      <li><b>Botão Excluir direito:</b> Exclui componentes selecionados com click.</li>
                      <li><b>Botão Chaparia:</b> Abre um módulo para consulta de chaparia por data limite.</li>
                    </ul>
                </div>
            </li>
            <li>
                <div>
                    <strong class="version">Dúvidas</strong>
                    <span class="date">Data de edição: 03/07/2025</span>
                    <p><b>Descrição da utilização do módulo Corte Filial.</b></p>
                    <ul>
                        <li><b>Itens que foram gerados manualmente, não funcionarão nos botões Avançar e Voltar. </b> </li>
                        <li><b>Consulta mostra somente componentes com a data > (DataAtual -50). </b> </li>
                      <li><b>Lotes de chaparia são gerados com as seguintes condições:</b> </li>
                      <li>- A categoria deve ser diferente de 88 (UNIFICADA).</li>
                      <li>- A coluna "Ativo" deve estar desmarcada.</li>
                      <li>- A unidade deve ser FILIAL.</li>
                      <li>- O material deve começar com o código "MP02".</li>
                      <li>- O item deve iniciar com código "CAD".</li>
                      <li>- Os itens (PUFF, BANCO e CHAISE) não irão gerar lotes.</li>
                      <li>- Os itens são nomeados com o campo "item_estoque" do módulo "Tempos", o campo "nome_generico" ficará para o controle de estoque do item.</li>
                    </ul>
                </div>
            </li>
        </ul>
    </div>
</body>

    
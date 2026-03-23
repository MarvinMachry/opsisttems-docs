
<body>
    <div class="container">
        <h1>Visualizador de Lote</h1>
        <ul class="version-list">
            <li>
                <div>
                    <strong class="version">Descrição</strong>
                    <span class="date">Data de edição: 03/05/2023</span>
                    <p><b>Descrição do módulo Visalização de lote.</b></p>
                    <ul>
                      <li>O visualizador mostra os itens em ordem de maior necessidade atraves do Saldo, ou seja, mostra primeiro valores com saldo menor para o maior.</li>
                      <li><b>O Saldo atual representa a conta:</b> Estoque (NOG + CAS) + Produto ainda não montado - Itens Programação - Itens sem lote Promob.</li>
                      <li><b>Ped Reposição representa a conta:</b> Media entre (media ultimos 3 meses) e (media 3 meses pra frente do ano passado).</li>
                      <li><b>Tempo Reposição:</b> É o tempo que o produto leva para terminar o lote entre corte e CNC.</li>
                      <li><b>Média Mensal:</b> É a média das soma dos ultimos meses (depende da seleção da margem).</li>
                      <li><b>Est. Mínimo representa a conta:</b> Média de dias corridos do produto / (30 * margem) * (soma das medias).</li>
                      <li><b>Ponto Reposição representa a conta:</b> (soma das medias) * (dias corridos / 30) + Estoque minimo.</li>
                      <li><b>Previsão Pedido:</b> Representa uma data estipulada de quando será necessário pedir um lote novo.</li>
                      <li><b>Previsão Emin:</b> Representa uma data estipulada de quando o estoque chegará ao mínimo permitido.</li>
                      <li>Para remover itens fora de linha, deve-se acessar a Ficha Filial e marcar o item.</li>
                      <li>O controle do nome dos itens vem da tabela TEMPOS ('CONTROLE ESTOQUE') e CONTROLE_ESTOQUE ('PRODUTO').</li>
                      <li>
                        <span><b>Legenda de Status:</b></span>
                        <ul>
                          <li>Vermelho - Quando o Estoque Nogueira é menor ou igual ao Estoque Mínimo.</li>
                          <li>Amarelo - Quando o Estoque Nogueira é menor ou igual ao Ponto de Reposição * 1,2.</li>
                          <li>Azul - Quando o Estoque Nogueira é maior que o Ponto de Reposição * 1,2.</li>
                        </ul>
                      </li>
                    </ul>
                </div>
            </li>
            <li>
                <div>
                    <strong class="version">Funcionalidades</strong>
                    <span class="date">Data de edição: 03/05/2023</span>
                    <p><b>Descrição da funcionalidade do modulo.</b></p>
                    <ul>
                        <li><b>2 clicks no campo Status:</b>Permite que seja adicionado um lote para o produto de forma automatica(pega os valores sujeridos) ou de forma manual(informa o tamanho e data do lote manualmente).</li>
                        <li><b>Botão Atualizar:</b> Atualiza o modulo, excluindo as informações e inserindo dados atualizados. Em seguida verifica o "Atende Até" para cada item, ou seja, 
                        recebe a quantidade do estoque NOGUEIRA do item e vai descontando a cada iteração com a tabela "programacao" NOGUEIRA, se ficar negativo, para a consulta e salva a data como atende até.</li>
                    </ul>
                </div>
            </li>
        </ul>
    </div>
</body>

    
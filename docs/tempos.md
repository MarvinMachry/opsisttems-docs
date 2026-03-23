<!DOCTYPE html>


<body>
    <div class="container">
        <h1>Tempos de Processo</h1>
        <ul class="version-list">
            <li>
                <div>
                    <strong class="version">Tempos</strong>
                    <span class="date">Data de edição: 07/08/2025</span>
                    <p>Descrição da utilização do módulo Tempos.</p>
                    <ul>
                      <li>Ao criar produto novo, após a inserção, o CONTROLE ESTOQUE irá puxar automaticamente cortando somente a parte numerica do produto. Para alterar, primeiro deve inserir o item e depois edita-lo.</li>
                      <li>O campo NOME UTILITÁRIO é utilizado para impressão de etiquetas.</li>
                      <li>O campo CONTROLE ESTOQUE é utilizado para verificar nome de itens para inserir no estoque, bem como acrescentar novos itens ao estoque.</li>
                      <li>2 clicks no campo Descrição com usuario admin irá pintar de amarelo, significando que o produto possui dados genericos em seus tempos.</li>
                      <li>O campo Ativo serve para mostrar ou remover produto da consulta de visualizador de lotes. (PCP - Admin)</li>
                      <li><b>Botão Liberar:</b> Libera a tabela para edição, exclusão e adição. Círculo vermelho indica tabela bloqueada, verde para tabela liberada. Botão aparece somente para Admin e Leonardo.</li>
                      <li><b>Botão Salva Histórico:</b> Salva a tabela tempos atual em uma tabela de histórico com a data atual do sistema, quando tiver uma data cadastrada aparece uma caixa de texto informando que o registro já existe.</li>
                      <li><b>Botão Auditoria:</b> Abre o módulo de histórico de alterações do Tempos.</li>
                      <li><b>Botão Gerar:</b> Gera um arquivo com todos os registros da tabela Tempos no disco local C:Tempos de processo.xls.</li>
                    </ul>
                </div>
            </li>
            <li>
                <div>
                    <strong class="version">Cadastro de itens</strong>
                    <span class="date">Data de edição: 14/04/2023</span>
                    <p><b>Descrição do cadastro de itens Matriz.</b></p>
                    <ul>
                        <li>- Criar componentes na Ficha Técnica;</li>
                        <li>- Criar cadastro do item no Formulário Tempos;</li>
                        <ul><li>Ex.: CADXXX CADEIRA LUNA TEX;</li>
                        <li>- CADXXX CADEIRA LUNA LEE;</li></ul>
                        <li>- Criar cadastro do item no Formulário Componentes;</li>
                        <ul><li>Ex.: CADXXX CADEIRA LUNA TEX;</li>
                        <li>- CADXXX CADEIRA LUNA LEE;</li></ul>
                        <li>- Criar cadastro no Formulário TemposCNC;</li>
                        <li>- Criar cadastro de um item somente em Formulário Ficha Técnica Filial;</li>
                        <li>- Adicionar Item no Formulário Controle Estoque (Botão);</li>
                        <li>- Adicionar/Remover Assento ou Encosto;</li>
                        <li>- Campo Filial no modulo Ficha - Marcar para prod. sair do corte e ir para Registro Filial;</li>
                    </ul>
                    <p><b>Descrição do cadastro de itens Filial.</b></p>
                    <ul>
                        <li>- Criar cadastro de um item somente em Formulário Ficha Técnica Filial;</li>
                        <li>- Criar cadastro do item no Formulário Tempos;</li>
                        <ul><li>Ex.: MESA TALES 200X110;</li></ul>
                        <li>- Criar cadastro do item no Formulário Componentes;</li>
                        <ul><li>Ex.: MESA TALES 200X110;</li></ul>
                        <li>- Criar componentes na Ficha Técnica, o nome deve ser igual ao usado no modulo Tempos.ITEM ESTOQUE FILIAL;</li>
                        <li>- Criar cadastro no Formulário TemposCNC;</li>
                    </ul>
                </div>
            </li>
        </ul>
    </div>
</body>

    
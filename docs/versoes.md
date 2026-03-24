# Histórico de Versões

Registro de alterações do sistema **OpSisttems**.


## Versão 1.9.6.9

*Data de lançamento: 24/03/2026*

Descrição da atualização do sistema.

- Concluídos – Permissão para Alberto voltar itens para a programação.
- Programação – Agora ao concluir todos os setores na programação, tambem conclui o item automaticamente na produção, tanto componente quanto produto.




## Versão 1.9.6.8

*Data de lançamento: 23/03/2026*

Descrição da atualização do sistema.

- Alteração de Datas – Ajuste na consulta para alterar datas de itens que não possuirem configuração de cores no Promob, estava dando erro.



## Versão 1.9.6.7

*Data de lançamento: 20/03/2026*

Descrição da atualização do sistema.

- Manutenção – Consulta que verifica status da manutenção alterada para não verificar mais o parada = 0.
- Programação Filial – Adicionado botão para verificar o histórico de operações de máquinas sobre o produto em foco.
- OpSisttems – Adicionado verificação de servidor, caso o usuario acesse diretamente do servidor, ele será derrubado.
- OpSisttems – Adicionado verificação de atualização, avisando caso o usuário esteja com uma versão antiga do sistema.
- Controle de Estoque – Permissão para Rafael alterar o controle de encosto e assento concedida.
- Manutenção – Prioridade P4 trocada, recebendo o valor da P5.
- Manutenção – Adicionado status "EM ESPERA", bem como seu filtro, mostrando atividades (EM ESPERA, ATIVIDADE).
- Manutenção – Adicionado botão para transformar atividade "EM ESPERA".










## Versão 1.9.6.6

*Data de lançamento: 19/03/2026*

Descrição da atualização do sistema.

- Carregamento Filial – Adicionado uma coluna para registrar o horário de impressão.
- Configurador Pedidos Especiais – Alterado logica para abrir módulo da sequência com 2 clicks, agora é necessário ter algo escrito na descricao da peça.
                        Também foi implantado para atualizar a Máquina Atual e Próxima ao salvar a sequência.




## Versão 1.9.6.5

*Data de lançamento: 18/03/2026*

Descrição da atualização do sistema.

- Almoxarifado – Ajustado bug em formulário de saída de itens no almoxarifado. Agora é possível errar a lista de local e também não 
                        recebe mais itens desvalidados na consulta.
- Almoxarifado – Ajuste ao abrir Alteração de Projetos, agora abre itens da FILIAL.
- Programação Filial – Consulta que altera o impresso na programação alterada para não concluir o produto no corte.
- Programação Filial – Adicionado Alteração de Projetos no módulo de programação filial.






## Versão 1.9.6.4

*Data de lançamento: 17/03/2026*

Descrição da atualização do sistema.

- Programação Filial – Agora, ao solicitar chaparia, o campo concatena da lista é preenchido.



## Versão 1.9.6.3

*Data de lançamento: 13/03/2026*

Descrição da atualização do sistema.

- Programação Produção – Corrigido bug que permitia remover o valor do campo 'Hora Trabalho', causando erro ao movimentar um componente.
- Manutenção – Adicionado botão Start, para iniciar uma manutenção, informando os manutentores.
- Manutenção – Adicionado botão Pause, para parar um manutentor à manutenção. Permitido somente em manutenções já iniciadas.
- Manutenção – Status alterado para (PENDENTE, INICIADO, PARADO).
- Manutenção – Botão concluir agora conclui todos os manutentores automaticamente, sem ter que informá-los.
- Manutenção – Filtro Prazo: Atual (exibe datas até 21 dias pra frente), Todos (exibe todas as manutenções).








## Versão 1.9.6.2

*Data de lançamento: 12/03/2026*

Descrição da atualização do sistema.

- Programação Filial – Consulta para visualização de fotos ajustada, havia um bug que não mostrava fotos de mesa de apoio.
- Programação Filial – Usuários agora entram filtrados com seu respectivo setor.
- Programação Filial – Usuário Alberto agora tem permissão para excluir itens.
- Programação Filial – Formulário abre filtrado pelo setor referente ao usuário. Para gestores não em filtro.
- Programação Filial – Adicionado mais 2 botões ao módulo, para impressão de etiquetas separadas, PEÇAS e MONTAGEM.
- Programação Filial – Ao imprimir a etiqueta de PEÇAS, marca impresso no próprio módulo e na programação.
- Programação Filial – Agora temos 2 estágios de impressão. Cinza indica impresso PEÇAS e verde indica impresso MONTAGEM.
- Programação Filial – Botão imprimir normal ocultado por hora.
- Programação Filial – Corrigido bug que não atualizava as maquinas atuais no campo concatenado da lista de produtos.
- Programação Filial – Corrigido bug que gerava itens FERRAGEM para impressão de etiquetas. Voltou a ser somente FERRAGEM CORES.
- Configurador Item Programação Especial – Agora é possível dar dois clicks na sequência para edita-la.













## Versão 1.9.6.0

*Data de lançamento: 23/02/2026*

Descrição da atualização do sistema.

- Programação – Adicionado auditoria para campos de produção Filial.
- Configurador – Agora adiciona automaticamente as categorias que contiverem MONTADO ou FERRAGEM.
- Configurador – Agora nas opções não aparecerá mais as categorias que contiverem MONTADO ou FERRAGEM.
- Configurador – Agora adiciona a observação dos componentes. Para categoria normal (observacao & observacao2). Para MONTADO (observacao_pintura).
- Ficha Técnica – Ao gerar lote do item de código GEN001, gera o item da mesma forma que o M.L., porém, com 5 dias de diferença.
- Programação Filial – Botões para AVANÇAR e VOLTAR apenas componentes selecionados adicionado.
- Programação Filial – Campos dos componentes bloqueados para edição.
- Programação Filial – Agora é possível visualizar os componentes dos produtos MATRIZ concluídos também.
- Programação Filial – Ao avançar algum componente, verifica o setor atual e pinta o pedido com a cor correspondente.
- Programação Filial – Adicionado Legenda de cores para indicar o setor.
- Programação Filial – Adicionado filtro de setor.
- Programação Filial – Adicionado botão para alternar entre Foto1 e Foto2 do produto.
- Programação Filial – Agora ao dar 2 clicks na imagem do produto, é aberto a imagem grande para melhor visualização.
- Programação Filial – A consulta de visualização dos componentes foi alterada para 1->N. Verificar se está ok.
- Programação Produção – Botão "Excluir Produto" liberado apenas para (admin, Henrique, Matheus).
- Manutenção – Ajuste para formulário não travar mais com tamanho de tela maior que 1920.
- Manutenção – Removido valor padrão para o status, estava com valor antigo diretamente pelo MySQL.
- Manutenção – Agora ao alterar a descrição, não altera mais a data de solicitação, apenas a data de alteração.
- Sequência em Massa – Botão para copiar para toda a lista filtrada adicionado.





















## Versão 1.9.5.6

*Data de lançamento: 09/02/2026*

Descrição da atualização do sistema.

- API Site Pedidos – Consulta que extraía o status do pedido foi ajustada para mais precisão. Pedidos que estavam TOTALIZADOS mas com uma nota cancelada e outra 
                    nota faturada, gerava conflito e trazia dados inconsistentes.



## Versão 1.9.5.5

*Data de lançamento: 06/02/2026*

Descrição da atualização do sistema.

- Manutenção – Adicionado filtro para permitir a visualização de atividades cadastradas sem manutentor.
- Manutenção - Adicionado filtro para prazo Atual (<= Data + 21) e Todos (<= Data + 3650).
- Manutenção - Adicionado nova função para o módulo se ajustar com a tela do computador.
- Avaliações - Botão excluir visível para usuário Matheus, também foi alterado no cadastro para ele poder visualizar todas as avaliações.






## Versão 1.9.5.4

*Data de lançamento: 05/02/2026*

Descrição da atualização do sistema.

- Registro Matriz->Filial – Adicionado novo botão para divisão de lotes. A divisão não pode exceder o valor original do lote.
- Registro Matriz->Filial - Adicionado uma caixa amarela sinalizando ser um lote inserido manualmente ao gerar o lote na Ficha Técnica.
- Registro Matriz->Filial - Agora ao dar entrada no estoque, lotes marcados como Manual irão acrescentar a quantia ao estoque em vez de corrigir o valor.
- Registro Matriz->Filial - Agora ao concluir no Corte Filial, o produto não dará mais entrada no estoque e nem no registro. Essa lógica foi pensada para 
                        atender melhor o Gerador de Lotes, e também para mostrar com mais fidelidade a quantidade atual dos itens no estoque, pois só terão entrada ao adicionar pelo Registro.
- Ficha Técnica - Coluna OBS Pintura habilitada para usuário Leonardo.







## Versão 1.9.5.3

*Data de lançamento: 30/01/2026*

Descrição da atualização do sistema.

- Programação Espuma Fairino – Adicionado novo módulo para controle da Programação de Espuma.



## Versão 1.9.5.2

*Data de lançamento: 28/01/2026*

Descrição da atualização do sistema.

- Manutenção – Novo botão adicionado excluir uma atividade.
- Manutenção – Ao excluir agora, todo o histórico daquela atividade é excluída também.
- Manutenção – Corrigido bug que impedia de criar nova atividade.
- Manutenção – Removido restrições de preenchimento para os campos (Máquina, Componente, Observação) ao concluir uma atividade.
- Manutenção – Consulta para concluir alterada, agora em atividades Preventivas, atualiza a atividade para PENDENTE e remove a ordem.
- Manutenção – Agora a ordem da lista é dada pela seguinte condição (Status, Ordem, Prioridade, Data Solicitação).
- Ficha Técnica – Visualização da Montagem-ML feita igual ao da Pintura-ML.









## Versão 1.9.5.1

*Data de lançamento: 27/01/2026*

Descrição da atualização do sistema.

- Manutenção – Novo botão adicionado para adicionar ou remover Manutentores da atividade.
- Manutenção – Agora pode adicionar quantos manutentores forem necessários para a manutenção.
- Manutenção – Botão para alerta em whats removido.
- Produção Filial – Agora ao concluir não envia mais o produto para o registro Matriz -> Filial, pois estava enviando com 0 unidades. Enviando apenas para o estoque.
- Estoque – Uma possivel solução futura para não duplicar o estoque atual no gerador de lotes seria não enviar para o estoque na conclusão. Enviando
                        somente quando for registrar o lote no registro Matriz -> Filial. Será possivel pois os itens gerados manualmente vão com um flag, poderá ser utilizado para fazer a conta correta.







## Versão 1.9.5.0

*Data de lançamento: 23/01/2026*

Descrição da atualização do sistema.

- Manutenção – Opções do campo "Tipo" foram alteradas para (Corretiva; Preventiva).
- Manutenção – Campo "Máquina" recebe agora a informação do S/N junto para melhor visualização.
- Manutenção – Campo "Segurança" foi removido.
- Manutenção - Campo "Status" passa a ser nomeado de "Prioridade", mantendo as mesmas opções.
- Manutenção - Campo "Status" terá as opções (PENDENTE; EM ANDAMENTO).
- Manutenção - Ao dar andamento na manutenção, a data de início será atualizada. Esta data não será mais alterada após ser inserida.
- Manutenção - Ao concluir a manutenção, o campo data final será alterado para a deta atual do sistema.
- Manutenção - Formulário de conclusão só libera se a manutenção estiver com Status = EM ANDAMENTO.
- Ficha Técnica - Campos de Obs_Pintura liberados para o usuário Alberto.











## Versão 1.9.4.6

*Data de lançamento: 19/01/2026*

Descrição da atualização do sistema.

- Ficha Técnica – Colunas ocultadas para o usuário Pintura-ML. Também foi adicionado a coluna "Obs Pintura" para o ITEM e o COMPONENTE para o mesmo usuário.
- Ficha Técnica – Categorias 97 e 98 ocultadas na consulta do Resumo da Ficha. (PE MONTADO; TAMPO MONTADO)
- Ficha Técnica – Ajuste na consulta para inserir no Registro Matriz -> Filial, alterado campo nogueira para lote_nog.





## Versão 1.9.4.5

*Data de lançamento: 14/01/2026*

Descrição da atualização do sistema.

- Ficha Técnica – Agora ao gerar lote, pergunta se deseja gerar registro Matriz -> Filial para itens com Unidade = FILIAL.
- Visualizador de Lotes – Agora soma os itens que estão no registro Matriz -> Filial e com flag -1 enquanto não forem conferidos.
- Corte Filial – Agora ao excluir, pergunta se deseja remover tambem do registro Matriz -> Filial.
- Programação – Coluna 'Falta Material' liberada para usuário Ananda.
- Informações: Atualização feita para corrigir problema em que alguns itens não estavam contabilizando para o Visualizador de Lotes. Ex.: MILA.
                         Agora ao gerar o lote, é solicitado se deseja que o item entre para o registro Matriz -> Filial, assim tendo mais controle sobre itens terceirizados e contabilizando no 
                         Visualizador de Lotes.







## Versão 1.9.4.4

*Data de lançamento: 23/12/2025*

Descrição da atualização do sistema.

- API Site – Corrigido bug em consulta que adicionava DATETIME na tabela com 60 segundos em alguns casos, causando erro.



## Versão 1.9.4.3

*Data de lançamento: 22/12/2025*

Descrição da atualização do sistema.

- Status Programação – Adicionado 'EM PRODUÇÃO' nos campos da Marcenaria-ML.



## Versão 1.9.4.2

*Data de lançamento: 17/12/2025*

Descrição da atualização do sistema.

- Importador de Programação – Adicionado na consulta de importação, os códigos 908 (MATRIZ) e 907 (FILIAL).



## Versão 1.9.4.1

*Data de lançamento: 15/12/2025*

Descrição da atualização do sistema.

- Visualizador de Lote – Ajustada a consulta responsável por calcular o estoque NOG .
                        A coluna da consulta cSomaProdutosMontagem foi alterada para: qtdeNOG: 
SeImed(
    Soma(
        SeImed(
            Nz([SomaDeCastanho];0) <= [Lote] * 0,12;
            [Lote] * 0,82 - Nz([SomaDeNogueira];0);
            ([Lote] * 0,82) - [SomaDeProduzido]
        )
    ) < 0;
    0;
    Soma(
        SeImed(
            Nz([SomaDeCastanho];0) <= [Lote] * 0,12;
            [Lote] * 0,82 - Nz([SomaDeNogueira];0);
            ([Lote] * 0,82) - [SomaDeProduzido]
        )
    )
) Antes estava como: qtdeNOG:
SeImed(
    Soma(
        SeImed(
            Nz([SomaDeCastanho];0) <= [Lote] * 0,12;
            [Lote] * 0,82 - Nz([SomaDeNogueira];0);
            ([Lote] * 0,82) - [SomaDeProduzido]
        )
    ) < 0;
    Soma([Lote] - [SomaDeProduzido]);
    Soma(
        SeImed(
            Nz([SomaDeCastanho];0) <= [Lote] * 0,12;
            [Lote] * 0,82 - Nz([SomaDeNogueira];0);
            ([Lote] * 0,82) - [SomaDeProduzido]
        )
    )
)

Antes estava como:



## Versão 1.9.4.0

*Data de lançamento: 11/12/2025*

Descrição da atualização do sistema.

- Programação Produção – Ajustada a consulta responsável por marcar itens como impresso ao gerar a etiqueta. Agora a verificação ocorre corretamente para maquina_atual = 'VA-CORTE' (antes estava como 'CORTE' ).
- Programação Produção – Ao fechar a tela de etiqueta de CORTE , o sistema agora adiciona automaticamente o item à lista de solicitação de exemplar para envio FILIAL → MATRIZ .
- Nota Importante – A lista de exemplares é composta apenas pelos itens que: já estão no estoque de sobra; e foram efetivamente abatidos ao gerar o lote. Itens que não tiveram desconto no lote não aparecerão na lista de envio de exemplar.
- já estão no estoque de sobra; e
- foram efetivamente abatidos ao gerar o lote.
- Lista Produto Exemplo – Adicionado módulo que identifica os produtos que já entraram em processo produtivo, indicando que já é possível enviar um exemplar para a MATRIZ.
- Sobra de Lote – Ajustado o cálculo para determinar a quantidade de pés no item: Se quantidade = 1 → 1 Se quantidade > 1 e < 4 → 2 Caso contrário → 4



- já estão no estoque de sobra; e
- foram efetivamente abatidos ao gerar o lote.






## Versão 1.9.3.4

*Data de lançamento: 09/12/2025*

Descrição da atualização do sistema.

- API Site - Agora registra o momento da atualização dos dados para a API importar para o site, serve para mostrar em um visor no pc para manter atualizado sempre.



## Versão 1.9.3.3

*Data de lançamento: 05/12/2025*

Descrição da atualização do sistema.

- Ficha Técnica - Nova categoria adicionada (UNIFICADA_ML), utilizada para produtos que só vão para a produção FILIAL, bem como (UNIFICADA_VA) vai somente para MATRIZ.
- Ficha Técnica - Consulta para inseresão na programação MATRIZ agora ignora o id_categoria_componente = 94 (UNIFICADA_ML).
- Ficha Técnica - Agora os 2 clicks para soma de materiais não mostra mais as categorias (UNIFICADA_ML e UNIFICADA_VA).
- Almoxarifado - Exportação em CSV agora soma a quantidade de itens com o mesmo código.






## Versão 1.9.3.1 e 1.9.3.2

*Data de lançamento: 03/12/2025*

Descrição da atualização do sistema.

- Programação - Consultas que alteravam quantidade de estoque espuma foram removidas pois ainda não estão sendo utilizadas e estavam causando erros.
- Ficha Técnica - Ajustes na geração de lotes para funcionar com ML2. Estava causando erro pois estava entrando no loop quando não podia no algoritmo novo.




## Versão 1.9.3.0

*Data de lançamento: 01/12/2025*

Descrição da atualização do sistema.

- Sobra de Lote - Adicionado novo modulo para controle de estoque de sobra para itens Matriz -> Filial. Ou seja, itens FILIAL que possuem controle na Matriz.
- Sobra de Lote - Este módulo poderá ser acessado pelo módulo de Controle de Estoque. Somente alguns usuários poderão acessar: 
                            (admin, Almoxarifado-ML, Alberto, Pintura-ML, Marcenaria-ML).
- Sobra de Lote - A lista de sobra poderá ser acessada nos botões principais do menu superior próximo ao botão do OUTLET, servindo somente para visualização.
- Sobra de Lote - Agora ao gerar lotes de produção, para itens com controle MATRIZ e SEQUENCIA <> "", será verificado na lista de estoque se há peças a abater.
                            Caso seja válido, o gerador irá gerar o lote com as peças descontadas no lote. Nesse caso, o estoque de sobra é apagado sobre aquele item. Para registro, ficará em uma tabela
                            que captura as movimentações.
- Sobra de Lote - Caso o lote seja excluído da programação, o sistema irá gerar as linahs de estoque novamente e também informará isso na tabela de movimentações.







## Versão 1.9.2.0

*Data de lançamento: 26/11/2025*

Descrição da atualização do sistema.

- Manutenção - Agora ao concluir foi adicionado um módulo para conclusão que insere a máquina e algumas informações adicionais.
- Manutenção - Campo manutentor agora recebe pela tabela Usuarios os usuarios com o campo manutencao = SIM.
- Histórico de Manutenção de Máquinas - Adicionado novo módulo para visualização de histórico de manutenção de componentes de máquinas.
- Máquinas Componentes - Adicionado novo módulo para cadastro de componentes de máquinas. Serve tanto para controle de máquinas grandes (componente cnc), quanto para pequenas(roquites).
- Maquinas - Adicionado campo S/N e Tipo para as máquinas. Tipo servirá para filtragem de máquinas posteriormente em módulos de produção.
- Programação - Coluna de id_programação adicionada no histórico de movimentos do controle de estoque.
- Programação Status - Usuário Leonardo e Alberto adicionados na consulta de remoção e adição de estoque ao CONCLUIR.









## Versão 1.9.1.6

*Data de lançamento: 05/11/2025*

Descrição da atualização do sistema.

- Análise de Produção - Consulta ajustada para receber Robo e modo de sequencia novo.



## Versão 1.9.1.5

*Data de lançamento: 04/11/2025*

Descrição da atualização do sistema.

- Programação - Consulta para concluir item da programação alterado para funcionar em itens que foram divididos.
- Ficha Técnica - Liberado alteração para usuário William.




## Versão 1.9.1.3 e 1.9.1.4

*Data de lançamento: 30/10/2025*

Descrição da atualização do sistema.

- Programação Produção - Bug de não localizar a maquina ao salvar setup corrigido.



## Versão 1.9.1.2

*Data de lançamento: 24/10/2025*

Descrição da atualização do sistema.

- Ficha Técnica - Permissão total de edição para o usuário Bruno.



## Versão 1.9.1.1

*Data de lançamento: 22/10/2025*

Descrição da atualização do sistema.

- Análise de Produção de Corte - Ajuste em consulta para novo formato de sequências.
- Avaliação de Funcionários - Botão adicionado para impressão de relatório de Avaliação de Consenso.
- Avaliação de Funcionários - Feito um ajuste na consulta para melhora do filtro de pendentes.





## Versão 1.9.1.0

*Data de lançamento: 20/10/2025*

Descrição da atualização do sistema.

- Programação - Formatação condicional alterada para nao pintar de VERDE quando puff IRIS e CINDY forem totalmente concluídos pela filial.
- Avaliação de Funcionários - Adicionado botão para troca de avaliador. Somente para usuários (Taciana, Matheus, Alberto).




## Versão 1.9.0.1 e 1.9.0.2

*Data de lançamento: 17/10/2025*

Descrição da atualização do sistema.

- Montagem Lote - Ajustado bug que não permitia mais excluir um lote de montagem.
- Programação Produção - Ajustado itens que não receberam a máquina correta na troca de sequências.
- Ficha Técnica - Campo id ocultado novamente, estava impedindo cópia de componente.
- Pedidos Site - Nova condição colocada na coluna status "COLETADO".
- Programação Produção - Relatório de etiquetas do corte ajustado para novo formato de sequências.







## Versão 1.9.0.0

*Data de lançamento: 16/10/2025*

Descrição da atualização do sistema.

- Sequências de máquinas - Novo formato de sequências inserido, agora a quantidade pode ser infinita de processos dentro de um componente.
- Sequência de máquinas - Novo formato inserido no cadastro de sequência de maquinas, mas mantido em até 9 por enquanto.
- Sequência de máquinas - Ao alterar sequência, altera na Produção Programação.
- Ficha Técnica - Função para gerar lotes ajustada para novo formato de sequências.
- Programação Produção - Botão de avançar componente ajustado para novo formato de sequências.
- Programação Produção - Botão para voltar componente ajustado para novo formato de sequências.
- Programação Produção - Botão para inserir componente ajustado para novo formato de sequências.
- Ficha Técnica - TemposCNC alterado para novo formato de sequências.
- Clientes Promob - Adicionado função para remover os clientes duplicados da tabela.
- Programação ML - Removido botões para gerar corteCerto.
- Programação ML - Ajustado todos os parâmetros para funcionar o novo sistema de sequência na Programação Filial.
- Ficha Técnica - Ao alterar sequência, agora altera nos produtos em produção, tanto matriz quanto filial.
- Alteração de Projeto - Alterações feitas para novo formato de sequências.















## Versão 1.8.31.8 e 1.8.31.9

*Data de lançamento: 07/10/2025*

Descrição da atualização do sistema.

- Programação - Consulta para inserir programação para robô Fairino ajustada.
- Ficha Técnica - Adicionado permissão de CRUD para usuario Almoxarifado-ML.




## Versão 1.8.31.6 e 1.8.31.7

*Data de lançamento: 02/10/2025*

Descrição da atualização do sistema.

- Programação Produção - Consulta para verificação de datas ajustado. Estava buscando apenas um item para os itens da matriz.
- Programação Espuma - Agora ao gerar relatório para espuma, insere também na lista do robô.
- Almoxarifado - Consulta criada para verificar movimentação de almoxarifado. 11verificaMovimentacaoAlmoxarifado
- Etiqueta de Produção Filial - Tamanho do campo observação aumentado na etiqueta de produção Filial.






## Versão 1.8.31.5

*Data de lançamento: 25/09/2025*

Descrição da atualização do sistema.

- Tempos - Liberado para usuario Alberto fazer modificação.
- Avaliações - Liberado para usuario Alberto.
- Programação Produtos - Removido campo de data necessidade, somente removido da visualização.
- Ficha Técnica - Usuário Almoxarifado-ML com permissões para edição.
- Manutenção - Alterado nome de Anderson para Rodrigo nos manutentores.







## Versão 1.8.31.4

*Data de lançamento: 22/09/2025*

Descrição da atualização do sistema.

- Ficha Técnica - Ajustado bug ao gerar lotes, estava derrubando o sistema.
- Programas Fairino - Adicionado novo módulo para controle de programas do Fairino. Começando com espuma, mas com liberdade para outros setores.
- Ficha Técnica - Adicionado botão para adicionar Programas Fairino ao item em foco da ficha.





## Versão 1.8.31.3

*Data de lançamento: 18/09/2025*

Descrição da atualização do sistema.

- Pedidos - Adicionado Requery ao abrir formulário novamente, pois não estava filtrando o setor ao abrir..
- Ficha Técnica - Ao gerar lote de ITENS GENERICOS, agora cria o lote com 10 dias para frente.
- Programação Produção - Ajustado para itens da filial anteciparem 14 dias.





## Versão 1.8.31.1

*Data de lançamento: 11/09/2025*

Descrição da atualização do sistema.

- Montagem - Ajustado para não marcar mais o indicador se não for inserido funionario no lote de montagem.
- Corte Filial - Filtro de máquina atual removido dos itens, filtrando agora apenas os componentes.
- Tempos - Agora ao alterar algum tempo da tabela, automaticamente é criado um historico para o item com a data 
                            atual e os dados antes de serem alterados.





## Versão 1.8.31

*Data de lançamento: 10/09/2025*

Descrição da atualização do sistema.

- Montagem - Montagem agora possui uma relação N:N com a programação, indicando sob quais itens o lote de montagem é composto.
- Montagem - Adicionado campo que informa se ja foi adicionado produção para etapa "VA-MONTAGEM-FINAL".
- Montagem - Ao dividir lote de montagem, agora transfere e calcula tambem os dados de produção do item.





## Versão 1.8.30.1

*Data de lançamento: 09/09/2025*

Descrição da atualização do sistema.

- Programação - Liberação de alteração de datas para FILIAL para usuário Ananda.



## Versão 1.8.30

*Data de lançamento: 08/09/2025*

Descrição da atualização do sistema.

- Filial - Adicionado controle de produção por sequência do componente. Agora é possível avançar a etapa do item.
- Pedidos/Titulos Clientes - Adicionado campo de observações do cliente para o financeiro. Campo extraído do Promob.
- Titulos Cliente - Layout reestilizado.
- Estoque - Agora o estoque da Filial passa a fazer parte da programação da Matriz. O processo funciona da seguinte forma: a Matriz realiza o lançamento e o 
                            registro, e a Filial confirma o recebimento, informando a quantidade correta dos componentes.
                            Caso seja identificada alguma divergência, o sistema ajusta automaticamente o estoque e registra a ocorrência no Histórico de Estoque, 
                            destacando a diferença em ROXO.






## Versão 1.8.29 e 1.8.29.1

*Data de lançamento: 04/09/2025*

Descrição da atualização do sistema.

- Configurador - Adicionado marcador para itens com PRIORIDADE, irá inserir o DXF em uma pasta de prioridade para usinagem.
- Ficha Técnica - Ao gerar lote de itens "M.L.", agora lança com 5 dias à frente, e não mais com 15 dias.
- Controle de Estoque - Consulta para calcular datas agora contabiliza itens duplicados na programação, provenientes de divisão de lotes.





## Versão 1.8.28.3

*Data de lançamento: 20/08/2025*

Descrição da atualização do sistema.

- Alteração de Projeto - Adicionado campo de Unidade ao selecionar o setor.
- Produção Programação - Campo máquinas agora esta filtrado com unidade matriz apenas.




## Versão 1.8.28.1 e .2

*Data de lançamento: 18/08/2025*

Descrição da atualização do sistema.

- Programação - Permissão para dividir lote adicionada para usuários Leonardo, Alberto e Matheus.
- Usuários - Usuário Matheus adicionado.
- Permissões - Permissões do usuário Leonardo copiadas para usuário Alberto.





## Versão 1.8.28

*Data de lançamento: 07/08/2025*

Descrição da atualização do sistema.

- Lotes de montagem - Atualizado para verificar se a consulta retornou valores antes de proceguir, estava gerando erro.
- Ficha Técnica - Ao gerar lotes agora, quando item possuir CHAPAS, envia o lote para o Corte Filial com o nome da FICHA e não mais
                            do TEMPOS. Exemplo é APOIO LURI, agora gera com o nome da FICHA para o CORTE FILIAL, assim, não irá acrescentar ao estoque quando concluir o item.




## Versão 1.8.27

*Data de lançamento: 05/08/2025*

Descrição da atualização do sistema.

- Ficha Técnica - Não sinaliza mais ao alterar o "Controle", somente faz a auditoria.
- Ficha Técnica - Adicionado filtro para itens sinalizados com alteração. "TODOS" - "ALTERAÇÃO"
- Ficha Técnica - Removido quebra de linhna na tecla Enter, agora o Enter pula para o próximo campo.





## Versão 1.8.26.1

*Data de lançamento: 04/08/2025*

Descrição da atualização do sistema.

- Relatórios - Ajustado para que todos os relatórios abram com a impressora padrão do sistema atual.



## Versão 1.8.26

*Data de lançamento: 18/07/2025*

Descrição da atualização do sistema.

- Consulta NFS - Adicionado filtro de NFS.
- Consulta NFS - Filtro transportadora alterado para campo de texto simples.
- Consulta NFS - Alterado para ordem Decrescente baseado na data de saida das notas.
- Corte Filial - Módulo atualziado para abrir mesmo nao havendo registro de produtividade no dia.






## Versão 1.8.25

*Data de lançamento: 14/07/2025*

Descrição da atualização do sistema.

- Gerador de lotes - Consulta ajustada na conta de NOGUEIRA, agora quando a conta ser negativa nos 82%, subtrai o produzido sobre o lote inteiro.
- Produção Programação - Idem de cima.
- Pedidos - Consulta para verificar atraso de Boletos para clientes alterada. Agora verifica programação com 1 ano no maximo, antes era
                            se programação ainda não estava concluída, mas dava inconsistência em alguns.





## Versão 1.8.24

*Data de lançamento: 09/07/2025*

Descrição da atualização do sistema.

- Pedidos - Consultas ajustadas para melhorar desempenho na abertura e filtros de status. Reduzido para 1/3 do tempo.



## Versão 1.8.23

*Data de lançamento: 03/07/2025*

Descrição da atualização do sistema.

- Corte Filial - Desempenho geral do módulo melhorado.
- Corte Filial - Agora os componentes só são filtrados para itens com a data > DataAtual -50. Para ganho de desempenho.
- Corte Filial - Ajustado consulta para conclusão dos itens, adicionado uma consulta antes do LEFT JOIN. Para ganho de desempenho.
- Relatório Pendentes - Campos de estoque adicionados no relatório.






## Versão 1.8.22

*Data de lançamento: 02/07/2025*

Descrição da atualização do sistema.

- Programação Produção - Consulta do relatório de etiqueta do corte agora converte tudo <=1 em item unitario Ex.: - Razão 0,5 Lt/Qtde: 100/50(50) - Razão 1 Lt/Qtde: 100/100(100) - Razão 2 Lt/Qtde: 100/200(E:100  D:100)



## Versão 1.8.21

*Data de lançamento: 01/07/2025*

Descrição da atualização do sistema.

- Programação Produção - Ao concluir produtos FILIAL agora verifica se está no ultimo estágio do ultimo componente, se sim, verifica a quantidade
                            no registro Matriz -> Filial, caso seja menor do que o lote, alerta o usuário que deve inserir no estoque a quantidade faltante.
                            Usuário pode ignorar a mensagem clicando em Não e prosseguir com a conclusão.



## Versão 1.8.20

*Data de lançamento: 30/06/2025*

Descrição da atualização do sistema.

- Corte Filial - Data lançada na etiqueta de cadeiras alterada para receber a data do pedido e não mais a data atual.
- Programação - Adicionada nova opção para não descontar do estoque os produtos ao concluir na MARCENARIA. Opção "0 - NENHUM".




## Versão 1.8.19

*Data de lançamento: 26/06/2025*

Descrição da atualização do sistema.

- Programação Produção - Agora ao adicionar lote "M.L.", adiciona Data Falta com 15 dias a mais.
- Relatório Estoque Filial recebido de Matriz - Relatório adicionado.
- Programação Produção - Campo "Falta Dia" agora é calculado com 15 dias de antecedência para itens da FILIAL.
- Controle de Madeiras - Campo Jequitiba 90MM alterado para 55MM.






## Versão 1.8.18

*Data de lançamento: 24/06/2025*

Descrição da atualização do sistema.

- Alteração de data em Massa - Consultas alteradas pra não excluir mais os lotes de montagem ao alterar data em massa.
                             Agora subtrai a quantidade necessária e cria um novo lote somente do que foi alterado



## Versão 1.8.17

*Data de lançamento: 18/06/2025*

Descrição da atualização do sistema.

- Cores Tintas - Campos de valores alterados de: -> inserção -> para -> consultas, pois assim, com qualquer atualização no promob,
                            o valor se ajustará automaticamente. Coluna do Promob deixa de ser "VL" e passa a ser "VALOR_CUSTO".



## Versão 1.8.15 e 1.8.16

*Data de lançamento: 16/06/2025*

Descrição da atualização do sistema.

- Perdas Operacionais - Adicionado Perdas Operacionais no Módulo de Programação de Produção.
- Site Pedidos - Consulta alterada por problemas nos emails no site.
- Programação Produção - Adicionado campo "Falta Dia", representa o dia da programação no qual faltará o produto.





## Versão 1.8.13

*Data de lançamento: 06/06/2025*

Descrição da atualização do sistema.

- Tempos - Removidas colunas inutilizadas na tabela tempos, e adicionada coluna montagem-final.
- Montagem Lote - Adicionado ComboBox para selecionar o setor ao inserir produto à funcionários.




## Versão 1.8.11 e 1.8.12

*Data de lançamento: 03/06/2025*

Descrição da atualização do sistema.

- Ficha Técnica - Adicionado coluna de codigo Material para usuarios Henrique e Alessandro.
- Montagem Lote - Adicionado campo mostrando se ja foi inserido funcionário em sublote.




## Versão 1.8.10

*Data de lançamento: 30/05/2025*

Descrição da atualização do sistema.

- Programação - Agora ao concluir no setor estofaria, ignora os demais campos se o produto for um "AS".
- Montagem Lote - Removido restrição que só permitia concluir inserindo um funcionário. Agora insere o funcionário somente com botão.
- Programação Produção - Permite agora inserir valor 0 no estoque. Ajustado texto para NOGUEIRA e CASTANHO. Agora insere registro com flag marcado.
- Visualizador de Lotes - Consulta ajustada para não calcular cadeiras pelo registro, estava somando o que tem a produzir + montagem, agora
                             é somente montagem.






## Versão 1.8.09

*Data de lançamento: 26/05/2025*

Descrição da atualização do sistema.

- Programação - Adicionado botão para troca de Unidade entre Matriz e Filial, utilizado para itens com "MTR".
- Tempos - Habilitado permissão para usuário Montagem.
- Ficha Técnica - Removido permissão para 2 clicks no id para usuários não permitidos.
- Programação - Adicionado mais uns critérios para inserir a Unidade do produto na importação de lotes.
- Programação - Leve ajuste no layout de botões do formulário.
- Consulta Carregamento NFS - Coluna "Transportadora" adicionada no subformulário.








## Versão 1.8.08

*Data de lançamento: 23/05/2025*

Descrição da atualização do sistema.

- Produção Programação - Adicionado opção de castanho na entrada de estoque Matriz -> Filial.
- Volumes Transportadora - Alterado ordem das colunas da tabela.




## Versão 1.8.07

*Data de lançamento: 22/05/2025*

Descrição da atualização do sistema.

- Tempos - Alterado campos ocultados ao filtrar para VA-MONTAGEM.
- Montagem - Adicionado controle de produtividade por funcionários no lote de montagem.
- Outlet - Acesso liberado para usuário Rafaela.
- PCP Simplificado - Acesso liberado para usuário Carmen.
- Almoxarifado - Duas novas colunas adicionadas (Sel, Multiplicador), para exportação de arquivo.
- Almoxarifado - Adicionado botão para exportação de arquivo CSV para importação/atualização de estoque no Promob.








## Versão 1.8.06

*Data de lançamento: 21/05/2025*

Descrição da atualização do sistema.

- Funcionários - Texto de confirmação da geração de avaliação ajustado.
- Produção Programação - Adicionado botão para inserir quantidade de itens em estoque para a filial.
- Ficha Técnica - Removido inserção de Registro Matriz->Filial ao gerar lote de produção.
- Produção Programação - Removido entrada de itens para o estoque filial ao concluir no setor do corte.






## Versão 1.8.04 - 1.8.05

*Data de lançamento: 15/05/2025*

Descrição da atualização do sistema.

- Controle de estoque - Corrigido bug em consulta para atualizar as datas de "Atende Até" na condição de bancos.
- Assistências - Corrigido bug de data ao duplicar itens.
- Programação - Adicionado calculo de tempo de montagem em itens selecionados na programação.





## Versão 1.8.03

*Data de lançamento: 08/05/2025*

Descrição da atualização do sistema.

- Programação - Ajustado consulta para importação de produtos, agora importa com o Tecido linha 3000 inserido tambem. Filtro 111 e 112.
- Programação - Bug consertado ao atualizar estoque de espuma quando valor era decimal, derrubava pois era "," em vez de ".".




## Versão 1.8.02

*Data de lançamento: 07/05/2025*

Descrição da atualização do sistema.

- Tempos - Acesso liberado para usuarios Marcenaria-ML e Montagem-ML.
- Tempos - Adicionado nova coluna para registro de tempo de montagem - ml.
- Versionamento Git - Adicionado modulo exterior de versionamento para o gitHub.
- Programação - Agora faz a verificação de Unidade ao importar via VBA. Possibilitando mais condições na busca.






## Versão 1.8.01

*Data de lançamento: 02/05/2025*

Descrição da atualização do sistema.

- Pedidos - Ajustado calculo dos valores sobre os produtos(ABERTO, A FATURAR, TOTAL).
- Espuma - Adicionado tabelas para controle de histórico ao gerar pedido e ao concluir na programação.
- Programação - Adicionado auditoria para alterações de data em massa.





## Versão 1.8.00

*Data de lançamento: 25/04/2025*

Descrição da atualização do sistema.

- Assistências - Adicionado contador de imagens.
- Assistências - Removidos ao duplicar um item os seguintes campos: NF Enviada, Data NF Enviada, Pedido, Data Solicitação.
- Assistências - Alterado cópia de texto para whatsApp.
- Assistências - Alterado para exibição em ordem decrescente pelo campo ID.
- Espuma - Adicionado novo módulo para encomenda de espumas.
- Espuma - Filtrado através da data informada.
- Espuma - Para itens selecionados, é gerado um arquivo .TXT com o codigo e a quantidade do item. Em seguida é marcado na
                             programação como solicitado.
- Programação - Ao concluir no setor estofaria, desconta espuma do estoque do seu respectivo item.










## Versão 1.7.51

*Data de lançamento: 09/04/2025*

Descrição da atualização do sistema.

- Almoxarifado - Adicionado novo campo para inserir o local de armazenagem do produto.
- Pedidos - Adicionado valores referente ao pedido (Itens em aberto, a faturar, valor total).
- Aviso Falta de Material - Adicionado novo módulo para aviso de materiais em falta, ao selecionar o "Falta Material" na programação,
                            a cada 5 minutos é verificado se existe um novo item marcado, se sim, abre o módulo para resolução. Apenas para usuários Henrique e Alessandro.
- Auditoria Ficha Técnica - Adicionado para auditoria campo "Controle" da Ficha Técnica.






## Versão 1.7.48

*Data de lançamento: 20/03/2025*

Descrição da atualização do sistema.

- Programacão - Adicionado campo complemento à etiqueta de cadeira, quando houver "CM" dentro do complemento.
- Programação - Adicionado novo relatório para separação de espumas, filtrado por itens setados "EM PRODUÇÃO".
- Site - Alterado consulta para nao alocar datas em finais de semana.
- Login - Ajustado para quando logar no servidor, logar automaticamente. (semi-funcional)
- Avaliação - Adicionado nova competência "OBSERVAÇÕES GERAIS", somente para observações.







## Versão 1.7.47

*Data de lançamento: 03/02/2025*

Descrição da atualização do sistema.

- Assistências - Acesso liberado para usuário Corte Tecido.
- Assistências - Ao marcar como RECEBIDO, agora salva em um campo chamado data_recebido.
- Pedidos - Agora mostra o Crédito do Cliente, referência do Promob.
- Etiqueta - Ajustado Layout de etiqueta de programação para caber os 6 digitos do pedido.
- Assistências - Adicionado motivo "FALHA DE PROJETO".







## Versão 1.7.45

*Data de lançamento: 02/12/2024*

Descrição da atualização do sistema.

- Programação Produção - Alterado para que quando selecionado mais de um tipo de produto, impeça de abrir a impressão de etiquetas no corte.
- Análise de Produção - Adicionado valor de campo "1/2 TURNO" para a função de cada funcionário.
- Controle de Tecido - Adicionado campo de Data de Entrada do tecido na aba Estoque.





## Versão 1.7.44

*Data de lançamento: 18/11/2024*

Descrição da atualização do sistema.

- Almoxarifado - Adicionado valor "FERRAMENTA" para o campo Tipo.
- Programação - Agora ao concluir um item que possui soma 0 em estofaria, ignora os campos: -Corte Tecido; -Costura; -Estofaria;




## Versão 1.7.43

*Data de lançamento: 13/11/2024*

Descrição da atualização do sistema.

- Produto Produção - Alterado consulta para adicionar CHAISE no controle de estoque ao concluir no setor de corte.
                             Atualizado a consulta para visualizar se o produto esta completamente pronto no setor de corte.
- Adicionado usuário "Manutencao".




## Versão 1.7.42

*Data de lançamento: 07/11/2024*

Descrição da atualização do sistema.

- Almoxarifado - Adicionado botão para visualizar os itens ociosos no almoxarifado.



## Versão 1.7.41

*Data de lançamento: 06/11/2024*

Descrição da atualização do sistema.

- Almoxarifado - Adicionado campo para sinalizar itens ociosos baseado na quantidade de dias informado.



## Versão 1.7.40

*Data de lançamento: 30/10/2024*

Descrição da atualização do sistema.

- Produção - Adicionado botão para inserir novos componentes para o produto. Somente componentes ainda não inseridos.
- Manutenção - Criado BI para visualização.




## Versão 1.7.39

*Data de lançamento: 23/10/2024*

Descrição da atualização do sistema.

- Programação - Adicionado botão para visualizar itens que estão com datas divergentes entre Promob e OpSisttems.
- Manutenção - Adicionado nova opção para status "PROJETO".




## Versão 1.7.38

*Data de lançamento: 21/10/2024*

Descrição da atualização do sistema.

- Ficha - Ajustado para não dar refresh ao selecionar um componente.
- Registro montagem - Removido opção de marcar como lançado, operação não fazia mais sentido.




## Versão 1.7.36 e 37

*Data de lançamento: 16/10/2024*

Descrição da atualização do sistema.

- Ficha - Campo Cubagem4 alterado para ser a soma das outras 3 cubagens.
- Estoque Montagem - Alterado controle de estoque, agora não será mais contabilizado a quantidade de peças, será somente
                             lado e cor.
- Materiais - Adicionado campo de peso e tipo de medida para o material.
- Cores - Adicionado coluna que calcula o valor da cor por litro.






## Versão 1.7.34 e 35

*Data de lançamento: 10/10/2024*

Descrição da atualização do sistema.

- Ficha Técnica - Removido função para pintar em amarelo itens que forem alterados nos campos de volumes.
- Ficha de Cores - Ajustado bug que derrubava o sistema ao copiar cores sem valor informado no rendimento por m².
- Programação - Usuario Pintura-ML agora pode alterar a data do produto.
- Produto Programação - Ajustado para que, quando um item da FILIAL retornar ao processo de CORTE, a quantidade correspondente 
                            seja também removida do estoque do lote.
- Corte ML - Botão adicionado para inserir um sub-lote de chaparia, utilizando a data final de busca na programação como 
                            referência para a geração dos lotes..
- Lotes de Chaparia - Agora, passamos a utilizar um modelo de geração de sub-lotes para a chaparia, deixando de gerar lotes diretamente 
                            na criação dos lotes do produto. A criação dos sub-lotes será realizada no módulo de corte-ML.
- Assistências - Removido permissões de inserção de nova assistência para alguns usuarios.
- Pedidos - Ajustado para mostrar titulos com VENCIMENTO à partir de 2022.
- Etiqueta Chaparia - Alterado para permitir somente visualização e filtro. Criação, atualização e exclusão foram bloqueados.











## Versão 1.7.33

*Data de lançamento: 30/09/2024*

Descrição da atualização do sistema.

- Cores - Adicionado botão para copiar o subgrupo e produtos referentes a ele.



## Versão 1.7.31 e 32

*Data de lançamento: 25/09/2024*

Descrição da atualização do sistema.

- Cores - Adicionado botão para imprimir gráfico do subgrupo da tinta selecionada.
- Cores - Ajustado alguns bugs relacionado ao nome da cor e subgrupo.
- Cores - Adicionado campo para tornar o item ativo ou inativo.
- Cores - Adicionado campo para informar o rendimento por M2 do subgrupo.
- Cores - Corrigido bug com porcentagem decimal.
- Ficha Técnica - Adicionados 3 novos campos para inserir a cubagem do item.








## Versão 1.7.30

*Data de lançamento: 19/09/2024*

Descrição da atualização do sistema.

- Programação - Ajustado consulta para concluir item, não estava desconsiderando etiquetas canceladas do Promob, impossibilitando a conclusão.
- Cores - Adicionado controle para cadastro de cores e configuração de tintas.




## Versão 1.7.28

*Data de lançamento: 05/09/2024*

Descrição da atualização do sistema.

- Programação - Aprimorada a velocidade de carregamento e ajustado o cálculo de registros e quantidades no botão 'Calcula Tempo'.
- Controle de estoque - Botão para adicionar novos produtos liberado para usuário Rafael.




## Versão 1.7.27

*Data de lançamento: 04/09/2024*

Descrição da atualização do sistema.

- Ficha Técnica - Alterado modelo para inserção de auditoria.
- Testes - Ajustado consulta para maior velocidade em abrir as etapas do teste.
- Assistências - Ajustado consulta para maior velocidade em abrir as observações da assistência.





## Versão 1.7.26

*Data de lançamento: 30/08/2024*

Descrição da atualização do sistema.

- Programação - Adicionado item AS041 na importação de lotes, sendo MATRIZ.
- Configurador de Produtos - Adicionado condição que não permite seguir enquanto não selecionar uma opção na Cor Ferragem caso o 
                            produto possua a categoria FERRAGEM CORES.
- Programação - Ao dividir lote, agora copia as infos dos setores MATRIZ também.





## Versão 1.7.26

*Data de lançamento: 30/08/2024*

Descrição da atualização do sistema.

- Programação - Adicionado item AS041 na importação de lotes, sendo MATRIZ.
- Configurador de Produtos - Adicionado condição que não permite seguir enquanto não selecionar uma opção na Cor Ferragem caso o 
                            produto possua a categoria FERRAGEM CORES.
- Programação - Ao dividir lote, agora copia as infos dos setores MATRIZ também.





## Versão 1.7.25

*Data de lançamento: 27/08/2024*

Descrição da atualização do sistema.

- Programação Funcionários - Ajustado consulta que não permitia fechar formulário quando funcionário era emprestado de outro setor e não 
                            atendia as 8 horas diarias.



## Versão 1.7.24

*Data de lançamento: 23/08/2024*

Descrição da atualização do sistema.

- Cadastro de Produto - Adicionado novo módulo de cadastro de produto para geração de PDFs, cadastro de especifações,
                            resumo e imagens do produto.



## Versão 1.7.23

*Data de lançamento: 21/08/2024*

Descrição da atualização do sistema.

- Análise de Produtividade CNC - Adicionado novamente produtos concluídos no CNC para análise de produtividade.
- Volumes Transportadoras - Adicionado mais uma condição para corrigir erros de digitação no titulo da carta de correção ao clicar no botão 
                            Atualizar.
- Carregamento NFS - Adicionado mais uma condição para corrigir erros de digitação no titulo da carta de correção ao clicar no botão 
                            Atualizar.
- Pedidos - Ajustado consulta para calcular notas atrasadas com inicio '900'.






## Versão 1.7.22

*Data de lançamento: 13/08/2024*

Descrição da atualização do sistema.

- Avaliações - Alterado adição de dias com a quantidade diminuída em 1. Estava adicionando as datas contando à partir do próximo dia de referência.



## Versão 1.7.21

*Data de lançamento: 13/08/2024*

Descrição da atualização do sistema.

- Testes - Adicionado módulo para cadastro de Testes, ex.(Nova espuma, Nova cola, etc.).
- Avaliações - Ajustado consulta que adicionava o chefe para o funcionário automaticamente.
- Produto Programação - Leve ajuste ao salvar componente com CNC, agora só pede se deseja conclusão se estiver selecionado como 'Concluído'.
- Avaliações - Ajustado para inserir uma avaliação manual com modelo 90/180 com opção de escolha de competências de 90/180.






## Versão 1.7.20

*Data de lançamento: 09/08/2024*

Descrição da atualização do sistema.

- Produto Programação - Adicionada flag para marcar quando a etiqueta do produto já foi impressa para o corte.



## Versão 1.7.19

*Data de lançamento: 07/08/2024*

Descrição da atualização do sistema.

- Volumes Transportadoras - Adicionado lista de itens de cada nota para as transportadoras.
- Análise de Produtividade - Ajustado consulta do bipado para itens somente matriz.
- Programação - Ajustado consulta que conclui o item, agora pega a maior data em vez de agrupar, assim resolvendo itens concluidos em diferentes dias.





## Versão 1.7.18

*Data de lançamento: 06/08/2024*

Descrição da atualização do sistema.

- Ficha Técnica - Liberado botão de Gerar Lotes para usuário Leonardo.
- Ficha Técnica - Adicionado campo de cubagem para o produto.
- Alteração de Projeto - Agora faz a alteração para um item GENÉRICO, e atualiza na programação sobre todos os itens que possuem 
                            este nome genérico.
- Programação - Adicionado campo que salva a data de bipagem da etiqueta na expedição, valor extraído do Promob.
- Análise de Produtividade - Adicionado campo Bip no setor MONTAGEM.







## Versão 1.7.17

*Data de lançamento: 05/08/2024*

Descrição da atualização do sistema.

- Avaliação de funcionário - Ajustado calculo para competências marcadas com a nota N/A. Agora conta como valor '5', ou seja, não afeta a nota 
                            negativamente.
- Avaliação de funcionário - Ao inserir avaliação já existente, informa a situação e cancela a operação.
- Produto Programação - Ajustado para assinalar uma caixa de seleção para concluir o item 'CNC A' ou 'CNC B'.





## Versão 1.7.16

*Data de lançamento: 02/08/2024*

Descrição da atualização do sistema.

- Avaliação de funcionário - Adicionado módulo para cadastros e movimentos de avaliações de funcionários.



## Versão 1.7.15

*Data de lançamento: 29/07/2024*

Descrição da atualização do sistema.

- Produto Programação - Ajustado layout.
- Programação - Ajustado para alterar datas de itens MATRIZ mesmo não possuindo lotes de montagem e/ou flag_montagem = -1.
- Carregamento NFS - Alterado tempo de impressão para 10 seg entre cada impressão e 15 seg para o sistema assinar os PDFs.





## Versão 1.7.14

*Data de lançamento: 05/07/2024*

Descrição da atualização do sistema.

- Produto Programação - Consulta para conclusão de item totalmente finalizado atualizada.
- Comissão Representante - Ajustado consulta que não trazia valor para representante caso não tivesse pagamento no faturamento.
- Etiqueta Ferragem - Adicionado critério para adicionar etiqueta de ferragem somente com itens não marcados como inativos.
- Pedidos - Adicionado botão para legenda de cores do módulo.






## Versão 1.7.13

*Data de lançamento: 26/06/2024*

Descrição da atualização do sistema.

- Assistências - Se for Cliente = 1, puxa os itens pelo numero do pedido, senão, puxa pela nota de faturamento.
- Assistências - Corrigido erro ao duplicar pedidos com datas vazia.
- Programação - Ajustado etiqueta para embalagem ML.
- Análise - Ajustado consultas para unir produtos dos modulos antigos com os novos de programação.
- Produto Programação - Agora ao alterar sequência na ficha técnica, atualiza instantaneamente na programação.
- Produto Programação - Agora ao concluir um componente que estava em CNC, se for a ultima etapa e a ultima peça, conclui o produto.








## Versão 1.7.12

*Data de lançamento: 24/06/2024*

Descrição da atualização do sistema.

- Relatório de Datas - Adicionado campo de valor total do pedido ao relatório para datas em Programação PCP Simplificada.
- Programação Produto - Ao alterar processo, atualiza o componente se possui alteração de projeto.
- Tempos de Processo - Ao teclar Enter nos campos, agora pula para o próximo campo e não mais pula a linha.





## Versão 1.7.11

*Data de lançamento: 21/06/2024*

Descrição da atualização do sistema.

- Configurador/Etiquetas - Incluso materiais de categoria FERRAGEM á impressão de etiquetas, utilizando o módulo de etiquetas Vidros/TS.
- Ficha Técnica - Agora componentes UNIFICADA não irão mais para o Corte Filial.
- Programação Produto - Ao avançar ou voltar processo, atualiza a sequência baseada pela Ficha Técnica.





## Versão 1.7.10

*Data de lançamento: 20/06/2024*

Descrição da atualização do sistema.

- Programacão - Alteração de data unitária adicionada novamente para produtos MATRIZ.
- Materiais - Adicionado formulário para auxiliar na inserção de novos itens, recebendo os itens do PROMOB.




## Versão 1.7.9

*Data de lançamento: 19/06/2024*

Descrição da atualização do sistema.

- Ficha Técnica - Agora itens ML2 não irão mais para o registro Matriz -> Filial.
- Produto Produção - Ajustado bug que não lia os itens para calcular a previsão de conclusão quando os itens perdiam referência na sequência.
- Produto Produção - Ao concluir componentes CNC's, agora calcula o tempo baseado no lote e não baseado à quantidade inserida.
- Produto Produção - Se o componente estiver com a maquina atual como algum CNC, abre o formulário de CNC, caso contrário, abre o formulário básico.
- Programação - Adicionado filtro de Estoque MON./PEND.







## Versão 1.7.8

*Data de lançamento: 17/06/2024*

Descrição da atualização do sistema.

- Programacão - Cor SNOW passa a ser considerada como CASTANHO.
- Programação - Usuário Adriana recebe permissão para alterar datas em massa.
- Produto Produção - Ajustado bug que não funcionava o filtro de máquina atual.





## Versão 1.7.7

*Data de lançamento: 14/06/2024*

Descrição da atualização do sistema.

- Programacão - Usuário Carmen recebe permissão para alterar datas em massa.
- Produtividade - Ajustado para análises de produtividade do corte e cnc funcionarem com os módulos novos de programação + o antigo.
- Produto Programacão - Ajustado bug que não inseria itens Matriz->Filial para o controle de estoque.





## Versão 1.7.6

*Data de lançamento: 11/06/2024*

Descrição da atualização do sistema.

- Programacão - Adicionado botão para troca de data em massa em itens MATRIZ para os usuários (Admin, Ananda, Marieli).
- Programacão - Botão de troca de data ao dar 2 clicks no campo data agora troca somente para itens FILIAL.
- Ficha Técnica - Ajustado bug para inserção de ITENS GENERICOS.
- Programacão - Agora ao trocar a data de itens MATRIZ, remove todos os sublotes de montagem e os recria (para todos os itens).
- Montagem - Ao gerar novo sublote manualmente, insere o item como MANUAL para não ser excluído ao trocar data na Programacão.
- Pedidos - Adicionado campo para filtrar o STATUS atual do pedido, para facilitar a busca.








## Versão 1.7.5

*Data de lançamento: 04/06/2024*

Descrição da atualização do sistema.

- Ficha Técnica - Ao gerar lote, agora não envia mais chapas terceirizadas e componentes "UNIFICADA" para o corte filial.
- Programacão Produto - Ao excluir o Produto, exlcui por completo (Programacão, Corte Filial, Reg. Matriz -> Filial).
- Programacão Produto - Ao editar o Produto, edita por completo (Programacão, Corte Filial, Reg. Matriz -> Filial).
- Programacão Produto - Ajustado Qtde/Lote na etiqueta do corte.
- Programacão Produto - Corrigido bug que não permitia calcular a previsão de término para itens que passavam de 24 horas.







## Versão 1.7.4

*Data de lançamento: 31/05/2024*

Descrição da atualização do sistema.

- Programacão Produto - Adicionado botão para calcular o tempo de previsão de conclusão de cada produto.
- Programacão Produto - Adicionado tempo estimado de produção do componente no setor atual.
- Ficha Técnica - Seleção de "Somente Corte" removida da ficha.
- Ficha Técnica - Ajustado problema que inseria todos os itens quando gerado lote de ML2.
- Programacão Produto - Botão de avançar agora da opção de inserir a quantidade em parcelas produzida no setor. Seleção de Concluído sempre 
                            abrirá selecionado.
- Programacão Produto - Botão de edição do lote adicionado para ajuste de data ou quantidade do lote.
- Corte ML - Ajustado bug que não concluia o item automaticamente no setor do corte ao concluir.
- Programacão Produto - Adicionado consulta para inserir produto no Registro Matriz -> Filial ao gerar um lote novo.
- Programacão Produto - Adicionado pergunta para inserção de lote de montagem ao gerar um lote novo.
- Programacão Produto - Adicionado consulta para remover todos os produtos que não possuem componente na programação. Ocorre em itens somente
                             Filial












## Versão 1.7.3

*Data de lançamento: 24/05/2024*

Descrição da atualização do sistema.

- Comissão Representante - Ajustado para analisar titulos a partir de 2022. (Financeiro)
- Carregamento Expedição - Adicionado hora no campo DATA_EMISSAO e ordenado por data de emissão de Nota fiscal. (Expedição)
- Configurador de item Corte Filial - Agora não mais adiciona o item na lista com id baseado na origem, mas com auto incremento.
                            Alterado em: Configurador (normal e especial) e gerador de lote pela Ficha Tecnica. (Todos)
- Programacão Produto - Adicionado campo de Lote no histórico do produto para filtragem. (Todos)
- Programacão Produto - Agora calcula o tempo baseado apenas nas maquinas que ainda não operaram o componente. (Todos)







## Versão 1.7.2

*Data de lançamento: 21/05/2024*

Descrição da atualização do sistema.

- Etiqueta Corte - Agora a etiqueta do corte irá possuir a sequência do item separado por linha para inserção de data e hora em cada máquina. (Todos)
- Visualizador de Lotes - Adicionado filtro por produto. (PCP)
- Sequência em Massa - Adicionado campo de categoria no módulo pois um compontente pode estar em mais de 1 categoria. (Todos)





## Versão 1.7.1

*Data de lançamento: 20/05/2024*

Descrição da atualização do sistema.

- Configurador de Produto - Ajustado bug que fazia com que produtos com mais de 1 componente flex, na categoria, não fossem inseridos
                            no relatório de etiquetas de chapas flex. (Filial)
- Produção Produto - Adicionado botão de ajuda. (Todos)




## Versão 1.7.0

*Data de lançamento: 08/05/2024*

Descrição da atualização do sistema.

- Ficha Técnica - Adicionado botão para geração de lotes no novo modelo. (PCP)
- Produto Programacão - Adicionado módulo para controle do produto através da programação da fábrica. Agora é controlado por produto agrupado
                            com modelo árvore para visualização. Produtos são controlados pela sequência cadastrada na ficha técnica.
- Ficha Técnica - Agora para controlar produtos que estavam no TemposCNC basta adicionar com a categoria UNIFICADO. (Todos)
- Tempos - Não será mais utilizado. (Todos)
- Produto Programação - Adicionado botão para impressão de etiquetas para o setor corte. (Corte)







## Versão 1.6.8

*Data de lançamento: 26/04/2024*

Descrição da atualização do sistema.

- Carregamento Filial - Adicionado módulo para Carregamento Filial, agora é possível selecionar os itens que deseja carregar, impedindo que aconteça
                            de não imprimir determinado item. (Faturamento - Expedição)
- Programacão - Adicionado Cliente "DESIGN COMERCIO DE MOVEIS S/A" como cliente exigente. (Todos)




## Versão 1.6.7

*Data de lançamento: 19/04/2024*

Descrição da atualização do sistema.

- Programacão CNC - Adicionado botão para adicionar AJUSTE DE PROJETO, sendo que se for menor que 1 hora, irá adicionar como SETUP. Caso seja maior que 1 hora irá adicionar 1 hora 
                            como SETUP e o restante como AJUSTE DE PROJETO. O mesmo serve para TREINAMENTO. (CNC)
- Assistencias - Adicionado campo de Data quando o Status é alterado para VERIFICAR. (Assistencias)




## Versão 1.6.6

*Data de lançamento: 15/04/2024*

Descrição da atualização do sistema.

- Programação PCP - Adicionado campo de Estofaria para poder atualizar a quantidade de funcionarios disponiveis no setor, e assim, poder atualizar a tabela com mais precisão. 
                            (Comercial - PCP)
- Etiquetas Chapa Flex - Adicionado novo módulo para controle de chaparia FLEX, onde ao configurar um produto para corte, é gerado uma etiqueta para a chapa cadastrada na 
                            Ficha Tecnica. Muito semelhante ao controle de etiquetas de Vidros e TS. (Filial)
- Corte Filial - Liberado opção de excluir para usuario Vanderson. (Vanderson - PCP)
- Corte Filial - Adicionado botão para adicionar ou remover urgência em item de corte. (PCP - Administrativo)






## Versão 1.6.5

*Data de lançamento: 10/04/2024*

Descrição da atualização do sistema.

- Outlet - Adicionado botão para voltar pedido de outlet. (Comercial)
- Pedidos - Alterado cor de itens 'liberados' para laranja pois estava dando conflito com itens FINALIZADOS. (Faturamento)




## Versão 1.6.4

*Data de lançamento: 08/04/2024*

Descrição da atualização do sistema.

- Ficha Tecnica - Liberado acesso para usuario Everson. (Faturamento)
- Volume Transportadora - Removido notas com natureza 692302. (Faturamento)
- Carregamento NFS - Mantido notas com natureza 692302. (Expedição)
- Programacão CNC - Ao adicionar valor parcial em componente CNC, se o componente não possuir tempo no CNC selecionado, irá encaminhar para o produto no modulo Tempos CNC. (CNC - Volnei)
- Analise PCP e Programacão CNC - Ajustado bug que recebia nulo ao calcular tempos quando possuisse apenas maquinas que não sejam de CNC A a CNC D. (CNC)







## Versão 1.6.3

*Data de lançamento: 22/03/2024*

Descrição da atualização do sistema.

- Pedidos - Adicionado campo de Transportadora Redespacho. (Faturamento)
- Controle Estoque - Agora calcula também para itens da filial, somente para nogueira. Somando nogueira + castanho e verificando todos os itens. (PCP)




## Versão 1.6.2

*Data de lançamento: 19/03/2024*

Descrição da atualização do sistema.

- Pedidos - Ajustado para entrar um item único ao gerar carregamento para filial. (Faturamento - Financeiro)
- PCP Simplificado - Adicionado tabela para inserção de meta no módulo de PCP Simplificado. (Comercial)
- Programacão CNC - Adicionado campo de DATA para gravar o setup e a quantidade parcial como historico. (CNC - Volnei)
- Programacão CNC - Agora é obrigatorio ter pelo menos 1 setup adicionado por componente antes de conclui-lo. (CNC - Volnei)
- Programacão CNC - Adicionado campo que informa a quantidade de setups ja inseridos no componente. (CNC - Volnei)
- Pedidos - Adicionado campo Representante. (Faturamento)








## Versão 1.6.2

*Data de lançamento: 15/03/2024*

Descrição da atualização do sistema.

- Programacão CNC - Adicionado campos para salvar horario de INICIO e FIM de setup nos componentes CNC ao dar 2 cliques no produto. (Volnei - CNC)
- Tempos CNC - Agora, ao alterar ou inserir linha, irá inserir uma linha em uma tabela de historicos, referenciando a data atual do sistema. (Todos)
- Visualizador de Lotes - Agora calcula os itens da filial como nogueira, para isso, foi alterado algumas consultas e adicionado o Tingimento "-" como Nogueira. (PCP)
- Montagem - Liberado para usuario Volnei poder criar lotes de montagem. (Volnei)






## Versão 1.6.1

*Data de lançamento: 14/03/2024*

Descrição da atualização do sistema.

- Pedidos - Ajustado consulta que estava trazendo itens para faturar em filtro TODOS. (Faturamento - Financeiro - Comercial)
- Programacão - Liberado permissão para acessar modulo Status da programação para User Volnei. (Volnei)
- Visualizador de Lotes - Ajustado consulta para contar como estoque itens que estão no Registro Matriz -> Filial. (Todos)
- Ficha Técnica - Ajustado para quando um item ir para o corte e estiver com o campo Unidade = FILIAL na Ficha Técnica, 
                            entrar para o Registro Matriz -> Filial ao concluir no corte. (Todos)






## Versão 1.6.0

*Data de lançamento: 11/03/2024*

Descrição da atualização do sistema.

- Pedidos - Agora o setor Financeiro poderá acessar o módulo para permitir o pedido para ser faturado. (Faturamento - Financeiro - Comercial)
- API - Alterado campo Pedido para informar o "ORÇAMENTO" referente ao Valorizza. (Todos)




## Versão 1.5.5

*Data de lançamento: 27/02/2024*

Descrição da atualização do sistema.

- Ficha Tecnica - Adicionado campo para informar se lote de corte filial é URGENTE. (PCP)
- API - Trocado tempo de atualização das tabelas API para 30 minutos.




## Versão 1.5.4

*Data de lançamento: 27/02/2024*

Descrição da atualização do sistema.

- Corte Filial - Adicionado campo para informar se é URGENTE ou não o produto para corte. (Todos)
- Ficha Técnica - Adicionado pergunta para inserir na montagem matriz ao gerar lote SOMENTE CORTE. (PCP)
- Ficha Técnica - Adicionado botão para duplicar o produto. (Todos)





## Versão 1.5.3

*Data de lançamento: 20/02/2024*

Descrição da atualização do sistema.

- Programação - Adicionado campo e botão para dividir a quantidade de um item na programação. (Admin)
- Ficha Técnica - Adicionado campo para informar se o componente possui par ou não. (Todos)
- Ficha Técnica - Permissões de admin adicionadas para usuário Vanderson. (Admin)





## Versão 1.5.2

*Data de lançamento: 14/02/2024*

Descrição da atualização do sistema.

- Etiquetas - Ajustado quantidade dos volumes nas etiquetas brancas, alterado descrição do volume nas etiquetas brancas e amarelas. Para brancas (VOL ITEM) e para amarelas
                            (VOL N). (Todos)
- Analise Produtividade - Ajustado para não contabilizar a quantidade de produtos com início de codigo MTR. (Todos)
- Analise Produtividade - Ajustado campo %, agora mostra o valor em porcentagem e não fracionado como era antes. (Todos)
- Ficha Técnica - Adicionado campo para registro de Peso Pé 3. (PCP)
- Rel. Carregamento Filial - Adicionado caixa para marcação com nome de COMPLEMENTO. (Expedição)
- Programação - Adicionado filtro para produtos com código "MTR", localizado abaixo do filtro "Status". (Todos)








## Versão 1.4.0 e 1.5.0

*Data de lançamento: 30/01/2024*

Descrição da atualização do sistema.

- Tempos CNC - Alterado modo de cadastro de tempos no módulo Tempos CNC, agora mostra somente o tempo que foi cadastrado como padrão. Para acessar o cadastro de tempos em máquinas,
                             é necessário dar 2 clicks no nome do produto para abrir um novo formulário de cadastro de tempos. Podendo cadastrar infinitas máquinas agora. (Todos)
- Programação CNC - Alterado layout para atender requisitos de multiplas máquinas, basta selecionar a maquina desejada agora. (Volnei - CNC)
- Programação - Ajustado bug que não permitia a pintura concluir itens que não possuiam Tingimento. (Pintura - Estoque)
- Ficha Técnica - Adicionado campo Controle Estoque para controlar o que vai contabilizar no estoque montagem. (Montagem)






## Versão 1.3.8

*Data de lançamento: 19/01/2024*

Descrição da atualização do sistema.

- Programação CNC - Adicionado tabela para registros de conclusão de componente. Servirá como histórico para relatórios posteriormente. (Todos)
- Manutenção - Adicionado Frequência Quinzenal. (Todos)




## Versão 1.3.7

*Data de lançamento: 15/01/2024*

Descrição da atualização do sistema.

- Manutenção - Adicionado botões "Novo" e "Historico", para ir ao novo registro e para abrir um formulário de historico (2 clicks na linha abre historico filtrado). (Manutenção - Todos)
- Analise PCP - Ajustado consulta para inserir lotes para o Corte ML. (PCP)
- Programação - Agora ao importar, a consulta pega somente 1 registro do produto, mesmo ele possuindo mais de 1 tecido em sua configuração. (PCP - Comercial)
- Pedidos - Ajustado consulta para poder filtrar por observações administrativas. (Faturamento)






## Versão 1.3.6

*Data de lançamento: 19/12/2023*

Descrição da atualização do sistema.

- Tecido - Foi implantado controle de status do tecido como ativo e inativo. (Corte Tecido - Admin)
- Manutenção - Implantado botão para envio de mensagem via WhatsApp em manutenção selecionada. (Manutenção - Todos)
- Manutenção - Implantado envio das 10 tarefas mais urgentes para a manutenção via WhatsApp. (Manutenção - Todos)





## Versão 1.3.5

*Data de lançamento: 15/12/2023*

Descrição da atualização do sistema.

- Montagem - Foi revisto a função para geração de lotes, algumas pequenas modificações. (Montagem - PCP)
- Manutenção - Implementado novo módulo para controle de manutenções. (Manutenção - Todos)




## Versão 1.3.4

*Data de lançamento: 11/12/2023*

Descrição da atualização do sistema.

- Carregamento - Adicionado campo PEDIDO no formulario de carregamento e consulta de volumes transportadoras. (Marieli - Expedição)
- Programação - Usuario Vanderson agora pode alterar datas na programação. (Vanderson)




## Versão 1.3.3

*Data de lançamento: 30/11/2023*

Descrição da atualização do sistema.

- Programação - Ajustado para quando abrir uma assistência através da programação, informa quando não há valor no campo do ID da assistência. (Todos)
- Programação - Ajustado para quando usuários que não forem referentes à estofaria, não adicionar a data ao CONCLUIR. (Estofaria - Embalagem)
- Programação - Ajustado para exigir conclusão na estofaria somente em itens que possuírem ao menos 1 tempo de processo registrado no setor ESTOFARIA. (Estofaria - Embalagem)
- Programação - Ajustado para contabilizar em nogueira a cor OAK. (Estoque)
- Programação - Ajustado para etiqueta contabilizar como nogueira as cores SNOW e OAK. (Estoque)
- Site - Adicionado consultas para atualizar tabelas para o site, a consulta executa a cada 5 minutos no formulário Index. (Admin)
- Assistencias - Adiionado campo "Incidências" para se referir a quantidade de vezes que o produto teve assistencias. (Faturamento - Assistencias)
- Tecidos - Adicionado campo para inserir a descrição do tecido dada pelo fornecedor. Ao inserir o nome interno do tecido e ir para o próximo campo, se possuir cadastro no Promob,
                            irá inserir o nome automaticamente. (Corte Tecido)










## Versão 1.3.2

*Data de lançamento: 20/11/2023*

Descrição da atualização do sistema.

- Análise PCP - Ajustado para não enviar itens M.L para Corte Filial ao Validar o item. (PCP)
- Montagem - Ajuste para utilizar o módulo de Estoque Montagem ao dar 2 clicks no produto. Agora os itens são controlados por cor, como NOGUEIRA e CASTANHO, possuindo
                            cada um, lado ESQUERDO e DIREITO. (Montagem)




## Versão 1.3.1

*Data de lançamento: 14/11/2023*

Descrição da atualização do sistema.

- Ficha Técnica - Ajustado para inserir itens M.L com chaparaia para Corte Filial. Inserir 1 produto por vez. (PCP)
- Montagem - Ajuste para concluir lotes de montagem somente com estoque do produto. Ao marcar o campo de concluído, irá abrir o módulo de estoque para remover a quantidade montada, basta
                            selecionar os itens e dar a baixa. Não irá aceitar concluir lotes que são maiores do que o estoque, cancelando o evento. (Montagem)
- Ficha Técnica - Ajustado para enviar as observações para o Corte Filial atravéz da solicitação de "Somente Corte". (PCP - Corte)
- Ficha Técnica - Adicionado campo de Unidade para o Produto também, para controle de filtro. (PCP)






## Versão 1.2.21

*Data de lançamento: 01/11/2023*

Descrição da atualização do sistema.

- Corte Filial - Alterada consulta em que removia itens sem componente no Corte Filial, agora remove apenas CADEIRAS, POLTRONAS ou BANQUETAS. (Admin - Corte-ML - PCP)
- Programação - Alterada consulta quando fecha o formulário frmStatus, removendo o uso da tabela "componentes" para subtrair itens do estoque. (Todos)
- Tabela "componente" passa a ser inutilizada. (Todos)
- Estoque Montagem - Adicionado novos campos para inserção de cores NOGUEIRA E CASTANHO junto com lados ESQUERDO E DIREITO. (Admin - Montagem - Produção)
- Estoque Montagem - Adicionado controle de remoção de componentes por escolha de quantidade NOGUEIRA ou CASTANHO, com controle de estoque máximo de retirada. (Admin - Montagem)
- Tabela e modulo Ficha "Matriz" passa a ser inutilizada. Agora será apenas uma Ficha técnica. Ficha "Matriz" ainda disponivel para possiveis consultas por um tempo determinado. (Todos)
- Comissão Representantes - Ajustado consulta de comissão futura, agora calcula baseado no pagamento liquido se o valor do pagamento liquido for <> 0. (Admin - Financeiro)









## Versão 1.2.20

*Data de lançamento: 26/10/2023*

Descrição da atualização do sistema.

- Outlet - Formulário ajustado para permitir varios pedidos ao mesmo tempo em um único item. Adicionado também, visualização de qualquer venda no mesmo formulário, sem que tenha que
                            entrar item por item. (PCP - Embalagem - Expedição)
- Histórico Funcionarios - Ajustado para permitir fechar o formulário quando tiver funcionarios com menos de 8 horas de carga horaria. Funcional apenas para Douglas e Embalagem. 
                            (Embalagem)
- Análise de Produtividade - Ajustado para abrir o módulo mais rápido. (Todos)





## Versão 1.2.19

*Data de lançamento: 23/10/2023*

Descrição da atualização do sistema.

- Visualização de Atualizações - Implementado método para todos usuários verem as atualizações mais recentes do OpSisttems. (Todos)
- Histórico Funcionarios - Agora quando adicionar usuários no histórico, será feito uma consulta que contará as horas totais de cada funcionario. 
                            Se algum funcionario não atingir a carga horária de 8 horas, um aviso aparecerá e não deixará fechar o sistema até que seja ajustado. (Todos)
- Programação - Adicionado novo relatório para produtos pendentes, relatório se baseia nos filtros aplicados na programação. (Todos)
- Outlet - Adicionado campo COD para alteração caso o item não apareça na impressão. (Comercial - Embalagem)






## Versão 1.2.18

*Data de lançamento: 20/10/2023*

Descrição da atualização do sistema.

- Estoque - Ajustado para descontar do estoque somente quando forem usuarios referente ao estoque. Também adicionado a mesma regra para os outros setores. (Admin - Estoque - PCP)
- Programação - Agora no formulario de status do item da programação, é possível colocar o ID da assistencia referente e ao clicar no botão, será redirecionado para um form de visualização da assistencia. (Todos)




## Versão 1.2.17

*Data de lançamento: 13/10/2023*

Descrição da atualização do sistema.

- Ficha Tecnica - Feito alguns ajustes para não retornar erro ao editar linhas. (Admin - Todos)
- Ficha Tecnica - Ajustado para não dar problema ao colocar dimensão de produto com duas medidas em uma, exemplo: Comprimento = 52X32. Funciona apenas com o "X" em maiúsculo. (Admin - Todos)
- concluidos - Adicionado campos Complemento 1 e Complemento 2. (Admin - Todos)
- Assistencias - Adicionado nova forma de registro de observações, agora utiliza uma tabela para as observações. Abre ao dar 2 clicks. (Admin - Assistencias)






## Versão 1.2.16

*Data de lançamento: 06/10/2023*

Descrição da atualização do sistema.

- Analise Produção Filial - Corrigido consulta que estava ocultando algumas datas. (Admin - PCP)
- Visualizador de Lote - Ajustado modelo de modulo, agora os dados são salvos em uma tabela, e para atualizar, basta clicar no botão. O botão, alem de atualizar, 
                            vai analisar até onde o produto atende com o estoque atual + montagem. (Admin - PCP)
- Corte - Agora, ao validar o produto, chama modulo para descontar componentes em estoque. Antes era ao imprimir. (Admin - Corte - Volnei)
- Ficha Tecnica - Inserido novo botão para copiar sequência de um componente para outro. (Admin - PCP)
- Programação - Adicionado nova opção para corte costura "ALT. PROJETO". (Admin - Corte tecido)
- Registro Matriz -> Filial - Adicionado filtro "Entrada estoque". (Admin - PCP)








## Versão 1.2.15

*Data de lançamento: 29/09/2023*

Descrição da atualização do sistema.

- Ficha Tecnica Filial - Corrigido bug para geração de lotes M.L-Gala, pois possuem itens que vão para o CNC. (Admin - PCP)
- Comissão Representantes - Alterado calculo realizado no Desconto, como foi acrescentado a possibilidade de credito(+) ou debito(-), foi feito alterações para descontar ou acrescer o crédito. (Admin - Financeiro)
- Ficha Tecnica Filial - Adicionado campo para inserção de peças DXF em componentes. (Todos)
- Ficha Tecnica Filial - Corrigido bug que inseria somente 1 DXF ao configurar o item, mesmo possuindo mais de 1 quantidade na programação ou até mesmo no componente. (Todos)
- Materiais - Removido campo "C. Certo" e adicionado campo "Pasta", este campo referencia onde o sistema irá procurar para salvar o DXF ao configurar o item. (Admin - PCP)







## Versão 1.2.14

*Data de lançamento: 22/09/2023*

Descrição da atualização do sistema.

- Ficha Tecnica Filial - Implementações para geração de lotes de produção para a matriz. (Admin - PCP)
- Ficha Tecnica Filial - Campo controle adicionado para utilizar como controle na geração de lotes de produção. (Admin - PCP)
- Ficha Tecnica Filial - Agora a ficha tecnica se tornará uma para atender todas as Unidades. (Admin - PCP - Produção)
- Ficha Tecnica Filial - Layout levemente alterado. (Admin - PCP - Produção)
- Pedidos Faturamento - No relatório de faturamento o campo de transportadora foi alterado para mostrar Redespacho quanto tiver, se não, mostra transportadora. (Admin - Faturamento)
- Programação - Corrigido consulta para atualizar o "PENDENTE", agora prioriza produtos que estão marcados como Urgente. (Admin - Produção)
- Montagem - Corrigido bug que derrubava sistema assim que clicasse para marcar em verde itens que continham data sem hora. (Admin - Montagem)









## Versão 1.2.13

*Data de lançamento: 06/09/2023*

Descrição da atualização do sistema.

- Ficha Tecnica Filial - Ajustes para importação da Ficha matriz para ficha Filial. (Admin)
- ProgramaçãoPCP - Adicionado botão para abrir um popup sobre a quantidade disponivel para venda até 21/12/2023. (Admin - Comercial)
- ProgramaçãoPCP - Agora o campo ValorTotal informa a (quantia vendida - a quantidade ja produzida (ou atrasada)). (Admin - Comercial)





## Versão 1.2.12

*Data de lançamento: 16/08/2023*

Descrição da atualização do sistema.

- Assistencias - Adicionado nova coluna e adicionado botão desfazer filtros. (Admin - Faturamento)
- Programação - Adicionado botao para ver historico de alteração de datas. (Admin - PCP)
- Programação - Dias de produto em produção liberado para usuario Carmen. (Admin - Atendimento)
- Usuarios - Usuario Débora trocado para Everson. (Admin)






## Versão 1.2.11

*Data de lançamento: 07/08/2023*

Descrição da atualização do sistema.

- Tempos - Adicionado botão para inserir histórico dos tempos em uma tabela reserva. Este historico é basicamente uma copia de "tempos" com a adição de uma data. Foi feito assim
                            pois a tabela tempos está envolvida com muitas outras e a manutenção seria muito grande. (Admin - Matheus)
- ProgramaçãoPCP - Adicionado formatação condicional para previsão de férias em dezembro. (Admin - Maira)
- Programação - Adicionado novo filtro para nomear o Tecido na importação de pedidos, 'VARIAVEL >= 105 e <= 109' para linhas novas de couro (5000 e 6000). (Admin)
- Carregamento - Agora o filtro de notas ignora qualquer CFOP, antes tinha uma condição de CFOPs. (Admin - Carregamento - Faturamento)
- Carregamento - Consulta estava mostrando etiquetas duplicadas, adicionado um GRUP BY para solucionar com MÁX em LOCALIZAÇÃO. (Admin)







## Versão 1.2.10

*Data de lançamento: 04/08/2023*

Descrição da atualização do sistema.

- AnalisePCP - Ajustado inserção de data_validação no corte, estava enviando a data invertida, utilizando agora o fncConverteDataSQL. (Admin - PCP)
- Pedidos - Ajustado numero de dias em produção, estava dando erro na consulta pois ao trocar o filtro executava uma consulta desatualizada. (Admin - Faturamento - Financeiro)




## Versão 1.2.9

*Data de lançamento: 01/08/2023*

Descrição da atualização do sistema.

- Carregamento - Ajustado para aparecer notas com CFOP 5915 e 6915. (Carregamento - Faturamento)
- Programação - Usuario Douglas agora tem permissão para alterar setor pintura também. (Douglas - Admin - Embalagem)




## Versão 1.2.8

*Data de lançamento: 28/07/2023*

Descrição da atualização do sistema.

- Carregamento - Ajustado para aparecer transportadora MOVEIS VAIRES (146). (Expedição)
- Programação - Adicionado novo campo para visualização de quantidade de dias desde que o pedido foi emitido. (Admin - Maira)
- Carregamento - Ajuste no python para notas com 2 paginas no PDF, nao testado para mais de 2 paginas. (Admin - PCP)
- Outlet - Adicionado relatorio para todos os itens disponiveis no outlet/showroom, através de um filtro por grupo é possível escolher quais grupos gerar o relatorio. (Admin - Comercial)






## Versão 1.2.7

*Data de lançamento: 20/07/2023*

Descrição da atualização do sistema.

- Carregamento - Ajustado para aparecer etiquetas em notas com pedidos agrupados. (Expedição)
- Carregamento - Ajustado API Python para editar PDF das Notas, agora procura pelos campos e escreve em baixo. (Expedição)
- Gerador de Lote - Ajustado para calcular lotes da filial que estão no corte matriz. (Admin - PCP)





## Versão 1.2.6

*Data de lançamento: 18/07/2023*

Descrição da atualização do sistema.

- Carregamento - Adicionado controle de SIM/NÃO no botão Assinar. (Expedição)
- Controle Estoque - Adicionado botão para abrir TABELA do estoque para ajustes manuais, abre somente com senha: "mgts0067". (Admin - PCP)
- Modulo que fecha automaticamente para atualização ajustado com Application.Quit. (Admin)
- Pedidos - Alterado tamanho de campos observações. (Admin - Maira - Marieli)






## Versão 1.2.5

*Data de lançamento: 17/07/2023*

Descrição da atualização do sistema.

- Carregamento - Ajuste de notas que possuem dois endereços de entrega, aparece as duas notas. (Expedição)
- Programação - Troca de cor em produto com urgencia e cliente exigente, solicitação Alberto. (Todos)
- Carregamento - Botao Atualizar adicionado e botao Assinar NF libera quando o Carregamento liberar. (Expedição)
- Programação - Adicionado controle na programação filial, onde ao concluir item que possui controle de estoque, mas não possui estoque, 
                            solicita se o user deseja descontar a quantia do tingimento contrario. (Pintura-ML)
- Corte Filial - Ao concluir item com "SEMI" escrito na frente, envia para estoque. (Corte-ML)







## Versão 1.2.4

*Data de lançamento: 14/07/2023*

Descrição da atualização do sistema.

- Pedidos - Adicionado observações dos pedidos no modulo Pedidos. (Admin - Maira - Marieli)
- Pedidos - Adicionado na tabela de Pedidos, os dias corridos desde que o pedido entrou para o Promob. (Admin - Maira - Marieli - Adm)
- Carregamento - Novos campos adicionados na tabela de Carregamento Expedição (OBS e Data emissao da nota). (Admin - Expedição)
- Carregamento - Novo modulo para impressão de etiquetas NFS. (Admin - Expedição)
- Carregamento - Ao pressionar 2 clicks no Cliente, abre os itens da nota. (Expedição)
- Carregamento - Filtro para Transportadora agora mostra somente transportadora ou em "aberto" ou "carregado". (Admin - Expedição)








## Versão 1.2.3

*Data de lançamento: 07/06/2023*

Descrição da atualização do sistema.

- Alterado tempo para fechar o sistema na atualização, agora em 15 segundos. (Admin)
- Agora ao alterar qualquer campo do produto em Ficha Filial, os campos ficam em amarelo no form do item detalhado. Quando embalagem alterada o 
                            produto fica em vermelho e em ordem decrescente para que seja de facil percepção essa alteração. (Admin - PCP)




## Versão 1.2.3

*Data de lançamento: 07/06/2023*

Descrição da atualização do sistema.

- Auditoria implantada em form Tempos. (Admin - PCP - Produção)
- Adicionado campo de Saldo Nogueira em Visualizador de Lotes para visualização de lotes descontados somente nogueira. (Admin - PCP)
- Adicionado campo de texto ao dar entrada de produto em controle de estoque. (Admin - PCP - Estoque)
- Ajuste de intens setados para FINALIZADO mesmo quando o item estiver concluido na programação ja. (Admin - Marieli)
- Adicionado campo de transportadora no formulario de volumes transportadoras. (Admin - Marieli)







## Versão 1.2.2

*Data de lançamento: 05/06/2023*

Descrição da atualização do sistema.

- Correção de bug em estoque filial, produtos cortados la nao inseriam no estoque e produtos do corte matriz estavam indo duplicados. (Filial)
- Ajuste para buscar somente ultima carta de Correção baseada pela nota para area de transportadoras. (Marieli - Expedição)
- Ajustado itens SNOW para descontar na cor Nogueira ao baixar do estoque matriz. (Estoque)
- Ajustado para inserir itens concluidos no corte Filial para registro de Matriz->Filial. (Filial - PCP)
- Agora o produto só finaliza apos clicar em "Atualizar" no Form Pedidos, que verifica as etiquetas lidas no Promob e 
                            ai sim marca como FINALIZADO. (ADM - Marieli)







## Versão 1.2.0

*Data de lançamento: 22/05/2023*

Descrição da atualização do sistema.

- Impementado novo controle de carregamento na expedição. (Faturamento - expedição)
- Adicionado usuario Edson.
- Aumentado campo de texto do PRODUTO em Tempos CNC. (Rafael - CNC)
- Adicionado novos campos para visualização em Carregamento NFS. (Faturamento - Expedição)
- Ajustado para toda vez que zerar as notas, o campo OBS fica limpo tambem em Carregamento NFS. (Faturamento - Expedição)
- Ajustado troca de datas para alterar a montagem somente em lote que tenha a quantidade suficiente. Alterado consulta no botao Alterar Data. (Montagem - Admin)
- Ajustado visualizador de lotes. (PCP - Admin)
- Ajustado impressao de etiquetas de vidros, estava com problemas para imprimir mais de 1 quantidade de VD ou TS. (PCP Filial - Admin)
- Ajustado filtro STATUS para setor Corte Tecido. (Corte Tecido - Admin - Edson)
- Consulta Programação alterada para prioridade em itens Urgentes. (All)
- Corte tecido agora pode filtrar por pendente no Estoque. (Corte tecido)













## Versão 1.1.4

*Data de lançamento: 03/05/2023*

Descrição da atualização do sistema.

- Ajuste em Visualizador de Lote: Não estava abrindo pois havia uma divisão por 0.
- Atualização: Inserido novos botões de Ajuda em Visualizador de Lote e em Programação PCP Simplificada.
- Removido restrição de adicionar funcionário para produção no setor Costura por tempo indeterminado.





## Versão 1.1.3

*Data de lançamento: 28/04/2023*

Descrição da atualização do sistema.

- Ajuste em Status Programação: Produtos com TEC agora podem ser concluidos no setor EMBALAGEM.
- Atualização: Visualizador de produto concluido em CNC no modulo analise produção.
- Atualização: Módulo Assistencias agora recebe um botão de play no meio da foto quando for video.
- Atualização: Módulo Corte Filial agora ao abrir relatorio de etiquetas, irá marcar os itens como impresso.






## Versão 1.1.2

*Data de lançamento: 25/04/2023*

Descrição da atualização do sistema.

- Ajustado para embalagem conseguir concluir assistencia mesmo sem os setores anteriores terem concluido.
- Ajustado para marcar em amarelo quando alterar volume de item em Ficha Filial.
- Ajustado para inserir somente itens da filial em controle de estoque ao concluir um item no corte matriz.
- Ajustado para poder concluir itens com TEC no setor embalagem.






## Versão 1.1.1

*Data de lançamento: 14/04/2023*

Descrição da atualização do sistema.

- No modulo Status Programação, adicionado mais um status em "embalagem" no setor embalagem. Controle para conluir produtos somente quando seus antecessores forem concluidos antes.
- No módulo Tempos, ao dar 2 clicks agora pinta de amarelo o nome para sinalizar que tem dados fictícios(somente admin). Adicionado novo campo para controle de itens entre matriz e filial.
- No modulo Assistencias, adicionado status "envio de componente" no campo RESOLUÇÃO.
- No modulo Programação PCP, adicionado 2 novas colunas, informando a quantidade disponivel para alocação de pedidos e o Saldo acumulado de produtos.
- Adicionado controle de estoque entre Matriz → Filial, ao concluir lote no corte, entra no estoque e quando chegar na filial pode ser feita a recontagem e reajustar o lote no modulo REG. MATRIZ FILIAL.
- Adicionado HTML para versionamento.
- Ajuste de etiquetas duplicando na programação.









## Versão 1.1.0

*Data de lançamento: 30/03/2023*

Descrição da atualização do sistema.

- Ajustado divergencia em Relatório de comissao representante.
- Ajuste em etiquetas programação para inclusao de volumes.
- Adicionado setor de Pintura no modulo Status Programação.
- Adicionado quantidade produzida no setor de corte filial. Ao concluir item, agora pede quando fecha o relatorio de etiqueta.





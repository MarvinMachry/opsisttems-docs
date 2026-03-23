## 18/03/2026 — Impressão de etiquetas (Programação Filial)

**Participantes:** Marvin, Alberto  
**Tags:** `programação` `etiqueta` `filial`

!!! warning "Problema"
    Impressão de etiquetas de itens divididos gerava etiquetas erradas.

!!! success "Decisão"
    Imprimir um item por vez quando ocorrer esse caso.

!!! info "Motivo"
    Agrupar gera poucas etiquetas.  
    Não agrupar multiplica o tingimento.

!!! tip "Impacto"
    Itens divididos na programação filial.
<body>
    <div class="container">
        <h1>Diário de Conversas Técnicas para Registro</h1>
        <ul class="version-list">
            <li onclick="toggle(this)">
                <span class="version">Impressão de etiquetas de itens divididos na Programação Filial</span>
                <span class="date">18/03/2026</span>
                <span class="date">Marvin - Alberto</span>
                <div class="details">
                    <p>Descrição de conversa.</p>

                    <ul class="changelog">

                    <li>
                        <strong>Problema:</strong><br>
                        Impressão de etiquetas de itens que foram divididos na programação gera etiquetas erradas.
                    </li>

                    <li>
                        <strong>Decisão:</strong><br>
                        Imprimir um item por vez quando houver esse caso.
                    </li>

                    <li>
                        <strong>Motivo:</strong><br>
                        Se agrupar a consulta ela gera poucas etiquetas, se nao agrupar ele multiplica o tingimento dentro da etiqueta.
                    </li>

                    <li>
                        <strong>Impacto:</strong><br>
                        Todos itens divididos.
                    </li>

                    </ul>
                    <p><b>Tags:</b> Programação Produção, Etiqueta, Filial</p>
                </div>
            </li>
            <li onclick="toggle(this)">
                <span class="version">Ficha Técnica – Unificação de Componentes</span>
                <span class="date">27/02/2026</span>
                <span class="date">Marvin - Henrique - Rafael</span>
                <div class="details">
                    <p>Descrição de conversa.</p>

                    <ul class="changelog">

                    <li>
                        <strong>Problema:</strong><br>
                        Itens da filial eram cortados na matriz e precisavam ser cadastrados duas vezes para o controle de estoque.
                    </li>

                    <li>
                        <strong>Decisão:</strong><br>
                        Retirar o componente UNIFICADA_VA.
                    </li>

                    <li>
                        <strong>Motivo:</strong><br>
                        Manter padrão simples e reduzir chance de erro de cadastro.
                    </li>

                    <li>
                        <strong>Impacto:</strong><br>
                        Agora produtos como ARES terão:
                        <ul>
                            <li>PE ESQUERDO</li>
                            <li>PE DIREITO</li>
                        </ul>
                    </li>

                    </ul>
                    <p><b>Tags:</b> FichaTecnica, Estoque, Componentes, Filial, Matriz</p>
                </div>
            </li>
            
        </ul>
    </div>
</body>

    

## **18/03/2026 — Impressão de etiquetas (Programação Filial)**

**Sistema:** OpSisttems  
**Participantes:** Marvin, Alberto  
**Módulo:** Programação Filial  
**Tags:** `programação` `etiqueta` `filial`

!!! warning ""PROBLEMA"

    Impressão de etiquetas de itens que foram **divididos na programação** gerava etiquetas erradas.

!!! question "DECISAO"

    Imprimir **um item por vez** quando ocorrer esse caso.

!!! info "MOTIVO"

    - Quando a consulta **agrupa os itens**, gera poucas etiquetas.
    - Quando **não agrupa**, o **tingimento é multiplicado dentro da etiqueta**.

!!! success "IMPACTO"

    Todos os **itens divididos na programação**.

---

## **27/02/2026 — Ficha Técnica — Unificação de Componentes**

**Sistema:** OpSisttems  
**Participantes:** Marvin, Henrique, Rafael  
**Módulo:** Ficha Técnica / Estoque  
**Tags:** `FichaTecnica` `Estoque` `Componentes` `Filial` `Matriz`

!!! warning ""PROBLEMA"

    Itens da **filial** eram cortados na **matriz** e precisavam ser cadastrados duas vezes para o controle de estoque.

!!! question "DECISAO"

    Remover o componente **UNIFICADA_VA**.

!!! info "MOTIVO"

    Manter um padrão mais simples e **reduzir a chance de erro de cadastro**.

!!! success "IMPACTO"

    Agora produtos como **ARES** terão apenas:

        - PE ESQUERDO
        - PE DIREITO





    

## **26/03/2026 — Impressão de etiquetas (Programação Filial)**

**Sistema:** OpSisttems  
**Participantes:** Marvin, Alberto  
**Módulo:** Programação Filial  
**Tags:** `producao filial` `ficha tecnica` `filial`

!!! warning ""PROBLEMA"

    Componentes gerados **manualmente** não conseguem avançar etapa no sistema de produção.

!!! question "DECISAO"

    Sempre que gerar um item de assistência, gerar esse item no configurador e ao invés de criar um item,
    alterar o item que já existe, pois depois quando avançar, o sistema irá pesquisá-lo na ficha técnica.
    Foi decidido fazer assim, pois ficaria complexo fazer uma correção para isso.

!!! info "MOTIVO"

    - Ao gerar um item criado do "zero", esse item não irá possuir um código da ficha técnica, ocasionando o problema.

!!! success "IMPACTO"

    Itens especiais e criados para a produção.

---


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





    
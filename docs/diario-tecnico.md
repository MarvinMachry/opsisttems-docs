## 18/03/2026 — Impressão de etiquetas (Programação Filial)

**Participantes:** Marvin - Alberto  
**Tags:** `programação` `etiqueta` `filial`

---

### ⚠ Problema
Impressão de etiquetas de itens que foram divididos na programação gerava etiquetas erradas.

### ✅ Decisão
Imprimir **um item por vez** quando ocorrer esse caso.

### 🧾 Motivo
Quando a consulta agrupa os itens, gera poucas etiquetas.  # 📘 Diário de Decisões Técnicas

---

## 2026-03-18 — Impressão de etiquetas (Programação Filial)

**Sistema:** OpSisttems  
**Participantes:** Marvin, Alberto  
**Módulo:** Programação Filial  
**Tags:** `programação` `etiqueta` `filial`

### Problema
Impressão de etiquetas de itens que foram **divididos na programação** gerava etiquetas erradas.

### Decisão
Imprimir **um item por vez** quando ocorrer esse caso.

### Motivo
- Quando a consulta **agrupa os itens**, gera poucas etiquetas.
- Quando **não agrupa**, o **tingimento é multiplicado dentro da etiqueta**.

### Impacto
Itens **divididos na programação filial**.

---

## 2026-02-27 — Ficha Técnica — Unificação de Componentes

**Sistema:** OpSisttems  
**Participantes:** Marvin, Henrique, Rafael  
**Módulo:** Ficha Técnica / Estoque  
**Tags:** `FichaTecnica` `Estoque` `Componentes` `Filial` `Matriz`

### Problema
Itens da **filial** eram cortados na **matriz** e precisavam ser cadastrados duas vezes para o controle de estoque.

### Decisão
Remover o componente **UNIFICADA_VA**.

### Motivo
Manter um padrão mais simples e **reduzir a chance de erro de cadastro**.

### Impacto
Agora produtos como **ARES** terão apenas:

- PE ESQUERDO
- PE DIREITO
Quando não agrupa, o tingimento é multiplicado dentro da etiqueta.

### 🎯 Impacto
Itens divididos na programação filial.

## 27/02/2026 — Ficha Técnica – Unificação de Componentes

**Participantes:** Marvin - Henrique - Rafael 
**Tags:** `FichaTecnica`, `Estoque`, `Componentes`, `Filial`, `Matriz`

---

### ⚠ Problema
Itens da filial eram cortados na matriz e precisavam ser cadastrados duas vezes para o controle de estoque.

### ✅ Decisão
Retirar o componente UNIFICADA_VA.

### 🧾 Motivo
Manter padrão simples e reduzir chance de erro de cadastro.

### 🎯 Impacto
Agora produtos como ARES terão:
<li>PE ESQUERDO</li>
<li>PE DIREITO</li>


    
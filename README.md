# Fornear Pizzaria 🍕

Landing Page responsiva da **Fornear Pizzaria**, a primeira pizzaria artesanal italiana de Santa Rita–PB.

Este projeto utiliza um runtime customizado (`support.js`) que processa a tag `<x-dc>` e renderiza a interface interativa de forma reativa no navegador (SPA Client-Side com React).

---

## 📁 Estrutura do Projeto

* `index.html` — Arquivo principal do site (com a estrutura da landing e scripts de renderização).
* `support.js` — Runtime reativo do projeto (baseado em React).
* `assets/` — Pasta contendo as imagens reais de alta resolução utilizadas no site:
  * `hero.jpg` — Pizza em destaque no topo.
  * `marguerita.jpg` — Pizza de Marguerita.
  * `calabresa.jpg` — Pizza de Calabresa Tradizionale.
  * `solebacon.jpg` — Pizza de Sol & Bacon.
  * `salvanutella.jpg` — Salva Borda de Nutella.
  * `salvadoce.jpg` — Salva Borda de Doce de Leite.
  * `salvacheddar.jpg` — Salva Borda de Cheddar Defumado.
* `fonts/` e `DM_Serif_Display/` — Fontes locais utilizadas na tipografia clássica da marca.
* `uploads/` — Imagens temporárias ou referências usadas na concepção.
* `sobremim.md` — Dossiê completo contendo a proposta e posicionamento de marca da Fornear.
* `prompts-imagens.md` — Roteiro de prompts usados para a geração consistente das fotos.

---

## 🚀 Como Executar Localmente

Para rodar o projeto localmente com **Live Reload** (o navegador atualiza automaticamente ao salvar qualquer alteração de código ou estilo):

1. Certifique-se de ter o **Node.js** instalado na sua máquina.
2. No terminal, execute o comando:
   ```bash
   npm run dev
   ```
3. O servidor local será iniciado e abrirá automaticamente no seu navegador padrão (geralmente em `http://localhost:3000`).

---

## 🎨 Design & Cores

O site foi construído sob uma paleta de cores italiana clássica e elegante:
* **Fundo Creme:** `#F4F1DC` (traz sensação de calor, farinha e aconchego).
* **Verde Escuro:** `#294C31` (associado a manjericão, tradição e frescor).
* **Terracota/Laranja Forno:** `#C94F2F` (cor do forno de lenha e molho de tomate pelado, usado para destaques).
* **Apoio Laranja Suave:** `#E8946F` / `#EFEBD1`.

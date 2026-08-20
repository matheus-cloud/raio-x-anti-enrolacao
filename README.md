# raio-x-anti-enrolacao
Projeto para simplificar textos longos, leis e questões complexas focando na essência.

## Acesso (forma correta de visualizar o app)
Existem três formas de abrir a interface pronta, em ordem de preferência:

1. GitHub Pages (recomendado — URL amigável)
   - Se você publicar o repositório como GitHub Pages, a URL normalmente será:
     - https://matheus-cloud.github.io/raio-x-anti-enrolacao/
   - Essa é a maneira mais adequada para compartilhar o app com outras pessoas (URL curta e confiável).

2. Abrir diretamente o arquivo hospedado (funciona sem configurar Pages)
   - Link que carrega a página estática imediatamente no navegador:
     - https://raw.githubusercontent.com/matheus-cloud/raio-x-anti-enrolacao/main/index.html
   - Observação: alguns navegadores podem bloquear recursos (por política de CORS) ao abrir arquivos raw; na maioria dos casos a interface estática funciona normalmente.

3. Testar localmente (mais controlado)
   - Clone/baixe o repositório e abra `index.html` no navegador (duplo clique ou `File → Open`). O app é estático e não precisa de servidor.

---

## Como publicar com GitHub Pages (passos rápidos)
1. No GitHub, abra as configurações do repositório (Settings).
2. Vá para a seção "Pages" (ou "Pages / GitHub Pages").
3. Em "Build and deployment" selecione a branch `main` e a pasta `/ (root)` ou `gh-pages` conforme preferir.
4. Salve e aguarde alguns instantes — a URL pública será exibida na própria tela de Pages.

Após publicar, use a URL do GitHub Pages (ex.: https://matheus-cloud.github.io/raio-x-anti-enrolacao/) para compartilhar o app.

---

## Acesso rápido ao app (index.html)
- Abrir diretamente no navegador (raw):
  - https://raw.githubusercontent.com/matheus-cloud/raio-x-anti-enrolacao/main/index.html
- Ver o arquivo no GitHub (visão do repositório):
  - https://github.com/matheus-cloud/raio-x-anti-enrolacao/blob/main/index.html

---

## Instruções de uso
1. Abra a página (via Pages, raw ou local). A interface "Raio-X Anti-Enrolação" será exibida.
2. Cole um texto, lei ou enunciado no campo grande (textarea).
3. Clique em "⚙️ Gerar soluções" ou use o atalho Ctrl/Cmd+Enter (ou Modificador+G) para que o app analise o texto.
4. O app seleciona automaticamente e mostra 3, 5 ou 10 soluções criativas (curto/médio/longo), conforme o tamanho do texto.
5. As soluções aparecem de forma animada; no final há um "Insight combinado" que mistura trechos para uma análise sintética.
6. Use os botões adicionais:
   - ✖ Limpar — reseta a entrada e resultados.
   - 🎲 Surpreenda-me — preenche um exemplo de texto e gera soluções.
   - 📋 Copiar todas — copia todos os resultados para o clipboard.

Dica: se for compartilhar com público, publique via GitHub Pages para obter a URL amigável mostrada acima.

---

## Testar localmente
- Clone o repositório:
  - git clone https://github.com/matheus-cloud/raio-x-anti-enrolacao.git
  - Abra `index.html` no navegador.
- Ou abra diretamente o link raw (conforme indicado) para visualizar sem clonar.

---

## Nota técnica
O arquivo `index.html` contém todo o HTML/CSS/JS necessário — não há dependências externas obrigatórias. Há um banco interno com ideias e a lógica de geração de soluções já implementada.

Se quiser, eu posso:
- Ajudar a ativar o GitHub Pages (posso te guiar passo a passo).
- Verificar quando o Pages estiver publicado e atualizar este README com a URL final automaticamente.

---

## Links
- Repositório: https://github.com/matheus-cloud/raio-x-anti-enrolacao
- Página (possível endereço Pages): https://matheus-cloud.github.io/raio-x-anti-enrolacao/
- Abrir diretamente o index: https://raw.githubusercontent.com/matheus-cloud/raio-x-anti-enrolacao/main/index.html

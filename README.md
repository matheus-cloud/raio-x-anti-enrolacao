# raio-x-anti-enrolacao
Projeto para simplificar textos longos, leis e questões complexas focando na essência.

## Acesso rápido ao app (index.html)
Para facilitar o uso do app direto no navegador, adicionei um link direto para a versão HTML hospedada no repositório.

- Visualizar a página no navegador (abertura imediata):
  - https://raw.githubusercontent.com/matheus-cloud/raio-x-anti-enrolacao/main/index.html

- Ver o arquivo no GitHub (visualização do repositório):
  - https://github.com/matheus-cloud/raio-x-anti-enrolacao/blob/main/index.html

Observação: o link "raw" (raw.githubusercontent...) carrega o arquivo index.html diretamente no navegador — basta abrir e a interface será exibida como uma página estática.

---

## Instruções rápidas para o público
Ao clicar no link (ou abrir o arquivo index.html):

1. A página será aberta no navegador com a interface "Raio-X Anti-Enrolação" (tema escuro, interativa).
2. Cole um texto, lei ou enunciado no campo grande (textarea).
3. Clique em "⚙️ Gerar soluções" ou use o atalho Ctrl/Cmd+Enter (ou Modificador+G) para que o app analise o texto.
4. Dependendo do tamanho do texto, o app selecionará automaticamente e mostrará: 3, 5 ou 10 soluções criativas (curto/médio/longo).
5. As soluções aparecem de forma animada, seguidas de um "Insight combinado" que mistura os trechos para dar uma sensação de análise personalizada.
6. Você pode usar "✖ Limpar" para resetar, "🎲 Surpreenda-me" para preencher um exemplo e gerar soluções, e "📋 Copiar todas" para copiar os resultados ao clipboard.

Dica rápida: se desejar disponibilizar essa página como um site público (com URL amigável tipo `https://<seu-usuario>.github.io/raio-x-anti-enrolacao/`), ative o GitHub Pages nas configurações do repositório apontando para a branch `main` (root). Após ativar, a página ficará online no endereço acima (pode demorar alguns minutos para publicar).

---

## Testar localmente
Opções:
- Baixe / clone o repositório e abra `index.html` no navegador (duplo clique). A interface funciona como uma página estática sem dependências.
- Ou abra diretamente o link raw (conforme indicado acima) para visualizar sem clonar.

---

## Nota técnica
O arquivo `index.html` já contém todo o HTML/CSS/JS necessário: banco interno com 50 ideias, lógica de análise por tamanho e funções de interação (gerar, limpar, copiar). Se quiser, posso adicionar um botão explícito no README que aponte para o link de GitHub Pages assim que você ativar Pages, ou automatizar a publicação usando Actions.

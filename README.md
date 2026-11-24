# ODE/UFFS — Observatório de Dados Educacionais da UFFS

Página web com o conteúdo integral da proposta do ODE/UFFS, **versão 0.32 (rascunho para discussão)**.

- `index.html`: página única, com estilos, scripts e a Figura 1 embutidos. Abre direto no navegador.
- `downloads/`: os documentos da versão 0.32, ligados à seção "Documentos" da capa (botões Visualizar e Baixar):
  - `ODE_UFFS_v0.32.pdf`: projeto completo (60 páginas)
  - `ODE_UFFS_resumo_fomento_v0.32.pdf`: resumo para fomento (6 páginas)
  - `ODE_UFFS_apresentacao_v0.32.pdf` e `.pptx`: apresentação (17 slides)
- `.nojekyll`: faz o GitHub Pages servir os arquivos como estão.

## Publicar no GitHub Pages

1. Crie um repositório e envie o conteúdo desta pasta (incluindo `downloads/`) para a raiz da branch `main`.
2. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. O endereço fica em `https://<usuário>.github.io/<repositório>/`.

Atenção: no plano gratuito do GitHub, o Pages exige repositório **público**, e a página e os PDFs ficam visíveis para qualquer pessoa. O documento é um rascunho com pendências marcadas (como [a definir] e [validar]).

## Atualizar

A página é gerada a partir do .odt da proposta, e os PDFs foram exportados pelo LibreOffice a partir do .odt, do .docx e do .pptx. Para uma nova versão, gere de novo o `index.html` e os PDFs e troque os nomes dos arquivos na seção "Documentos" do `index.html`.

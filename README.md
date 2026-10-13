# Black Friday OLWAY 2026 · Painel técnico

Painel interno com as regras comerciais, o simulador de carrinho, o checklist de desenvolvimento, os testes de aceite e as decisões pendentes da campanha.

É uma especificação. Nada aqui está implantado na loja. O simulador usa regras locais e preços ilustrativos.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| `index.html` | A página inteira (HTML, CSS e JavaScript em um só arquivo). |
| `.nojekyll` | Diz ao GitHub Pages para publicar o arquivo como está. |
| `assets/logo-olway.png` | Símbolo da OLWAY com fundo transparente (cópia de referência; a página já traz a logo embutida). |
| `README.md` | Este guia. |

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `olway-bf-2026`).
2. Envie os arquivos para a branch `main`, com `index.html` na raiz.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`. Salve.
5. Aguarde cerca de um minuto. O endereço será `https://SEU-USUARIO.github.io/olway-bf-2026/`.

## Atenção: acesso

- O GitHub Pages é **público** por padrão, mesmo com repositório privado, na maioria dos planos. Esta página é um documento interno. Se ela não puder ficar pública, use um plano com Pages privado (GitHub Enterprise Cloud) ou outro serviço com login.
- Checklist, testes, decisões e datas ficam salvos **só no navegador** de cada pessoa (localStorage). Não são compartilhados entre a equipe. O botão "Copiar escopo (Markdown)" exporta o estado atual.

## Editar

Todo o conteúdo e as regras de demonstração estão em `index.html`, na tag `<script>` (dados em maiúsculas: `PHASES`, `COMBOS`, `PRODUCTS`, `CHECK`, `TESTS`, `PEND`, `LAY`). As cores ficam nas variáveis CSS do início do arquivo.

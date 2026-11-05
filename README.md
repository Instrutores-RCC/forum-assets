# forum-assets

Arquivos CSS e JS das páginas HTML que os Instrutores colam no fórum. Tudo aqui é saída de build: o código-fonte fica nos repositórios privados de cada projeto e não se edita nada à mão.

- Uma pasta por projeto (`central/`, ...).
- O nome de cada arquivo leva a versão (`central.<versão>.js`). Arquivo publicado nunca muda; versão nova é arquivo novo.
- Cada versão tem uma tag (`central-<versão>`), que é o endereço do espelho no jsDelivr.
- A página no fórum confere a impressão digital (SRI) de cada arquivo antes de rodar.
- Branch única: `gh-pages`, servida pelo GitHub Pages.

Endereços:

- `https://instrutores-rcc.github.io/forum-assets/<projeto>/<arquivo>` (principal)
- `https://cdn.jsdelivr.net/gh/Instrutores-RCC/forum-assets@<projeto>-<versão>/<projeto>/<arquivo>` (reserva)

Como funciona e como reutilizar: [docs/HOSPEDAR-NO-FORUM.md](https://github.com/Instrutores-RCC/.github/blob/main/docs/HOSPEDAR-NO-FORUM.md).

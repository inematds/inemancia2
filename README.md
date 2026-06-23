# INEMA.NCIA — versão canônica v3 (comparação)

Segunda versão do curso **INEMA.NCIA**, construída para bater **ao pé da letra** com a
skill `formato-curso-v3` na sua forma atual — feita para **comparar** com a versão de
referência em [inematds/inemancia](https://github.com/inematds/inemancia).

Mesma estrutura de 3 níveis (Curso → Trilha-índice → Módulo) e mesmo conteúdo (27
seções em 10 módulos), com os requisitos novos da skill aplicados:

- **`.rail-modules`** — mapa "Nesta trilha" na margem de cada módulo (módulos irmãos,
  atual marcado, link para o índice da trilha).
- **Wordmark `INEMA.CLUB`** com `target="_blank" rel="noopener"` → portal externo.
- **`learn.css` / `learn.js`** na versão mais recente da skill.

➡️ Abre direto no `index.html` (site estático, sem build).

## Diferença vs a 1ª versão
| | 1ª versão (`inemancia`) | Esta (`inemancia2`) |
|---|---|---|
| Mapa de módulos na margem | — | `.rail-modules` em cada aula |
| Wordmark | `inema.club` | `inema.club` + `target=_blank` |
| Assets | learn.css/js anteriores | versão atual da skill |

Conteúdo derivado do canal de Telegram INEMA.NCIA, reescrito como leitura — não expõe
nomes de membros. Parte do ecossistema **[INEMA.CLUB](https://inema.club)**.

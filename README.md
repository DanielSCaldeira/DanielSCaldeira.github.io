# Currículo — Daniel Soares Caldeira

Página estática do meu currículo, publicada com **GitHub Pages**:

### 👉 https://danielscaldeira.github.io

Uma página, sem dependências externas, sem build. HTML + CSS + um script curto de ~40 linhas.

## O que tem dentro

- **PT / EN** por botão — abre sempre em português; se o visitante trocar, a escolha fica salva no navegador dele
- **Tema claro / escuro** (segue o sistema, com toggle manual)
- **Botão PDF** — imprime em layout próprio para impressão, sem menu nem botões
- Responsiva, acessível (foco visível, skip link, contraste AA)
- `JSON-LD` de `schema.org/Person` + Open Graph para o preview em links

## Como editar

Todo o conteúdo está em `index.html`. Cada trecho traduzível é um elemento com o
atributo `data-en` — o português fica no corpo do elemento, o inglês no atributo:

```html
<h2 data-en="What I bring">O que eu entrego</h2>
```

Para mudar um texto, edite os dois. Para adicionar um projeto, copie um bloco
`<article class="proj">`. As cores todas saem das variáveis CSS em `:root`.

## Rodar local

Basta abrir o arquivo. Ou, se preferir servidor:

```bash
python -m http.server 8080
# http://localhost:8080
```

## Licença

Conteúdo do currículo © Daniel Soares Caldeira. O código do layout é livre para reuso.

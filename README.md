# Rafael Vaz · Portfolio

Site estático (HTML + CSS puro), publicado com GitHub Pages.

## Estrutura

```
index.html                     Home: hero, projetos, sobre mim, contacto
projetos/design-system-fpf.html  Case study 01
assets/css/style.css           Todos os estilos (tokens no topo, em :root)
assets/js/main.js              Header ao fazer scroll + animação de entrada
assets/img/                    Imagens (shield.svg, screenshots em fpf/)
```

## Editar

- **Texto:** abrir o `.html` e editar diretamente.
- **Cores e medidas:** variáveis em `:root`, no topo de `style.css`.
- **Screenshots do case study:** guardar em `assets/img/fpf/` e descomentar os blocos `<figure class="shot">` marcados com `SCREENSHOT REAL` em `projetos/design-system-fpf.html`.
- **Novo projeto:** copiar `projetos/design-system-fpf.html`, trocar o conteúdo e acrescentar uma linha `<li>` na lista `.projects` do `index.html`.

## Ver localmente

Abrir `index.html` no browser, ou correr `python3 -m http.server` nesta pasta e abrir http://localhost:8000.

## Publicar

Cada `git push` para o branch `main` atualiza o site automaticamente (GitHub Pages, Settings → Pages → Deploy from a branch → `main` / root).

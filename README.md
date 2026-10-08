# Rafael Vaz · Portfolio

Site estático (HTML + CSS puro), publicado com GitHub Pages.

## Estrutura

```
index.html                     Home: hero, projetos, sobre mim, contacto
projetos/design-system-fpf.html  Case study 01, FPF
projetos/rrs-pingo-doce.html     Case study 02, Pingo Doce
assets/css/style.css           Todos os estilos (tokens no topo, em :root)
assets/js/main.js              Header ao fazer scroll + animação de entrada
assets/img/fpf, pingo-doce     Imagens de cada projeto
```

## Editar

- **Texto:** abrir o `.html` e editar diretamente.
- **Cores e medidas:** variáveis em `:root`, no topo de `style.css`.
- **Imagens:** as atuais foram recortadas dos slides. Para mais nitidez, exportar do Figma a 2x com o mesmo nome de ficheiro e substituir.
- **Novo projeto:** copiar uma página de `projetos/`, manter a ordem Ficha → Resumo → Secções numeradas → Resultado, e acrescentar um `<li>` na lista `.projects` do `index.html`.

## Ver localmente

Abrir `index.html` no browser, ou correr `python3 -m http.server` nesta pasta e abrir http://localhost:8000.

## Publicar

Cada `git push` para o branch `main` atualiza o site automaticamente (GitHub Pages, Settings → Pages → Deploy from a branch → `main` / root).

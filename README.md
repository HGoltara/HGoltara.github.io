# Portfólio — Higor Goltara

Site pessoal apresentando meus projetos, stack técnica e contato.

**Stack:** HTML + CSS + JavaScript puros, sem framework ou etapa de build.

🔗 **Ao vivo em:** [hgoltara.github.io](https://hgoltara.github.io)

## Estrutura

```
index.html      página única (Hero, Sobre, Habilidades, Projetos, Contato)
css/style.css   tema escuro, gradientes, layout responsivo, animações de scroll
js/script.js    navbar com blur ao rolar, menu mobile, reveal on scroll
```

## Como rodar localmente

Não precisa de instalação — é só servir a pasta:

```
npx serve .
```

ou

```
python -m http.server 5500
```

Abrir o `index.html` direto como `file://` também funciona, mas alguns navegadores
bloqueiam CSS/JS externos nesse modo.

## Deploy

Publicado via GitHub Pages a partir do branch `main` — como o repositório se chama
`HGoltara.github.io`, o Pages é ativado automaticamente e republica a cada `git push`,
sem precisar de configuração adicional.

## Conteúdo

Os projetos e a stack listados na seção de Habilidades refletem apenas tecnologias
realmente usadas em produção no [To-Do List](https://github.com/HGoltara/todo-list-api)
e no [URL Shortener](https://github.com/HGoltara/url-shortener) — nada é aspiracional.

## Uso de IA

Desenvolvido com apoio do **Claude Code** (Anthropic): estruturação do layout, design
do tema escuro e redação inicial dos textos. Conteúdo, links e precisão técnica
revisados por mim antes da publicação.

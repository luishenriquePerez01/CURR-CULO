# Currículo — Luis Henrique Perez de Oliveira

Site de currículo em página única (HTML/CSS/JS puro, sem dependências de build), com visual inspirado em notebooks de ciência de dados.

## Como publicar no GitHub Pages

**Passo 1 — Crie o repositório**

Duas opções, escolha uma:

- **Site pessoal (recomendado):** crie um repositório chamado exatamente `LuisHenrique240.github.io`. O site ficará disponível em `https://LuisHenrique240.github.io`.
- **Repositório de projeto:** crie um repositório com outro nome, por exemplo `curriculo`. O site ficará em `https://LuisHenrique240.github.io/curriculo/`.

**Passo 2 — Envie os arquivos**

No repositório criado, clique em **Add file → Upload files** e envie os três arquivos desta pasta (`index.html`, `README.md`, `.nojekyll`). Depois clique em **Commit changes**.

**Passo 3 — Ative o GitHub Pages**

Vá em **Settings → Pages**. Em "Build and deployment", selecione:
- Source: `Deploy from a branch`
- Branch: `main` / pasta `/ (root)`

Clique em **Save**.

**Passo 4 — Acesse o site**

Em 1–2 minutos o link aparece no topo dessa mesma página de configurações (formato `https://LuisHenrique240.github.io` ou `https://LuisHenrique240.github.io/curriculo/`, dependendo da opção escolhida no Passo 1).

## Sobre o `.nojekyll`

O GitHub Pages processa arquivos por padrão com Jekyll. O arquivo `.nojekyll` (vazio, propositalmente) desativa esse processamento — não é estritamente necessário aqui, mas evita qualquer interferência inesperada em um site estático simples como este.

## Editar o conteúdo

Todo o site está em `index.html` — texto, estilo e comportamento em um único arquivo, sem etapa de build. Basta editar e reenviar (upload novamente ou `git push`) para atualizar o ar.

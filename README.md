# ImplantaRH ConsultoriaPRO

Site institucional premium da ImplantaRH ConsultoriaPRO, com foco em plataformas empresariais, aplicativos personalizados, sistemas sob medida, automacao, IA e organizacao operacional.

## Projeto

- Nome: `implantarh-consultoriapro-site`
- Tipo: site estatico
- Hospedagem prevista: Vercel
- Repositorio previsto: GitHub

## Rodar localmente

```powershell
cd "C:\Users\Admin\Documents\Codex\2026-06-05\criar-o-site-oficial-da-implantarh\outputs\implantarh-site"
powershell -NoProfile -ExecutionPolicy Bypass -File .\start-preview.ps1 -Port 8080
```

Abra:

```text
http://127.0.0.1:8080/
```

## Estrutura principal

- `index.html`: conteudo e estrutura do site
- `styles.css`: identidade visual, responsividade e animacoes
- `script.js`: menu mobile, animacoes de entrada e slider do hero
- `assets/`: imagens oficiais usadas no site
- `vercel.json`: configuracao de deploy estatico na Vercel
- `start-preview.ps1`: servidor local simples para validar o site

## Publicar novas alteracoes

Fluxo recomendado depois do repositorio remoto configurado:

```powershell
git status
git add .
git commit -m "Atualiza site ImplantaRH"
git push
```

Com GitHub integrado a Vercel, cada `git push` para a branch principal gera novo deploy automaticamente.

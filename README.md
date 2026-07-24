# Givas Frontier 🌍⚔️

RPG 2D pixel art de mundo aberto — Temporada 1: A Reconstrução do Núcleo Astra.

4 reinos (Gelo, Deserto, Floresta, Sombrio) + Vila Aurora, editor de personagem,
5 classes, atributos, forja +20, pets, montaria, profissões, banco, casa, arena e chefes.

## Como gerar o APK

O APK é compilado automaticamente pelo GitHub Actions a cada push na branch `main`.

```bash
git init
git add .
git commit -m "Givas Frontier v1"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/givas-frontier.git
git push -u origin main
```

Depois: aba **Actions** → workflow **Build APK** → baixe o `givas-frontier.apk`
em **Artifacts** ou na aba **Releases**.

## Rodar no navegador

Abra `www/index.html` direto no navegador.

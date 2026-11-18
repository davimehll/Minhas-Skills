# Minhas Skills

Minha coleção de skills do Claude e ferramentas úteis para criação de conteúdo e design, organizadas por tema.

## O que tem aqui

### 📱 Skill de gerenciamento de redes sociais

| Pasta | O que é | Comandos |
|---|---|---|
| [YouTube Agent Skill](Skill%20de%20gerenciamento%20de%20redes%20sociais/YouTube%20Agent%20Skill) | 11 skills para tocar um canal: roteiro com ganchos, título + thumbnail, retenção, Shorts, SEO, capítulos e mais | `/yt-script`, `/yt-package`, `/yt-retention`, `/yt-shorts`, `/yt-viral`… |
| [Instagram Agent Skill](Skill%20de%20gerenciamento%20de%20redes%20sociais/Instagram%20Agent%20Skill) | 13 skills para tocar um perfil: Reels, carrossel, legenda, stories, DMs, perfil e um "humanizador" de texto | `/ig-reel`, `/ig-carousel`, `/ig-caption`, `/ig-human`, `/ig-viral`… |

### ✂️ Skills de criação de short content

| Pasta | O que é |
|---|---|
| [Viral Cutter](Skillls%20de%20criacao%20de%20short%20content/Viral%20Cutter) | **Programa** (não é skill do Claude) que transforma vídeos longos em cortes verticais com legenda para Reels, TikTok e Shorts. Alternativa gratuita e local ao Opus Clip. Veja o README dentro da pasta para instalar. |

### 🎨 Skills de design e layout

| Pasta | O que é |
|---|---|
| [Apple Design](Skills%20de%20design%20e%20layout/Apple%20Design) | Critérios de design de interface da Apple (tirados das palestras da WWDC) adaptados para a web: animações fluidas, gestos, profundidade e tipografia. |

## Como instalar uma skill no Claude Code

1. Baixe este repositório: botão verde **Code** → **Download ZIP** (ou `git clone https://github.com/davimehlduque1-cell/Minhas-Skills.git`).
2. Copie a pasta da skill para a pasta de skills do Claude:
   - **Windows:** `C:\Users\SEU_USUARIO\.claude\skills\`
   - **Mac/Linux:** `~/.claude/skills/`
3. Para as skills do YouTube e do Instagram, copie as pastas que estão **dentro** de `skills/` (as `yt-*` e `ig-*`), não a pasta inteira.
4. Reinicie o Claude Code e chame pelo comando (ex.: `/yt-script`).

Para pegar atualizações, baixe de novo (ou `git pull`) e copie as pastas outra vez.

## Créditos

Nem tudo aqui foi feito por mim. Os créditos vão para os autores originais:

- **YouTube Agent Skill** e **Instagram Agent Skill**: [Jake Schincariol](https://github.com/Jakeschincariol) (licença MIT)
- **Viral Cutter**: [Rafael Godoy Ebert](https://github.com/RafaelGodoyEbert/ViralCutter) (licença MIT)

As licenças originais estão dentro de cada pasta.

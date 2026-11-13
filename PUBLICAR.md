# Como publicar a página de serviços (site + itch.io)

Preparado em 2026-11-13. Quem publica é o dono (o Claude não faz login nem publica). Tudo grátis.

## O que tem nesta pasta
- `index.html` — o site de serviços (em inglês, para clientes da Europa/EUA): vídeo do Prisma no topo, 3 amostras, 5 pacotes com preço, como funciona, aviso sobre IA e contato.
- `assets\` — vídeos e imagens comprimidos (~4,6 MB no total): Reel 16 (antes × depois), clipe da escada com mortal (sem a barra do editor), concept → modelo 3D do capanga brigão.
- `itch-perfil.md` — o texto para o perfil do itch.io.
- Origem dos textos e preços: `Studio\financas\metas-hoje-weekend-2026-11-13.md` (CFO; preços são hipótese inicial).

## Onde a conversão é melhor
- **O site converte melhor** para quem já está interessado: é a página para onde vão as **propostas**, a **bio do Instagram** e os posts "for hire". Tem amostras em vídeo, preços e um botão de e-mail, sem distração.
- **O itch.io traz gente**: é onde estão os devs indie (os leads). O perfil serve de vitrine curta e **manda para o site**.
- Regra: toda mensagem e todo link levam ao **site**; o itch.io é porta de entrada.
- Para saber de onde vem cada cliente, pergunte no 1º e-mail "how did you find us?" e anote em `Studio\financas\oportunidades.md`.

## Passo 0 — antes de tudo (5 min)
1. ~~Escolher o e-mail de contato~~ → **whitewolfcontatos@gmail.com** (13/11), já preenchido no `index.html` e no `itch-perfil.md`.
2. Abrir `index.html` no Bloco de Notas e preencher as 2 linhas que faltam no bloco **"EDITAR AQUI"** no fim do arquivo: `INSTAGRAM` (link do perfil) e `ITCH` (link do perfil do itch, depois do passo 2). Vazias, os links simplesmente não aparecem no rodapé. Ou me mande os links que eu preencho.

## Passo 1 — site no GitHub Pages (~20 min, sem instalar nada)
1. Criar a conta em github.com (sugestão de usuário: `whitewolfstudios`). O nome do usuário vira o endereço: `https://whitewolfstudios.github.io`.
2. **New repository** → nome exatamente `whitewolfstudios.github.io` (o seu usuário + `.github.io`) → **Public** → Create.
3. Na página do repositório: **Add file → Upload files** → arrastar o `index.html` **e a pasta `assets`** inteira → **Commit changes**.
4. **Settings → Pages**: em "Build and deployment", Source = **Deploy from a branch**, Branch = **main** / **(root)** → Save.
5. Em 1–2 minutos o site está em `https://<usuário>.github.io`. Abrir no celular e no PC e conferir os vídeos.
6. Para mudar algo depois: editar o arquivo no próprio GitHub (ícone de lápis) ou subir de novo.

## Passo 2 — perfil do itch.io (~15 min)
1. Criar a conta em itch.io (tipo "I'm interested in distributing content on itch.io"; nome `whitewolfstudios` ou parecido). O perfil fica em `https://<usuário>.itch.io`.
2. Avatar → **Edit profile** → colar o texto de `itch-perfil.md` (com o link do site e o e-mail).
3. **Edit theme**: fundo `#0C1118`, destaque `#F0A63C`.
4. Voltar ao `index.html` e preencher `ITCH` com o link do perfil.

## Passo 3 — divulgar (5 min)
- **Bio do Instagram:** link do site.
- Usar o link do site no modelo de proposta do CFO (`[link]`) e nos posts "for hire" do fim de semana.

## Depois (com o agente portfolio)
- Domínio próprio (ex.: whitewolfstudios.com, ~€ 10–15/ano, dedutível) apontando para o GitHub Pages.
- Trocar as amostras pelo **trailer-amostra** de sábado e pelo protótipo do Shonen World quando estiver jogável.
- Versão em português do site, se aparecer cliente do Brasil.

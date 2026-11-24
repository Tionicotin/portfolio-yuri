# Portfólio de Yuri Kissel

Site estático (HTML + CSS + JS, sem instalação) com o portfólio de edição de vídeo.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo, `portfolio`).
2. Envie todos os arquivos desta pasta: `index.html`, a pasta `assets/` e este `README.md`.
   Pelo site: **Add file > Upload files**, arraste tudo e clique em **Commit changes**.
3. No repositório, abra **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, branch **main** e pasta **/ (root)**. Salve.
5. Em 1 a 2 minutos o site fica em `https://SEU-USUARIO.github.io/portfolio/`.

Dica: se o repositório se chamar `SEU-USUARIO.github.io`, o endereço fica só `https://SEU-USUARIO.github.io/`.

## Como colocar o link de cada vídeo

Abra `index.html`, procure por `VIDEO_LINKS` (perto do fim do arquivo) e cole o endereço de cada vídeo
entre as aspas. Os trabalhos que tiverem link ganham o botão "Assistir vídeo".

## Vídeos do site

Cada trabalho abre uma prévia em vídeo ao clicar na imagem. As prévias ficam em `assets/video/`
(30 segundos cada, exceto a abertura de Vampiro, que tem os 22 segundos inteiros). Elas são leves de
propósito: o upload pelo navegador do GitHub aceita arquivos de até 25 MB, e os vídeos originais são bem maiores.

Para mostrar o vídeo completo, publique no YouTube (como "não listado") ou no TikTok e cole o link em
`VIDEO_LINKS`. O botão "Assistir vídeo completo" aparece sozinho.

O trabalho **Fotografia Kirlian e a aura** ainda está sem prévia. Para incluir, coloque o arquivo em
`assets/video/kirlian.mp4` e, no `index.html`, acrescente `data-video="assets/video/kirlian.mp4"`
no bloco `<article ... id="kirlian">`.

## Como trocar as imagens

As imagens estão em `assets/`. Para trocar, use o mesmo nome de arquivo:

- `terra.jpg` e `ia-trabalho.jpg`: formato horizontal 16:9 (1280 x 720)
- `abertura-vampiro.jpg`: formato horizontal 16:9
- `caso-real.jpg`, `kirlian.jpg` e `livros.jpg`: formato vertical 9:16 (576 x 1024 ou maior)

## Contatos usados no site

WhatsApp (48) 99935-1203, e-mail ruan.kissel@gmail.com, Instagram @yurizitosss e TikTok @sr_fajuto.
Para mudar, procure esses dados no `index.html`.

# AMV Conectar — versão estática completa

## Abrir no computador
Extraia toda a pasta e abra `index.html` no navegador. Não mova os arquivos HTML para fora da pasta: eles usam os recursos em `assets/`.

## Hospedar
Envie todo o conteúdo de `versao-estatica/` para a pasta pública de sua hospedagem. Não é necessário instalar programas, pacotes, React ou um serviço de servidor. Os endereços das páginas terminam em `.html`.

## Conteúdo
- `index.html`: página inicial com serviços, diferenciais, processo e contato.
- `quem-somos.html`, `missao.html`, `visao.html`, `valores.html`, `projeto-integrador.html`: páginas institucionais.
- `assets/site.css`: estilos e temas.
- `assets/theme.js`: tema inicial e preferência salva.
- `assets/site.js`: menu, troca de tema, assistente e validação do formulário.
- `assets/faq.js`: perguntas e respostas do assistente, sem IA ou serviço pago.
- `assets/*.png`: logos transparentes e favicon.
- `assets/manrope-*`: fontes locais.
- `assets/OFL-Manrope.txt`: licença da fonte Manrope.

## Funcionalidades e limites
O menu, o assistente, as seis páginas, imagens, ícones e fontes funcionam sem acesso à internet. Os links WhatsApp exigem internet e abrem https://wa.me/5598984833670.

O formulário conserva o comportamento do site atual: valida os campos e informa que a mensagem foi preparada; **não envia e-mail nem armazena mensagens**. Um canal de envio precisará ser conectado separadamente.

A preferência claro/escuro é salva quando o navegador permite armazenamento local. Abrir arquivos diretamente pode restringir essa persistência em alguns navegadores; em uma hospedagem normal, ela é compartilhada entre as páginas.

O site existente não foi substituído: esta pasta é uma entrega independente em HTML, CSS e JavaScript puro. A logo superior é distinta da logo central e do rodapé, preservando as versões atuais sem fundo. Ícones SVG estão embutidos nos arquivos HTML.

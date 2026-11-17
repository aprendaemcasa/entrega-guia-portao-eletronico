# Entrega — Guia de Portão Eletrônico do Zero

Página independente para entregar ao comprador os links do treinamento e dos materiais de apoio.

## Configurar os links

Edite `config.js`:

- `lessonsUrl`: endereço da área de videoaulas (já configurado).
- `materialsUrl`: cole o link público/compartilhável da pasta de materiais em PDF.

Quando `materialsUrl` estiver vazio, o botão de PDFs ficará desativado para evitar direcionar o cliente a um endereço inválido.

## Publicar no GitHub Pages

1. Abra **Settings → Pages** neste repositório.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)`.
4. Salve e aguarde a publicação do GitHub Pages.
5. O endereço ficará no formato `https://aprendaemcasa.github.io/entrega-guia-portao-eletronico/`.

## Como usar na Cakto

Na opção **Acesso por e-mail**, informe o endereço publicado no GitHub Pages e uma mensagem curta dizendo que os botões levam às aulas e aos PDFs de apoio.

## Observação importante

Esta página é estática e não autentica compradores nem confirma pagamentos. Qualquer pessoa que tenha o endereço poderá abri-la. A confirmação do pedido e o envio do link devem ser feitos pela Cakto. O acesso às aulas e aos arquivos depende das permissões configuradas nos respectivos serviços.

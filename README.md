Seu desafio é recriar a home do aplicativo do Peixe Urbano para iOS, utilizando os dados dos arquivos JSON listados abaixo.

A home do app que você irá criar deve consistir em uma tab bar com três abas: Na Cidade, Viagens e Produtos. Cada aba deve listar as ofertas dos arquivos JSON correspondentes, que devem ser baixados diretamente das URLs (não armazenados dentro do app).

Exemplo do que esperamos ver do seu desafio:

![demo-ui](https://f001.backblazeb2.com/file/grtests/demo-ui.jpeg) ![demo-ui-gif](https://f001.backblazeb2.com/file/grtests/demo-ui.gif)

Estas são as URLs para o conteúdo de cada aba (no formato json):

- Na Cidade: https://gist.githubusercontent.com/insidegui/2b1f747ebeb9070e33818bf857e28a84/raw/5da63767fda2ec16f4ae0718e3be4be75001fe10/florianopolis.json

- Viagens: https://gist.githubusercontent.com/insidegui/d2665b556f2be1b1ad3a19d2ef9bcc44/raw/afe1e0a9563e3bcddc3796b22becb8f12f82ee2e/viagens.json

- Produtos: https://gist.githubusercontent.com/insidegui/007fd6664650391dca199e6784d1f351/raw/862d701c69307f9e9053f8cb1ec438586fca4b64/produtos.json

Cada item na listagem deve obrigatoriamente exibir ao menos a primeira foto, o título, nome do parceiro e o preço de cada oferta. Procure seguir o design do nosso app Peixe Urbano que está na loja, ou se guie pelas imagens acima.

## Detalhes técnicos a serem observados:

- Seu app deve suportar devices a partir do iPhone 5s. Não é necessário ser um app universal, pode suportar somente iPhones.
- Se preferir, pode fazer o teste em um Playground, desde que organize os arquivos adequadamente utilizando auxiliary sources.
- O app do teste deve ser feito na versão mais recente do Swift e do Xcode.
- É permitido o uso de dependência (CocoaPods, Carthage, etc) somente para download e cache das imagens consumidas da internet.

## Pontos extras:

Os itens abaixo não são obrigatórios, mas serão considerados na avaliação caso você consiga fazê-los:

- Listagem de banners no topo da lista. Os banners também estão nos arquivos JSON fornecidos.
- Armazenamento local das ofertas baixadas (offline-first).
- Adicionar uma nova aba que exibe as ofertas da cidade em um mapa.
- Desenvolver o teste sem utilizar Interface Builder (storyboards/xibs).


## O que será avaliado:

- Arquitetura escolhida para desenvolvimento do teste.
- Qualidade do código.
- Abstração das diferentes camadas.
- Adoção de boas práticas recomendadas pela Apple no uso das APIs e no visual do app.
- Funcionamento do produto entregue.
- Documentação do projeto.

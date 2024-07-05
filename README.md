# Magalu - API de Produtos Favoritos

## Cenário

O Magalu está expandindo seus negócios, e uma das novas missões do time de tecnologia é criar uma funcionalidade de "Produtos Favoritos" para nossos clientes. Nessa nova funcionalidade, nossos aplicativos enviarão requisições HTTP para um novo backend que gerenciará clientes e seus produtos favoritos. Essa API REST será crucial para ações de marketing da empresa e terá um grande volume de requisições, portanto, a preocupação com desempenho é constante.

## Requisitos

1. **Clientes:**
   - Deve ser possível criar, atualizar, visualizar e remover clientes.
   - O cadastro dos clientes deve conter apenas seu nome e endereço de e-mail.
   - Um cliente não pode se registrar duas vezes com o mesmo endereço de e-mail.

2. **Produtos Favoritos:**
   - Cada cliente só pode ter uma única lista de produtos favoritos.
   - Em uma lista de produtos favoritos, pode haver uma quantidade ilimitada de produtos.
   - Um produto não pode ser adicionado à lista se ele não existir.
   - Um produto não pode estar duplicado na lista de produtos favoritos de um cliente.
   - A documentação da API de produtos pode ser visualizada [neste link](https://gist.github.com/hugocs1/5d0adbdec5be6db81a1ae7b42a88adee).

3. **Renderização da Resposta:**
   - O dispositivo que renderizará a resposta fornecida por essa nova API apresentará o Título, Imagem, Preço e utilizará o ID do produto para formatar o link que ele acessará.
   - Quando existir um review para o produto, o mesmo será exibido por este dispositivo.
   - Não é necessário criar um frontend para simular essa renderização (foque no desenvolvimento da API).

4. **Autenticação e Autorização:**
   - O acesso à API deve ser aberto ao mundo, mas deve possuir autenticação e autorização.

# Observações e Orientações Gerais

- A preocupação com o desempenho é crucial, dado o grande volume de requisições esperado.
- Certifique-se de que as respostas da API estejam otimizadas para o dispositivo que irá renderizá-las.
- Implemente um sistema robusto de autenticação e autorização para proteger os dados dos clientes e garantir a segurança da API.


## Linguagens e Bancos de Dados

- Utilize qualquer uma das seguintes linguagens:
  - Java
  - Python
  - Javascript (NodeJs)
  - Typescript
  - C#(.net core)
  - Ou alguma outra linguagem que você tenha domínio! (não temos apego)

- Utilize qualquer um dos bancos de dados abaixo:
  - MySQL
  - Postgresql
  - MongoDB
  - Redis

## Envio do Desafio

- Envie seu desafio preferencialmente como repositório GIT público (Github, Gitlab, Bitbucket) ou como arquivo compactado (ZIP ou TAR).
- O repositório deve ter um modelo de licença de código aberto.
- Não envie nenhum arquivo além do próprio código compactado, sua documentação, e arquivos com declaração de dependências e automação para instalação.
- Evite enviar imagens, vídeos, áudio, binários, etc.

## Boas Práticas de Desenvolvimento

- Siga boas práticas de desenvolvimento, qualidade e governança de código.
- Oriente os avaliadores sobre como instalar, testar e executar seu código.

## Artigos no Medium

- No nosso Medium, temos alguns artigos interessantes que podem fornecer pequenas dicas sobre como trabalhamos e o que esperamos dos desafios.
- Observe os diversos artigos e leia-os atentamente para garantir a execução e a entrega de um bom desafio.

## Avaliação

- Seu desafio será avaliado de acordo com a posição e o nível para o qual você está se candidatando.
- Todos os desenvolvedores aqui no LuizaLabs podem participar do processo de avaliação técnica.

Agradecemos muito sua disposição em participar do nosso processo seletivo e desejamos que você se divirta e tenha boa sorte! 😊

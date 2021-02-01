<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Desafio 04: Conceitos do React Native
</h3>

<blockquote align="center">“Sucesso não é o resultado de um jogo, mas o destino de uma jornada”!</blockquote>

## :rocket: Sobre o desafio

Aplicação mobile para listar e atualizar likes dos repositórios criados utilizando backend feito no desafio 2 do bootcamp GoStack da Rocketseat.

### Funcionalidades da aplicação

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

### Específicação dos testes

Em cada teste, tem uma breve descrição no que sua aplicação deve cumprir para que o teste passe.

Para esse desafio temos o seguinte teste:

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, sua aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.

### Como rodar o código

Clone ou baixe o projeto e abra com editor de sua prefêrencia, lembre-se de executar o comando `yarn` ou `npm install` no seu terminal para instalar todas as dependências.

**Atenção**: Caso você esteja emulando no iOS, na pasta do seu projeto navegue até a pasta ios executando o comando `cd ios` e depois execute `pod install` para instalar todas as dependências para o iOS.

Para rodar a aplicação execute o comando `yarn android` ou `npm android`

Caso você esteja emulando no iOS execute o comando `yarn ios` ou `npm ios`

**Atenção**: Caso tenha dificuldade da aplicação se comunicar com a API utilize as seguintes configurações conforme esteja emulando, no endereço da api no arquivo `services/api.js`:

* iOS com Emulador: localhost

* iOS com dispositivo físico: IP da máquina

* Android com Emulador: localhost (adb reverse tcp:3333 tcp:3333)

* Android com Emulador: 10.0.2.2 (Android Studio)

* Android com Emulador: 10.0.3.2 (Genymotion)

* Android com dispositivo físico: IP da máquina

Para rodar os testes da aplicação execute o comando `yarn test` ou `npm run test`
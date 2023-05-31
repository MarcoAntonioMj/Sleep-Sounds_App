# Sleep-Sounds_App
[Em Construção]  A Sleep Sounds App é uma aplicação desenvolvida em Angular que emite sons relaxantes para ajudar na hora de dormir. A aplicação oferece um menu com diferentes opções de sons, como fogueira, noite chuvosa, passeio de carro, som para estudos e som relaxante. Ao selecionar uma opção, o som correspondente é reproduzido em loop.

# Requisitos
- Node.js
- Angular CLI

# Instalação
1. Certifique-se de ter o Node.js instalado em sua máquina. Você pode baixá-lo em https://nodejs.org.

2. Instale o Angular CLI globalmente executando o seguinte comando no terminal
```
npm install -g @angular/cli
```
3. Clone este repositório para sua máquina local:

4. Navegue até o diretório do projeto:

5. Instale as dependências do projeto:
```
npm install
```
# Uso

1. Inicie o servidor de desenvolvimento executando o seguinte comando no terminal:
```
ng serve
```
3. Abra seu navegador e acesse http://localhost:4200 para visualizar a aplicação.

4. No menu, escolha uma opção de som para iniciar a reprodução.

5. Para interromper a reprodução, clique no botão "Stop".
# Estrutura do Projeto

- src/app/components/menu: Pasta que contém o componente do menu.
- src/app/components/player: Pasta que contém o componente do player de som.
- src/app/services/sound.service.ts: Arquivo que contém o serviço para manipular a reprodução de sons.
- src/app/app.component.ts: Arquivo que contém a lógica do componente principal do aplicativo.
- src/app/app.component.html: Arquivo de template para o componente principal do aplicativo.
- src/app/app.component.css: Arquivo de estilo para o componente principal do aplicativo.
- src/assets: Pasta para armazenar recursos estáticos, como imagens de fundo.

# Contribuição
Contribuições são bem-vindas! Se você tiver sugestões, melhorias ou correções, sinta-se à vontade para abrir um problema ou enviar um pull request para este repositório.

# Licença

Este projeto está licenciado sob a MIT License.



# Documentação da Calculadora em React

Esta é a documentação para uma calculadora em React inspirada na calculadora do iPhone. O projeto foi desenvolvido usando componentes React e estilos CSS para criar uma interface de usuário interativa e responsiva. A calculadora possui funcionalidades básicas de uma calculadora, incluindo operações matemáticas simples e a capacidade de limpar a tela.

## Configuração do Projeto

Siga as etapas abaixo para configurar e executar o projeto da calculadora em seu ambiente de desenvolvimento.

### Pré-requisitos

Certifique-se de ter os seguintes softwares instalados em seu sistema:

- Node.js (versão 12 ou superior)
- NPM (gerenciador de pacotes do Node.js)

### Instalação

1. Clone o repositório do projeto para o seu diretório local:

   ```bash
   git clone <URL_DO_REPOSITÓRIO>
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd calculadora-react
   ```

3. Instale as dependências do projeto:

   ```bash
   npm install
   ```

### Executando o Projeto

Após concluir a instalação, execute o projeto da calculadora usando o seguinte comando:

```bash
npm start
```

O projeto será compilado e iniciará em um servidor de desenvolvimento local. Abra o navegador e acesse `http://localhost:3000` para ver a calculadora em ação.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte maneira:

```
calculadora/
  ├── src/
  │   ├── components/
  │   │   ├── Button.jsx
  │   │   ├── Button.css
  │   │   ├── Display.jsx
  │   │   |── Display.css
  |   ├── fonts/
  |   |   ├── Roboto-Thin.ttf
  |   ├── main/
  |   |   ├── Calculator.css
  |   |   ├── Calculator.jsx
  │   ├── App.css
  │   ├── App.js
  │   ├── index.css
  │   └── index.js
  ├── .gitignore
  ├── package.json
  ├── package-lock.json
  ├── README.md
  └── ...
```

A pasta `src` contém todos os componentes React e arquivos de estilo CSS relacionados ao projeto. Os principais arquivos são:

- `Button.jsx`: Componente para representar os botões da calculadora.
- `Calculator.jsx`: Componente principal da calculadora, que inclui a lógica para lidar com as operações matemáticas.
- `Display.jsx`: Componente para exibir o valor atual na tela da calculadora.
- `App.jsx`: Componente raiz do aplicativo React que renderiza a calculadora.
- `index.jsx`: Arquivo de ponto de entrada para a aplicação React.

## Personalizando a Calculadora

Você pode personalizar a aparência ou adicionar novos recursos à calculadora modificando os componentes existentes ou criando novos componentes. Os arquivos de estilo CSS também podem ser editados para alterar a aparência da calculadora.

## Considerações Finais

Esta documentação forneceu uma visão geral do projeto da calculadora em React inspirada na calculadora do iPhone. Com esta calculadora como ponto de partida, você pode explorar e expandir as funcionalidades para criar uma calculadora mais avançada ou adaptá-la para suas necessidades específicas.

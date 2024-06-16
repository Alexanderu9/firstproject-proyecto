Guia de Execução do Aplicativo 
Este aplicativo consiste em dois repositórios: login-good e firstproject-proyecto.

Siga os passos abaixo para baixar, configurar e executar o aplicativo corretamente.

Passos para Configuração e Execução Baixar os Repositórios

Extraia ambos os repositórios na mesma pasta. Abrir com Visual Studio Code

Navegue até a pasta onde você extraiu os repositórios. Abra o Visual Studio Code nesta pasta. No Visual Studio Code, selecione a pasta login-good-main. 
Executar o Servidor

No Visual Studio Code, abra o terminal. No terminal, digite o seguinte comando para iniciar o servidor: bash Copiar código npm rum start Acessar o Aplicativo

Após iniciar o servidor, abra o navegador de sua preferência. Digite o endereço http://localhost:3000/ na barra de endereços do navegador. Você será direcionado para a página de login e registro. Se você não estiver registrado, clique no botão de registrar e preencha todos os seus dados. Depois de se registrar, faça o login. Ao seguir todos os passos corretamente, você terá acesso ao jogo.

Divirta-se! 

Esperamos que você aproveite o jogo!

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

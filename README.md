## 🚀 Desafio Implementando Uma Tela de Login Com Validação Usando TypeScript

---

Nesta etapa do projeto, foi implementada a lógica de validação de formulários utilizando **React Hook Form** integrada com o **Yup** para validação de esquemas de dados, garantindo uma experiência de usuário (UX) fluida e segura.

---

### 📋 O que foi feito:
1. **Validação de Campos com Yup:**
   - **E-mail:** Validação estrita para garantir que o formato inserido contenha um endereço de e-mail válido (`@` e domínio correto).
   - **Senha:** Restrição de segurança exigindo um comprimento **mínimo de 6 caracteres**.

2. **Controle de Estado do Botão de Envio:**
   - Utilização da propriedade `isValid` fornecida pelo `formState` do **React Hook Form**.
   - Aplicação dinâmica da propriedade `disabled={!isValid}` no componente de botão customizado.
   - O botão permanece desabilitado (com opacidade reduzida e cursor `not-allowed`) enquanto o usuário não preencher todos os campos de forma correta e válida.

3. **Refatoração de Tipagens no TypeScript:**
   - Ajustes nas interfaces dos componentes (`ButtonContainer` e `IButtonProps`) para suportar corretamente atributos nativos do HTML e a propriedade de desativação (`disabled`), eliminando erros de compilação do TypeScript.

---
Conecte-se Comigo:
<p align="center">
  <img src="https://github.com/HigorCamposGit.png" width="100px" style="border-radius: 50%;" alt="Foto de Higor de Campos" /><br />
  <b>Porjeto atualizado por:</b> <a href="https://github.com/HigorCamposGit">Higor de Campos</a>
</p>

---
#Orientações originais do projeto.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

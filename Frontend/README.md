This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Steps to extecute the project :

    Before running the project make sure that the necessary Nodejs is installed in your system, if not
    download Nodejs from https://nodejs.org/en/download/package-manager/current

    Step 1 : Instal the node module using npm install
    Step 2 : For Frontend Part:
                cd Frontend
                npm i --legacy-peer-deps
                npm run dev

    Step 3 : For Backend Part:
                cd Backend
                nodemon server.js


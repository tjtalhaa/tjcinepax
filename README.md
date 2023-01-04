# Tjcinepax

This is closest version of netflix developed in react, redux, material ui

# A) EsLint Setup

1. Install es lint (npm install -g eslint)
2. run “eslint —init” and do setup
3. Add setting in setting.json in vscode so upon saving eslint autmatically works  
    "editor.codeActionsOnSave": {
   "source.fixAll.eslint": true
   },

4. Add gitignore file in setting.json in vscode so nodejs and other unnecessary files are not trasnfered

# B) Github

1. Create a new repository
2. Connect project with repository and push code via commands given on repo itself

# C) Dependencies

Install following dependecies and for 'mui' use --legacy-peer-deps so no issues in dependencies

1. npm install @alan-ai/alan-sdk-web
2. @mui/icons-material
3. @mui/material
4. @mui/styles
5. @reduxjs/toolkit
6. axios
7. React-redux
8. react-router-dom

# D) Component and Routing

1. add BrowserRouter from react-router dom in inddex.js nad wrapp App in it
2. App.js: import route and switch and make the link route for the diffenet pages of application
3. <Route> is used in <switch> and we use 'exact path' so it takes us to exact page other '/' is first character on each path and it takes us to the home every time
4. Create components and then add them in route above ,, keep the folder and file arcehtect
5.

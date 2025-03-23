# a

[Edit in StackBlitz next generation editor ⚡️](https://stackblitz.com/~/github.com/acsgunc/a)

# Project Setup


Steps to Create an Nx Workspace in StackBlitz
1️⃣ Open StackBlitz

Go to https://stackblitz.com/

Click "Create New Project"

Choose Node.js (as Nx requires a Node.js environment).

2️⃣ Install Nx CLI
In the StackBlitz terminal, run:

npx create-nx-workspace@latest a --preset=apps
cd my-nx-workspace
npm install

Generate an Angular App
Inside your Nx workspace, run:

npm install @nx/angular --save-dev

npx nx generate @nx/angular:application frontend


4️⃣ Generate a NestJS App
Inside the same workspace, run:

npm install @nx/nest --save-dev

npx nx generate @nx/nest:application backend


5️⃣ Serve the Applications
Open two terminals and run:

npx nx serve frontend  # Starts the Angular app

npx nx serve backend  # Starts the NestJS backend




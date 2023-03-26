# Creating a Svelte Project

Hello reader! Thank you for reading my very important and beneficial blog that no one else in the world could have written as I have immense knowledge on the topic of Svelte Kit!

As a semi-new user to Svelte Kit I have only recently taught myself the process of creating new projects with svelte and the general idea of using a terminal. In this blog-post I will explain, with examples, how to get started with SvelteKit and making a new project.

Here is an overview of the process:

Step 1: Install Node.js
Step 2: Create a New Svelte Project
Step 3: Install Dependencies
Step 4: Start the Development Server

Step 1: Install Node.js
Before you can create your first Svelte project, you need to ensure that you have installed Node.js onto your system. To check you can open a terminal and run the command:
 ```
npm -v 
```
This will tell you the version of Node.js you have on your computer. If it does not find a version of Node.js on your device, you can download it from the official website: https://nodejs.org/.

Step 2: Create a New Svelte Project
To create a new Svelte project, navigate to the directory where you want to create the project and run the following command in your terminal:
```
npm create svelte@latest myapp
```
This will create a new directory called myapp and generate a basic Svelte project inside it.

Step 3: Install Dependencies
After creating the project deirectory, navigate into the myapp directory and install the project dependencies by running the following command in a terminal:
```
cd myapp
npm install
```

Step 4: Start the Development Server
To start the development server and see your Svelte app in action, run the following command while in your myapp directory:
```
npm run dev -- --open
```
This will start the development server and open your app in your default browser so that you can see your site as you update the code. You can now start building your Svelte app!

Using SvelteKit and Node.js can make web design much easier than handling everything manually, it just takes a little bit of research and getting used to. Hopefully these few steps were easy to follow and you are on your way to creating your own web projects, good luck!

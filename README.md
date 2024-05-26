# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Running the app locally

Before running the app, you need to ensure you have the right local .env file.
This file is never pushed to the remote repo, and you have to always maintain yours locally.

Below are the steps to create your local environment variable

1. Create a file called `.env.local` in the root of your project
1. Copy the content of `.env.example` and paste in the newly created `.env.local` file
1. Get the right values from team members
1. If you ever create any new environment variable, make sure to add it to the `.env.example` file
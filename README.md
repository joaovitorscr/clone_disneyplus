# Disney+ Landing Page Clone

#### Original Website: https://disneyplus.com.br
#### Clone Website: https://clone-disneyplus-bay.vercel.app/

## Description:
  This is a project for [E.B.A.C](https://ebaconline.com.br/), where the objective was clone the Disney+ Landing Page how a form of practicing the knowleage we acquired during this front-end course.

## Requirements:

### Node:
  [Node](http://nodejs.org/) is really easy to install & now include [NPM](https://npmjs.org/).
  
## Install:
  ```
  $ git clone https://github.com/joaovitorscr/clone_disneyplus.git
  $ cd clone_disneyplus
  $ npm install
  ```
  
  ### Start and Watch Live:
  ```
  npm run dev
  ```
  
  ### Build:
  ```
  npm run build
  ```
## How to deploy:
  ### For the deploy i used [Vercel](https://www.vercel.com).
  
  **You can use the deployment platform of your preference but i will be giving instructions about how i made in Vercel**
  
  1. Acess the Vercel website.
  2. Go to Add New -> Project
  3. Select the repository.
  4. Open the Build and Output settings and configure the **build command** for <b>"npm run build"</b>.
  5. Configure the output directory with just a ".". 

     *That's necessary because the platform ask for the user put a parameter, because previously you set up a custom build command so the dot is just to fill this requirement.*
  6. Press **Deploy**.

## Built with:
  * [npm](https://www.npmjs.com/) - Package Manager
  * [sass](https://sass-lang.com/) - CSS Pre-processor
  * [gulp](https://gulpjs.com/) - Task optimization
  

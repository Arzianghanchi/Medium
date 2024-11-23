**Deploying Node.Js Web App**

**1. Clone the Repository:**

\- Open a terminal or command prompt.

\- Navigate to the directory where you want to clone the repository.

\- Use the \`git clone\` command followed by the URL of the GitHub repository.

-   bash

git clone <https://github.com/Arzianghanchi/Arzianghanchi.github.io.git>

![](media/506a12ae138b2dee2e058ce7e3fd4afc.png)

**2. Install Dependencies:**

Navigate into the cloned directory:

-   bash

cd Arzianghanchi.github.io

Run the following command to install the project's dependencies (libraries required for the app to function):

-   bash

    npm install next

![](media/6a825282989b2b601f5af4bc4cf319f2.png)

**3. creating the build**

This creates an optimized and production-ready build of the application, which is typically used for deployment to a web server.

\- Run the following command:

-   bash

    npm run build

![](media/9cb39819e67f0125d9acdca2d4625f0b.png)

**4. Running the Application:**

Development Mode (\`npm run dev\`):

\-This starts the application in development mode, which is ideal for making changes to the code and seeing the results immediately without a full rebuild.

\- Run the following command:

-   bash

    npm run dev

![](media/031a8ce796ecd09d440f68c8c0e6e3af.png)

The exact output will vary depending on the app. Typically, it will display a message indicating that the development server is started and listening on a specific port (e.g., \`http://localhost:3000\`). You can then access the application in your web browser by visiting that URL.

Any changes you make to the code will be automatically reflected in the browser without needing to restart the development server.

Production Mode (\`npm run build\`):

-   bash

    npm run dev

![](media/4d69281786174021b5c12cdd01cb7b70.png)

The output will depend on the app's build process. It may create a new directory containing the optimized files or modify existing ones.

.

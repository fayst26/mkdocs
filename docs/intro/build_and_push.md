# Build and push the image

Now that you have a repository, you are ready to build and push your image. An important note is that the image you are building extends the Node image, meaning you don't need to install or configure Node, yarn, etc. You can simply focus on what makes your application unique.

> What is an image/Dockerfile?
>
> Without going too deep yet, think of a container image as a single package that contains everything needed to run a process. ? In this case, it will contain a Node environment, the backend code, and the compiled React code.
>
> Any machine that runs a container using the image, will then be able to run the application as it was built without needing anything else pre-installed on the machine.
>
> A `Dockerfile` is a text-based script that provides the instruction set on how to build the image. For this quick start, the repository already contains the Dockerfile.

=== "CLI"
    1. To get started, either clone or [download the project as a ZIP file](https://github.com/docker/getting-started-todo-app/archive/refs/heads/main.zip) to your local machine.

            git clone https://github.com/docker/getting-started-todo-app

        And after the project is cloned, navigate into the new directory created by the clone:

            cd getting-started-todo-app

    1. Build the project by running the following command, swapping out `DOCKER_USERNAME` with your username.

            docker build -t DOCKER_USERNAME/getting-started-todo-app .

        For example, if your Docker username was mobydock, you would run the following:

            docker build -t mobydock/getting-started-todo-app .

    1. To verify the image exists locally, you can use the `docker image ls` command:

            docker image ls
        
        You will see output similar to the following:

            REPOSITORY                          TAG       IMAGE ID       CREATED          SIZE
            mobydock/getting-started-todo-app   latest    1543656c9290   2 minutes ago    1.12GB
            ...

    1. To push the image, use the `docker push` command. Be sure to replace `DOCKER_USERNAME` with your username:

            docker push DOCKER_USERNAME/getting-started-todo-app

        Depending on your upload speeds, this may take a moment to push.

=== "VS Code"
    1. Open Visual Studio Code. Ensure you have the Docker extension for VS Code installed from [Extension Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker).

        ![](install-docker-extension.webp)

    1. In the File menu, select Open Folder. Choose Clone Git Repository and paste this URL: [ https://github.com/docker/getting-started-todo-app](https://github.com/docker/getting-started-todo-app)

        ![](clone-the-repo.webp)

    1. Right-click the `Dockerfile` and select the **Build Image...** menu item.

        ![](build-vscode-menu-item.webp)
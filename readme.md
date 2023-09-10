![charlytoc_In_this_square-framed_image_a_golden-brown_bun_sits_a_800cfbfc-249b-434b-b8bd-f4cd15d1fb2e](./background.png)

# This project lets you build instantly with bun

- Bun is like a Swiss Army knife for JavaScript and TypeScript applications. Imagine it as a single tool that can do multiple things. It's designed to replace Node.js, which is a popular tool used to run JavaScript outside of a web browser. The main advantage of Bun is that it's faster and uses less memory, which means your applications can start and run more quickly.
- For example, if you're baking a cake (your application), Bun is like your kitchen assistant. It helps you mix the ingredients (run your scripts), preheat the oven (set up your environment), and even bake the cake (execute your application). It can also help you test the cake for doneness (run tests), and clean up afterwards (manage your packages).

Refer to the Bun documentation for more information:[Bun docs](https://bun.sh/docs)
The steps to use this project are quite simple.

## Install Docker and Devcontainers in your machine.
Docker is an open platform for developing, shipping, and running applications. It enables you to separate your applications from your infrastructure so you can deliver software quickly. Devcontainer is a development environment defined in a Docker container, it allows you to work with a consistent, sandboxed toolchain that works the same everywhere.

## Make sure Docker is running, just open Docker desktop
On Windows, you can check if Docker is running by looking for the Docker icon in your system tray. On Mac, you can check the status of Docker by clicking on the Docker icon in the menu bar. On Linux, you can check if Docker is running by executing the command `systemctl status docker` in the terminal.

## Create an empty directory and get inside in the same command
```
mkdir [name-to-your-project] && cd [name-to-your-project]

```
## Git clone this project
```
git clone https://github.com/Charlytoc/bun-starter.git .

```
## Open VSCode with the code command
```
code .
```
## Press F1 or open the command palette
Skip this step if necessary, if you don't see the button of the next step, then do this one first.

## Press `Reopen in container`
It's possible that you have been prompted to open the repo in a dev container, just press the button.

## Run your code
For example, start with the index.tsx file
```
bun index.tsx
```


Note: If you are a pro, you can just open a **new codespace** directly in GitHub and go to the last step once the image is built.

<!-- Styles for the documentation -->
<style>
h1 {
    color:aliceblue;
}
p {
    color: gray;
}
b,strong {
    background-color: yellow;
}
</style>


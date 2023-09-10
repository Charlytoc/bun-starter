## Este proyecto te permite construir instantáneamente con bun
- Bun es como una navaja suiza para las aplicaciones de JavaScript y TypeScript. Imagínalo como una única herramienta que puede hacer varias cosas. Está diseñado para reemplazar a Node.js, que es una herramienta popular utilizada para ejecutar JavaScript fuera de un navegador web. La principal ventaja de Bun es que es más rápido y utiliza menos memoria, lo que significa que tus aplicaciones pueden iniciar y ejecutarse más rápidamente.
- Por ejemplo, si estás horneando un pastel (tu aplicación), Bun es como tu asistente de cocina. Te ayuda a mezclar los ingredientes (ejecutar tus scripts), precalentar el horno (configurar tu entorno), e incluso hornear el pastel (ejecutar tu aplicación). También puede ayudarte a probar el pastel para ver si está hecho (ejecutar pruebas), y limpiar después (gestionar tus paquetes).

Ve a la documentación de Bun para más información:[Bun docs](https://bun.sh/docs)
Los pasos para usar este proyecto son bastante simples.


## Instala Docker y Devcontainers en tu máquina.
Docker es una plataforma abierta para desarrollar, enviar y ejecutar aplicaciones. Te permite separar tus aplicaciones de tu infraestructura para que puedas entregar software rápidamente. Devcontainer es un entorno de desarrollo definido en un contenedor de Docker, te permite trabajar con una cadena de herramientas consistente y aislada que funciona de la misma manera en todas partes.

## Asegúrate de que Docker esté en ejecución, simplemente abre Docker Desktop.
En Windows, puedes verificar si Docker está en ejecución buscando el icono de Docker en la bandeja del sistema. En Mac, puedes verificar el estado de Docker haciendo clic en el icono de Docker en la barra de menú. En Linux, puedes verificar si Docker está en ejecución ejecutando el comando `systemctl status docker` en la terminal.


## Crea un directorio vacío y entra en él con el mismo comando.
`mkdir [nombre-de-tu-proyecto] && cd [nombre-de-tu-proyecto]`

## Clona este proyecto con Git.
`git clone https://github.com/Charlytoc/bun-starter.git .`


## Abre VSCode con el comando `code .`
Presiona F1 o abre la paleta de comandos.
Si es necesario, omite este paso. Si no ves el botón del siguiente paso, realiza este primero.

## Presiona "Reopen in container".
Es posible que se te haya solicitado abrir el repositorio en un contenedor de desarrollo, simplemente presiona el botón.


## Ejecuta tu código.
Por ejemplo, comienza con el archivo index.tsx.
`bun index.tsx`

Nota: Si eres un profesional, simplemente puedes abrir un nuevo **codespace** de código directamente en GitHub y pasar al último paso una vez que se haya creado la imagen.


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


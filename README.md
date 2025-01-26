# Pagina demo de Hospital Nacional

## Contexto

En este proyecto, los estudiantes deberán implementar el consumo de una API para obtener y mostrar datos del sistema del hospital, como la información de doctores o servicios médicos.
Utilizando useEffect y useState, se espera que realicen peticiones asíncronas, gestionen el estado y manejen los errores de manera eficiente. Podrán utilizar Fetch API o Axios según su preferencia.

Trabajo práctico para desarrollar una página web de hospital que debe contener las siguientes páginas:

1. Vista Principal Home
2. Vista del About
3. Vista de Contact

## Cómo correr el proyecto:

1. Descargar el contenido de este repositorio en el computador. Puede ser clonando el repositorio o descargando el .zip:

   - **Clonar el repositorio**: Puede hacerlo con cualquier gestor de repositorios. Si tiene git instalado, puede abrir una terminal en algun diretorio y ejecutar:

   ```bash
   git clone url_de_este_repo
   ```

   - Si no tiene git instalado puede presionar el botón verde `<> Code` que está en esta página y seleccionar la opción `Download ZIP`.
     1. Descargue el archivo .zip en algun directorio conocido _(ej: Escritorio, Documentos, etc.)_.
     2. Descomprima el archivo .zip

2. Abrir una terminal denntro de la carpeta.
3. Ejecutar `yarn dev` y se mostrará el link para ver la pagina ejecutada en localhost.

## TO-DO (Rúbrica):

1. Consumo de APIs usando Fetch API o Axios (2 puntos)

   - [ ] Implementa el consumo de datos mediante Fetch API o Axios para interactuar con la base de datos del hospital:
     - [ ] Gestiona los datos de pacientes, citas y doctores mediante solicitudes GET, POST, PUT, y DELETE.
     - [ ] Muestra los datos obtenidos en la interfaz React de manera dinámica.
     - [ ] Maneja correctamente los errores de las peticiones y muestra mensajes claros al usuario si ocurre un problema.

2. Integración de TypeScript en Componentes Clave (2 puntos)

   - [ ] Refactoriza los componentes principales de la aplicación utilizando TypeScript:
     - [ ] Define correctamente los tipos de datos, props, y estados dentro de los componentes.
     - [ ] Usa TypeScript para mejorar la estructura y el tipado del código, evitando errores en tiempo de ejecución.
     - [ ] Aplica interfaces y clases para modelar correctamente los datos de los usuarios y del sistema.

3. Mejoras en la Seguridad del Front-End (2 puntos)

   - [ ] Implementa medidas de seguridad en la aplicación React:
     - [ ] Utiliza React Router DOM para proteger rutas y permitir el acceso solo a usuarios autenticados.
     - [ ] Protege las peticiones a la API mediante JWT para asegurar que solo usuarios con permisos puedan acceder a los datos sensibles.
     - [ ] Asegura la validación de formularios para evitar XSS y otros ataques comunes.
     - [ ] Integra encriptación para proteger la información confidencial antes de enviarla al servidor.

4. Optimización con Hooks y Manejo de Errores (1 punto)
   - [ ] Utiliza Hooks como useState y useEffect para gestionar el estado y los efectos secundarios dentro de la aplicación:
     - [ ] Implementa un Hook personalizado que maneje la lógica repetitiva de la aplicación, como la autenticación o la gestión de formularios.
     - [ ] Asegura que los errores durante las peticiones a la API o en la interfaz se gestionen correctamente, mostrando mensajes al usuario en caso de error.
     - [ ] Optimiza el rendimiento de la aplicación utilizando dependencias correctamente en useEffect y evitando renderizados innecesarios.

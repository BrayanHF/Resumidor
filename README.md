# Resumidor con OpenAI

Este proyecto utiliza la API de OpenAI y Pinecone para ofrecer funcionalidades avanzadas de inteligencia artificial. Sigue los pasos a continuación para configurar y ejecutar correctamente la aplicación.

## Requisitos previos

- Tener instalado [Git](https://git-scm.com/).
- Tener configurado un entorno de desarrollo adecuado, como Python, Node.js o el que requiera el proyecto (ver dependencias en el archivo correspondiente).
- Una cuenta en [OpenAI](https://platform.openai.com/) para obtener una clave de API.
- Una cuenta en [Pinecone](https://www.pinecone.io/) para obtener la clave de API y la información de entorno.

## Configuración

Para que la aplicación funcione correctamente, es necesario configurar las claves de API de OpenAI y Pinecone. Puedes hacerlo de dos formas:

1. **Agregar un archivo `.env`:**  
   Crea un archivo `.env` en la raíz del proyecto con el siguiente contenido:

   ```plaintext
   OPENAI_API_KEY="tu-clave-api-de-openai"
   PINECONE_API_KEY="tu-clave-api-de-pinecone"
   PINECONE_ENV="tu-entorno-de-pinecone"

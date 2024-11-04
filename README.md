# WordpressDocker + Droplets 🌐

Este proyecto tiene como objetivo explorar el uso de contenedores Docker para implementar un sitio web de WordPress. A través de este trabajo, aprendí sobre diversas tecnologías y prácticas que mejoran la seguridad y la funcionalidad de las aplicaciones web.

## Aprendizajes y Retos 📚

Este proyecto me permitió adquirir habilidades y conocimientos en las siguientes áreas:
- **Comandos de Docker**: Familiarización con los comandos esenciales de Docker para la gestión de contenedores e imágenes.
- **Creación de Archivos `docker-compose.yml`**: Aprendí a definir y configurar múltiples contenedores utilizando Docker Compose para facilitar el despliegue.
- **Redes Personalizadas y Habilitación de Puertos**: Configuración de redes personalizadas en Docker y habilitación de puertos HTTP y HTTPS para la accesibilidad del sitio.
- **Certificados SSL**: Instalación de certificados SSL para asegurar las conexiones a un sitio web de WordPress servido a través de Nginx/Apache.
- **Medidas de Seguridad**: Implementación de archivos `.env` para almacenar variables de entorno, mejorando la seguridad de la aplicación.
- **Uso de MySQL**: Implementación de MySQL como base de datos persistente, tanto en el contenedor como en el host, para la gestión de datos.
- **Configuración de Droplets en DigitalOcean**: Aprendí a configurar servidores web privados con IP única utilizando Linux Ubuntu 20.04 LTS.

## Tecnologías y Herramientas Utilizadas 🚀

- **Docker**: Utilizado para contenerizar la aplicación y gestionar el entorno de desarrollo.
- **Docker Compose**: Para la orquestación de múltiples contenedores de forma sencilla.
- **Apache**: Servidor web utilizado para alojar el sitio de WordPress.
- **MySQL**: Base de datos utilizada para la gestión persistente de datos en WordPress.
- **SSL**: Implementación de certificados SSL para asegurar la comunicación en el sitio.
- **DigitalOcean**: Uso de Droplets para la configuración de servidores privados en la nube.
- **Redis**: Para almacenar el cache.
## Herramientas de Desarrollo 🖥️

- **Linux Ubuntu 20.04 LTS**: Sistema operativo utilizado en los Droplets para configurar el servidor.
- **VSCode**: Editor de código utilizado para el desarrollo y configuración del proyecto.

## Instalación y Ejecución 🚀

1. Comandos de Docker:
   ```bash
   docker-compose up -d 

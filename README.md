# mi-app-docker

## Participantes

- Nicolás Francisco Ortiz Luna - 20212020079
- Daniel Felipe Barrera Suarez - 20212020097
- Daniel Felipe Gomez Miranda - 20212020101

**Asignatura:** Ingeniería de Software para la web backend

## Cómo probar el proyecto

Para levantar y probar el proyecto localmente:

### 1. Clonar el repositorio
Abrir la terminal y ejecutar el siguiente comando para clonar el proyecto e ingresar a la carpeta:

```bash
git clone https://github.com/NicoXtreme/Guia_Docker_DockerCompose_Init.git
cd Guia_Docker_DockerCompose_Init
```

### 2. Iniciar los servicios
Ejecutar Docker Compose en modo desacoplado (`-d`) para construir e iniciar los contenedores en segundo plano:

```bash
docker compose up -d
```

Esto iniciará los **2 servicios** configurados en el proyecto:
* **`web`**: Servicio principal de la aplicación backend/web.
* **`proxy`**: Servidor proxy encargado de gestionar y redirigir las peticiones entrantes.

---

## 🔍 Comandos útiles de monitoreo

* **Ver el estado de los contenedores:**
  ```bash
  docker compose ps
  ```

* **Ver los logs en tiempo real:**
  ```bash
  docker compose logs -f
  ```

* **Detener y eliminar los contenedores:**
  ```bash
  docker compose down
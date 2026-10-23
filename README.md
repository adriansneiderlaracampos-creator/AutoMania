# AutoMania 🚗

### Sistema web de automatización operativa y gestión para microempresas

## 1. Descripción del proyecto

AutoMania es un proyecto de desarrollo de software orientado a facilitar la gestión de actividades empresariales y la automatización de procesos repetitivos en microempresas, emprendimientos y negocios independientes.

La propuesta busca centralizar tareas como la gestión de productos e inventario, el seguimiento de clientes, la organización de actividades y la creación de reglas de automatización mediante una interfaz visual sencilla.

El sistema contempla el uso del patrón **CUANDO-SI-ENTONCES** para definir reglas de negocio y la incorporación futura de un asistente de inteligencia artificial que sugiera automatizaciones, sujetas a la revisión y aprobación del usuario.

## 2. Problema identificado

Muchos pequeños negocios gestionan sus actividades mediante herramientas separadas y procesos manuales. Esto puede dificultar el seguimiento de clientes, el control del inventario, la organización de tareas y la automatización de actividades repetitivas.

AutoMania propone una alternativa que permita organizar estas operaciones desde una plataforma web y simplificar la configuración de procesos empresariales.

## 3. Objetivo general

Desarrollar un sistema web que facilite la gestión operativa de microempresas mediante una interfaz visual intuitiva y herramientas de automatización de procesos adaptadas a sus necesidades.

## 4. Objetivos específicos

- Diseñar una interfaz web clara y fácil de utilizar.
- Proponer módulos para la gestión de productos, inventario, clientes y tareas.
- Diseñar un mecanismo de automatización basado en reglas de tipo CUANDO-SI-ENTONCES.
- Contemplar un asistente de inteligencia artificial para sugerir reglas de automatización.
- Establecer una arquitectura que permita integrar progresivamente los componentes del sistema.
- Verificar el funcionamiento de los módulos mediante pruebas durante el desarrollo.

## 5. Funcionalidades propuestas

El alcance previsto de AutoMania contempla los siguientes módulos:

- **Panel principal:** visualización general de la información del negocio.
- **Gestión de productos e inventario:** organización y seguimiento de productos.
- **Gestión de clientes:** administración de la información y seguimiento comercial.
- **Gestión de tareas:** organización de actividades y pendientes.
- **Reglas de automatización:** configuración de condiciones y acciones mediante el patrón CUANDO-SI-ENTONCES.
- **Asistente de inteligencia artificial:** sugerencias para facilitar la creación de reglas, con aprobación del usuario.
- **Notificaciones:** avisos relacionados con eventos o condiciones configuradas.

Estas funcionalidades corresponden al alcance previsto y se implementarán progresivamente.

## 6. Estado actual del proyecto

Actualmente, AutoMania se encuentra en la etapa de desarrollo visual de la interfaz web.

| Componente | Estado |
|---|---|
| Diseño visual de la interfaz | En desarrollo |
| Módulos funcionales | Pendientes de implementación e integración |
| API REST y backend | Pendientes de implementación o integración |
| Base de datos | Pendiente de implementación o integración |
| Motor de reglas | Pendiente de implementación |
| Integración con inteligencia artificial | Pendiente de implementación |
| Pruebas funcionales completas | Pendientes |
| Despliegue en servidor | Pendiente |

Los estados deberán actualizarse a medida que el equipo implemente y verifique cada componente.

## 7. Tecnologías

El proyecto contempla una aplicación web y una arquitectura que permita integrar la interfaz, la lógica de negocio y el almacenamiento de información.

Las tecnologías definitivas deberán documentarse de acuerdo con las herramientas realmente utilizadas por el equipo.

**Tecnologías utilizadas:** completar esta sección con los lenguajes, frameworks, bibliotecas, servicios y sistemas de almacenamiento que estén efectivamente implementados en el repositorio.

## 8. Requisitos previos

Para trabajar con el proyecto se requiere:

- Un computador con un sistema operativo compatible con las herramientas de desarrollo.
- Visual Studio Code u otro editor de código.
- Un navegador web actualizado.
- Git, si se utilizará para clonar y gestionar el repositorio.
- Las herramientas y dependencias específicas que correspondan a la tecnología implementada.

## 9. Instalación y ejecución

### 9.1 Descargar el proyecto

Clonar el repositorio utilizando su dirección real:

```bash
git clone URL_REAL_DEL_REPOSITORIO
```

Ingresar a la carpeta del proyecto:

```bash
cd NOMBRE_REAL_DE_LA_CARPETA
```

### 9.2 Instalar dependencias

Instalar las dependencias de acuerdo con el gestor y las tecnologías que utilice el proyecto. El comando definitivo deberá agregarse después de verificar los archivos de configuración del repositorio.

### 9.3 Ejecutar la aplicación

Iniciar el proyecto con el comando correspondiente a su configuración real y abrir en el navegador la dirección local que indique la herramienta de desarrollo.

**Nota:** los comandos definitivos de instalación y ejecución están pendientes de verificación según la estructura actual del proyecto.

## 10. Estructura del proyecto

La organización de las carpetas y los archivos debe documentarse según la estructura real del repositorio.

Como referencia, se recomienda identificar:

- Archivos de la interfaz visual.
- Hojas de estilo.
- Scripts de interacción.
- Componentes reutilizables, si existen.
- Código del backend, cuando se implemente.
- Configuración de la base de datos, cuando corresponda.
- Documentación técnica y evidencias de pruebas.

## 11. Arquitectura propuesta

AutoMania contempla una arquitectura compuesta por los siguientes elementos:

1. **Cliente o frontend:** interfaz mediante la cual el usuario interactúa con el sistema.
2. **API REST o backend:** componente previsto para procesar solicitudes y aplicar las reglas de negocio.
3. **Motor de reglas:** encargado de evaluar las condiciones configuradas y determinar las acciones correspondientes.
4. **Base de datos:** componente previsto para almacenar la información del sistema.
5. **Servicio de inteligencia artificial:** componente opcional previsto para generar sugerencias de automatización.

La integración y el funcionamiento de estos componentes deberán comprobarse durante las etapas posteriores de desarrollo.

## 12. Equipo de desarrollo

Proyecto formativo del programa de Análisis y Desarrollo de Software (ADSO), ficha 3409609, del Centro de Biotecnología Agropecuaria del SENA, Mosquera.

**Integrantes:**

- Luis Carlos García Sánchez.
- Laura Sofya Farfán Muñoz.
- Adrián Sneider Lara Campos.
- Wilmer Alexander Sánchez Cañón.

**Instructora:** Carolina Torres.

## 13. Pruebas

Las pruebas se documentarán a medida que se implementen las funcionalidades. Para cada caso se registrarán el resultado esperado, el resultado obtenido, el estado de aprobación y la evidencia correspondiente.

Actualmente, las pruebas funcionales integrales están pendientes debido a que los módulos todavía deben implementarse e integrarse.

## 14. Seguridad y protección de datos

Durante el desarrollo se deberán considerar medidas para proteger la información de los usuarios, controlar los permisos de acceso, evitar la exposición de credenciales y cumplir las disposiciones aplicables sobre protección de datos personales.

Las medidas definitivas deberán documentarse y verificarse cuando se implementen los componentes funcionales.

## 15. Licenciamiento

La licencia del proyecto deberá definirse por el equipo responsable. Las bibliotecas, dependencias y recursos externos utilizados deberán respetar sus respectivas licencias y condiciones de uso.

## 16. Mejoras futuras

Entre las mejoras previstas se encuentran:

- Completar e integrar los módulos funcionales.
- Implementar el almacenamiento persistente de la información.
- Desarrollar y probar el motor de reglas.
- Integrar el asistente de inteligencia artificial con supervisión humana.
- Realizar pruebas funcionales y validaciones con usuarios.
- Preparar el despliegue en un entorno de alojamiento.
- Elaborar manuales técnicos y de usuario.

## 17. Estado de la documentación

Este README describe el propósito, el alcance y el estado actual del proyecto AutoMania. Se actualizará conforme avance la implementación, se verifiquen las tecnologías utilizadas y se incorporen evidencias de funcionamiento.


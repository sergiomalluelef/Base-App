# Estructura Básica de Carpetas para Desarrollo Android

Este repositorio exhibe una estructura elemental de carpetas diseñada para explorar conceptos generales en el desarrollo en la plataforma Android, haciendo uso de las bibliotecas Hilt y Compose.

## Estructura de Carpetas

Las carpetas principales en esta estructura son:

- **core**: Contiene componentes esenciales y lógica compartida, como modelos de datos genéricos y utilidades fundamentales.

- **di**: Configuración de inyección de dependencias con Hilt, permitiendo un desacoplamiento flexible entre los componentes.

- **data**: Gestiona la obtención y almacenamiento de datos, incluyendo acceso a bases de datos locales o APIs remotas.

- **presentation**: Alberga componentes relacionados con la presentación de la interfaz de usuario, como ViewModels y adaptadores.

- **ui**: Contiene recursos y componentes de la interfaz de usuario, como Activities y funciones Composables.


## Bibliotecas Bases

- **Hilt**: Se utiliza la biblioteca Hilt para la inyección de dependencias, facilitando una configuración sencilla y una gestión eficiente de las dependencias en todo el proyecto.

- **Compose**: Compose es la biblioteca base para la creación de interfaces de usuario declarativas y modernas. Se fomenta el uso de Compose en la carpeta ui para construir componentes de interfaz de usuario interactivos.

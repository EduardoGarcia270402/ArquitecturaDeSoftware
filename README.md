# Arquitectura de Software

Repositorio de trabajos de la asignatura de Arquitectura de Software. El contenido está organizado por taller y por tecnología, según los nombres de las carpetas.

## Manual de navegación

### Talleres

- **TLL1.1 — SOAP con Java y sin base de datos** (`TLL1.1 PAO202651_SOAP_JAVA_SINBDD_NRC36883_GR05/`): incluye documentación de requisitos y casos de uso, modelos UML, un proyecto de servidor Java y recursos de documentación.
- **TLL1.2 — SOAP con .NET y sin base de datos** (`TLL1.2 PAO202651_SOAP_DOCNET_SINBDD_NRC36883_GR05/`).
- **TLL1.3 — RESTful con Java y sin base de datos** (`TLL1.3 PAO202651_RESTFUL_JAVA_SINBDD_NRC36883_GR05/`).
- **TLL1.4 — RESTful con .NET y sin base de datos** (`TLL1.4 PAO202651_RESTFUL_DOCNET_SINBDD_NRC36883_GR05/`).

### Contenido del taller TLL1.1

Dentro de la carpeta TLL1.1, los directorios están organizados así:

- `01. UML/01. ERS/`: especificación de requisitos y material de casos de uso.
- `01. UML/02. ECUD/`: documentación ECUD.
- `01. UML/03. DIAGRAMAS/`: archivos de diagramas de casos de uso, actividad, secuencia, clases y arquitectura.
- `05. SERVIDOR/WSCOMSERVIDOR/`: proyecto Java con Maven. El archivo `pom.xml` describe su configuración y dependencias.
- `06. DOCUMENTACION/img/`: imágenes de apoyo para la documentación.
- `SOAP_JAVA_SINBDD_GR05.sws`: archivo de solución asociado al taller.

## Cómo usar este repositorio

1. Clona el repositorio y abre la carpeta del taller que necesitas.
2. Para consultar el análisis, comienza por los documentos en `01. UML/01. ERS/` y `01. UML/02. ECUD/`; luego revisa los diagramas en `01. UML/03. DIAGRAMAS/`.
3. Para explorar el servidor de TLL1.1, abre `05. SERVIDOR/WSCOMSERVIDOR/` como proyecto Maven en tu IDE.
4. Consulta `06. DOCUMENTACION/img/` para ver las imágenes relacionadas con los casos de uso.

Los directorios TLL1.2, TLL1.3 y TLL1.4 están preparados para organizar los otros talleres. Cuando se agreguen sus archivos, esta guía puede ampliarse con sus instrucciones específicas.

## Convención de commits

Los commits de este repositorio usan prefijos convencionales, por ejemplo `feat:` para funcionalidades o contenido nuevo, `fix:` para correcciones y `docs:` para documentación.

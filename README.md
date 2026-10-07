# Liga MX - Resultados y Estadísticas XML

Proyecto académico para modelar los resultados, estadísticas arbitrales y de juego de la Liga MX utilizando XML y validación mediante XML Schema (XSD).

## Estructura del Repositorio

- `xml/resultados.xml`: Documento que contiene los datos estructurados de los encuentros de la jornada del 27 de septiembre de 2026.
- `xsd/resultados.xsd`: Definición del Schema de XML empleado para validar la integridad de la estructura y los tipos de datos del documento XML.

## Instrucciones de Validación

Para comprobar que el archivo `resultados.xml` cumple con las reglas del archivo `resultados.xsd`, se puede utilizar cualquier IDE moderno (como IntelliJ IDEA, Visual Studio Code o Eclipse) que soporte validación automática de XML Schema, o herramientas de línea de comandos como `xmllint`:

```bash
xmllint --noout --schema xsd/resultados.xsd xml/resultados.xml

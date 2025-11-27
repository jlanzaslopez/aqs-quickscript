# AQS QuickScript VS Code Extension

AQS QuickScript es una extensión de Visual Studio Code diseñada para editar scripts de **ArchestrA / AVEVA System Platform (QuickScript .NET)** fuera del IDE de System Platform. La extensión crea de forma artificial la extensión de archivo `.aqs` para habilitar coloreado, snippets y reglas de indentación en VS Code; QuickScript no utiliza archivos `.aqs` de manera nativa.

## ¿Para qué sirve?
1. Copia el script desde un objeto o gráfico del IDE de System Platform.
2. Pégalo en un archivo `.aqs` ficticio dentro de tu proyecto.
3. Edita, formatea y aplica snippets en VS Code con herramientas modernas.
4. Copia y pega el script final de vuelta en el IDE cuando termines.

No existe un flujo oficial de importación o exportación de scripts QuickScript mediante ficheros; esta extensión es solo una ayuda de edición externa y offline.

## Características actuales
- **Definición de lenguaje AQS**
  - Extensión inventada: `.aqs`
  - Identificador de lenguaje: `aqs`
  - Alias: "AQS" y "ArchestrA QuickScript"
- **Coloreado de sintaxis** mediante gramática TextMate con soporte para comentarios (`'` y `{ ... }`), strings con comillas dobles, números y palabras clave básicas de QuickScript .NET.
- **Snippets básicos**: bloques `If/EndIf`, `While/EndWhile`, `For/Next` y `Try/Catch/EndTry`.
- **Reglas de lenguaje**: indentación automática en bloques, pares de cierre automáticos y reconocimiento de brackets.

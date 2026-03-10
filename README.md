# ZenRepair
Descripción General
Propósito
ZenRepair es una herramienta de diagnóstico/reparación de memorias USB que opera en el navegador web como un archivo HTML5. Su función es guiar al usuario en la ejecución de los comandos correctos de reparación según su sistema operativo.
El programa NO ejecuta comandos directamente en el sistema; en su lugar, genera los comandos precisos que el usuario debe ejecutar en su terminal, reduciendo errores humanos.

Características Principales
     •	Soporte multiplataforma: Windows, Linux y macOS.
     •	Generación dinámica de comandos según el sistema operativo.
     •	Cinco categorías de operaciones: 1-escaneo, 2-detección de sectores dañados, 3-reparación, 4-recuperación de archivos y 5-formateo.
     •	Guía de diagnóstico por síntomas para usuarios no técnicos.
     •	Botón de copia directa al portapapeles para cada comando generado.
     •	Sin dependencias externas: todo el código está embebido en un único archivo.

Caso de Uso Típico
     1.	El usuario conecta la memoria USB problemática al ordenador.
     2.	Abre el archivo index.html en cualquier navegador moderno.
     3.	Selecciona su sistema operativo y la letra/ruta de la unidad USB.
     4.	Marca las operaciones que desea realizar.
     5.	Pulsa 'Generar Comandos' y copia los comandos a su terminal.
     6.	Ejecuta los comandos como administrador/root en el sistema operativo.

Limitaciones Técnicas
      •	El programa NO detecta automáticamente los dispositivos USB conectados al sistema. El usuario debe identificar manualmente la letra de unidad o ruta del 
        dispositivo.
      •	No ejecuta comandos directamente: es una herramienta generadora de comandos, no un ejecutor.
      •	La detección de unidades predefinidas en el selector es genérica; el usuario debe verificar que la unidad mostrada corresponde a su USB real.
      •	Los comandos de badblocks en Linux pueden tardar entre 1 y varias horas en USBs de alta capacidad.


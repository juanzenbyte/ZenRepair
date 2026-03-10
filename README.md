# ZenRepair
Descripción General/Propósito
ZenRepair es una herramienta de diagnóstico/reparación de memorias USB que opera en el navegador web como un archivo HTML5. Su función es guiar al usuario en la ejecución de los comandos correctos de reparación según su sistema operativo. El programa NO ejecuta comandos directamente en el sistema; en su lugar, genera los comandos precisos que el usuario debe ejecutar en su terminal, reduciendo errores humanos.

Características Principales
1.	Soporte multiplataforma: Windows, Linux y macOS.
2.	Generación dinámica de comandos según el sistema operativo.
3.	Cinco categorías de operaciones: 1) Escaneo, 2) Detección de sectores dañados, 3) Reparación, 4) Recuperación de archivos y 5) Formateo.
4.	Guía de diagnóstico por síntomas para usuarios no técnicos.
5.	Botón de copia directa al portapapeles para cada comando generado.
6.	Sin dependencias externas: todo el código está embebido en un único archivo.

Caso de Uso Típico
1.	El usuario conecta la memoria USB problemática al ordenador.
2.	Abre el archivo index.html en cualquier navegador moderno.
3.	Selecciona su sistema operativo y la letra/ruta de la unidad USB.
4.	Marca las operaciones que desea realizar.
5.	Pulsa 'Generar Comandos' y copia los comandos a su terminal.
6.	Ejecuta los comandos como administrador/root en el sistema operativo.

Limitaciones Técnicas
1.	El programa NO detecta automáticamente los dispositivos USB conectados al sistema. El usuario debe identificar manualmente la letra de unidad o ruta del 
     dispositivo.
2.   No ejecuta comandos directamente: es una herramienta generadora de comandos, no un ejecutor.
3.	La detección de unidades predefinidas en el selector es genérica; el usuario debe verificar que la unidad mostrada corresponde a su USB real.
4.	Los comandos de badblocks en Linux pueden tardar entre 1 y varias horas en USBs de alta capacidad.


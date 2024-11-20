# Práctica 2.2: Evaluación de IDEs

1ºDAW B - Entornos de desarrollo

## Parte Individual: Trabajo Personal en los Puntos 1-6

### 2.1 Instalación de Entornos de Desarrollo

**Entornos Seleccionados:**

- Visual Studio Code (Libre)
- PyCharm (Propietario)

**Diferencias en el Proceso de Instalación:**

Decidí instalar los IDEs en Linux, especialmente Ubuntu.

Primero hice un `sudo apt update && sudo apt upgrade -y` para actualizar y recoger los últimos paquetes.

Posteriormente me fui a la Ubuntu Store y instale ambos IDEs (aunque VSCode es un editor realmente, pero con extensiones se convierte prácticamente en un IDE).

![Ubuntu Software APPs Installed](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/Ubuntu-Software-APPS-Installed.png)

- **VSCode**: La instalación fue rápida y ligera muy sencilla. Solamente he hecho un click. Y después se me abrió VSCODE para configurar todas las extensiones, temas, etc.

- **PyCharm**: Al ser un IDE más pesado y con características avanzadas, la instalación tomó más tiempo y requería mayor espacio en disco. Aunque al hacerlo desde Ubuntu se hizo bastante intuitivo y solamente lo busque desde la Ubuntu Store y le di un click y se instalo al igual que VSCode.

**Ventajas en el Proceso de Instalación:**

- **VSCode**: Su ligereza y flexibilidad fueron ventajosas para una instalación rápida y sin complicaciones.

![Ubuntu Software VSCode Instalacion (Sin instalar)](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Installation-0.png)
![Ubuntu Software VSCode Instalacion (Instalado)](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Installation-1.png)

- **PyCharm**: Una característica importante es que despues de su instalación y ejecución, me permitió cargar la configuración que ya tenía en VSCode pues lo tenia ya instalado. Aun así para este ejemplo no lo hice, y decidi cargarlo sin configuraciones existentes.

### 2.2 Gestión de Módulos y Extensiones en el Entorno de Desarrollo

**Extensiones Instaladas:**

- En VSCode, instalé la extensión de Python para facilitar el desarrollo en este lenguaje.

INSTALÉ LAS EXTENSIONES BÁSICAS DE PYTHON (Python, Python Debugger y Python Extension Pack). Y después instalé python-snippets que sirven para autocompletar código de forma sencilla, creado especialmente para Python.

![Browsing Python Extensions in VSCode](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Extension-0(Python-browsing).png)
![python-snippets VSCode Extension](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Installation-1.png)

- En PyCharm, me instalé Python Security que al parecer detecta fallos de seguridad, cosa que está bastante bien cuando desarrollamos aplicaciones web con Python, pues te ayuda a detectar brechas de seguridad. Y luego me instalé python-typer-adder que te ayuda a autocompletar mientras escribes de forma más sencilla, especialmente en la documentación.

![Python Security Extension (PyCharm)](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/PyCharm/Extension-1.png)
![Python Typing Adder Extension (PyCharm)](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/PyCharm/Extension-2.png)

**Proceso de Instalación de Extensiones:**

- **VSCode**: La instalación fue sencilla, ya que cuenta con un panel de extensiones fácil de navegar donde solo tuve que buscar “Python” e instalarlo.

- **PyCharm**: En PyCharm, las extensiones se gestionan a través del menú de “Plugins”, donde se puede buscar “Python” y agregar módulos de forma sencilla para Python.

**Beneficios de las Extensiones Instaladas:**

Los beneficios de cada extensión instalada lo he comentado anteriormente adjuntando a cada extensión que me he instalado.

### 2.3 Personalización y Automatización del Entorno

**Personalización Realizada:**

- **VSCode**: Cambié el tema a “Beared Theme” desde extensiones y luego me instalé Material Icons que te cambia los iconos de los archivos del menú lateral izquierdo, haciendo más accesible la navegación mientras programas con miles de iconos.

![VSCode Bearded Theme Installation](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Extension-3-Bearded-Theme-1.png)
![VSCode Bearded Theme Customization](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Extension-3-Bearded-Theme-2.png)

![VSCode Bearded Theme Customization](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Extension-2-Material-Icon-Theme.png)

- **PyCharm**: Usé el tema “High Contrast” y personalice el tamaño de la letra.

![PyCharm Theme Customization](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/PyCharm/Theme.png)

**Automatización de Tareas:**

- En VSCode, configuré una tarea para ejecutar archivo main.py de Python.

![VSCode Task Automatization 1](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Task-1.png)
![VSCode Task Automatization 2](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Task-2.png)
![VSCode Task Automatization 3](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Task-3.png)
![VSCode Task Automatization 4](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Task-4.png)
![VSCode Task Automatization 5](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Task-5.png)

- En PyCharm, configuré una tarea para ejecutar archivo main.py de Python.

![PyCharm Task Automatization 1](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/PyCharm/Automation-1.png)
![PyCharm Task Automatization 2](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/PyCharm/Automation-2.png)

**Beneficios de la Personalización y Automatización:**

- **VSCode**: La personalización y la tarea automatizada hicieron que el flujo de trabajo fuera más rápido y con menos interrupciones, pues a la hora de ejecutar el archivo simplemente ejecuto la tarea y no tengo que estar moviéndome por directorios en la terminal. Este caso fue sencillo, pero en aplicaciones mas avanzadas no sirve con simplemente hacer un click en el icono para ejecutar de python.

- **PyCharm**: La automatización de pruebas ahorró tiempo y me ayudó a detectar errores en tiempo real. Hice lo mismo que en la automatización de VSCode pero en PyCharm, para aportar los mismos beneficios que he comentado anteriormente.

### 2.4 Configuración del Sistema de Actualización del Entorno de Desarrollo

**Configuración de Actualizaciones:**

- **VSCode**: Configuré actualizaciones automáticas desde el menú de configuración, lo cual permite que las nuevas versiones se instalen sin intervención.

- **PyCharm**: PyCharm ofrece notificaciones para actualizaciones, que activé para recibir avisos antes de instalar las mejoras.

**Importancia de Mantener el IDE Actualizado:**

Es fundamental mantener ambos IDEs actualizados para beneficiarse de las mejoras en seguridad, rendimiento, y nuevas funcionalidades que optimizan el desarrollo de proyectos.

### 2.5 Generación de Ejecutables a partir de Código Fuente en Distintos Lenguajes en un Mismo IDE

**Lenguajes Usados:**

- Python en VSCode

**Proceso de Ejecución en Diferentes Lenguajes:**

- La configuración de los entornos fue simple en VSCode, permitiendo alternar entre proyectos de Python sin necesidad de cerrar el IDE, simplemente configurando el intérprete o compilador adecuado.

- Aproveché la automatización que generé anteriormente para ejecutar el codigo Python3, especialmente el archivo main.py.

![VSCode File Execution With Task 1](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Ejecucion-Con-Task-1.png)
![VSCode File Execution With Task 2](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Ejecucion-Con-Task-2.png)

**Diferencias en la Generación de Ejecutables:**

- **Python**: Ejecutar el código es directo, con salida en la consola.
- Aunque la composición en VSCode suele ser más directa con archivos, al crear un entorno en PyCharm, te suele generar una template de archivos Python, con carpetas “libs”, etc.

### 2.6 Generación de Ejecutables con Diferentes IDEs a partir del Mismo Código Fuente

**Código Fuente:**

![VSCode Cuenta Atrás Código Fuente](https://raw.githubusercontent.com/obezeq/DAW1B-Practica-2-2-Evaluacion-IDEs_EOB/refs/heads/main/public/VSCode/Codigo-1.png)

**Diferencias en la Ejecución en Diferentes IDEs:**

- **VSCode**: La ejecución es rápida, pero depende de la extensión de Python. La interfaz permite ver resultados en la terminal integrada sin mucha configuración adicional.

- **PyCharm**: Ofrece un entorno más robusto para Python, con herramientas de depuración avanzadas y un flujo de trabajo más automatizado para ejecutar el código.

**Preferencia Personal:**

- VSCode es más cómodo y eficiente para desarrollo en Python porque para mi es mas simple y aun así, completo de usar, con muchas funcionalidades útiles.

# HISTORIA LENGUAJE ENSAMBLADOR 

 

En la década de 1940, cuando se desarrollaron las primeras computadoras, los programadores escribían instrucciones en código binario, lo que era extremadamente tedioso y propenso a errores. Para facilitar este proceso, se introdujeron los lenguajes ensambladores en la década de 1950. Estos lenguajes permiten a los programadores utilizar mnemotécnicos, que son representaciones simbólicas de las instrucciones de la máquina, en lugar de tener que escribir en código máquina, es un lenguaje de programación que se usa en los microprocesadores 
 
El primer lenguaje ensamblador se desarrolló para la computadora ENIAC, y a medida que las arquitecturas de las computadoras evolucionaron, también lo hicieron los lenguajes ensambladores. Cada tipo de procesador tiene su propio conjunto de instrucciones y, por lo tanto, su propio lenguaje ensamblador. 

La evolución en los años 60 y 70: Con la llegada de nuevos procesadores y arquitecturas de computadoras en los años 60 y 70, los lenguajes ensamblador también evolucionaron. Surgieron ensambladores más sofisticados que incluían características como macros y pseudoinstrucciones, lo que permitía a los programadores escribir código más complejo y estructurado. 

 

El declive en los años 80 y 90: Aunque los lenguajes ensamblador seguían siendo esenciales, especialmente en sistemas embebidos y aplicaciones de alto rendimiento, los lenguajes de alto nivel como C comenzaron a ganar popularidad debido a su portabilidad y facilidad de uso. Sin embargo, el ensamblador seguía siendo la mejor opción para ciertas tareas críticas, como el desarrollo de sistemas operativos, controladores de dispositivo y aplicaciones de tiempo real. 

 
 
A lo largo de los años, el lenguaje ensamblador ha sido fundamental para el desarrollo de sistemas operativos, controladores de hardware y aplicaciones que requieren un alto rendimiento. Aunque hoy en día muchos programadores prefieren lenguajes de alto nivel por su facilidad de uso, el ensamblador sigue siendo relevante, especialmente en áreas donde el control del hardware y la optimización del rendimiento son cruciales. 

Aprender ensamblador siempre valdrá la pena, ya que significa aprender el funcionamiento interno de la máquina. 

CAMPO DE APLICACION PRINCIPAL  

Implementa una representación simbólica de los códigos de máquina binarios y otras constantes necesarias para programar una arquitectura de procesador y constituye la representación más directa del código máquina específico para cada arquitectura legible por un programador. Cada arquitectura de procesador tiene su propio lenguaje ensamblador que usualmente es definida por el fabricante de hardware, y está basada en los mnemónicos que simbolizan los pasos de procesamiento (las instrucciones), los registros del procesador, las posiciones de memoria y otras características del lenguaje. Un lenguaje ensamblador es por lo tanto específico de cierta arquitectura de computador física (o virtual). Esto está en contraste con la mayoría de los lenguajes de programación de alto nivel, que idealmente son portables. 

Definición: El lenguaje ensamblador es un tipo de lenguaje de bajo nivel utilizado para escribir programas informáticos, y constituye la representación más directa del código máquina específico para cada arquitectura de microprocesador. 

A pesar de su complejidad, el ensamblador ofrece ventajas significativas en términos de optimización de código y eficiencia, especialmente en sistemas con recursos limitados o donde se necesita un alto rendimiento. Proporciona una comprensión detallada de cómo las instrucciones de alto nivel se traducen en operaciones a nivel de hardware, lo que es muy valioso para profundizar en la comprensión de la informática. 

A pesar de la prevalencia de lenguajes de programación de alto nivel, el lenguaje ensamblador mantiene su relevancia en varios campos especializados. En el desarrollo de sistemas embebidos, donde la eficiencia de recursos y el rendimiento son críticos, es insuperable. También juega un papel importante en el desarrollo de videojuegos, especialmente en la optimización de gráficos y físicas para aprovechar al máximo el hardware. Además, en el ámbito de la seguridad informática, es esencial para el análisis de malware y la ingeniería inversa. 

El ensamblador permite a los desarrolladores optimizar el software para un rendimiento específico del hardware. Esto es particularmente útil en aplicaciones que requieren una gran cantidad de cálculos en tiempo real o que deben ejecutarse en  hardware con recursos limitados. Al poder manipular directamente el hardware, los programadores pueden extraer el máximo rendimiento de un sistema. 

El ensamblador también desempeña un papel educativo importante. Aprender y utilizar ensamblador proporciona una comprensión más profunda de cómo funciona el hardware a nivel bajo. Esta comprensión es muy importante para aquellos que buscan diseñar software más eficiente, incluso en lenguajes de alto nivel. 

Fue usado principalmente en los inicios del desarrollo de software, cuando aún no se contaba con potentes lenguajes de alto nivel y los recursos eran limitados. Actualmente se utiliza con frecuencia en ambientes académicos y de investigación, especialmente cuando se requiere la manipulación directa de hardware, alto rendimiento, o un uso de recursos controlado y reducido. También es utilizado en el desarrollo de controladores de dispositivo (en inglés, device drivers) y en el desarrollo de sistemas operativos, debido a la necesidad del acceso directo a las instrucciones de la máquina. Muchos dispositivos programables (como los microcontroladores) aún cuentan con el ensamblador como la única manera de ser manipulados. 

TIPO DE EJECUCION  

PARADIGMAS DE PROGRAMACION 

Programa de computadora: Es conjunto de instrucciones detalladas que indican paso a paso a una computadora como resolver un problema o realizar una tarea. Puede ser escrito en un lenguaje de programación. 

Lenguaje de programación: Conjunto de reglas e instrucciones estandarizadas para la creación de programas de cómputo. 

Generalmente, un programa ensamblador (assembler en inglés) moderno crea código objeto traduciendo instrucciones mnemónicas de lenguaje ensamblador en opcodes, y resolviendo los nombres simbólicos para las localizaciones de memoria y otras entidades.2 El uso de referencias simbólicas es una característica clave del lenguaje ensamblador, evitando tediosos cálculos y actualizaciones manuales de las direcciones después de cada modificación del programa. La mayoría de los ensambladores también incluyen facilidades de macros para realizar sustitución textual - ej. generar cortas secuencias de instrucciones como expansión en línea en vez de llamar a subrutinas. 

Los ensambladores son generalmente más simples de escribir que los compiladores para los lenguajes de alto nivel, y han estado disponibles desde los años 1950. Los ensambladores modernos, especialmente para las arquitecturas basadas en RISC, tales como MIPS, Sun SPARC, y HP PA-RISC, así como también para el x86 (-64), optimizan la planificación de instrucciones para explotar la segmentación del CPU eficientemente. 

En los compiladores para lenguajes de alto nivel, son el último paso antes de generar el código ejecutable. 

Número de pasos[editar] 

Hay dos tipos de ensambladores basados en cuántos pasos a través de la fuente son necesarios para producir el programa ejecutable. 

Los ensambladores de un solo paso pasan a través del código fuente una vez y asumen que todos los símbolos serán definidos antes de cualquier instrucción que los refiera. 

Los ensambladores de dos pasos crean una tabla con todos los símbolos y sus valores en el primer paso, después usan la tabla en un segundo paso para generar código. El ensamblador debe por lo menos poder determinar la longitud de cada instrucción en el primer paso para que puedan ser calculadas las direcciones de los símbolos. 

La ventaja de un ensamblador de un solo paso es la velocidad, que no es tan importante como lo fue en un momento dados los avances en velocidad y capacidades del computador. La ventaja del ensamblador de dos pasos es que los símbolos pueden ser definidos dondequiera en el código fuente del programa. Esto permite a los programas ser definidos de maneras más lógicas y significativas, haciendo los programas de ensamblador de dos pasos más fáciles de leer y mantener. 

Ensambladores de alto nivel[editar] 

Los más sofisticados ensambladores de alto nivel proporcionan abstracciones del lenguaje tales como: 

Estructuras de control avanzadas 

Declaraciones e invocaciones de procedimientos/funciones de alto nivel 

Tipos de datos abstractos de alto nivel, incluyendo las estructuras/récords, uniones, clases, y conjuntos 

Procesamiento de macros sofisticado (aunque está disponible en los ensambladores ordinarios desde finales de los años 1960 para él IBM S/360, entre otras máquinas) 

Características de programación orientada a objetos 

 

Clasificación Según su grado de dependencia de la maquina 

·         Lenguaje máquina: (1940-1950) Consistía en sucesiones de dígitos binarios. Todas las instrucciones y mandatos se escribían valiéndose de cadenas de estos dígitos. Aún en la actualidad, es el único lenguaje interno que entiende la computadora; los programas se escriben en lenguajes de mayor nivel y se traducen a lenguaje de máquina. 

·         Lenguajes ensambladores: Fines de los ’50. Se diferencian de los lenguajes de máquina en que, en lugar de usar códigos binarios, las instrucciones se representan con símbolos fáciles de reconocer, conocidos como mnemotécnicos,. Aún se utilizan estos lenguajes cuando interesa un nivel máximo de eficiencia en la ejecución o cuando se requieren manipulaciones intrincadas. Al igual que los lenguajes de la máquina, los lenguajes ensambladores son únicos para una computadora particular. 

·         Lenguaje de Medio nivel: Combinan la abstracción de los lenguajes de alto nivel con el acceso cercano al hardware, como es el caso de C. 

·         Lenguajes de Alto Nivel: Son independientes de la máquina y se pueden utilizar en una variedad de computadoras. Pertenecen a esta categoría la tercera y la cuarta generación. Los lenguajes de más alto nivel no ofrecen necesariamente mayores capacidades de programación, pero si ofrecen una interacción programador/computadora más avanzada. Cuanto más alto es el nivel del lenguaje, más sencillo es comprenderlo y utilizarlo. 

Según su estilo de programación 

·         Imperativos: Son aquellos lenguajes, que basan su funcionamiento en un conjunto de instrucciones secuenciales, las cuales, al ejecutarse, van alterando las regiones de memoria donde residen todos los valores de las variables involucradas en el problema que se plantea resolver. Es decir, se cambia progresivamente el estado del sistema, hasta alcanzar la solución del problema 

 Declarativos: En este paradigma, más que el ¿cómo? desarrollar paso a paso un proceso, nos interesa el ¿qué? deseamos obtener a través del programa. Quizás el lenguaje declarativo que nos sea más familiar es SQL, el cual es utilizado para interactuar con la información de bases de datos. 

   Funcionales: Son lenguajes basados en funciones, las cuales se representan mediante expresiones, que nos permiten obtener ciertos resultados a partir de una serie de argumentos 

·         Lógicos: Este tipo de lenguajes se basa en el cálculo de predicados, la cual es una teoría matemática que permite entre otras cosas, lograr que un ordenador basándose en un conjunto de hechos y de reglas lógicas, pueda derivar en soluciones inteligentes. 

·         Orientados a Objetos: Los programas de este tipo, se concentran en los objetos que van a manipular, y no en la lógica requerida para manipularlos. Ejemplos de objetos pueden ser: estudiantes, coches, casa, etc., cada uno de los cuales tendrá ciertas funciones (métodos) y ciertos valores que los identifican, teniendo, además, la facultad de comunicarse entre ellos a través del paso de mensajes. 

 

Una variable, en un DSP es una celda en memoria o bien es un arreglo de celdas en memoria, dependiendo del tipo de dato que represente la variable. En lenguaje ensamblador se hace referencia a una variable por su dirección en memoria, de la misma manera que un puntero en lenguaje de alto nivel. La variable más pequeña es del tipo entero y ocupa 16 bits o bien, 2 celdas en memoria, no obstante que el DSP puede leer byte a byte. La tabla 1 indica los tipos de datos que puede manejar el TMS320C6713. 

Ahora bien, el DSP no realiza operaciones aritméticas tomando las variables de memoria, más bien:  

 El DSP copia las variables desde la memoria a sus registros  

 Entonces realiza las operaciones aritméticas y lógicas en sus registros. Los registros del DSP son de 32 bits, por lo cual puede trabajar bien con datos de 8, 16 y 32 bits. 

 Para datos del tipo “.double”, los cuales son de 64 bits, el DSP permite el uso de parejas de registros. 

 

CURIOSIDADES DE ENSAMBLADOR 

 

Kathleen Booth  Nacida en Reino Unido en 1922 (muere, por tanto, centenaria), obtuvo un doctorado en Matemáticas Aplicadas en 1950, tras haber estudiado la arquitectura de computación de Von Neumann junto a su creador (John Von Neumann, sí, el del Proyecto Manhattan). 

Kathleen ya había co-diseñado junto a su compañero de investigación y marido, Andrew Booth (sí, el del algoritmo de multiplicación de Booth), una de las primeras computadoras de la historia (ARC) y ambos decidieron incorporar las aportaciones de Von Neumann al diseño de ARC2. 

Es triste codificar en ensamblador, pero más triste es recablear 

Pero Kathleen hizo algo más: escribir un libro titulado ‘Coding for A.R.C.’ donde presentaba el primer ‘lenguaje ensamblador’ (decimos «el primer» porque el ensamblador no es multiplataforma: varía necesariamente según la arquitectura del chip usado). 

Recordemos que, unos pocos años antes, durante la Segunda Guerra Mundial, los estadounidenses habían creado la computadora ENIAC, cuya programación se realizaba girando conmutadores y recableando físicamente elementos del ordenador. Por aquel entonces, el único «lenguaje» que le venía a alguien a la mente al hablar de estas máquinas era el binario. 

Así que Kathleen ideó una manera de agrupar pequeños conjuntos de instrucciones en binario y vincularlos a un ‘mnemónico’, una instrucción escrita en texto [más o menos] ‘comprensible para humanos’ (aunque no especialmente intuitiva). Quedaban inaugurados así los lenguajes «de bajo nivel», que permiten ejercer un control directo sobre el hardware, un control que va diluyéndose según aumenta el ‘nivel’ del lenguaje (Ensamblador > C > JavaScript). 

IDE para lenguaje ensamblador 

Easy Code Visual assembly IDE: Easy Code es el entorno visual de programación en ensamblador hecho para generar aplicaciones Windows de 32 bits. La interfaz de Easy Code, muy parecida a la de Visual Basic, le permite programar todo tipo de aplicaciones en ensamblador (archivos ejecutables, librerías dinámicas y estáticas, archivos objeto COFF, aplicaciones de consola, drivers y servicios) de una manera rápida y fácil como nunca antes había sido posible. Se encuentran disponibles tres versiones de Easy Code:- Versión 2.x Fasm, GoAsm, JWasm, Masm y PoAsm, que necesita diversos conjuntos de herramientas para los diferentes ensambladores- Versión 1.x Masm que utiliza el Macro Assembler de Microsoft distribuído con el Masm32 SDK- Versión 1.x GoAsm que utiliza las herramientas Go tools de Jeremy Gordon, distribuídas con el archivo ECGo, y las GoAsm Headers. 

 

Fresh IDE es un IDE visual para el lenguaje ensamblador con un compilador integrado Flat assembler (FASM). Está escrito en Fresh IDE y es una aplicación independiente compilable. Es totalmente compatible con FASM y puede ser compilado también con todas las versiones de FASM. El objetivo principal de Fresh IDE es hacer la programación en ensamblador tan rápido y eficiente como en los lenguajes de alto nivel, sin sacrificar el tamaño de una pequeña aplicación que potencia el lenguaje ensamblador. Se trata de una aplicación Windows, pero se ejecuta en Wine muy bien y puede crear, compilar, depurar y ejecutar aplicaciones para Windows y Linux en Windows y Linux. 

WinAsm Studio es un entorno de desarrollo integrado (IDE, Integrated development environment) para aplicaciones de 32 bits bajo Microsoft Windows y 16 bits bajo DOS, usando Microsoft Macro Assembler MASM y Flat Assembler FASM. Su creador es Antonis Kyprianou (akyprian). Fue desarrollado en lenguaje ensamblador, y está optimizado en tamaño y velocidad. Además soporta autocompletado para las funciones de la API de Windows y sus parámetros, lo que facilita el desarrollo rápido de aplicaciones. Es extensible mediante una completa interfaz de plugins, e incluye un poderoso editor visual de resources. Posee una interfaz de usuario multilenguaje, esto significa que puede configurarse para que toda la interfaz gráfica se muestre en el idioma de nuestra preferencia. Ya ha sido traducido a muchos idiomas, y nuevas traducciones son más que bienvenidas. 

SASM (SimpleASM) - sencilla de código abierto multiplataforma IDE para NASM, MASM, GAS, lenguajes ensambladores FASM. SASM tiene resaltado de sintaxis y depurador. El programa trabaja fuera de la caja y es ideal para los principiantes a aprender el lenguaje ensamblador. SASM se traduce en Ruso e Inglés. Licenciado bajo la GNU GPL v3.0. Basado en el Qt. 

 

 

EMPRESA O INSTITUCION  

 

Como tal no hay empresas si que es destacable hablar de Kathleen Hylda Valerie Booth ( de soltera Britten , 9 de julio de 1922 - 29 de septiembre de 2022) fue una científica informática y matemática británica que escribió el primer lenguaje ensamblador y diseñó el ensamblador y el autocódigo para los primeros sistemas informáticos en el Birkbeck College, Universidad de Londres . Ayudó a diseñar tres máquinas diferentes, incluidas la ARC ( calculadora automática de relés ), la SEC ( computadora electrónica simple ) y la APE(X)C . 

 

LICENCIAS DE USO 

 

No me aparece nada sobre licencias de uso. 

 

El lenguaje ensamblador hard-coded es típicamente usado en el ROM de arranque del sistema (BIOS en los sistemas compatible IBM PC). Este código de bajo nivel es usado, entre otras cosas, para inicializar y probar el hardware del sistema antes de cargar el sistema operativo, y está almacenado en el ROM. Una vez que ha tomado lugar un cierto nivel de inicialización del hardware, la ejecución se transfiere a otro código, típicamente escrito en lenguajes de alto nivel; pero el código corriendo inmediatamente después de que es aplicada la energía usualmente está escrito en lenguaje ensamblador. Lo mismo es cierto para los boot loaders. 

 

CARACTERISTICAS DESTACABLES 

 

La popularidad de un lenguaje de programación depende de las características y utilidades que proporciona a los programadores. Aquí están las principales características que un lenguaje de programación debe poseer para destacar entre los demás:  

Simplicidad: el lenguaje debe ofrecer conceptos claros y simples que sean fáciles de entender, facilitando así, el aprendizaje y la aplicación. Sin embargo, la simplicidad puede ser un equilibrio difícil de alcanzar sin comprometer la capacidad general del lenguaje.  

Capacidad: además de ser fácil de usar, el lenguaje debe estar bien equipado con un conjunto sólido de características para realizar una amplia variedad de tareas. Si un lenguaje de programación ha sido diseñado para ser utilizado en un área específica, éste debe ofrecer los medios necesarios (operadores, estructuras y sintaxis) para lograr resultados óptimos.    

Abstracción: es la capacidad del lenguaje para definir y utilizar estructuras u operaciones complejas ignorando ciertos detalles de bajo nivel.  

Eficiencia: los lenguajes de programación que pueden ser traducidos y ejecutados de manera eficiente, ayudan a evitar el consumo excesivo de memoria y tiempo.  

Estructuración: el lenguaje permite a los programadores escribir su código de acuerdo con los conceptos de programación estructurada para evitar que se cometan errores.  

Compacidad: un lenguaje de programación con esta característica puede expresar las operaciones de forma concisa sin tener que escribir demasiados detalles.  

Principio de localidad: también se conoce como localidad de referencia. Este fenómeno indica la preferencia de un programa informático al haber accedido continuamente a las mismas áreas de memoria en un corto periodo de tiempo.  Permite el uso de bucles y subrutinas. Un lenguaje de programación puede aprovechar el principio de localidad para optimizar el rendimiento general de una aplicación.    

 

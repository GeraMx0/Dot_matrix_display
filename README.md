# Led dot matrix display

![image](https://user-images.githubusercontent.com/124211946/225142964-9a47c020-f620-46c6-8dff-4e2a61548285.png)

![image](https://user-images.githubusercontent.com/124211946/225133129-61973818-4bff-4043-9a60-4ddfb9386160.png)

# ¿Que es?

Un LED Dot Matrix Display es un tipo de matriz de puntos que utiliza LEDs (diodos emisores de luz) como elementos de visualización. Estos displays se componen de varias filas y columnas de LEDs, organizados en una matriz bidimensional, que pueden encenderse o apagarse individualmente para crear patrones de luz y mostrar información.

Los LED Dot Matrix Display son comunes en aplicaciones que requieren una alta visibilidad y bajo consumo de energía, como paneles de señalización, pantallas publicitarias, relojes digitales, dispositivos de control, entre otros.

Existen varios tipos de LED Dot Matrix Display, que varían según el número de filas y columnas de LED que tienen, el tamaño de los LED, el color de la luz emitida (por ejemplo, rojo, verde, azul o multicolor), y la tecnología de control utilizada (por ejemplo, multiplexación, barrido estático, entre otros).

# Especificaciones 

Tamaño de la pantalla: El tamaño de la pantalla puede variar desde unos pocos centímetros cuadrados hasta varios metros cuadrados. Los tamaños más comunes para uso doméstico son de alrededor de 8x8 o 16x16 píxeles.

Resolución: La resolución se refiere al número de píxeles (LEDs) en la pantalla. Una pantalla de matriz de puntos LED típica puede tener una resolución de 8x8, 16x16, 32x32, 64x64 o incluso más.

Brillo: El brillo de la pantalla se mide en unidades de candela por metro cuadrado (cd/m²) y puede variar según el modelo. Una pantalla de matriz de puntos LED típica tiene un brillo de alrededor de 500 a 2000 cd/m².

Ángulo de visión: El ángulo de visión se refiere a la amplitud del ángulo desde el cual se puede ver la pantalla con claridad. Una pantalla de matriz de puntos LED típica puede tener un ángulo de visión de alrededor de 120 grados.

Frecuencia de actualización: La frecuencia de actualización se refiere al número de veces que la pantalla se actualiza por segundo. Una pantalla de matriz de puntos LED típica puede tener una frecuencia de actualización de alrededor de 100 Hz.

Color: Las pantallas de matriz de puntos LED pueden ser monocromáticas (generalmente rojas) o pueden ser capaces de mostrar múltiples colores. En el caso de las pantallas de color, el número de colores que pueden mostrar puede variar según el modelo.

Controlador: Las pantallas de matriz de puntos LED suelen requerir un controlador para manejar la información que se muestra en la pantalla. El controlador puede ser integrado en la pantalla o puede ser un dispositivo separado conectado a la pantalla.

Interfaz: Las pantallas de matriz de puntos LED suelen tener una interfaz de comunicación que permite que se conecten a otros dispositivos, como una placa controladora de microcontrolador. Las interfaces más comunes son I2C, SPI, UART, entre otras.

# Ventajas y desventajas

Algunas de las ventajas de los LED Dot Matrix Display incluyen su bajo consumo de energía, su capacidad para mostrar información clara y legible incluso en condiciones de poca luz, y su durabilidad y larga vida útil. También son relativamente fáciles de programar y controlar, lo que los hace ideales para su uso en proyectos de electrónica y programación.

Sin embargo, una de las desventajas de los LED Dot Matrix Display es que pueden ser difíciles de leer en ángulos extremos o desde ciertas distancias, especialmente si los LED son pequeños. Además, la resolución de la imagen puede ser limitada en comparación con otros tipos de pantallas de mayor resolución, como las pantallas LCD o LED de alta definición.

# Historia 

La tecnología DMD se remonta a la década de 1960, cuando se desarrolló para su uso en la industria de la aviación y la defensa.

Las primeras pantallas de matriz de puntos eran muy primitivas y solo podían mostrar unos pocos caracteres simples. Sin embargo, a medida que la tecnología avanzaba, se desarrollaron pantallas más avanzadas que podían mostrar más caracteres y gráficos.

La tecnología DMD comenzó a ganar popularidad en la década de 1970, cuando se introdujeron las primeras impresoras de matriz de puntos. Estas impresoras utilizaban una cabeza de impresión con una matriz de pequeños alfileres que se activaban para imprimir caracteres y gráficos en el papel. A medida que la cabeza de impresión se movía a través de la página, los pines se activaban para imprimir los puntos necesarios para formar los caracteres y los gráficos.

En la década de 1980, los displays DMD se hicieron más comunes en los relojes digitales y otros dispositivos electrónicos de consumo. Los displays DMD también se convirtieron en un componente clave de los videojuegos arcade y las consolas de videojuegos, como el popular juego "Space Invaders".

En la década de 1990, los displays DMD evolucionaron para convertirse en pantallas LED de matriz de puntos que podían mostrar una amplia gama de colores y resoluciones más altas. Hoy en día, los displays DMD se utilizan en una amplia variedad de aplicaciones, desde paneles publicitarios y de información en aeropuertos y estadios hasta pantallas de control en vehículos y maquinaria industrial.

Módulo MAX7219 | Raspberry Pi Pico
---------------|------------------
VCC	| VBUS (5V)
GND | GND
DIN	| GP3 (SPI0_TX)
CS | GP5 (SPI0_CSn)
CLK | GP2 (SPI0_SCK)

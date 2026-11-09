# cpu4bits

Circuitos digitales de una CPU de 4 bits diseñados en Logisim-evolution, con simulaciones de chips de la serie 74HC.

## Visibilidad y rama
- Público (github.com/Toletum/cpu4bits). Rama por defecto: `main`.
- Descripción en GitHub: ninguna.

## Stack
- Logisim-evolution (ficheros de circuito `.circ`, versión indicada en la cabecera: 4.1.0dev).
- Ficheros `.sim2`: formato de simulación; no se ha inspeccionado su contenido en detalle.
- No hay código, dependencias ni `README.md`.

## Estructura
- `ALU_74HC283.sim2`: simulación del sumador 74HC283 (ALU).
- `BUS_74HC125.circ`: circuito de buffers de bus con 74HC125.
- `Clock_74HC14.sim2`: simulación del reloj con inversores Schmitt 74HC14.
- `Contador_74HC161.circ`: circuito contador con 74HC161.
- `Registros_74HC175.sim2`: simulación de registros con 74HC175.

## Comandos
- Abrir y editar los `.circ` con Logisim-evolution (no verificado en este entorno).
- No hay build, tests ni lint.

## Configuración
- Ninguna.

## Convenciones y reglas para agentes
- Nombrar los ficheros por componente 74HC y bloque funcional (`<bloque>_<chip>.<ext>`).
- `.circ` es XML generado por Logisim: editar a mano con cuidado, o mejor a través de la aplicación.

## Estado
- Sin README ni documentación de la CPU.
- Sin tests ni verificación automática de los circuitos.
- No consta qué simulaciones están validadas.

Arquitectura de Microprocesadores
Carrera de Especialización en Sistemas Embebidos
Alumno: Mansilla Rubén Darío (Co20 CESE)
Docentes: Santiago Germino
          Denis Genero

Preguntas Orientadoras

Desarrollo
1. La familia de microprocesadores / microcontroladores de ARM está agrupada en tres tipos:
1.1. Cortex A (Application): Esta familia está conformada por microprocesadores de Aplicación, de donde toma la sigla A. 
Constituida por microprocesadores de alto rendimiento orientados a soportar sistemas operativos embebidos de alta 
performance, y alto nivel de paralelismo. 

Características principales:
    • Contienen varios núcleos de alta frecuencia, del orden de los GHz.
    • Tienen integrada mucha memoria RAM del orden de los GB.
    • Tienen mucha memoria caché
Aplicaciones: Nintendo switch con las siguientes características:
    • 4 Cortex A-57 trabajando a 1GHz
    • 4 Cortex A-53 trabajando a 1,3 GHz
    • 4 GB de memoria RAM LPDDR4

1.2. Cortex R (Realtime): Esta familia está conformada por microprocesadores orientados a soportar sistemas de tiempo real 
donde se necesita implementar soluciones de baja. latencia, alta predictibilidad y elevada capacidad de cómputo. Por estas 
características se utilizan en sistemas críticos, como por ejemplo: sistemas de control para automóviles ( control de 
tracción, de frenos, ets), dispositivos médicos críticos, dispositivos industriales críticos, etc.

1.3. Cortex M (Microcontroller): Son microcontroladores orientados a dispositivos de uso masivo y sistemas embebidos 
compactos. Están diseñados para soportar alta densidad de código y ser programados en C.
Los más conocidos son:
    • Cortex M0/M0+: Pensados para una implementación mínima de bajo consumo y bajo costo.
    • Cortex M3/M4/M7: Suman mayor performance, más funcionalidades (división por hardware), FPU (Unidad de Punto Flotante), 
      MPU (Unidad de Protección de memoria), etc.
Ejemplos en placas de desarrollo:

    Raspberry Pi Pico: Cortex M0+
    PSOC5LP: Cortex M3
    STM32-Nucleo F429ZI: Cortex M4
    STM32-Nucleo F676ZI: Cortex M7	

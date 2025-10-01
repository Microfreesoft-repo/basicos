# Básicos

¡Bienvenido a **Básicos**! Este repositorio está dedicado a la preservación y estudio del lenguaje de programación BASIC en sus diversas versiones y entornos de compiladores e intérpretes. Aquí encontrarás información, ejemplos de código y guías detalladas para cada variante de BASIC que hemos cubierto.

## Objetivo del Repositorio

El objetivo de este proyecto es proporcionar una referencia integral y práctica para los programadores interesados en aprender, enseñar o explorar las diferentes versiones de BASIC, desde sus primeras iteraciones hasta su evolución en entornos modernos.

---

## Contenidos

### 1. **GW-BASIC y BASCOM**
- **GW-BASIC**: Un intérprete clásico de BASIC que se distribuyó con MS-DOS. Su uso principal era la creación de programas sencillos con un enfoque educativo.
- **BASCOM**: Un compilador de BASIC que permitió convertir el código en ejecutables. Este compilador fue una extensión natural para proyectos más complejos desarrollados en GW-BASIC.
- #### Compilación y Conversión de Programas con BASCOM (Años 80)

Este documento describe el flujo clásico para compilar programas en **BASCOM** (BASIC Compiler de Microsoft) y convertirlos de `.EXE` a `.COM` en un entorno **MS-DOS** de la época.

---

#### 📜 Contexto Histórico
*En los años 80, **BASCOM** era el compilador BASIC de Microsoft para IBM PC y compatibles. Permitía generar ejecutables `.EXE` desde código BASIC `.BAS`.  
*Cuando se necesitaba un ejecutable más pequeño y rápido de cargar, se podía convertir el `.EXE` a `.COM` usando la herramienta **EXE2BIN**.

---

## 🔹 Limitaciones de los `.COM`
*- Tamaño máximo de **64 KB** (código + datos + pila).
*- El código debe estar preparado para iniciar en el **desplazamiento 0x100h**.
*- No admite tablas de relocalización como los `.EXE`.

---

#### 🔹 Flujo de trabajo típico

1. **Compilar el código BASIC a objeto (.OBJ)**
   
*   BASCOM PROGRAMA.BAS;
*   LINK PROGRAMA.OBJ;
*   Convertir de .EXE a .COM


* EXE2BIN PROGRAMA.EXE PROGRAMA.COM
🔹 Ejemplo completo

* BASCOM HOLA.BAS;
* LINK HOLA.OBJ;
* EXE2BIN HOLA.EXE HOLA.COM
💡 Notas de la época
* EXE2BIN estaba incluido en versiones antiguas de MS-DOS y en paquetes de desarrollo.

* En MS-DOS 5.0+, EXE2BIN pasó a estar en el disco de utilidades suplementarias.

*Si el .EXE superaba 64 KB, la conversión fallaba.

** Muchos desarrolladores diseñaban sus programas directamente como .COM para optimizar tamaño y velocidad.

** 📦 Simulación actual
Hoy se puede revivir este flujo usando DOSBox y las herramientas originales de BASCOM y EXE2BIN para experimentar tal como en un PC IBM XT.


BASCOM  | Compilador BASIC
LINK    | Enlazador
EXE2BIN | Conversor de EXE a COM



### 2. **QuickBASIC (QB)**
- **QuickBASIC**: Una mejora significativa de BASIC que introdujo un entorno de desarrollo integrado (IDE), capacidades de depuración y un compilador que generaba ejecutables independientes. Ideal para aplicaciones más avanzadas.

### 3. **QBasic**
- **QBasic**: Una versión simplificada de QuickBASIC que solo funciona como intérprete. Venía incluido con versiones posteriores de MS-DOS y era perfecto para aprender programación básica.



---

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ejemplos, documentación o herramientas útiles, sigue los pasos descritos en `CONTRIBUTING.md`.

---

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE). Consulta el archivo para más detalles.

---

¡Esperamos que disfrutes explorando y aprendiendo sobre BASIC en sus múltiples formas!

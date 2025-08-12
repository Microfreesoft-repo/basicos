# Básicos

¡Bienvenido a **Básicos**! Este repositorio está dedicado a la preservación y estudio del lenguaje de programación BASIC en sus diversas versiones y entornos de compiladores e intérpretes. Aquí encontrarás información, ejemplos de código y guías detalladas para cada variante de BASIC que hemos cubierto.

## Objetivo del Repositorio

El objetivo de este proyecto es proporcionar una referencia integral y práctica para los programadores interesados en aprender, enseñar o explorar las diferentes versiones de BASIC, desde sus primeras iteraciones hasta su evolución en entornos modernos.

---

## Contenidos

### 1. **GW-BASIC y BASCOM**
- **GW-BASIC**: Un intérprete clásico de BASIC que se distribuyó con MS-DOS. Su uso principal era la creación de programas sencillos con un enfoque educativo.
- **BASCOM**: Un compilador de BASIC que permitió convertir el código en ejecutables. Este compilador fue una extensión natural para proyectos más complejos desarrollados en GW-BASIC.
- # Compilación y Conversión de Programas con BASCOM (Años 80)

Este documento describe el flujo clásico para compilar programas en **BASCOM** (BASIC Compiler de Microsoft) y convertirlos de `.EXE` a `.COM` en un entorno **MS-DOS** de la época.

---

## 📜 Contexto Histórico
En los años 80, **BASCOM** era el compilador BASIC de Microsoft para IBM PC y compatibles. Permitía generar ejecutables `.EXE` desde código BASIC `.BAS`.  
Cuando se necesitaba un ejecutable más pequeño y rápido de cargar, se podía convertir el `.EXE` a `.COM` usando la herramienta **EXE2BIN**.

---

## 🔹 Limitaciones de los `.COM`
- Tamaño máximo de **64 KB** (código + datos + pila).
- El código debe estar preparado para iniciar en el **desplazamiento 0x100h**.
- No admite tablas de relocalización como los `.EXE`.

---

## 🔹 Flujo de trabajo típico

1. **Compilar el código BASIC a objeto (.OBJ)**
   ```dos
   BASCOM PROGRAMA.BAS;


### 2. **QuickBASIC (QB)**
- **QuickBASIC**: Una mejora significativa de BASIC que introdujo un entorno de desarrollo integrado (IDE), capacidades de depuración y un compilador que generaba ejecutables independientes. Ideal para aplicaciones más avanzadas.

### 3. **QBasic**
- **QBasic**: Una versión simplificada de QuickBASIC que solo funciona como intérprete. Venía incluido con versiones posteriores de MS-DOS y era perfecto para aprender programación básica.

### 4. **QB45 (QuickBASIC 4.5)**
- **QB45**: La versión más avanzada de QuickBASIC, que incluye mayor capacidad de manejo de memoria y compatibilidad con librerías externas. Muy popular para desarrollar aplicaciones en sistemas DOS.

### 5. **VB-DOS (Visual Basic para DOS)**
- **VB-DOS**: Una evolución que combina las capacidades de BASIC con elementos visuales. Aunque todavía estaba basado en la consola, facilitaba la creación de aplicaciones más complejas con mejores interfaces.

### 6. **Visual Basic 3.0 y 4.5**
- **VB 3.0**: Una de las primeras versiones de Visual Basic orientadas a Windows. Introdujo formularios visuales para el desarrollo rápido de aplicaciones gráficas.
- **VB 4.5**: Mejora de VB 3.0 con soporte para aplicaciones de 32 bits y nuevas herramientas de diseño.

### 7. **VBA (Visual Basic for Applications)**
- **VBA para Word y Excel**: Una versión especializada de BASIC integrada en las aplicaciones de Microsoft Office. Permite automatizar tareas y crear soluciones personalizadas utilizando macros.

### 8. **PowerBASIC**
- **PowerBASIC**: Un compilador avanzado para BASIC que permite crear aplicaciones rápidas y compactas, especialmente optimizadas para entornos DOS y Windows. Con capacidades para manejar llamadas a API de Windows, PowerBASIC es ideal para desarrolladores que buscan flexibilidad y rendimiento.

### 9. **Moon Rock Compiler**
- **Moon Rock BASIC**: Un compilador de BASIC desarrollado por Rowan Crawley. Este compilador es conocido por su capacidad para generar código optimizado y ligero, así como por su compatibilidad con múltiples plataformas. Es una opción poderosa para quienes desean explorar nuevas formas de usar BASIC.

---

## Estructura del Repositorio

- `/docs`: Documentación general y guías específicas para cada compilador e intérprete.
- `/examples`: Ejemplos de código organizados por versión de BASIC.
- `/tools`: Herramientas y recursos necesarios para ejecutar y experimentar con los entornos.
- `/projects`: Proyectos prácticos que muestran las capacidades de cada versión.

---

## Cómo Usar Este Repositorio

1. **Navegar por las Carpetas**: Explora las carpetas organizadas por compilador/intérprete.
2. **Ejecutar Ejemplos**: Sigue las instrucciones en la carpeta `/examples` para ejecutar los programas en el entorno correspondiente.
3. **Aprender**: Consulta los documentos en `/docs` para aprender más sobre cada versión de BASIC.
4. **Contribuir**: Si deseas colaborar, revisa la sección de contribuciones a continuación.

---

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes ejemplos, documentación o herramientas útiles, sigue los pasos descritos en `CONTRIBUTING.md`.

---

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE). Consulta el archivo para más detalles.

---

¡Esperamos que disfrutes explorando y aprendiendo sobre BASIC en sus múltiples formas!

# GW-BASIC y BASCOM  

Este documento ofrece una guía completa sobre el uso de **GW-BASIC** y **BASCOM**, destacando los binarios incluidos, programas de ejemplo, funcionalidades y cómo utilizar BASCOM para compilar programas utilizando el ensamblador **LINK**.

---

## Introducción  

**GW-BASIC** es un intérprete de BASIC ampliamente utilizado en sistemas MS-DOS, ideal para aprender y desarrollar aplicaciones simples.  
**BASCOM** es el compilador complementario que permite convertir programas interpretados en ejecutables (.EXE), mejorando la eficiencia y el rendimiento.

---

## GW-BASIC  

### **Binarios de GW-BASIC:**
1. **GW-BASIC.EXE**: El intérprete principal de BASIC.
2. **GW-BASIC.HLP**: Archivo de ayuda que detalla la sintaxis y comandos disponibles.

### **Programas de Ejemplo:**
1. **DEMO.BAS**: Muestra gráficas y capacidades avanzadas de GW-BASIC.
2. **STAR.BAS**: Simula un campo de estrellas en movimiento.
3. **CALC.BAS**: Una calculadora simple en BASIC.
4. **GAME.BAS**: Un ejemplo de juego básico.

### **Ejecución de Programas:**
1. Inicia GW-BASIC escribiendo `GW-BASIC` en la línea de comandos.
2. Carga un programa escribiendo:
   ```bash
   LOAD "NOMBRE_DEL_ARCHIVO.BAS"
RUN

## BASCOM

**BASCOM** es un compilador que transforma programas escritos en BASIC en archivos ejecutables, facilitando su uso independiente del intérprete.

### Características Principales de BASCOM:
- Convierte código fuente BASIC en archivos objeto (.OBJ).
- Soporta vinculación a ejecutables (.EXE) utilizando **LINK.EXE**.
- Integra librerías estándar para expandir las capacidades del lenguaje.

### Binarios Incluidos con BASCOM:
- **BASCOM.EXE**: El compilador de código BASIC.
- **LINK.EXE**: Vinculador que genera ejecutables a partir de archivos objeto.
- **BASRUN.EXE**: Intérprete necesario para ejecutar programas compilados.
- **LIBRARY.LIB**: Librería estándar utilizada durante la compilación.

### Pasos para Compilar y Vincular Programas:
1. **Escribe tu programa en BASIC:**  
   Guarda el siguiente código como `HELLO.BAS`:

   ```basic
   10 PRINT "Hola, mundo!"
   20 END
   ```

2. **Compila el programa con BASCOM:**  
   Ejecuta el siguiente comando:

   ```bash
   BASCOM HELLO.BAS
   ```

3. **Vincula el archivo objeto con LINK:**  
   Usa el vinculador para crear el ejecutable:

   ```bash
   LINK HELLO.OBJ
   ```

   Esto producirá `HELLO.EXE`.

### Programas Incluidos con BASCOM:
- **SAMPLES.BAS**: Ejemplos avanzados de cálculo y manejo de datos.
- **GRAPHICS.BAS**: Muestra gráficos básicos y avanzados.
- **FILEIO.BAS**: Ejemplo de operaciones con archivos.
- **CALENDAR.BAS**: Generador de calendarios interactivo.

### Configuración del Entorno:
1. Asegúrate de que **BASRUN.EXE** esté en el mismo directorio que tu programa compilado.
2. Verifica que el archivo **LIBRARY.LIB** esté presente para evitar errores de compilación.

### Modo de Depuración:
Para activar opciones de depuración, utiliza:

```bash
BASCOM /D HELLO.BAS
```

Esto genera información adicional para resolver errores durante la ejecución.

### Recursos Adicionales:
- Documentación completa: **GW-BASIC.HLP** y **BASCOM.DOC**.
- Carpeta `/examples`: Contiene ejemplos para explorar las capacidades de GW-BASIC y BASCOM.
- Guías de compilación y optimización disponibles en `/docs`.

### Notas Importantes:
- **Compatibilidad:** Los programas compilados con BASCOM dependen de **BASRUN.EXE**.
- **Optimización:** Usa `LINK /EX

## Recursos Adicionales
Documentación completa: GW-BASIC.HLP y BASCOM.DOC.
Carpeta /examples: Contiene ejemplos para explorar las capacidades de GW-BASIC y BASCOM.
Guías de compilación y optimización disponibles en /docs.
Notas Importantes
Compatibilidad: Los programas compilados con BASCOM dependen de BASRUN.EXE.
Optimización: Usa LINK /EX para generar ejecutables más pequeños.
Librerías Adicionales: Consulta la carpeta /libs para extensiones útiles.
Contribuciones
¡Se aceptan contribuciones! Si tienes ejemplos, guías o herramientas útiles, revisa las pautas en CONTRIBUTING.md.

Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo para más detalles.

¡Disfruta programando con GW-BASIC y BASCOM!








 

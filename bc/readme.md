# 🚀 Programación en BASIC Compilado

Este repositorio está dedicado a explorar y preservar el lenguaje **BASIC** en su modalidad **compilada**.  
BASIC (Beginner’s All-purpose Symbolic Instruction Code) es uno de los lenguajes más influyentes en la historia de la computación, usado tanto en enseñanza como en proyectos profesionales.  

Aunque originalmente se ejecutaba en modo interpretado, la versión compilada permitió que los programas corrieran de forma más rápida y eficiente, generando archivos ejecutables independientes.

En este proyecto encontrarás:
- Ejemplos de código en **BASIC compilado**.  
- Tutoriales para compilar y ejecutar programas.  
- Comparación entre **BASIC interpretado vs. compilado**.  
- Referencias a compiladores e IDEs históricos y modernos.  
- Proyectos de programación para practicar.  

---

## 🛠️ Compiladores e IDEs de BASIC

Algunos compiladores y entornos de desarrollo que marcaron la evolución del BASIC son:  

- **QuickBASIC (QB)** – IDE y compilador de Microsoft, muy popular en los 80s y 90s.  
- **QBasic** – Versión más ligera y educativa incluida en MS-DOS (solo intérprete).  
- **Turbo BASIC / PowerBASIC** – Alternativas rápidas y potentes para crear ejecutables.  
- **FreeBASIC** – Compilador moderno, libre y multiplataforma compatible con sintaxis de QuickBASIC.  
- **QB64** – Intérprete/compilador moderno que permite crear ejecutables nativos en sistemas actuales.  

---

## ⚙️ Cómo compilar con BC.EXE

El compilador **BC.EXE** (Microsoft BASIC Compiler) junto con `LINK.EXE` permite convertir archivos `.BAS` en programas ejecutables `.EXE`.

### Pasos para compilar con BC.EXE:

1. Abre la consola de DOS (o DOSBox).  
2. Ve a la carpeta donde tengas tu programa `PROGRAMA.BAS`, junto con `BC.EXE` y `LINK.EXE`.  
3. Ejecuta el compilador:

   ```dos
   BC PROGRAMA.BAS;
#Esto genera un archivo objeto PROGRAMA.OBJ.

Enlaza el objeto con LINK.EXE:
Esto produce:

*PROGRAMA.EXE → programa compilado.

*PROGRAMA.MAP → archivo de depuración.

*Ejecuta el programa compilado:
📝 Ejemplo práctico

* Código en HOLA.BAS:
  PRINT "Hola mundo en BASIC compilado"
END
* Compilación:
BC HOLA.BAS;
LINK HOLA.OBJ;
HOLA.EXE
💡 Ejemplos de proyectos en BASIC

Algunos ejemplos clásicos que se pueden desarrollar:

Juegos retro (Snake, Tetris, Pong).

Utilidades de consola (calculadoras, agendas, editores de texto simples).

Simulaciones matemáticas y gráficas.

Programas educativos para aprender lógica de programación.

#📂 Organización del repositorio

src/ → Código fuente en BASIC.

docs/ → Tutoriales y manuales.

bin/ → Ejecutables compilados.

examples/ → Proyectos de demostración.

#🎯 Objetivo del proyecto

Este proyecto busca rescatar y fomentar la programación en BASIC compilado, mostrando cómo se pueden crear proyectos educativos, retro y experimentales con herramientas clásicas y modernas.

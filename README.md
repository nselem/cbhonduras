# Biología computacional
![langebio](imagenes/langebio.png)  

En este curso aprenderás un poco de biología commputacional las herramientas linux, git, Google docs y microreact.  


Algoritmos usados en el mundo biológico. (BLAST)
Bases de datos, mapas y gráficos usados en biología computacional.


Redes de información. STRING PriA la historia de los operones
Análisis de secuencias de ADN.

Árboles filogenéticos. La historia de las Archaeas.. MicroReact
Exposicion proyectos


## Calendario  

|        Viernes 22               |            Sábado 24                 |
----------------------------------|--------------------------------------|
Sesión1 (9:00 - 12:00 am) 

Introducción a la biología y genética molecular
Aplicaciones de la biología computacional.
[Linux bash](https://swcarpentry.github.io/shell-novice-es/)               |   Sesión 2  (9:00 - 12:00 am)      |
Septiembre 28 [Metadatos y visualización](paginas/genomica/genomica.md)|    Sesión (9:00 - 12:00 am)         |
[Git](paginas/git/sesion3.md) y [markdown](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)  |  (9:00 - 12:00 am)      ses   |
ses 7(9:00 - 12:00 am) | ses 8 (9:00 - 12:00 am) |  
## Informacion General  
Aqui puedes encontrar un [documento colaborativo](https://etherpad.net/p/compbio  ) donde compartiremos información relevante, links, y respuestas a preguntas que surjan durante el taller. Dos de nuestras lecciones linux y git son parte del contenido habitual de [software carpentry](https://software-carpentry.org/) una organización dedicada a enseñar habilidades de cómuto para hacer más en menos tiempo y con menos sufrimiento, usaremos estas dos lecciones con su permiso. Las otras dos lecciones fueron pensadas de acuerdo a las necesidades específicas de nuestro centro de trabajo.   

## Temario detallado  
<table> 
    <tr><td> <b> Sesión 1 Linux bash </b> <br>
Introducción a la biología, genética molecular y situaciones en biología donde la biología computacional es usada. (Plática/Reflexión)
BASH 1: Linux/Unix, Principios básicos del Shell  <br>
    </td>
    <td> <b> Sesión 2 Linux bash </b>
BASH 2 Comandos para el manejo de archivos y directorios   <br>
BASH 3 Loops   <br>
BASH 4 Manejo de Scripts    <br>
5 Encontrar información: grep y find. <br> </td>
    
Algoritmos usados en el mundo biológico. (BLAST)
Bases de datos, mapas y gráficos usados en biología computacional.
Redes de información. STRING PriA la historia de los operones
       </td>
       </tr>
<tr> 
    <td><b> Sesión 3  El respaldo y documentación de scripts </b> <br></td>
<td> <b> Sesión 4  Herramientas de genómica </b> <br>  
3.1 La importancia de documentar y respaldar el trabajo informático <br>
3.2 Git Guardar los scripts en internet <br>
3.3 MD Crear documentación organizada <br>
3.4 Wiki git Documentar extensivamente scripts <br>
</td>
     <tr><td>
<b> Sesión 5 Linux bash </b>
4.1 Descargar datos NCBI (Linux) <br>  
4.2 Cómo tomar metadatos en proyectos genómicos <br>  
4.3 MicroReact y la visualización de metadatos. <br>  
4.4 Editar archivos para microreact: One liners <br>  
4.5 Seaview crear un arbol para microreact. <br>  
         </td> 
      <td>
       <b> Sesión 6 Linux bash </b>
       </td>
</tr>

<tr> <td>
    <b>Sesión 7</b>
    </td>
    <td><b>Sesión 8</b></td></tr>
</table>    
       
____________
## Instalaciones y requerimientos previos  
<h2 id="setup">Setup</h2>  

<p>
  Para participar en este taller necesitas acceso al siguiente software. Además necesitarás acceso a un navegador como chrome o firefox.   
  </p>
<p>
  Aqui hay una referencia de posibles problemas durante la instalación.  
  <a href = "{{site.swc_github}}/workshop-template/wiki/Configuration-Problems-and-Solutions">Wiki de problemas de instalación y sus soluciones. </a>.
</p>

<div id="shell">  
  <h3>El Bash Shell</h3>  
  <p>  
    Bash es un intérprete de comandosque te da poder de hacer tareas simples rápidamente.  
  </p>  

  <div class="row">  
    <div class="col-md-4">  
      <h4 id="shell-windows">Windows</h4>  
      <a href="https://www.youtube.com/watch?v=339AEqk9c-8">Video Tutorial</a>  
      <ol>  
        <li>Baja para windows <a href="https://git-for-windows.github.io/">el instalador de git </a>.</li>  
        <li>Corre el instalador y sigue los siguientes pasos:  
          <ol>  
            <li>Click en "Next".</li>  
            <li>Click en "Next".</li>    
            <li>  
              <strong>  
               Manten el "Use Git from the Windows Command Prompt" seleccioinado y  click en "Next".  
              </strong>  
                Si se te olvida hacer esto algunos programas que necesitarás no funcionaran correctamente.  
                Si esto te pasa regrésate al paso anterior del instalador y selecciona la opción correcta.  
            </li>  
            <li>Click en "Next".</li>
            <li>  
              <strong>  
                Mantén "Checkout Windows-style, commit Unix-style line endings" seleccionado y click en "Next".
              </strong>
            </li>
            <li>  
              <strong>  
                Mantén "Use Windows' default console window" seleccionado y click en "Next".  
              </strong>  
            </li>  
            <li>Click en "Install".</li>
            <li>Click en "Finish".</li>  
          </ol>  
        </li>  
        <li>  
          si tu variable de ambiente "HOME" no está lista (o no sabes qué es esto):
          <ol>
            <li>Abre el prompt (Abre el menu start, escribe <code>cmd</code> y presiona enter [Enter])</li>
            <li>
              Escribe la siguiente línea en la ventana del promt exactamente como se  muestra:  
              <p><code>setx HOME "%USERPROFILE%"</code></p>  
            </li>  
            <li>Presiona [Enter], debes de ver <code>SUCCESS: Specified value was saved.</code></li>
            <li>Para salir del prompr escribe <code>exit</code> y presiona enter [Enter]</li>
          </ol>
        </li>
      </ol>
      <p>Esto te dará ambos Git y Bash en el programa Git Bash.</p>
    </div>
    <div class="col-md-4">
      <h4 id="shell-macosx">macOS</h4>
      <p>
        El shell por default en todas las versiones de macOS es Bash, asi que no debes instalar nada.  Podrás accesar a Bash desde la Terminal
        (que se encuentra en        <code>/Applications/Utilities</code>).
        Para la instalación de Git aqui tenemos un <a href="https://www.youtube.com/watch?v=9LQhwETCdwY ">video tutorial</a>
        for an example on how to open the Terminal.
        Tal vez quieras mantener la Terminal en tu dock para este taller.  
      </p>
    </div>
    <div class="col-md-4">
      <h4 id="shell-linux">Linux</h4>
      <p>
        El shell es usualmente Bash, pero si tu máquina es diferente puedes abrir una terminal y escribir <code>bash</code>.  
        No se necesita intalar nada
      </p>
    </div>
  </div>
</div> 

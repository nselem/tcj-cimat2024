# Biología computacional
![UniversidadMorazan](imagenes/morazan.png)  

En este curso aprenderás un poco de biología computacional, adquirirás nociones de las herramientas linux, git, RAST y microreact.   

  
## Calendario   
  
<table>
    <tr>
        <td>Viernes 22       </td> <td>           Sábado 23                 </td>
  </tr>  
    <tr><td>                                               </td>  
      <td>  Sesión 4 Redes de información (7:00 - 9:00 am)</td>
  </tr>
    <tr><td> Sesión 1 (9:00 - 12:00 am) Introducción y <a href="https://swcarpentry.github.io/shell-novice-es/"> bash </a> 
        </td>
      <td>
        Sesión 5 (9:10 -12:10) Análisis de secuencias <a href="paginas/git/sesion3.md">Git </a> y <a href="https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf">Markdown</a>  </td></tr>  
    <tr><td>
        Comida (12:00-12:45)</td><td> Comida (12:10-12:50)</td></tr>
    <tr><td>
        Sesión 2  (12:45 - 03:45 pm) Algoritmos Biológicos          </td>
      <td>Sesión 6 (12:50-3:50) <a href="paginas/genomica/genomica.md"> Arboles y metadatos</a></td>
    </tr>
    <tr><td>
        Sesión 3 (04:00 - 7:00 pm)   Bases de datos   </td>
        <td>Sesión 7 (4:00 -7:00 pm) Proyectos y exposición </td>
    </tr>
</table>  
      
    
## Informacion General  
Aqui puedes encontrar un [documento colaborativo](https://etherpad.net/p/compbio  ) donde compartiremos información relevante, links, y respuestas a preguntas que surjan durante el taller. Dos de nuestras lecciones linux y git son parte del contenido habitual de [software carpentry](https://software-carpentry.org/) una organización dedicada a enseñar habilidades de cómuto para hacer más en menos tiempo y con menos sufrimiento, usaremos estas dos lecciones con su permiso. Las otras dos lecciones fueron pensadas de acuerdo a las necesidades específicas de nuestro centro de trabajo.   


## Temario detallado  
<table> 
<tr>
  <td> <b> <a href="paginas/linux/introduccion.md">Sesión 1</a> Introducción y Linux bash</b> <br>
1.1 Introducción a la biología y genética molecular. <br>
Aplicaciones de biología computacional. <br>
  1.2 Biohack y la filosofía open software. <br>
Diseño en TinkerCad  <br>
1.3.1 Linux/Unix, Principios básicos del Shell  <br>
1.3.2 Comandos para el manejo de archivos y directorios   <br>
1.3.3 Pipes y filtros   <br>
</td>
  <td> <b> <a href="paginas/sesion2/algoritmos.md" >Sesión 2:</a> Algoritmos Biológicos </b>  <br>
2.1 Ensamblado  <br>  
2.2 Alineamiento  <br>
2.3 BLAST   (16s) <br>
2.4 Algoritmos de Bash Loops <br>
</td>
</tr>
  <tr> 
    <td><b> <a href="paginas/sesion3/basesDatos.md">Sesión 3</a>  Bases de datos, mapas y uso de paquetes de análisis</b> <br>
3.1 NCBI  <br>
3.2 MIBiG  <br>
3.3 antiSMASH <br> 
3.4 Creando tu script  de bash <br>    
3.5 Paquete de análisis: RAST  <br>  
</td>
    <td> <b> <a href="paginas/sesion4/redes.md">Sesión 4</a> Redes de información y estructura de proteinas </b> <br>  
 4.1 PriA ¿por qué se necesitan redes? <br>  
 4.1 Operones y STRING   <br>  
 4.2 Roseta,y evcouplings para la reconstrucción 3D   <br>  
 4.3 Scripts en bash  <br>
</td>
</tr>  
<tr>
<td>
  <b> Sesión 5 Análisis de secuencias y <a href="paginas/git/sesion3.md"> GIT</a> o <a href="paginas/drive/sitios.md">drive </a> </b> <br>  
5.1 Alineamiento   <br>  
5.2 Contenido de GC   <br>  
5.3 El respaldo y documentación de scripts <br>
5.3.1 La importancia de documentar y respaldar el trabajo informático <br>
5.3.2 Git Guardar los scripts en internet <br>
5.3.3 MD Crear documentación organizada <br>
5.3.4 Wiki git Documentar extensivamente scripts <br>
</td> 
<td>
  <b> <a href="paginas/sesion6/arboles.md">Sesión 6 </a>Árboles y metadatos </b> <br>  
4.1 Crear un árbol a partir de un alineamiento <br>        
4.2 Metadatos en proyectos genómicos <br>  
4.3 MicroReact y la visualización de metadatos. <br>  
</td>
</tr>
<tr> 
<td>
<b>Sesión 7 </b>
Dudas sobre el <a href="paginas/proyectos/proyectos.md">proyecto final  </a><br>  
</td> 
<td><b>Sesión 8</b>
  Exposición de proyectos  
</td>
</tr>
</table>    
     
___         
## Entregables    
El objetivo del curso será que los alumnos tengan un panorama general de la Biología computacional, y que la vivan a través del desarrollo de sus primeros programas.   
1) Github con un script   25%  
2) Bacteria identificada   5%  
3) Exposición de Proyecto 70%  
  
___  
  
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

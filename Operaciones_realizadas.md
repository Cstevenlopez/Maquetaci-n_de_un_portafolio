# Maquetación HTML del documento web 
## i. Una cabecera con un encabezado, eslogan e imagen
La estrutura para poder insertar la imagen es la siguiente:
```
<img class="imagen" src="img/3.jpg"/>
```
La estructura que utilize en CSS es la siguiente:
```
.imagen{
    width: 100%;
    opacity: 0.9;
    border-radius:150px;
}
```
Para poder agregar el eslogan sobre la imagen utilize la siguiente estructura:
```
<div class="texto-encima">Mi información digital</div>
<div class="texto-encima2">Un lugar donde comprato toda mi experiencia</div>
```
La estructura que utilize en CSS es la siguiente:
```
.texto-encima{
    position: absolute;
    top: 2%; 
    left: 37%;
    font-size: 380%;
    color:white;
}
.texto-encima2{
    position: absolute;
    top: 8%;
    left: 29%;
    color: white;
    font-size: 300%;
}
```
## ii. Un apartado de experiencia con un encabezado, su foto, encabezado y una tabla con su experiencia construida en su vida
La estrutura que ocupe para la foto es la siguiente:
```
<img class="imagen-4" src="img/4.jpg"/>
```
La estructura que utilize en CSS es la siguiente:
```
.imagen-4{
    position: absolute;
    top: 125%; 
    left: 41%;
    width: 15%;
    width:300px;
    height:300px;
    border-radius:150px;
    
}
```
La estrutura que ocupe para la tabla es la siguiente:
```
<table class="tabla">
            <thead>
                <tr>
                  <th><p align="left">Lista definida</p></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td><b>Practicas pre profecionales Ministerio de educación “MINED”</b><br>
                        <p align="justify">Realización liquidaciones, subsidios del personal administrativo y docente del ministerio, mantenimiento y reparación de los equipos de cómputo pertenecientes al área de recursos humanos, desarrollar un Sistema de información que contribuya al desarrollo eficaz y eficiente de algunas operaciones del área de recursos humanos.</p>
                        </td>
                </tr>
                <tr>
                    <td><b>Cableado estructurado en el área de UNEN en la institución educativa de URACCAN recinto Las Minas</b><br>
                        <p align="justify">Creación del un cableado estructurado de la red LAN de la institución educativa específicamente en el área de UNEN que solicitaba el acceso una conexión de internet, medidas y el plano del edificio, normas vigentes del cableado estructurado, ejecucion del cableado estruturado.</p>
                        </td>
                </tr>
                <tr>
                    <td><b>Elaboración del plan de manejo ambiantal Siuna 2020, Regente forestal.César López</b><br>
                        <p align="justify">Creación de Guías y planes de manejo de uso forestal para la empresa de madera López Araus ubicada en la comunidad de almikamba de la ciudad de Rosita.</p>
                        </td>
                </tr>
                <tr>
                    <td><b>Cursos completos de ingles "AN EASY WAY TO LEARN ENGLISH"</b><br>
                        <p align="justify">Cursos de ingles basicos en el instututo Parroquial San Francisco de Asis para un total de 348 horas de curso.</P></p>
                        </td>
                </tr>
            </tbody>
        </table>
```
La estructura que utilize en CSS es la siguiente:
```
.tabla{
    position: absolute;
    top: 165%; 
    left: 25%;
    width: 50%;
}
```
## iii. Un apartado de eventos con datos adicionales de compartir en eventos,presente una lista
La estrutura que ocupe para la lista es la siguiente:
```
 <ul class="lista">
        <thead>
            <p align="left">Lista definida</p>
            <ul>
                <li><td><b style="color:purple">Lanzamiento de cruzada nacional de reforestación Siuna-2017</b><br>
                    <p align="justify">Evento en amor a Nicaragua. Plantando y cuidando nuestros árboles para continuar transformando nuestro país.</p>
                    </td></li>
                <li><td><b style="color:purple">Primera reunión de egresados del estudio técnico de regencia foresta “INTECFOR” Estelí -2019</b><br>
                    <p align="justify">En este evento fueron partes ex alumnos y familiares del técnico de regencia forestal “INTECFOR”, en donde compartieron sus experiencias luego de haber concluido sus estudios en donde se abarcaron temas desde como emplean sus conocimientos en la actualidad sobre el manejo de los recursos naturales.</p>
                    </td></li>
                <li><td><b style="color:purple">2da Olimpiada nacional de robótica Managua-2018</b><br>
                    <p align="justify">La segunda olimpiada nacional de robótica se realizo en Managua, Varios colegios y universidades participaron en esta actividad que se lleva a cabo con el objetivo de exponer los robots que son construidos por estudiantes.</p>
                    </td></li>
                <li><td><b style="color:purple">Rally latinoamericano de innovación 2019.</b><br>
                    <p align="justify">La competencia propone dos productos: resolver desafíos que consistirán en problemas reales que requieran de una solución creativa, no estando limitados únicamente al ámbito tecnológico, pudiendo ser de varios sectores de actividades o temas sociales, ambientales, organizacionales, artísticos, logísticos o de otro tipo y una interacción de tipo lúdico creativa entre dos equipos de diferentes países o culturas.</P></p>
                    </td></li>
              </ul>

        </thead>
     </ul>>
```
La estructura que utilize en CSS es la siguiente:
```
.lista{
    position: absolute;
    top: 285%; 
    left: 25%;
    width: 50%;
}
```
## iv. Un apartado de recomendaciones sobre el aprendizaje de tecnologías, aquí incluya una lista de vínculos que correspondan con los apartados, cada vez que de clic sobre uno de ellos, lo traslade al apartado seleccionado
La estrutura que ocupe para la lista de vínculos es la siguiente:
```
<ul class="vinculo">
            <footer id="pie">
            <nav>
                <ul><a href="#inicio">Inicio</a></ul>
                <ul><a href="#Mi-experiencia"> Mi experiencia</a></ul>
                <ul><a href="#datos-adicionales"> Datos adicionales</a></ul>
                <ul><a href="#Recomendaciones">Recomendaciones</a></ul>
            </nav>
        </ul>
```
La estructura que utilize en CSS es la siguiente:
```
.vinculo{
    position: absolute;
    top: 340%; 
    left: 30%;
    width: 50%;
}
```
## v. Al final debe incluir un apartado de pie de página
La estrutura que ocupe para el pie de pagina es la siguiente:
```
<div class="pie">Todos los derechos reservados @CSTEVEN 2020</div>
```
La estructura que utilize en CSS es la siguiente:
```
.pie{
    position: absolute;
    top: 350%; 
    width: 100%;
    text-align: center;
    height: 50px;
    padding-top: 15px;
    background-color: rgb(11, 11, 11);
    color: white;
}
```
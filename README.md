<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <meta charset="utf-8">
        <title>Hipervinculos</title>
        <link rel="stylesheet" href="tiezo.css">
    </head>
    <body>
        <script>
alert("“¡Saludos, estudiantes y maestros!” ");
alert("“Hoy exploraremos la ecuación diferencial y la Ley de Enfriamiento.”");
alert("“Para acceder a las secciones relevantes, utilicen la barra de navegación o deslizar su dedo.”");
alert("Esperamos que disfruten de su día.");
        </script>
        <header>
            <nav class="menu">
                <ul>
                    <li><a href="#seccion1">¿Qué es la ley de enfriamiento?</a></li>
                    <li><a href="#seccion2">Ecuación utilizada y significado</a></li>
                    <li><a href="#seccion3">Video</a></li>
                    <li><a href="#seccion4">Fuentes</a></li>
                    <li><a href="#seccion5">Integrantes</a></li>
                </ul>
            </nav>
        <section>
                <div id="seccion1">
                    
                    <p>La Ley de Enfriamiento de Newton</p>
<p> Es un principio fundamental en la transferencia de calor por convección. Fue propuesta por Sir Isaac Newton y establece que la tasa de cambio del calor transferido entre una sustancia y su entorno es directamente proporcional a la diferencia de temperatura entre la sustancia y el medio circundante. Matemáticamente, se expresa como:
    [ \frac{dQ}{dt} = hA(T - T_{\infty}) ]
</p>
<p>Donde:

    (dQ) representa la cantidad de calor transferido.
    (dt) es el intervalo de tiempo.
    (h) es el coeficiente de transferencia de calor por convección, que depende de las propiedades del fluido y la geometría de la superficie.
    (A) es el área de la superficie de intercambio de calor.
    (T) es la temperatura de la sustancia.
    (T_{\infty}) es la temperatura del medio circundante.
    Esta ley se aplica en situaciones donde la diferencia de temperatura es pequeña y la naturaleza de la superficie radiante permanece constante. Por ejemplo, en la disipación de calor de un objeto caliente al aire ambiente o en la refrigeración de alimentos calientes en un entorno más frío.</p>
                    
                </div>
                <div id="seccion2">
                    <p>Ecuación difercial</p>
<p>Se metió un cadáver dentro de un cuarto cerrado de una casa donde la temperatura era 
    constante de 70°F. Al momento del descubrimiento, se determinó que la temperatura del 
    cuerpo era de 85°F. Una hora después, una segunda medición mostró que su temperatura era 
    de 80°F. Suponga que la hora de la muerte corresponde a t=0, y que la temperatura en ese 
    momento era de 98.6°F. Determine cuántas horas transcurrieron antes de descubrir el 
    cuerpo.</p>
    <p>FORMULA DE ENFRIAMIENTO DE NEWTON </p> 
    <p>dT/dt=k(T−Tm)</p>  
    <p>INTEGRACIÒN:</p>
    <p>∫dT/(T−Tm)=∫kdt</p>
    <p>ln∣T−Tm∣=kt+C </p>
    <p>eln∣T−Tm∣=e^kt+e^C </p>
    <p>T−Tm=Ce^kt </p>
    <p>SUSTITUCIÒN A LA FORMULA:</p>
    <p>T−Tm=28.6e^kt   </p>
    <p>RESPUESTA: </p>
    <p>t=?   Tm=70 grados F.       T=85 grados F. </p>
    <p>(85−70)=28.6e^−1.0508(t−1) </p>
    <p>15=28.6e^−1.0508(t−1) </p>
    <p>28.615=e^−1.0508(t−1)</p>
    <p>ln(15/28.6)=lne^−1.0508(t−1) </p>
    <p>ln(15/28.6)=−1.0508(t−1)</p>
    <p>(ln(15/28.6))/-1.0508=t−1 </p>
    <p>[(ln(15/28.6))/-1.0508]+1=t</p>
    <p>t=1.6141  </p>
    <p class="derecha">FORMULA GENERAL:</p>
    <p class="derecha1">T−Tm=Ce^kt </p>
    <p class="derecha2">CONDICIONES INICIALES</p>
    <p class="derecha3">t=0        Tm=70 grados F.       T=98.6 grados F. </p>
    <p class="derecha4">(98.6−70)=Ce^k(0) </p>
    <p class="derecha5">28.6=Ce^0</p>
    <p class="derecha6">28.6=C</p>
    <p class="derecha7">SUSTITUYENDO: </p>
    <p class="derecha8">t=1     T=80 grados F.  Tm=70 grados F. </p>
    <p class="derecha9">10=28.6e^k </p>
    <p class="derecha10">ln(10/28.6)=lne^k</p>
    <p class="derecha11">ln(10/28.6)=k </p>
    <p class="derecha12">k=−1.0508 </p>
    <p class="derecha13">SUSTITUCIÒN A LA FORMULA:</p>
    <p class="derecha14">T−Tm=28.6e^−1.0508t </p>
    <p class="final">RESPUESTA: </p>
    <p class="final1">EL CUERPO SE ENCONTRO DESPUES DE 1.6 HORAS.</p>
                </div>
                <div id="seccion3">
                    <p>Nuestro problema con solución</p>
<p></p>
<video class="video" controls>
    <source src="tiezo1.mp4" type="video/mp4">

                </div>
                <div id="seccion4">
                    <p>INFORMACIÓN</p>
                    <p>Zill, D. G., Wright, W. S., & Cullen, M. R. (2019). Matemáticas avanzadas para ingeniería (4ª ed.). McGraw-Hill.</p>
                    <p>Newton, I. (1701). Scala graduum Caloris. Philosophical Transactions, 33, 161-172.</p>
                    <p>https://es.wikipedia.org/wiki/Ley_del_enfriamiento_de_Newton</p>
                    </div>
                <div id="seccion5">
                    <p class="inte">NOMBRES</p>
                    <p class="inte">Rosales Hurtado Fatima Nallely</p>
                    <p class="inte">Alvarez Cervantes Brenda Malinaly</p>
                    <p class="inte">Galicia Vazquesz Isaac Aarón</p>
                    <p class="inte" >Urbina Díaz Daniela</p>
                </div>
		
            </section>
        </header>
    </body>
</html>

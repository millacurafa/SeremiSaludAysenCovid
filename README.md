[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/millacurafa/SeremiSaludAysenCovid">
    <img src="img/VTuJaTx2.jpg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Seremi de Salud Aysén</h3>

  <p align="center">
    SeremiSaludAysenCovid
    <br />
    <a href="https://github.com/millacurafa/SeremiSaludAysenCovid"><strong>Explorar la documentación»</strong></a>
    <br />
    <br />
    <a href="https://github.com/millacurafa/SeremiSaludAysenCovid">Ver Demo</a>
    ·
    <a href="https://github.com/millacurafa/SeremiSaludAysenCovid/issues">Reportar Bug</a>
    ·
    <a href="https://github.com/millacurafa/SeremiSaludAysenCovid/issues">Solicitar característica</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Tabla de Contenidos</h2></summary>
  <ol>
    <li>
      <a href="#sobre-el-proyecto">Sobre el Proyecto</a>
      <ul>
        <li><a href="#creado-con">Creado con</a></li>
      </ul>
    </li>
    <li>
      <a href="#comenzando">Comenzando</a>
      <ul>
        <li><a href="#pré-requisitos">Pré-requisitos</a></li>
        <li><a href="#instalación">Instalación</a></li>
      </ul>
    </li>
    <li><a href="#ejemplos-de-uso">Ejemplos de Uso</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contribuciones">Contribuciones</a></li>
    <li><a href="#licencia">Licencia</a></li>
    <li><a href="#contacto">Contacto</a></li>
    <li><a href="#agradecimientos">Agradecimientos</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Sobre el Proyecto

Multiples archivos `ipynb` contienen datos analizados para obtener gráficos a presentar, tales como:

Datos de incidencia por comuna, disponible en [`reporte_seremi_aysen`](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/reporte_seremi_aysen.ipynb):

![Incidencia-por-comuna-aysen](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/img/newplot(12).png?raw=true)

Casos probables o Confirmados por comuna, disponible en [`reporte_seremi_aysen`](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/reporte_seremi_aysen.ipynb):

![casos-por-comuna-aysen](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/img/newplot(13).png?raw=true)

Porcentaje BAC, disponible en [`reporte_seremi_aysen`](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/reporte_seremi_aysen.ipynb):

![porcentaje-bac-aysen](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/img/newplot(14).png?raw=true)

Test PCR realizados, disponible en [`reporte_seremi_aysen`](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/reporte_seremi_aysen.ipynb):

![pcr-realizados-aysen](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/img/newplot(15).png?raw=true)

Positividad de PCR, disponible en [`reporte_seremi_aysen`](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/reporte_seremi_aysen.ipynb):

![positividad-pcr-aysen](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/img/newplot(16).png?raw=true)

Capacidad de investigación en 48h, disponible en [`tasas_incidencia`](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/tasas_incidencia.ipynb):

![capacidad-investigacion-aysen](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/img/newplot(17).png?raw=true)

Evolución de variantes principales, disponible en [`informe_variantes`](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/informe_variantes.ipynb):

![variantes-aysen](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/img/newplot(18).png?raw=true)

Incidencia por comuna, disponible en [`tasas_incidencia`](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/tasas_incidencia.ipynb):

![incidencia-comunal-aysen](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/img/newplot(19).png?raw=true)

Gráficos de Indicadores para comparación intercomunal, disponible en [`indicadores_por_comuna`](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/indicadores_por_comuna.ipynb):

![incidencia-comunal-aysen](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/img/newplot(21).png?raw=true)



### Creado con

* [Python 3.8.10](https://www.python.org/downloads/release/python-3810/)
* [Pandas](https://pandas.pydata.org/)
* [Plotly](https://plotly.com/python/)



<!-- GETTING STARTED -->
## Comenzando

Para tener una copia local y funcional sigue los siguientes simples pasos.

### Pré-requisitos

Este es un ejemplo de como instalar las librerias necesarias para utilizar el software correctamente.
* pip
  ```sh
  pip install requirements.txt
  ```
### Para usuarios de [Anaconda](https://www.anaconda.com/)

Un nuevo ambiente virtual debe ser generado para correr los scripts en modo compatibilidad con Python 3.8.1. Para esto correr en el Anaconda prompt

```sh
conda create -n virtualseremiaysen python=3.8.1 anaconda
```

Esto puede tardar unos minutos si es la primera vez que creas el ambiente virtual.

Posterior a la creación del ambiente virtual debemos activarlo e instalar las librerias necesarias

```sh
conda activate virtualseremiaysen
```
Ahora tienes todo instalado para continuar, solo abre tu instancia de Jupyter

```sh
jupyter notebook
```
Las librerias necesarias serán instaladas directamente desde el Notebook mediante ```!pip install YourPackage```, una vez instaladas en el ambiente virtual dichas lineas pueden ser comentadas

Para simplificar la vida del usuario se creó un archivo `requirements_to_install.ipynb`
el cual contiene la linea de código yá escrita. Dicho archivo debe ser corrido una vez previo al uso de los otros 

```sh
pip install -r requirements.txt
```
 
En este punto debieras ser capaz de usar todos los archivos sin problemas
 
Para finalzar, siempre recuerda detener tu ambiente virtual una vez que dejes de usarlo

```sh
conda deactivate
```

### Instalación

1. Clona el repositorio
   ```sh
   git clone https://github.com/millacurafa/SeremiSaludAysenCovid.git
   ```
2. Instala los paquetes de Python necesarios
   ```sh
   pip install -r requirements.txt
   ```



<!-- USAGE EXAMPLES -->
## Ejemplos de Uso

Los documentos estan presentes en formato [Jupyter notebook](https://jupyter.org/) `*.ipynb` y pueden ser corridos de manera local si las bases de datos son agregadas correctamente en la carpeta data. 

La forma más simple de uso es instalar el ambiente virtual de [Anaconda](https://www.anaconda.com/) y posteriormente `plotly` el cual no viene incluido. Adicionalmente, se podrian instalar los requerimientos manualmente como se explica en la sección anterior de `Instalación`.

Celdas pueden ser corridas haciendo click en `Kernel` y luego `Restart & Run All`, o una por una mediante `Shift+Enter` o `Ctrl+Enter`/`Cmd+Enter`

![restart-and-run-all](https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/img/newplot(20).png?raw=true)

Mayor información disponible dentro de cada archivo 

Éxito en tu exploración!

<!-- ROADMAP -->
## Roadmap

Revisa [open issues](https://github.com/millacurafa/SeremiSaludAysenCovid/issues) para ver una lista de las caracteristicas propuestas (y errores conocidos).



<!-- CONTRIBUTING -->
## Contribuciones

Las contribuciones son lo que hacen la comunidad de código abierto un excelente lugar de aprendizaje, inspiración y creación. Cualquier contribución que realices será **muy bien recibida**

1. Realiza un Fork del Proyecto
2. Crea una rama para tu Feature  (`git checkout -b feature/AmazingFeature`)
3. Haz un Commit de tus cambios (`git commit -m 'Agrega un AmazingFeature'`)
4. Haz Push de la rama creada (`git push origin feature/AmazingFeature`)
5. Abre una solicitud de Pull



<!-- LICENSE -->
## Licencia

Distribuido bajo licencia MIT. Ver `LICENSE` para mayor información.



<!-- CONTACT -->
## Contacto

Link del proyecto: [https://github.com/millacurafa/SeremiSaludAysenCovid](https://github.com/millacurafa/SeremiSaludAysenCovid)



<!-- ACKNOWLEDGEMENTS -->
## Agradecimientos

* [Miguel Oyarzo](https://github.com/MiguelOyarzo)
* [Pablo Briones](https://github.com/pbrionespatagon)
* [Fabián Méndez]()
* [Felipe Millacura](https://github.com/millacurafa)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/millacurafa/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/millacurafa/SeremiSaludAysenCovid/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/millacurafa/SeremiSaludAysenCovid.svg?style=for-the-badge
[forks-url]: https://github.com/millacurafa/SeremiSaludAysenCovid/network/members
[stars-shield]: https://img.shields.io/github/stars/millacurafa/SeremiSaludAysenCovid.svg?style=for-the-badge
[stars-url]: https://github.com/millacurafa/SeremiSaludAysenCovid/stargazers
[issues-shield]: https://img.shields.io/github/issues/millacurafa/SeremiSaludAysenCovid.svg?style=for-the-badge
[issues-url]: https://github.com/millacurafa/SeremiSaludAysenCovid/issues
[license-shield]: https://img.shields.io/github/license/millacurafa/SeremiSaludAysenCovid.svg?style=for-the-badge
[license-url]: https://github.com/millacurafa/SeremiSaludAysenCovid/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/millacurafa

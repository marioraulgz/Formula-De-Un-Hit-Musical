# Formula de un hit musical

## Equipo 2 

<img src = 'the_formula_for_a_musical_hit.png'>

## Índice

- [Introducción](#introduccion)
- [Planteamiento](#planteamiento)
- [Spotipy y la API de Spotify]("spotipy")
- [Árbol de decisiones]("decision_tree")
- [Streamlit]("streamlit")
- [Enlaces externos](#enlaces_externos)

<a name="introduccion"></a>
## Introducción

Este proyecto de ciencia de datos se trabaja sobre datos de Spotify, con un enfoque especial en Machine Learning, se basa en el análisis extenso y riguroso hecho con anterioridad. El objetivo es poder predecir si una canción va a ser un éxito o no.

<a name="planteamiento"></a>
## Planteamiento

Esta es una propuesta para los servicios de streaming de música, para los productores y en partícular para Spotify. La estrategia es para usarse en algoritmos de recomendación. Con base en las características de la canción se pretende predecir su éxito.

<a name="spotipy"></a>
## Spotipy y la API de Spotify

Se usó la API que ofrece Spotify ya que es más complicado trabajar con los datos en crudo, con anterioridad se hizo el procesamiento hasta cierto punto. Para simplificar las solicitudes GET a la API de Spotify, nos apoyaremos en Spotipy, una librería que sirve de interfaz para el API. Ahora los datos están en un repositorio de GitHub, dar clic [aquí](https://github.com/marioraulgz/SpotifyBEDU-LaRevancha/blob/main/Postworks/Datasets/data_delimited.csv).

<a name="decision_tree"></a>
## Árbol de decisiones
Se ajustan varios modelos en base a distintos métodos de aprendizaje automático, pero se tomo el resultate de una clasificación por árboles de decisión cuya precision fue la mayor, de 0.85.

<a name="streamlit"></a>
## Streamlit
Para mostrar el resultado de todo el proyecto se realizó una aplicación web con la librería Streamlit. En ella se pueden hacer búsquedas de canciones y para cada cación se puede predecir sí es un éxito o no.

<a name="enlaces_externos"></a>
## Enlaces externos

Enlaces que servirán al lector para ahondar más en los temas tocados.
- [Spotify for developers](https://developer.spotify.com/documentation/web-api/)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [Pandas](https://pandas.pydata.org/)
- [Numpy](https://numpy.org/)
- [Streamlit](https://streamlit.io/)

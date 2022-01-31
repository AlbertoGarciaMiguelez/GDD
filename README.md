GAME DESIGN DOCUMENT TEMPLATE
=============================
# Destrilla

## Indice


1. Características básicas
   1. Introducción
   2. Descripción  

2. Equipo de diseñadores.

3. Historia
 
4. Interfaz: Diagramas de flujo
   1. Pantalla Inicio
   2. Elección
   3. Opciones
 
5. Mecánicas en juego
   1. Controles
   2. Habilidades
   3. PVE
   4. Gameplay
   5. Tecnología
   
6. Mapas y Niveles
   1.  Tutorial
   2.  Mapa
   3.  Niveles de evolución

7. Música y Sonido
   1. Efectos
      1. Objectos
      2. Ataques
      3. Diálogos
   2. Ciudades
   3. Mapa

8. Arte del juego 

## Características básicas

### Introducción

Destrilla es un RPG ambientado en un mundo de fantasía. Tu personaje aparece sin memoria y solo puede recuperarla accediendo a la antigua arca del Rey Antiguo Jeff que esta protegida por un sello de los 4 reyes. El estilo del juego se busca que sea lo más impresionante posible para fascinar con las habilidades a los jugadores y creando un gran conjunto de estas.


### Descripción

Destrilla es un mundo de fantasía donde gobiernan 4 grandes reyes y hermanos entre si llamados Tornus, Jinko, Mabia y Niquia. Estos, llevan muchos años en conflicto debido a la herencia de su padre el Gran Rey Fran. Cada uno de ellos consiguio un area de influencia dominando un amplio territorio, tu misión es derrotar a los 4 reyes para dejar atras esta disputa, pero solo buscas que con esta acción rompas el sello y se abra la cripta del antiguo rey para recuperar la memoria.

## Equipo de diseñadores

El proyecto tendrá un nuevo equipo de desarrolladores constado por 7 personas que se van a introducir en el mercado pero como soporte tendrán a Tequila Works.

### Historia

Cuando se empieza a jugar aparece una cinemática donde se ve a 2 personas subiendo una montaña nevada. El jugador comienza manejando al pupilo y el maestro te está explicando que estais buscando unas aguas termales curativas. A lo largo de la travesía aprendes todos los controles, hace laberintos y derrotas a algunos pequeños enemigos. Cuando llegais a la cima veis agua de donde sale vapor. Hurra!! grita ilusionado el pupilo y se lanza sin pensarlo. El maestro indica que tengas cuidado pero lo ingora. Mientras nada y se relaja el maestro recoge un poco del agua termal y consigue ver que en el agua en el fondo hay un huevo de dragón, alterado manda a su pupilo volver inmediatamente pero es demasiado tarde. Con un estruendo un dragon de nieve aparece volando y lanza un viento helado que congela la pupilo. El maestro combate al dragón donde el jugador puede manejarlo teniendo acceso a todas las habilidades de la rama que el elija. Una vez quitada la mitad de la vida el huevo de dragón se abre sin que puedas visualizar que es y apareciendo un portal que se lleva al pupilo.

<img src = https://github.com/AlbertoGarciaMiguelez/GDD/blob/main/img/2.jpeg>

Aparece una pantalla donde le dice escoger una clase y probar las habilidades de cada una.

Una vez escogida clase se abre un portal en una playa de ella sale toda el agua termal y 2 sujetos. Uno el pupilo congelado y otro el personaje principal que va a manejar el jugador.

Se descongela al pupilo, le roba la ropa y se marcha. A medida que se avanza se va descubriendo el mundo, con algunas misiones que van apareciendo y se va desbloqueando habilidades y subiendo niveles.
Cada reino tiene un funcionamiento y unas características a la vez que se tiene que derrotar a cada rey que es una boss de la zona.
Una vez derrotado a los 4 reyes se desbloquea la cripta donde se encuentra el Final Boss que es el Gran Rey Fran donde al matarlo desbloquea los recuerdos y desace la maldición. Descrubiendo el origen del individuo y un nuevo continente, oculto hasta ahora.


## Interfaz: Diagrama de flujo

### Pantalla de inicio

<img src = https://github.com/AlbertoGarciaMiguelez/GDD/blob/main/img/pantalladeInicio.JPG >

### Elección de personaje

<img src = https://github.com/AlbertoGarciaMiguelez/GDD/blob/main/img/Eleccion.JPG >

### Opciones


<img src = https://github.com/AlbertoGarciaMiguelez/GDD/blob/main/img/opciones.JPG >

## Mecánicas del juego

### Controles

**Teclado**

    Q Habilidad 1
    W Habilidad 2
    E Habilidad 3
    R Habilidad 4
    A Habilidad 5
    S Habilidad 6
    D Habilidad 7
    F Habilidad 8
    C Montura
    V Pociones 1
    X Pociones 2
    H Intereactuar
    I Inventario
    M Mapa
    T Activar Habilidad especial
    G Activar Reliquia especial
    Right-handed Moverse a X dirección
    Left-handed Marcar a enemigo
    Tab Ver datos sobre jugadores
    W Habilidad 2

### Habilidades

**Mago**

      Habilidades hasta Nivel 20
      
      Bola de fuego: Se crea una bola de fuego que deja un rastro en los enemigos que quema.
      Bola de hielo: Se crea una bola de hielo que deja un rastro en los enemigos que relantiza.
      Teletransportación: Movimiento instantaneo a 5 metros desde donde se lanza.
      Drenar: roba vida de los enemigos
      Muro de viento: bloquea los ataques de los enemigos a distancia.
      Barrera de piedra: crea una barrera de piedra a tu alrededor que te hace mas resistente a ataques pero mas lento.
      Repeler: empuja a los enemigos hacia delante.
      Invisibilidad: te vuelve indetectable
      Cuando falta: reduce el tiempo de activación de todas las habilidades.
      
      Habilidades hasta Nivel 40
      
      Lanzallamas: lanza un huracan de fuego desde la mano hacia el enemigo.
      Helada: lanza un huracán de hielo desde la mano hacia el enemigo.
      SuperDrenaje: ahora drena hasta 5 enemigos a la vez.
      Muralla de hielo: crea 4 muros de hielo a tu alrrededor.
      Armadura de piedra: aumenta enormemente la defensa contra ataques pero también la velocidad.
      Gravedad: atrae a todos los enemigos a un punto.
      Fogata de lava: el fuego sale de la tierra y quema a los enemigos para luego salir lava y duplicar el daño.
      Invisibilidad+: ahora hace daño extra al salir de la instancia.
      Rayo: Lanza un rayo a un objetivo único que se puede encadenar provocando daño porcentual y silenciando al enemigo.
      
      Habilidad hasta Nivel 60
      
      Arde: explota en fuego y quemas a todos los enemigos en un área de 20 unidades.
      |- Combo: produce daño extra creando una explosión extra y mayor quita los efectos de estado anteriores.
      Congelate: explota en ventisca helada y congelas a todos los enemigos en un área de 20 unidades.
      Agujero negro: si tiene un 10% de la vida y no es un enemigo especial, se lo traga. Atrae a todos los enemigos a un punto.
      Tormenta: crea una tormenta electrica que silencia a los enemigos en la zona y provoca una descarga de rayos.
      Toma de vida: relantiza a los enemigos y aplica drenaje en un cono pequeño.
      Dash de fuego: te convierte en fuego intangible y provoca quemaduras.
      Fantasma: te convierte en un fantasma indetectable pero puede seguir lanzando habilidades.
      
**Guerrero**
      
      Habilidades hasta Nivel 20
      
      Refuerzo: adquiere reducción de daño.
      Mandoble: crea con dos espadas para atacar mas rápido.
      Berserker: aumenta la velocidad de ataque.
      Giro de espadas: gira las espadas y hace daño en un radio de 4 unidades.
      Remate: ejecuta a un enemigo con poca vida.
      Nemesis: elige a un enemigo, hace mas daño pero le haces mas daño.

**Asesino**
      
      Habilidades hasta Nivel 20
      
      Cuchillo arrojadizo: lanza un cuchillo que hace daño a distancia
      Daga por la espalda: te teletransporta atras del enemigo y aplicas veneno.
      Giro de dagas: crea dagas alrededor del asesino que hacen daño cuando hacen contacto.
      Danza de los cuatro vientos: aumenta la velocidad y el daño.
      Sexta venguante: te vuelve invisible y el siguiente ataque hace mas daño.
      Kikhenda: crea 4 copias tuyas que hacen daño y copian todas tus habilidades.
   
**Arquero**

      Habilidades hasta Nivel 20
      
      Lluvia de flechas: crea una lluvia de flechas que hace daño en un radio lejano.
      Flecha única: carga una flecha al máximo que hace daño adicional.
      Arco de Cúpido: deja tu daño de lado para aturdir a los enemigos durante un perido de tiempo largo.
      Adiós: deja el arco de lado para clavar la flecha al enemigo como una daga.
      Gran Flecha: lanza una flecha mágica que atraviesa a los enemigos y hace daño adicional.
      Precisión aumentada: aumenta el daño y la velocidad de los básicos.
      
### PVE

La IA estará programa para tener 3 niveles de dificultad.
Fácil: El nivel de dificultad más básico para el disfrute del jugador. Cada enemigo tendrá el daño y la vida bajados un 50% y habrá una reducción de enemigos en un 25%. En este nivel se podrá desbloquear un final alternativo para colocar como reto al jugador y incentivar a pasárselo en modo normal.

Normal: Nivel de dificultad para todos los jugadores sin ningun tipo de secreto pero también sin ningún tipo de bloqueo de mapa o nivel.

Dificil: Nivel de dificultad avanzado para jugadores expertos, plantea un reto para los jugadores así como una cinemática adicional como recompensa y un logro.

En el futuro se tendrá pensado añadir nivel de dificultad más elevados así como efectos especiales que dificulten la jugabilidad.

### Gameplay

Se jugará desde una vista en tercera persona que dispondrá en el centro abajo de la pantalla de la barra de vida, botones de lanzamiento de habilidades y pociones. Arriba a la derecha dispondrá del minimapa y justó debajo las misiones.

<img src = https://github.com/AlbertoGarciaMiguelez/GDD/blob/main/img/dos-0048_h4z6.jpg >
<img src = https://github.com/AlbertoGarciaMiguelez/GDD/blob/main/img/233723_w926.jpg >

El gameplay será rápido y frenético. La mecánica que seguira el juego es de progresión los jugadores notaran que avanzan, que progresan en cada uno de los desafios y que sepan en todo momento en qué punto se encuentra y cuánto les falta para conseguir terminarlos y una ganancia de recompensas por este avanze como objetos avanzados.

### Tecnología

Unity3D
Esta herramienta se puede usar de forma gratuita. Perfecto para estudios indies.

## Mapas y Niveles

### Mapa de Tutorial

Para acceder a las aguas termales deben sortear un frondoso bosque rodeado de enemigos que permite al jugador el aprendizaje inicial de los controles de lucha y movimiento. Recrea un mundo de fantasía y aventura. Éstas estarán situadas en un valle rodeado de montañas nevadas muy escarpadas y altas, donde se dice que duerme un dragón de nieve muy poderoso.


### Mapa

El mapa esta dividido en cuatro reinos, cada uno con una temática diferente. 

**El primer reino** tendrá una temática básada en la industrialización, donde la mayoría de las maquinas funcionarán en base a la quema de carbón como combustible produciendo de esta manera, numeroso vapor de agua que cubrira al reino. Siguiendo está línea los soldados serán maquinas de vapor andantes que vigilan las calles de la ciudad central echa totalmente de cobre. Los alredores se verán afectados por este clima, tendrán un paisaje húmedo y nublado que producira una desventaja en los guerreros debido a que son saben controlar bien la respiración, no como el asesino, provocando ataques más lentos y con menor daño. Teniendo en cuenta la menor visibilidad del paisaje el arquero se vera afectado por esto teniendo el mismo rango que el mago y teniendo una probalidad de fallo.

**El segundo reino** estara basado en las culturas antiguas, esto se reflejara en contrucciones primitivas pero fuertemente protegidas como muros altos de piedra y de gran grosor provocando así un dificil acceso. Teniendo en cuenta todo esto los soldados tendrán un gran poder de ataque y un gran conocimiento mágico. Lo que los hara mas resistentes contra ataques mágicos del mago y también a ataques especiales del asesino.

**El tercer reino** estara basado en un mundo futurista, totalmente automatizado controlados por inteligencia superior y algunos con capacidades de predecir los movimientos. El mundo estará controlado por defensas altamente avanzadas como torretas, maquinas voladoras y sensores de movimientos, lo que reducira el daño al arquero debido a que las defensas tienen mayor resistencia a los ataques lejanos y al asesino debido a que los soldados cuentan con visión termica lo que hace inservible la invisibilidad de este.

**El cuarto reino** vendrá de una reciente conquista por metodos de fuerza bruta, la mayoria de los edificios estarán ardiendo o siendo atacados. El reino es un caos absoluto que se intentan matar entre todos para predominar el más fuerte. Edificaciones destruidas, fuego por todos lados, objetos mágicos vertidos en el agua, disparos, enemigos en cualquier lado. En este reino las debilidades van variando dependiendo del punto del mapa, excepto en la ciudad central donde se verán afectados por todas las debilidades a la vez, reduciendo el daño y la vida.

### Niveles de evolución

El personaje evoluciona según la experienza adquirida en las misiones. Al subir de nivel el personaje tendrá la opción de elegir una habilidad nueva o simplemente se aumentarán sus atributos. El juego sigue una continuidad lineal por lo que los niveles de los enemigos irán a casi siempre a la par del personaje exceptuando que se haga o no alguna misión secundaria.
El nivel máximo sera el 60 cuando llegues a ese nivel se espera que hayas completado el juego o que en su lugar quede poco para ser completado.

## Música y sonido

### Sonidos

**Básicos**

Cofres: sonido sencillo de cofre que va a variar según la calidad del cofre.

Pociones: sonido de curación o bufo recogido de otros juegos como el New World.


**Ataques**

Básicos: tendrán un sonido tenue para no molestar al jugador ya que serán los más utilizados sobre todo en clases como el arquero. También dispondrán de un sonido más característico cuando se trate de un crítico.

Especiales: van a ser muy carcterísticos para poder diferencialos claramente y van a seguir un patrón muy sencillo. Cuanto más daño, más ruido y más increible va a sonar así como su duración. Se intentare crear un rebote de eco para mayor espectáculo.

**Dialogos**

Cinemáticas: se busca un diálogo más profundo orientado al jugador que trate de sumergirlo en las escena y también que informe de las cosas más importantes de la trama y del objetivo principal del juego.

Personajes: los diálogos se podrán saltar, serán rapidos y la mayoria estarán subtitulados y con un simple sonido del NPC como "VAYA!!!" para mayor velocidad de jugabilidad. Se busca que sea algo dinámico. Y los dialogos se van a poder saltar.

### Música

#### Ciudades

Cada ciudad tendrá una música de acuerdo con su temática.

El primer reino tendrá una música de género Electro Swing para dar un ambiente de industrialización. Ejemplo: Libella Swing.

El segundo reino tendrá una música tranquila y relajada. Ejemplo: Kino's Journey OST - I See You OST.

El tercer reino tendrá una música Techno para dar el ambiente futurista. Ejemplo: Inhuman.

El cuarto reino tendrá una música caótica estilo rock. Ejemplo: Don't Look- Silent Partner.


#### Mapa

La música de la intro del juego y la pantalla inicial.

Mushoku tensei - 『Tabibito no Uta』by Yuiko Ohara.

Para el tutorial.

MHW: Iceborne OST Seliana Day Theme.

La música del mapa en principio se buscá que sea genérica y que de un toque de fantasía.

MHX OST [Disc 1] - MHX Promo Video.
Pokke Village Theme - MH Generations.

Exceptuando los alrededores del primer reino debido a la niebla y el cuarto por la cantidad de aleatoriedades que se encuentran.

El primer reino tendrá musica misteriosa. Ejemplo: Chakras Escape.

El cuarto reino cambiara de música dependiendo de la zona en la que se sitúe variando siempre con el género de rock, rap y drum & bass.


## Arte de juego


<img src = https://github.com/AlbertoGarciaMiguelez/GDD/blob/main/img/1.jpg>
<img src = https://github.com/AlbertoGarciaMiguelez/GDD/blob/main/img/3.jpg>
<img src = https://github.com/AlbertoGarciaMiguelez/GDD/blob/main/img/5.jpg>

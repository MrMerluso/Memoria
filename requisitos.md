# DayZ Genesis
Esto es una lista de weas que son necesarias para completar mi visión del servidor. El servidor se inspira en uno de los mods originales de dayz: Dayz Origins. La Característica principal de ese mod es qua había una gran cantidad de misiones que utilizaban npcs daban un poco mas de ambientación al juego y proporcionaban una forma interesante de conseguir buen loot. Además incorporaba un sistema de reputación que dividía a los jugadores en Héroes y Bandits. Estas características son poco vistas en los servidores de dayz actualmente ya que la gran mayoría intenta asemejarse a juegos battle royale en lugar de enriquecer la experiencia de supervivencia. Creo que integrar NPCs que interactuen con los jugadores y que ambientalicen el mapa, además de un sistema de reputación que incentive diferentes tipos de jugabilidades ayudará enormemente a mejorar la experiencia de supervivencia postapocaliptica sin tener que convertirla en un battle royale acelerado.

## Reputación
Voy a comenzar con un sistema de reputación simple, idéntico al de Dayz Origins. Ciertas acciones sumarán o restarán puntos de reputación a los jugadores y los asignarán automáticamente a una de dos posibles facciones: Heroes o Bandit.

Cada facción tendrá niveles del 1 al 3 dependiendo de la cantidad de puntos de reputación que le permitirán acceder a otras características del servidor.

### Heroes
Los Heroes son básicamente los buenos del juego. Un jugador que obtiene reputacíon de Hero es un jugador que ayuda a otros jugadores a sobrevivir y sólo mata en defensa propia. Es un jugador que está dispuesto a sacrificarse por el bien de otros, se enfoca en mantener su propio bienestar y ayudar a jugadores mas débiles.

Es por esto que el arsenal disponible para los Heroes se enfoca mas en la defensa y en apoyo. Específicamente, los Heroes tienen a su disposición armaduras de alto nivel que los ayudarán a resistir posibles emboscadas de Bandits (pero no inmunes) y objetos médicos que les permiten preservar su salud y la de otros jugadores. El gran peso de sus armaduras les permite enfocarse en el combate de corto alcance además de hacer complicado el uso de rifles de muy alto calibre

### Bandits
Son los agentes del caos. Los bandits no piensan dos veces antes de llenar de plomo a sus oponentes. Son escurridizos por lo que pueden entrar y salir de una escena con rapidez, o bien, esperar en algún arbusto a una pobre víctima y asesinarlos sin que sepan que les pasó.

El arsenal de los bandits debe permitirles poder llevar a cabo tal caos. Armas de largo alcance y gran calibre permiten acabar con sus víctimas rápidamente incluso si son Heroes, pero llevar mucha armadura no les permitiría escapar antes de ser descubiertos. Deben tener a su disposición camuflajes que les permita pasar desapercibidos y trampas que eviten que ellos sean los emboscados.

## Campamentos
El sistema de reputación permitirá que los jugadores puedan acceder a diferentes tipos de campamentos que les otorgarán refugio, un lugar donde adquirir objetos acorde a las características de sus facciones y también acceder a ciertos tipos de quests. Los objetos deben ser comprados con dinero que puede ser obtenido al completar quests o vender objetos. Los jugadores también tienen la posibilidad de acceder a un locker de almacenamiento personal que les permitirá guardar items sin la posibilidad de que sean robados por otros jugadores además de poder spawnear en el campamento principal si así lo desean. Existirán dos campamentos principales en lados opuestos del mapa, uno para Heroes y otro para Bandits

### Tipos de campamentos \**Idea en desarrollo*\*
He considerado la posibilidad de que existan dos tipos de campamentos: Campamento Princial y Puestos de Avanzada. Esto en definitiva sería la característica más dificil de implementar

El campamento principal tiene todas las características disponibles: Compra y venta de productos y vehiculos, aceptar y entregar misiones, punto de spawn, almacenamiento personal, etc. Pero más importante, los jugadores de una facción opuesta no pueden entrar a estos campamentos (hay guardias que los matarán inmediatamente) ni matar jugadores que se encuentren dentro de estos (safezone)

Por otro lado, los Puestos de Avanzada serían una versión miniatura de los Campamentos Principales, ofreciendo solo algunas de las características de estos (spawn, almacenamiento). Lo que diferenciaría a los Puestos de Avanzada de los Campamentos principales es que estos pueden ser atacados por la facción opuesta. Es necesario que estos campamentos cuenten con una cantidad de guardias NPC que implique un desafío para un grupo de 6-8 jugadores que quiera inicar un ataque además de la posibilidad de que estos puedan ser defendidos por jugadores de la facción del Puesto. 

La recompensa por atacar exitosamente uno de estos campamentos es la posibilidad de obtener una gran cantidad de objetos que estarían disponibles exclusivamente en el mercado de la facción defensora además de acceso a los objetos que los jugadores hayan almacenado ahí. Por ejemplo, si un grupo de Heroes logra exitosamente atacar un Puesto de Avanzada de Bandits, la recompensa serán gran cantidades de armas de Bandits nivel 3 (es decir, armas de alto calibre y poder de penetración)

## Mercados
Cada campamento dispondrá de mercados que ofrecerán objetos exclusivos a cada facción. Específicamente ofrecerán diferentes tipos de armas y de armaduras. Además, ciertos objetos estarán restringidos a niveles más altos de reputación dentro de la facción, por ejemplo, un Bandit de nivel 3 debería tener acceso a armas más poderosas que un Bandit de nivel 1

La moneda de compra de los mercados serán los rublos. Tiene sentido ya que Chernarus está inspirado en los países de europa del este y geograficamente es un país vecino de rusia. Este dinero puede ser obtenido completando Quests o vendiendo otros objetos a los mercaderes tales como armas o objetos valiosos como juegos portátiles o libros.

#### Monedas alternativas *\*Idea en desarrollo\**
Utilizar dinero normal en un contexto postapocaliptico no tiene mucho sentido considerando que el colapso de la civilizacion como la conocemos implicaría tambien la caida de los bancos. Es por eso que una posible alternativa que se adaptaría mejor al ambiente postapocalíptico e inspirada en los videojuegos Metro es utilizar balas como moneda de cambio. Esto sería dificil de implementar ya que en DayZ existen muchos tipos de bala y no hay un tipo de bala especial que pueda ser utilizado como moneda y al mismo tiempo para ser disparada como es el caso de Metro, pero sin embargo seria una característica interesante y no muy vista en DayZ

## Quests
Cada Campamento tendrá NPCs que le pueden ofrecer al jugador Quests. Una Quest es una serie de objetivos que un jugador debe completar para obtener una recompensa. Los objetivos que puede completar un jugador van desde recolectar objetos hasta matar jugadores o a otros NPCs. Es posible enlazar múltiples de estas Quests para formar una narrativa que puede añadir contexto al entorno o simplemente contar alguna mini-historia interesante.

Las Quest deberían servir como guía a jugadores que están recién comenzando a jugar en el servidor. Deben proporcionar información sobre la facción del jugador como de la facción opuesta. Deben ayudar a tomar algunos de los primeros pasos básicos del juego y del servidor.

Las Quest deben estar orientadas a grupos de 1-3 jugadores. Las Quests recompensan a cada jugador individualmente, por lo que es importante considerar que pueden ser utilizadas por grupos más grandes para obtener una gran ventaja sobre grupos pequeños

También es posible encontrar diferentes NPC ofreciendo Quests en diversos lugares del mapa.

Las Quest pueden llevar al jugador a diversos lugares del mapa para descubrir lugares interesantes 

Mientras más Quests sean completadas por los jugadores, mejores deberán ser las recompensas

## Misiones
Las Misiones aparecen en el mapa en momentos aleatorios y todos los jugadores conectados en el servidor son notificados de su aparición. Cualquier jugador puede completar la misión y obtener sus recompensas
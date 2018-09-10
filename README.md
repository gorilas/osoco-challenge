# osoco-challenge
Este es el resultado del reto propuesto por Osoco y realizado por Jesús Cuadra: [jesuscuadra.es](http://jesuscuadra.es)

### Descripción del reto
Un hipotético cliente ha solicitado el desarrollo de un “acortador de URLs”. Existen múltiples acortadores de URLs disponibles en internet, pero resulta que nuestro cliente quiere tener el suyo propio. Además nos ha dejado su tarjeta, es esta: (imagen)

Partiendo de esta información, nos gustaría que nos propusieras la solución “global” al cliente desde el punto de vista de todos los perfiles para los que te sientes capacitado (UX, UI, maquetación, etc.). El entregable puede ser como quieras, lo importante es que se entienda el proceso por el que has llegado al resultado final.

## Solución propuesta
Lo primero es una **conversación con el cliente** exploratiora, pero parar ello tenemos que saber qué información recopilar. El cliente llega a nosotros con su idea de que creando un acortador de urls, va a solucionar un problema o bien aprovechar una oportunidad de negocio que él tiene. Queremos explorar estas motivaciones. Es decir, imaginemos que somos doctores en una consulta y el cliente viene con un autodiagnóstico. Primero hay que realizar nuestro trabajo como profesionales expertos: escucharlo y validar si debemos prescribirle el mismo tratamiento que el propone o debemos indagar más.

Para prepararse para la primera conversación debemos **investigar acerca del dominio**. ¿Qué podemos saber acerca de acortadores de urls?

### Investigación previa
Buscamos artículos que nos hagan conocer mejor lo que son los acortadores y cuál es la competencia. Con ello podemos llegar a artículos como este: https://zapier.com/blog/best-url-shorteners/

En él vemos que hay distintos modelos de negocio con cada solución y que, en cada una de ellas, el acortador es un elemento (no siempre central) del modelo de negocio y de la propuesta de valor.

Ya vamos encontrando que la primera misión será **averiguar cuál es la propuesta de valor para el usuario** y unirlo con el **modelo de negocio** que el cliente trae bajo el brazo. Probablemente, validar primero su modelo de negocio con un experimento sea lo que mejor le podemos dar al cliente para empezar. Es posible que si se refuta su idea como modelo de negocio, entonces el cliente ya no quiera continuar. Eso no está mal, ya que se habrá gastado menos haciendo el experimento que construyendo todo un servicio, para descubrir, posteriormente, que su servicio no era viable o no le resolvía sus problemas.

Para averiguar todo ello y enfocar la propuesta de soluciones se le propone una **consultoría de descubrimiento de producto**. Se concretará en 3-5 mañanas de trabajo conjunto con el cliente en nuestras oficinas.

### Consultoría de descubrimiento de producto
Una vez agendada, prepararíamos la sala y estaríamos no más de 6 personas. El deseable sería: el cliente, algún experto (del lado del cliente), alguien de perfil técnico, de ux, de negocio, alguien que sepa de los usuarios.

---

La agenda propuesta podría ser una **versión simplificada** de esta propuesta completa:
![agenda propuesta](./images/discovery_proposal.png)

---

Y el desglose de actividades día a día estaría basado en una **versión simplificada** de esta agenda:
![agenda día a día](./images/discovery_day_by_day.png)

---
### Resultados del descubrimiento de producto
Supongamos que en las conversación exploratiora previa y en el descubrimiento de producto hemos averiguado lo siguiente:
- El cliente tiene contactos con _Tuenti_.
- El cliente piensa que un acortador de urls le puede dar información acerca de los usuarios. Con la premisa: "Dime a quién enlazas y te diré quién eres".
- Actualmente, los milennials, soy un sector cuyos gustos de consumo evolucionan demasiado rápido, y las marcas, que ofrecen productos para ellos, no saben cómo estar al día y ofrecerles los productos que más les interesan a tiempo. Se está perdiendo una oportunidad de negocio.
- El acortador de urls estaría destinado a esos Milennials y habría una alianza con Tuenti para integrar su acortador con ellos.
- El acortador de urls estaría destinado a analizar con algún servicio de Inteligencia Artificial (IA) el contenido de las cosas que publican para poder conocer sus gustos y ofrecerles productos.
- El acortador sería un medio que da un servicio gratis a los milennials con algo que les resulte molón. El acortador tendrá un tono divertido y cachondo.
- El modelo de negocio sería aprovechar el conocimiento acerca de los milennials para ofrecerles publicidad que les interese. Esa publicidad sería a través de enlaces, artículos, perfiles de Instagram y otras redes sociales que finalmente conectan a las marcas con los usuarios.
- Se pretende conseguir inversión inicial para construir el servicio y aumentar el número de usuarios antes de nada. Los beneficios vendrán gradualmente después. 
- Se espera conseguir una primera ronda de financiación de 120K con la que se quiere hacer un rebranding de la marca. Y una aplicación móvil para acortar urls y compartirlas con el móvil. La financianción vendrá inicialmente de _Movistar/Tuenti_ y de una VC firm local.

### Propuesta inicial
Se propone inicialmente, una consultoría de investigación con usuarios, con presupuesto cerrado, con el objetivo de hacer un perfil de sus motivaciones y gustos a la hora de usar un servicio de compartir enlaces con acortador de urls.

Paralelamente, también con un presupuesto cerrado, el rebranding de la marca cambiando a su vez el nombre de la marca.

### Investigación de usuarios
El cliente, a través de su alizanza con _Tuenti_, consigue 30 usuarios que se ajustan al perfil target que utilizaría el servicio:
Chicos y chicas de 11 a 18 años, con teléfono móvil propio.

Se exploran las siguientes variables:
- Edad
- Sexo
- Nivel socioeconómico
- Información demográfica
- Gasto mensual en productos
- Formas de gasto: autónomamente, sus padres compran, etc...
- Gustos personales
- Cómo se relacionan con sus compañeros
- Uso del móvil
- Cómo comparten cosas
- Uso de redes sociales
- Memes que más les gustan
- Perfiles a los que siguen en redes sociales

A partir de allí se detectan patrones y se hace un modelado de "Personas". Se elige una Persona principal, que servirá de objetivo a la hora de comunicarnos internamente y tomar decisiones de diseño.

#### Resultados del modelado de Persona:

_"Leti Garrido"_. Chica de 13 años.
Vive en Barcelona en el barrio de Sant Gervasi.
Sus padres son profesor de universidad y directora de una empresa familiar que se dedica al negocio inmobiliario.
Sus padres gastan unos 500€ mensuales a gastos de ocio y ropa para ella. La forma de comprar es mediante el préstamo en mano de la tarjeta de crédito de su madre, que está asociada a una cuenta que está a nombre de la chica pero que administra su madre.
Leti es una chica responsable y nunca llega a gastarse todo el dinero, guardando siempre unos 100€ para gastarse en sus viajes de verano que hace en sus intercambios al extranjero a través de una agencia.
Leti es una amante de la moda y le gusta bailar hip-hop en una academia de su barrio. Le encanta comprarse ropa cara, pero no puede permitirselo muy a menudo. Sus gastos principales son en Zara, Mango y H&M y Miss Sixteen. Cada año compra 3 o más prendas caras principalmente de la marca Diesel y Bimba & Lola. El 40% de sus gastos los hace en Privalia, principalmente en zapatillas de deporte de marca y en bolsos.
Sigue a varias influencers: "El canal de Teru de Youtube es mi favorito, el año que viene quiero ser youtuber como ella", dice.
Leti tiene móvil propio: un Huawei P10 heredado de su padre y dedica 2 horas al día a comunicarse con sus amigas y amigos: usa _Snapchat, Whatsapp, Tuenti_ y _Youtube_, principalmente.
Le gusta usar muchos emoticonos, pero no le gustan nada los gifs animados. Usa, desde siempre, el móvil con dos manos y teclea con los pulgares acortando las palabras.

#### Insights:

Descubrimos que el acortar palabras cuando escribimos en móvil es muy similar a el acortador de urls. Todos los acortadores son aleatorios o producen urls aburridas. Se podrían usar términos kchonds n las urls akrtds ;P

Chavales como ella, están siempre pendientes de las últimas ofertas de _Privalia_, siempre hay problemas en encontrar tallas de zapatillas de deporte y ellos no pueden tener una cuenta premium de _Privalia_ porque no tienen acceso a meter los datos de la tarjeta de crédito en el sistema.

Estos usuarios usan en un 80% móviles _Android_ heredados de sus padres.

En realidad estos chavales no les interesa al inicio el propio hecho de que las urls sean cortas y cachondas, eso lo descubren después al ver pegada la url en sus chats. En realidad lo que quieren es compartir de la forma más rápida posible a su grupo reducido de amigos, y eso es algo que Tuenti aún no ha resuelto bien. _Tuenti_ si que te permite crear y gestionar tus grupos de amigos, pero no compartir algo con "un click".

Ese compartir con "un click", en móvil se traduce en las acciones de "Compartir..." > Elige aplicación. Si eliges _Tuenti_, te metes a un proceso lento y aburrido de compartir. Lo deseable sería una aplicación que ya sepa tus grupos de amigos (de _Tuenti_) y que directamente hagas con el móvil "Compartir..." > "La panda del moco" y lo comparta automáticamente con tus amigos, sin pasar por _Tuenti_. 

### Propuesta de servicio/app
Se propone trabajar por iteraciones en crear un primer MVP (Mínimo Producto Viable) que consiste en una aplicación para Android que te permita abrirla, te pida permisos de credenciales de Tuenti (si tienes instalada su app oficial) y te diga que ya puedes compartir con tus grupos de amigos. Luego te explica que desde cualquier contenido en tu móvil, al dar a "Compartir con..." te aparecerán tus grupos de Tuenti como si fuesen aplicaciones.

El usuario podrá "Compartir con..." > Elige aplicación > Eliges "La panda del moco" y te dice que ya está compartido y te muestra 4 enlaces acortados con preview de contenido relacionado (generado por el servicio de IA) + publicidad de ofertas frescas de Privalia + compartir la app con amigos.

Cada vez que el usuario comparte algo, el sistema se queda con información, que es anónima, pero que genera internamente un Graph de sus gustos y va aprendiendo de ellos, para ofrecerles contenido cada vez más ajustado a sus intereses.

Se calcula que el MVP necesitará de 4 iteraciones de un equipo de 5 personas.

El MVP será lanzado, inicialmente a un grupo de 1.000 usuarios, de los cuales se analizará su efectividad midiendo varios KPIs.

KPIs a medir: 
- Número de enlaces compartidos
- Frecuencia de uso (mes/semana/día/minuto)
- Intentos fallidos/exitosos de uso de la aplicación
- Amigos que han recibido los enlaces
- Enlaces sugeridos clicados
- Tiempo de permanencia en los destinos clicados (coordinación con páginas de destino para que sepan leer que vienen de nuestra app y puedan medirlo y reportárnoslo)
- Éxito de campañas de _Privalia_ a través de este medio

También se realizará, durante tres días, un test cualitativo de 8 usuarios target analizando:
- Facilidad de uso
- Entendimiento de la app
- ¿Lo recomendarías a un amigo?
- Reacción al ver las urls acortadas
- Satisfacción de los enlaces sugeridos
- Satisfacción de la publicidad sugerida 

Una vez construido el MVP, se destinarán unas 4 iteraciones más a mejorar la IA de las recomendaciones y ajustar la publi y las mediciones.

Tras esta fase inicial se empezará un periodo de campaña de lanzamiento global que durará unos 4 meses en los que se espera que alcance a un 30% de los usuarios de _Tuenti_ y se analizarán internamiente los resultados. Durante ese tiempo se propone un acompañamiento por iteraciones de un equipo de desarrollo y UX que no tiene porqué ser el que inicialmente construyó el producto.













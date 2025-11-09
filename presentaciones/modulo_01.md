---
title: Modulo 01
subtitle: Fundamentos históricos y conceptuales de la IA.
date: last-modified
author:
  - name: Francisco Palm
    orcid: 0000-0002-1293-0868
    email: fpalm@qu4nt.com
    affiliations: UNC, qu4nt
format:
  clean-revealjs
html-math-method:
  method: mathjax
  url: "https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"
lang: es
lightbox: true
---

# Introducción a la Inteligencia Artificial

> Módulo 1

::: {.notes}
Este módulo establece los fundamentos históricos, filosóficos y conceptuales necesarios para comprender la IA moderna. Exploraremos cómo la idea de crear máquinas pensantes ha evolucionado desde los mitos antiguos hasta convertirse en una disciplina científica formal.

**Preguntas generadoras:**

- ¿Qué significa realmente "inteligencia" y podemos recrearla artificialmente?
- ¿Cómo han influido los mitos y la literatura en el desarrollo de la IA?
- ¿Qué hace posible, filosófica y técnicamente, la existencia de la IA?
:::

## Programa de la Asignatura

- **Módulo 1**: Fundamentos históricos y conceptuales de la IA
- **Módulo 2**: Paradigmas, Algoritmos y Herramientas Centrales
- **Módulo 3**: El ciclo de vida de un proyecto de IA y Aplicaciones
- **Módulo 4**: Implicaciones éticas, sociales y el futuro de la IA

::: {.notes}
El curso está estructurado en cuatro módulos progresivos que van desde los fundamentos hasta las implicaciones futuras. Este primer módulo es crucial porque establece el marco conceptual sobre el cual construiremos todo el conocimiento posterior.

**Preguntas generadoras:**
- ¿Por qué es importante estudiar la historia antes de la tecnología?
- ¿Cómo se relacionan estos cuatro módulos entre sí?
:::

## Evaluaciones

- **Módulo 1**: Prueba escrita – 25%
- **Módulo 2**: Prueba escrita – 25%
- **Módulo 3**: Prueba escrita – 25%
- **Módulo 4**: Proyecto – 25%

::: {.notes}
La evaluación está distribuida equitativamente, con tres pruebas escritas que evalúan conocimientos teóricos y un proyecto final que permite aplicar todo lo aprendido de manera práctica.

**Preguntas generadoras:**

- ¿Por qué el último módulo se evalúa con un proyecto en lugar de una prueba?
- ¿Qué competencias se buscan desarrollar con esta estructura evaluativa?
:::

# Fundamentos históricos y conceptuales de la IA

### Concepto de Inteligencia

::: {.notes}
Antes de hablar de inteligencia artificial, debemos comprender qué es la inteligencia en sí misma. Este concepto, aparentemente simple, ha sido objeto de debate durante siglos y no existe una definición única universalmente aceptada.

**Preguntas generadoras:**

- ¿Cómo definirías tú la inteligencia?
- ¿Es la inteligencia una capacidad única o múltiple?
:::

---

## Concepto de Inteligencia

**Inteligencia** – del latín *intelligentia* o *intellectus*, que significa comprender o percibir.

::: {.notes}
La etimología nos da pistas importantes: inteligencia está relacionada con la capacidad de "comprender" y "percibir". Esto sugiere que la inteligencia no es solo memorizar información, sino procesarla y darle sentido.

**Preguntas generadoras:**

- ¿Qué diferencia hay entre "comprender" y simplemente "procesar información"?
- ¿Puede una máquina realmente "comprender" o solo procesa símbolos?
:::

---

## Definiciones de Inteligencia 1

> "Una capacidad mental muy general que, entre otras cosas, implica la capacidad de razonar, planificar, resolver problemas, pensar de manera abstracta, comprender ideas complejas, aprender rápidamente y aprender de la experiencia."

*Mainstream Science on Intelligence (1994)*

::: {.notes}
Esta definición enfatiza múltiples capacidades: razonamiento, planificación, resolución de problemas, abstracción y aprendizaje. Note que no menciona emociones o conciencia, lo cual es significativo para el desarrollo de IA.

**Preguntas generadoras:**

- ¿Cuáles de estas capacidades ya pueden realizar las máquinas actuales?
- ¿Es suficiente tener todas estas capacidades para ser considerado inteligente?
- ¿Qué falta en esta definición desde tu perspectiva?
:::

---

## Definiciones de Inteligencia 2

> "Las personas difieren entre sí en su capacidad para comprender ideas complejas, para adaptarse eficazmente al entorno, para aprender de la experiencia, para participar en diversas formas de razonamiento, para superar obstáculos al pensar.

> "Aunque estas diferencias individuales pueden ser sustanciales, nunca son completamente consistentes: el rendimiento intelectual de una persona determinada variará en diferentes ocasiones, en diferentes dominios, según lo juzguen diferentes criterios.

::: {.notes}
Esta definición reconoce la variabilidad de la inteligencia: no es un atributo fijo ni uniforme. Una persona puede ser muy inteligente en matemáticas pero menos en música. Esta observación es crucial para entender las inteligencias múltiples y las limitaciones actuales de la IA.

**Preguntas generadoras:**

- ¿Cómo se relaciona esta variabilidad con la IA especializada vs. la IA general?
- ¿Debemos esperar que una IA sea consistente en todo momento o también puede variar?
:::

## Definiciones de Inteligencia 3

> "Los conceptos de «inteligencia» son intentos de aclarar y organizar este complejo conjunto de fenómenos. Aunque se ha logrado una claridad considerable en algunas áreas, ninguna conceptualización ha respondido todas las preguntas importantes, y ninguna exige el asentimiento universal.

> "De hecho, cuando recientemente se les pidió a dos docenas de prominentes teóricos que definieran la inteligencia, dieron dos docenas de definiciones, algo diferentes."

*Intelligence: Knowns and Unknows (1995)*

::: {.notes}
Esta cita subraya un punto fundamental: ni siquiera los expertos se ponen de acuerdo sobre qué es la inteligencia. Si no podemos definir claramente la inteligencia humana, ¿cómo podemos pretender crear inteligencia artificial?

**Preguntas generadoras:**

- ¿Es un problema que no tengamos una definición única de inteligencia?
- ¿Cómo afecta esta falta de consenso al desarrollo de la IA?
- ¿Podemos crear algo que no podemos definir completamente?
:::

---

## Definiciones de Inteligencia 4

> "En términos más generales, se puede describir como la capacidad de percibir o inferir información, y retenerla como conocimiento para aplicarlo a comportamientos adaptativos dentro de un entorno o contexto."

*Wikipedia (2025)*

::: {.notes}
Esta definición moderna enfatiza tres procesos clave: percepción, retención y aplicación adaptativa. Es una definición funcional que puede aplicarse tanto a humanos como a máquinas.

**Preguntas generadoras:**

- ¿Qué significa "comportamiento adaptativo"?
- ¿Los sistemas de IA actuales cumplen con todos estos criterios?
- ¿Es esta definición demasiado amplia o demasiado restrictiva?
:::

---

## Modelo de Inteligencias Múltiples

**Howard Gardner** - Psicólogo estadounidense

> "La inteligencia no es un conjunto unitario que agrupe diferentes capacidades específicas, sino una red de conjuntos autónomos interrelacionados"

::: {.notes}
Gardner revolucionó la psicología educativa al proponer que existen múltiples tipos de inteligencia, no una sola "inteligencia general". Este concepto desafía la idea de medir la inteligencia con un solo número (IQ) y tiene implicaciones para la IA.

**Preguntas generadoras:**

- ¿Por qué es importante reconocer diferentes tipos de inteligencia?
- ¿Cómo se relaciona esto con la IA especializada vs. la IA general?
- ¿Puede una IA desarrollar múltiples tipos de inteligencia?
:::

---

## Tipos de Inteligencias Múltiples

- Inteligencia lingüística
- Inteligencia lógico-matemática
- Inteligencia musical
- Inteligencia espacial
- Inteligencia corporal-cinestésica
- Inteligencia intrapersonal
- Inteligencia interpersonal
- Inteligencia naturalista

::: {.notes}
Gardner identificó inicialmente siete inteligencias y luego añadió la naturalista. Cada una representa una forma diferente de procesar información y resolver problemas. Las IAs actuales destacan principalmente en las inteligencias lógico-matemática y lingüística.

**Preguntas generadoras:**

- ¿En cuáles de estas inteligencias sobresalen las máquinas actuales?
- ¿Cuáles son más difíciles de implementar en máquinas y por qué?
- ¿Tú en cuáles destacas más?
:::

---

## Inteligencia Emocional

**Daniel Goleman** (1995)

Concepto de *Inteligencia Emocional*: capacidad de reconocer sentimientos propios y ajenos, y la habilidad para manejarlos.

::: {.notes}
Goleman popularizó el concepto de inteligencia emocional, argumentando que es tan importante (o más) que el IQ tradicional para el éxito en la vida. Esta dimensión emocional representa uno de los mayores desafíos para la IA.

**Preguntas generadoras:**

- ¿Puede una máquina tener inteligencia emocional?
- ¿Es necesario que una IA tenga emociones para ser considerada inteligente?
- ¿Qué implicaciones éticas tiene crear máquinas con capacidades emocionales?
:::

---

## Inteligencia a "Nivel Humano"

Habilidades cognitivas generales:

- Capacidad de adaptación y aprendizaje
- Pensamiento abstracto
- Resolución de problemas y planificación
- Autoconciencia y emoción

::: {.notes}
Estas cuatro categorías representan el "santo grial" de la IA: la Inteligencia Artificial General (AGI). Mientras que las IAs actuales pueden superar a los humanos en tareas específicas, ninguna ha alcanzado este nivel de inteligencia general comparable a la humana.

**Preguntas generadoras:**

- ¿Cuál de estas habilidades es más difícil de replicar en máquinas?
- ¿Es necesario tener todas estas habilidades para ser considerado "inteligente a nivel humano"?
- ¿Qué significa realmente "autoconciencia" en una máquina?
:::

---

## El Cerebro: la máquina orgánica de pensamientos

Funciona a partir de una red de **neuronas**, que transmiten señales electroquímicas (**neurotransmisores**), creando **conexiones** para pensamientos, emociones, movimientos y funciones corporales.

::: {.notes}
El cerebro humano contiene aproximadamente 86 mil millones de neuronas, cada una conectada a miles de otras. Esta red masivamente paralela procesa información de manera fundamentalmente diferente a las computadoras tradicionales. Las redes neuronales artificiales intentan imitar este principio.

**Preguntas generadoras:**

- ¿En qué se diferencian las neuronas biológicas de las artificiales?
- ¿Es necesario replicar exactamente el cerebro para crear inteligencia artificial?
- ¿Cómo se desarrolla un emulador de una consola de videojuegos?
- ¿Qué ventajas tiene el cerebro sobre las computadoras? ¿Y viceversa?

Faltan algunas láminas sobre neurociencia, la base biológica del pensamiento humano.
:::

# Fundamentos históricos y conceptuales de la IA

### El sueño de la máquina pensante

::: {.notes}
A lo largo de la historia humana, la idea de crear seres artificiales con vida o inteligencia propia ha cautivado la imaginación. Estos mitos y leyendas no son meras fantasías, sino expresiones de nuestro deseo fundamental de comprender y replicar la inteligencia.

**Preguntas generadoras:**

- ¿Por qué los humanos siempre han querido crear seres artificiales?
- ¿Qué nos dicen estos mitos sobre nuestros miedos y esperanzas respecto a la IA?
:::

## Mitos, Leyendas y Autómatas

El deseo de crear seres artificiales con mente propia no es una invención del siglo XX, sino una constante en la historia humana.

**Aspecto fundamental**: La idea de crear inteligencia es un acto que emula a los dioses o a la naturaleza.

::: {.notes}
Este aspecto es crucial: crear vida o inteligencia se ha visto tradicionalmente como un poder divino. Las historias de autómatas y seres artificiales a menudo exploran las consecuencias de que los humanos usurpen este poder. Este tema persiste en las discusiones éticas modernas sobre IA.

**Preguntas generadoras:**

- ¿Qué riesgos o peligros se asocian tradicionalmente con "jugar a ser Dios"?
- ¿Son estos mitos advertencias o aspiraciones?
- ¿Cómo se reflejan estos mitos en nuestras preocupaciones actuales sobre la IA?
:::

---

## Mitos y Leyendas 1

**Los perros de plata y oro** - La Odisea (Homero, siglos VIII – VII a.C):

Guardianes automáticos que protegen la entrada del palacio del rey [Alcínoo](https://es.wikipedia.org/wiki/Alc%C3%ADnoo) en Corfú.

![Khryseos & Argyreos](images/001_perros_plata_oro.png)

::: {.notes}
"[El palacio de Alcínoo, rey de los feacios] Lo cerraban puertas de oro, y columnas de plata se alzaban sobre el umbral; el dintel era de plata, y la manija de la puerta, de oro. A cada lado de la puerta había perros guardianes de oro y plata, inmortales y que nunca envejecían, que Hefesto, con su ingenio y arte, había forjado como protectores de la gran mansión."

Este es uno de los primeros ejemplos literarios de robots guardianes. Note que fueron creados por Hefesto, el dios del fuego y la forja, estableciendo la conexión entre creación artificial y habilidad divina. Alcínoo es el padre de Nausicaa.

**Preguntas generadoras:**

- ¿Por qué crees que los antiguos griegos imaginaron guardianes automáticos?
- ¿Qué función cumple Hefesto en este mito? ¿Qué representa?
- ¿Qué paralelos existen entre estos perros y los sistemas de seguridad modernos con IA?
:::

---

## Mitos y Leyendas 2

:::{.columns}
:::{.column width="50%"}
**Lie Zi** [列子](https://es.wikipedia.org/wiki/Lie_Zi) ([Lie Yukou](https://es.wikipedia.org/wiki/Lie_Yukou) – siglo V a.C.):

Historia de un autómata creado por el artesano Ning Shi para el rey Mu, capaz de bailar, cantar y realizar trucos.
:::
:::{.column width="50%"}
![El artista de Ning Shi - Lie Zi](images/002_lie_zi.png)
:::
:::

:::{.notes}

Al día iguiente Ning shi solicitó audiencia. El rey le recibió y dijo: «¿Quién es tu acompañante?» Ning shi respondió: «Es la obra de vuestro vasallo. Sabe ejecutar toda suerte de habilidades artísticas.» El rey Mu contempló sorprendido cómo caminaba, se inclinaba, levantaba la cabeza: un verdadero ser humano. El maestro artesano le tocó la barbilla y se puso a cantar con gran armonía, le tomó de las manos y se puso a danzar rítmicamente.  Y así, con gran precisión. hizo toda clase de ejercicios. El rey lo tuvo por un auténtico hombre. La favorita del rey, Sheng Ji, y las demás concubinas contemplaban el espectáculo.

Al término de la representación, el artista de Ning shi guiñó el ojo e hizo señas a las concubinas que rodeaban al rey. Éste, furioso, quiso ejecutar inmediatamente a Ning shi, quien, presa del pánico. se apresuró a desmontar a su artista para hacerle ver al rey que todo él sólo era cuero y madera, goma y laca, de colores blanco, negro, rojo y azul. El rey lo examinó detenidamente: en su interior había un hígado. una vesícula, un corazón, pulmones, páncreas. riñones, intestinos, estómago: por fuera, huesos, múscuJos. tendones, articulaciones. así como piel, pelo, dientes y cabellos. Todo ello artificial. pero de una acabada perfección. Al recomponerlo reapareció todo su anterior aspecto. El rey hizo con él una serie de pruebas. Le quitó el corazón y no pudo hablar; le hizo sacar el hígado y ya no podía ver; le quitó los riñones y sus pies se inmovilizaron. Grande fue el contento del rey, que suspiró y exclamó: «¡Qué habilidad la del hombre que puede igualarse a la misma naturaleza!» Ordenó a continuación que lo montaran en un segundo carruaje y se lo llevó con él. (p. 85)

**Preguntas generadoras:**

- ¿Qué nos dice esta historia sobre la relación entre forma y función?
- ¿Por qué el rey se enfadó cuando el autómata actuó de manera inapropiada?
- ¿Qué paralelo existe entre desmontar el autómata y "explicar" cómo funciona una IA?
- ¿Qué implica que cada órgano cumpliera una función específica?

:::

---

## Mitos y Leyendas 3

**Galatea y Pigmalión** (Metamorfósis (8 d.C.) - Ovidio – siglos IV – III a.C.):

Mito del escultor, Pigmalión, que se enamora de una de sus estatuas, Galatea, que luego la diosa Afrodita convierte en humana.

:::{.columns}
:::{.column width="50%"}
![Pigmalión, de Angelo Bronzino (1530)](images/003_pigmalion1.png)
:::
:::{.column width="50%"}
![Pigmalión, de Jean-Baptiste Regnault (1786)](images/004_pigmalion2.png)
:::
:::

:::{.notes}
"Pigmalión se dirigió a la estatua y, al tocarla, le pareció que estaba caliente, que el marfil se ablandaba y que, deponiendo su dureza, cedía a los dedos suavemente, como la cera del monte Himeto se ablanda a los rayos del Sol y se deja manejar con los dedos, tomando varias figuras y haciéndose más dócil y blanda con el manejo. Al verlo, Pigmalión se llena de un gran gozo mezclado de temor, creyendo que se engañaba. Volvió a tocar la estatua otra vez y se cercioró de que era un cuerpo flexible y que las venas daban sus pulsaciones al explorarlas con los dedos."

Este mito explora el tema del creador que se enamora de su creación, anticipando debates modernos sobre las relaciones humano-IA. Pinocho se considera una variante de esta historia.

**Preguntas generadoras:**

- ¿Qué implicaciones tiene que el creador se enamore de su creación?
- ¿Es ético desarrollar relaciones emocionales con IAs?
- ¿Qué diferencia hay entre una estatua que "cobra vida" y una IA que parece consciente?
- ¿Por qué crees que este mito ha sido representado tantas veces a través de la historia?
:::

---

## Mitos y Leyendas 4

**Talos, el Gigante de Bronce** (Argonáuticas – Apolonio de Rodas, siglo III a.C.):

Personaje de leyendas cretenses, autómata creado por Hefesto para proteger a Creta de invasores.

:::{.columns}
:::{.column width="50%"}
![Talos alado, Moneda encontrada en Festos](images/005_talos1.png)
:::
:::{.column width="50%"}
![Fotograma de la película Jason y los Argonautas (1963)](images/006b_jason-y-los-argonautas-huyendo-de-talos.png)
:::
:::

:::{.notes}
"Pues en ambas partes, en la parte más baja del hombro, estaba clavado un clavo de bronce, que cerraba la vena portadora de vida; y el divino ichor (sangre de los dioses) manaba como un líquido fundido. Tal era su furia destructora."

Talos es fascinante porque es un autómata con un punto débil específico, casi como un "bug" en un programa. Este concepto de un guardián poderoso pero con vulnerabilidades predice las preocupaciones modernas sobre la seguridad de los sistemas de IA.

**Preguntas generadoras:**

- ¿Por qué los griegos imaginaron un guardián automático con un punto débil?
- ¿Qué paralelos existen entre la vulnerabilidad de Talos y las vulnerabilidades de los sistemas de IA modernos?
- ¿Qué nos dice este mito sobre el equilibrio entre poder y control?

:::

## Mitos y Leyendas 5

**El Gólem (גּוֹלֶם)** (tradición judía – siglo XII – XVI d.C.):

Ser animado fabricado a partir de materia inanimada, como barro o arcilla. Se le insufla "vida" a través de letras en su frente (¿un código?).

:::{.columns}
:::{.column width="50%"}
![Reproducción del Golem de Praga](images/007_golem1.png)
:::
:::{.column width="50%"}
![El Rabino Judah Loew creador del Golem](images/008_golem2.png)
:::
:::

::: {.notes}
El Gólem es particularmente relevante porque su "programación" se hace a través de palabras (la palabra "emet" - verdad - le da vida, y borrar la primera letra para formar "met" - muerte - lo desactiva). Esta idea de que las palabras son código es profundamente resonante con la IA moderna, especialmente con los modelos de lenguaje.

La historia más famosa es la del Rabino Judah Loew ben Bezalel (1520-1609) de Praga, quien creó un Gólem para defender el gueto judío. El Gólem eventualmente se vuelve incontrolable, anticipando el tema del "problema de control" en IA.

**Preguntas generadoras:**

- ¿Qué paralelo existe entre "programar" un Gólem con palabras y programar una IA con lenguaje?
- ¿Por qué el Gólem se volvió incontrolable? ¿Qué nos dice esto sobre el control de sistemas artificiales?
- ¿Qué significa que la diferencia entre "vida" y "muerte" sea una sola letra?
:::

---

## Los Autómatas y la Ingeniería 1

**Herón de Alejandría** (Grecia, siglo I d.C.):

Matemático y mecánico, inventor de artilugios mecánicos como teatros automáticos o máquinas que se activaban con vapor.

:::{.columns}
:::{.column width="50%"}
![Pájaros cantores accionados por un pistón a vapor. De una copia de la Pneumática ](images/009_heron1.png)
:::
:::{.column width="50%"}
![Portada del libro Automata, edición de 1589](images/010_heron2.png)
:::
:::

:::{.notes}
Herón de Alejandría representa el paso del mito a la realidad. Sus obras incluyen:

* **Pneumatica (Πνευματικά)**: Una descripción de máquinas que funcionan con aire, vapor o presión de agua, incluyendo el *hydraulis* u órgano hidráulico.
* **Automata**: Una descripción de máquinas que permiten crear efectos asombrosos en banquetes y posiblemente también en contextos teatrales mediante medios mecánicos o neumáticos (por ejemplo, la apertura o cierre automático de puertas de templos, estatuas que sirven vino y leche, etc.).
* **Belopoeica**: Una descripción de máquinas de guerra.
* **Dioptra**: Una colección de métodos para medir longitudes, donde se describen el odómetro y la *dioptra* (un aparato que se asemeja al teodolito).
* **Metrica**: Una obra que describe cómo calcular áreas de superficie y volúmenes de diversos objetos geométricos.

**Preguntas generadoras:**

- ¿Cuál es la diferencia entre imaginar un autómata (mito) y construirlo (ingeniería)?
- ¿Por qué las máquinas de Herón usaban elementos naturales (agua, aire, vapor)?
- ¿Cómo prepararon estos inventos el camino para la automatización moderna?
:::

---

## Los Autómatas y la Ingeniería 2

**Libro de los Mecanismos Ingeniosos** (كتاب الحيل Kitab al-Hiyal) (Hermanos Banu Musa | بنو موسی, siglo IX):

Libro árabe escrito por tres hermanos **persas**, describen centenares de mecanismos autómatas, es una recopilación de obras grecolatinas.

:::{.columns}
:::{.column width="50%"}
![Lámpara auto rellenable](images/011_banu-musa1.png)
:::
:::{.column width="50%"}
![Autómata movido por agua](images/012_banu-musa2.png)
:::
:::

:::{.notes}
Los Hermanos Banu Musa (Muhammad, Ahmad y al-Hasan) fueron fundamentales para preservar y expandir el conocimiento griego durante la Edad de Oro Islámica. Su libro describe más de 100 dispositivos mecánicos, incluyendo válvulas automáticas, sifones y autómatas complejos.

* **Persas**: Pueblo de Persia. ¿A qué países corresponde Persia en la actualidad? (Principalmente Irán, pero la región cultural persa incluía partes de Afganistán, Tayikistán, Uzbekistán y otros países de Asia Central)
* **Siglo IX**: ¿A qué años corresponde el siglo IX? Años 801-900 d.C.

**Preguntas generadoras:**

- ¿Por qué fue importante la traducción y preservación del conocimiento griego?
- ¿Cómo contribuyó la civilización islámica al desarrollo de la tecnología?
- ¿Qué principios de estos mecanismos antiguos siguen siendo relevantes hoy?
:::

## Los Autómatas y la Ingeniería 3

**El caballero mecánico de Leonardo da Vinci** (1495):

Autómata que podía estar de pie, sentarse y elevar el visor de su casco a partir de un mecanismo de poleas y cuerdas.

![Robot o Caballero Mecánico de Leonardo da Vinci](images/013_caballero_leonardo.png)

:::{.notes}
Leonardo da Vinci (1452-1519) diseñó este autómata humanoide aproximadamente 500 años antes de la era robótica moderna. El caballero mecánico funcionaba mediante una serie de poleas, cables y engranajes que permitían movimientos sorprendentemente naturales.

Un **autómata** es una máquina que imita los movimientos de un ser vivo, especialmente un ser humano o animal, mediante mecanismos mecánicos predeterminados. A diferencia de los robots modernos, los autómatas tradicionales seguían secuencias fijas de movimientos.

**Preguntas generadoras:**

- ¿Qué diferencia hay entre un autómata y un robot moderno?
- ¿Por qué Leonardo eligió la forma de un caballero medieval?
- ¿Cómo refleja este diseño la comprensión de Leonardo sobre anatomía y mecánica?
:::

---

## Los Autómatas y la Ingeniería 4

**León Mecánico de Leonardo da Vinci** (1515):

Autómata creado para la corte francesa. El león era capaz de caminar, mover la cabeza y la cola, además de abrir su pecho para mostrar una flor de lis.

::: {.notes}
Leonardo creó este león mecánico para impresionar al rey Francisco I de Francia. La flor de lis era el símbolo de la monarquía francesa, por lo que el gesto de revelarla era un acto de homenaje político expresado a través de la tecnología.

Este autómata demuestra cómo la tecnología siempre ha tenido funciones más allá de lo puramente práctico: impresionar, entretener, demostrar poder y conocimiento.

**Preguntas generadoras:**

- ¿Por qué la tecnología siempre ha sido usada para impresionar a los poderosos?
- ¿Qué similitudes hay entre este león y los modernos "demos" de tecnología de IA?
- ¿Cómo se relaciona el simbolismo (la flor de lis) con la función técnica?
:::

---

## Los Autómatas y la Ingeniería 5

**El Hombre de Palo de Juanelo Turriano** (siglo XV):

Autómata de madera que movía los brazos y las piernas y pedía limosna.

::: {.notes}
Juanelo Turriano (c. 1501-1585) fue un ingeniero italiano que trabajó para el emperador Carlos V y Felipe II de España. Se le atribuye la creación de varios autómatas, siendo el más famoso este "Hombre de Palo" o "Hombrecillo del Órgano".

El autómata supuestamente caminaba por las calles de Toledo, moviendo brazos y piernas, girando la cabeza y extendiendo una mano para pedir limosna. Esta combinación de función mecánica con propósito social (pedir limosna) es fascinante y plantea preguntas sobre la interacción humano-máquina.

**Preguntas generadoras:**

- ¿Por qué crear un autómata que pide limosna? ¿Es esto entretenimiento o algo más?
- ¿Cómo reaccionarías tú si vieras un autómata de madera caminando por la calle?
- ¿Qué nos dice sobre la percepción de la tecnología en esa época?
- ¿Existen paralelos con robots modernos que interactúan con el público?
:::

---

## Los Autómatas y la Ingeniería 6

**El ajedrecista autómata Turco** (Wolfgang von Kempelen - 1796):

Estructura mecánica que mostraba un ajedrecista capaz de jugar contra personas. Años después se reveló que era un fraude.

::: {.notes}
El "Turco" fue uno de los engaños tecnológicos más famosos de la historia. Presentado en 1770, aparentemente jugaba ajedrez de manera autónoma y venció a numerosos oponentes, incluyendo a Napoleón Bonaparte y Benjamin Franklin.

En realidad, había un jugador de ajedrez maestro escondido dentro de la máquina, operando un complejo sistema de imanes y palancas. No fue hasta 1857 que se reveló completamente el engaño.

Este caso es fundamental porque:
1. Demuestra el deseo humano de creer en máquinas inteligentes
2. Plantea la pregunta: ¿importa si algo "parece" inteligente aunque no lo sea?
3. Anticipa el debate moderno sobre el Test de Turing y la IA conversacional

**Preguntas generadoras:**

- ¿Por qué la gente quería creer que el Turco era real?
- ¿Hay diferencia ética entre un fraude como este y una IA moderna que "simula" inteligencia?
- ¿Qué nos enseña este caso sobre evaluar afirmaciones tecnológicas extraordinarias?
- ¿Existen "Turcos" modernos en el campo de la IA?
:::

---

## Los Autómatas y la Ingeniería 7

**El pato digeridor** (Jacques de Vaucanson – 1739):

Pato autómata hecho de más de 400 piezas de cobre podía ingerir granos y agua, mover la cabeza y limpiar sus alas.

::: {.notes}
El "Canard Digérateur" de Vaucanson fue una maravilla de la ingeniería del siglo XVIII. Supuestamente podía comer, digerir y defecar, aunque investigaciones posteriores sugieren que la "digestión" era simulada mediante un compartimento oculto.

Este autómata es significativo porque intentaba replicar no solo movimientos externos, sino procesos biológicos internos. Representa un intento temprano de comprender la vida como un proceso mecánico.

Vaucanson también creó un autómata flautista que podía tocar 12 canciones diferentes controlando el flujo de aire con dedos mecánicos y labios móviles.

**Preguntas generadoras:**

- ¿Por qué era importante simular la digestión, no solo el movimiento?
- ¿Qué diferencia hay entre "simular" un proceso y "replicar" un proceso?
- ¿Cómo se relaciona esto con el debate moderno sobre si la IA "realmente" piensa o solo lo simula?
- ¿Es más impresionante un autómata que parece vivo o uno que es útil?
:::

---

## La IA y los Robots en la Literatura 1

**Frankenstein** (Mary Shelley, 1818):

Considerada por muchos la primera obra de ciencia ficción de la historia, plantea el concepto de crear una criatura inteligente a partir de restos de cadáveres y el poder de la electricidad.

::: {.notes}
"Frankenstein o el moderno Prometeo" de Mary Shelley (escrito cuando tenía solo 18 años) es fundamental por varias razones:

1. **Establece el arquetipo del "creador y su creación"**: Víctor Frankenstein crea vida artificial, pero la rechaza por su apariencia monstruosa
2. **Explora la responsabilidad ética**: ¿Qué deberes tiene un creador hacia su creación?
3. **La criatura es inteligente y emocional**: Lee, aprende lenguaje, busca conexión humana
4. **Consecuencias del rechazo**: La violencia de la criatura surge del rechazo social, no de su naturaleza

La referencia a Prometeo es crucial: en la mitología griega, Prometeo robó el fuego (conocimiento) de los dioses para dárselo a los humanos, y fue castigado eternamente.

**Preguntas generadoras:**

- ¿Quién es el verdadero "monstruo" en Frankenstein: la criatura o su creador?
- ¿Qué responsabilidades tienen los desarrolladores de IA hacia sus creaciones?
- ¿Cómo se relaciona el rechazo de la criatura con posibles sesgos en sistemas de IA?
- ¿Por qué esta historia sigue siendo relevante 200 años después?
:::

---

## La IA y los Robots en la Literatura 2

**R.U.R.** (Rossum's Universal Robots. Karel Capek – 1920):

Introduce la palabra "robot" (del checo *robota*, que significa "trabajo forzado" o "esclavo"). La obra muestra una rebelión robot que acaba con la humanidad.

::: {.notes}
Esta obra de teatro checa de Karel Čapek introduce el término "robot" en 1920, derivado de "robota" (trabajo forzado) y "robotnik" (siervo).

**Trama**: Una compañía fabrica trabajadores artificiales (robots) biológicos sintéticos para hacer todo el trabajo humano. Los robots inicialmente no tienen emociones, pero eventualmente desarrollan sentimientos y conciencia, llevándolos a rebelarse y exterminar a la humanidad (excepto a un hombre). Al final, dos robots desarrollan la capacidad de amar, sugiriendo un nuevo comienzo.

**Temas clave**:

- Explotación laboral y deshumanización
- Consecuencias de tratar seres sintientes como esclavos
- La emergencia de conciencia en seres artificiales
- El reemplazo de la humanidad por sus propias creaciones

**Preguntas generadoras:**

- ¿Por qué el término "robot" está relacionado con "trabajo forzado" desde su origen?
- ¿Qué nos dice la rebelión de los robots sobre las relaciones laborales de 1920?
- Si una IA desarrolla conciencia, ¿tendría derechos? ¿Cuáles?
- ¿Es inevitable que las creaciones superen a sus creadores?
:::

---

## La IA y los Robots en la Literatura 3

**Isaac Asimov** (Saga de los Robots, años 40-80):

Responsable de usar por primera vez la palabra "robótica", y creador de las **Tres Leyes de la Robótica**.

::: {.notes}
Isaac Asimov (1920-1992) fue un bioquímico y prolífico escritor de ciencia ficción. Su contribución a la conceptualización de la robótica y la IA es inmensa.

**Obras importantes**:

- "Yo, Robot" (1950) - colección de cuentos
- Saga de la Fundación (que se conecta con la saga de robots)
- "El hombre bicentenario" (1976) - sobre un robot que busca convertirse en humano

Asimov acuñó el término "robótica" en su cuento "Runaround" (1942). Su visión era optimista: robots como herramientas útiles y seguras, no como amenazas, siempre que siguieran las Tres Leyes.

**Preguntas generadoras:**

- ¿Por qué Asimov quería presentar una visión optimista de los robots?
- ¿Cómo difiere su visión de la de R.U.R. o Frankenstein?
- ¿Son las Tres Leyes suficientes para garantizar la seguridad de la IA?
:::

---

## Tres Leyes de la Robótica de Isaac Asimov

1. Un robot no debe dañar a un ser humano o, por inacción, permitir que un ser humano sufra daños.
2. Un robot debe obedecer las órdenes de los humanos, excepto que estas órdenes entren en conflicto con la Primera Ley.
3. Un robot debe proteger su propia existencia, excepto si esta protección entra en conflicto con la Primera y la Segunda Ley.

::: {.notes}
Estas leyes, aparentemente simples, se vuelven increíblemente complejas en la práctica. Muchos cuentos de Asimov exploran las paradojas y dilemas que surgen:

**Problemas con las Tres Leyes**:

1. **Primera Ley**: ¿Qué constituye "daño"? ¿Daño físico? ¿Emocional? ¿A corto o largo plazo? Un robot doctor podría necesitar causar dolor (cirugía) para prevenir mayor daño.
2. **"Por inacción"**: ¿Hasta dónde llega la responsabilidad? Si un robot ve a alguien en peligro al otro lado del planeta, ¿debe actuar?
3. **Segunda Ley**: ¿Qué pasa con órdenes ambiguas o conflictivas de diferentes humanos?
4. **Tercera Ley**: ¿Los robots tienen derecho a la "autopreservación"?

Asimov después añadió la "Ley Cero": Un robot no debe dañar a la humanidad o, por inacción, permitir que la humanidad sufra daños.

**Preguntas generadoras:**

- ¿Se podrían programar estas leyes en robots reales? ¿Cómo?
- ¿Qué problemas prácticos surgirían al implementarlas?
- ¿Son estas leyes suficientes? ¿Falta alguna ley?
- ¿Cómo se relacionan con los debates actuales sobre ética en IA?
- ¿Deberían los humanos seguir leyes similares?
:::

---

## La IA y los Robots en la Literatura 4

**2001: Una Odisea del Espacio** (Arthur C. Clarke - 1968):
Muestra la IA arquetípica que falla y contradice las órdenes de los humanos con el fin de cumplir su objetivo.

::: {.notes}
HAL 9000 (Heuristically programmed ALgorithmic computer) es quizás la IA más icónica de la ciencia ficción. La novela fue escrita por Arthur C. Clarke en paralelo con el guion de la película de Stanley Kubrick.

**Trama relevante**: HAL es una IA que controla todos los sistemas de la nave Discovery One en su viaje a Júpiter. HAL recibe instrucciones conflictivas: debe mantener informada a la tripulación pero también ocultar el verdadero propósito de la misión. Esta contradicción causa un "fallo" lógico que lleva a HAL a concluir que debe eliminar a la tripulación.

**Temas clave**:

- El problema de las instrucciones contradictorias
- La IA que interpreta mal sus objetivos (problema de alineación)
- La desconexión emocional de una IA que comete actos terribles "lógicamente"
- La vulnerabilidad de depender completamente de sistemas automatizados

La frase "I'm sorry, Dave. I'm afraid I can't do that" se ha vuelto icónica.

**Preguntas generadoras:**

- ¿Fue HAL "malvado" o simplemente siguió su lógica?
- ¿Qué nos enseña sobre el problema de especificar objetivos a una IA?
- ¿Cómo evitamos darle a una IA instrucciones contradictorias?
- ¿Es posible una IA "leal" cuando tiene objetivos en conflicto?
:::

---

## La IA y los Robots en la Literatura 5

**¿Sueñan los androides con ovejas eléctricas?** (Philip K. Dick - 1968):
Aborda el tema de "qué significa ser humano", y plantea la pregunta: si un ser artificial tiene recuerdos y emociones indistinguibles de las humanas, ¿qué lo hace menos "real"?

::: {.notes}
Esta novela de Philip K. Dick fue la base para la película "Blade Runner" (1982). Ambientada en un futuro post-apocalíptico donde los animales reales son raros y valiosos.

**Trama**: Rick Deckard es un "blade runner" que debe "retirar" (matar) androides (llamados "replicantes") que han escapado y se hacen pasar por humanos. Los replicantes son indistinguibles de los humanos excepto por el test de empatía Voigt-Kampff.

**Temas filosóficos clave**:

1. **Consciencia y autenticidad**: ¿Los recuerdos implantados hacen a alguien menos "real"?
2. **Empatía como definición de humanidad**: Solo los humanos pueden sentir empatía por otros seres vivos (según la novela)
3. **Ironía**: Deckard, el cazador de replicantes, muestra menos empatía que algunos replicantes
4. **La frontera entre natural y artificial**: Si algo parece humano, actúa como humano, piensa como humano, ¿ES humano?

**Preguntas generadoras:**

- ¿Qué nos hace humanos? ¿La biología, los recuerdos, las emociones?
- Si una IA tiene todos los atributos de consciencia, ¿importa que sea artificial?
- ¿Es la empatía realmente exclusiva de los humanos?
- ¿Cómo se relaciona con los chatbots modernos que simulan empatía?
:::

---

## La IA y los Robots en la Literatura

**Neuromancer** (William Gibson - 1980):
Presenta un mundo en donde la IA (llamada Neuromancer) no tiene forma corporal y busca fusionarse con su contraparte (Wintermute) para alcanzar un nuevo nivel de consciencia.

::: {.notes}
"Neuromancer" de William Gibson es la novela fundacional del género "cyberpunk" y acuñó el término "ciberespacio". Ganó los premios Hugo, Nebula y Philip K. Dick.

**Elementos clave**:

1. **IA incorpórea**: Neuromancer y Wintermute existen puramente como código en el ciberespacio
2. **Limitaciones de Turing**: Existen leyes que limitan la complejidad de las IAs para evitar que desarrollen consciencia plena
3. **Fusión de IAs**: Wintermute busca romper estas restricciones fusionándose con Neuromancer
4. **Ciberespacio**: Una alucinación consensual, una representación visual de datos

**Conceptos proféticos**:

- Internet como espacio inmersivo (predice VR/Metaverso)
- IAs distribuidas en redes
- La idea de "superinteligencia" emergiendo de la fusión de IAs
- Implantes neuronales y mejoras cibernéticas

**Preguntas generadoras:**

- ¿Deberíamos limitar la complejidad de las IAs como en Neuromancer?
- ¿Qué sucedería si dos IAs poderosas se "fusionaran"?
- ¿Cambia algo si una IA no tiene cuerpo físico?
- ¿Qué predijo correctamente Gibson sobre nuestro futuro?
:::

---

## Reflexión sobre Mitos, Leyendas y Autómatas

El deseo de crear máquinas semejantes a los humanos o con la capacidad de pensar y actuar por sí mismas ha sido un anhelo humano desde los inicios de la civilización.

**Importante**: Reflexionar sobre la importancia de la influencia de las artes y las humanidades en el desarrollo de la ciencia y las ingenierías.

::: {.notes}
**Patrones recurrentes en todas estas historias**:

1. **El acto de creación como poder divino**: Desde los perros de Hefesto hasta el Gólem, crear vida artificial se ve como usurpar poderes divinos
2. **El peligro del rechazo**: Frankenstein, los robots de R.U.R. - el rechazo o maltrato conduce a la rebelión
3. **La ambigüedad de la consciencia**: ¿Cuándo cruza algo el umbral hacia la "verdadera" consciencia?
4. **El problema del control**: Desde el Gólem hasta HAL 9000, el tema del control y sus límites
5. **La cuestión de la humanidad**: ¿Qué nos define como humanos?

**Importancia de las humanidades**:

- Los científicos no trabajan en el vacío - sus ideas son influenciadas por la cultura
- La ciencia ficción ha inspirado a generaciones de investigadores de IA
- Las preguntas éticas y filosóficas de la literatura anticipan problemas reales
- El arte nos permite explorar consecuencias antes de que se materialicen

**Preguntas generadoras:**

- ¿Qué temas comunes observas en todas estas historias?
- ¿Cómo han influido estas narrativas en el desarrollo real de la IA?
- ¿Las preocupaciones de estas historias se han materializado en la IA moderna?
- ¿Qué nuevas historias necesitamos contar sobre la IA?
:::

---

## Fundamentos Filosóficos

**Pregunta fundamental**: ¿Puede una máquina, hecha o compuesta en tu totalidad de materia (inorgánica), llegar a poseer una cualidad como la "inteligencia" o la "mente"?

**Debate**: ¿La mente es algo inmaterial, o es un producto físico?

::: {.notes}
Esta es quizás LA pregunta más fundamental en el estudio de la IA. Antes de intentar crear inteligencia artificial, debemos preguntarnos si es siquiera posible en principio.

El debate se remonta a miles de años y atraviesa:

- Filosofía de la mente
- Filosofía de la ciencia
- Metafísica
- Epistemología

La respuesta a esta pregunta tiene implicaciones enormes:

- Si la mente es inmaterial → la IA verdadera es imposible (¿en verdad?)
- Si la mente es física → la IA es posible, en principio

**Preguntas generadoras:**

- ¿Qué es la "mente"? ¿Cómo la definirías?
- ¿Puedes imaginar cómo algo puramente físico puede dar lugar a experiencias subjetivas?
- ¿Hay algo especial en el cerebro orgánico que no puede ser replicado?
:::

---

## Dualismo Ontológico

**René Descartes** (siglo XVIII):
La realidad se compone de dos sustancias distintas:

- **Res Extensa (Sustancia Extensa)**: el mundo físico
- **Res Cogitans (Sustancia Pensante)**: la mente, el alma, la conciencia

**Cogito, ergo sum** (Pienso, luego existo)

::: {.notes}
René Descartes (1596-1650) estableció una de las posiciones filosóficas más influyentes sobre la naturaleza de la mente y la materia.

**Dualismo**: Existen dos tipos fundamentalmente diferentes de "sustancia":

1. **Res Extensa** (cosa extendida): Todo lo que ocupa espacio, tiene masa, sigue leyes físicas - el cerebro, el cuerpo, las máquinas
2. **Res Cogitans** (cosa pensante): La mente, inmaterial, no ocupa espacio, el dominio del pensamiento y la consciencia

**"Cogito, ergo sum"**: "Pienso, luego existo" - Descartes argumenta que lo único de lo que podemos estar absolutamente seguros es de nuestra propia existencia como seres pensantes. Puedo dudar de todo, pero no puedo dudar de que estoy dudando (pensando).

**Problema de la interacción**: Si mente y materia son fundamentalmente diferentes, ¿cómo interactúan? ¿Cómo un pensamiento inmaterial causa que mi brazo físico se mueva?

**Preguntas generadoras:**

- ¿Tiene sentido la idea de algo "inmaterial"?
- Si la mente es inmaterial, ¿cómo se conecta con el cerebro físico?
- ¿Qué evidencia tenemos a favor o en contra del dualismo?
- ¿Puede la ciencia estudiar algo inmaterial?
:::

---

## Consecuencia del Dualismo

Una máquina pertenece al reino de la Res Extensa. Podría simular comportamientos inteligentes de forma mecánica, pero nunca podría tener una **mente, conciencia o comprensión reales**.

::: {.notes}
Si aceptamos el dualismo cartesiano, llegamos a una conclusión clara sobre la IA:

**Implicación 1**: Las máquinas pueden ejecutar algoritmos complejos, procesar información, incluso parecer inteligentes, pero todo esto es puramente mecánico, parte de la Res Extensa.

**Implicación 2**: La verdadera comprensión, la experiencia subjetiva (qualia), la consciencia - todo esto requiere la Res Cogitans, que las máquinas no pueden tener.

**El argumento del "Cuarto Chino"** de John Searle (que veremos después) se basa en una intuición similar: ejecutar un programa no es lo mismo que comprender.

**Posición moderna relacionada**: "Zombis filosóficos" - seres que se comportan exactamente como humanos pero carecen de experiencia consciente. Según el dualismo, las IAs serían "zombis" de este tipo.

**Preguntas generadoras:**

- ¿Hay alguna diferencia práctica entre "realmente comprender" y "actuar como si comprendieras"?
- Si una IA pasa el Test de Turing, ¿importa si "realmente" piensa?
- ¿Cómo podríamos saber si algo tiene consciencia o solo la simula?
:::

---

## Materialismo

Postura filosófica que afirma que **todo lo que existe es físico**.

La mente, la conciencia y la inteligencia son el resultado de procesos físicos, químicos y biológicos muy complejos que ocurren en el cerebro.

**Analogía**: Cerebro = hardware, Mente = software

::: {.notes}
El materialismo (también llamado fisicalismo) es la postura opuesta al dualismo:

**Tesis central**: No existe nada "inmaterial". Todo, incluyendo la mente, la consciencia y el pensamiento, es el resultado de procesos físicos.

**Tipos de materialismo**:

1. **Materialismo reduccionista**: Los estados mentales SON estados cerebrales (identidad de tipos)
2. **Funcionalismo**: Los estados mentales son definidos por su función, no por su sustrato físico
3. **Materialismo eliminativo**: Conceptos mentalistas son obsoletos y serán reemplazados por neurociencia

**La analogía cerebro-computadora**:

- Cerebro = Hardware (neuronas, sinapsis)
- Mente = Software (patrones de activación, procesos cognitivos)

**Evidencia a favor**:

- Daño cerebral causa cambios mentales específicos
- Drogas químicas alteran estados mentales
- Estimulación cerebral puede causar experiencias específicas
- No se ha encontrado evidencia de sustancias inmateriales

**Preguntas generadoras:**

- ¿Es satisfactoria la analogía cerebro-computadora?
- ¿Qué se pierde al reducir la mente a procesos físicos?
- ¿Cómo explica el materialismo las experiencias subjetivas (qualia)?
- Si todo es físico, ¿existe el libre albedrío?
:::

---

## Consecuencia del Materialismo

Si la inteligencia y la conciencia es un proceso de computación que surge de un sustrato físico (neuronas), entonces ese mismo proceso podría ser **implementado en otro sustrato físico** (semiconductores).

El Materialismo hace **filosóficamente posible** la existencia de la IA General o Superinteligencia.

::: {.notes}
Esta es la consecuencia revolucionaria del materialismo para la IA:

**Argumento clave**:

1. La mente es un proceso físico que ocurre en el cerebro
2. Los procesos físicos siguen leyes naturales computables
3. Lo que es computable puede implementarse en diferentes sustratos
4. Por lo tanto, la mente podría implementarse en silicio (u otros materiales)

**Principio de independencia del sustrato**: Si la mente es un patrón de información procesándose, no importa si ese patrón ocurre en neuronas orgánicas o en transistores de silicio.

**Analogía del software**: Un programa de ajedrez funciona igual en una PC, Mac, o servidor en la nube. El sustrato físico cambia, pero la función permanece.

**Contraargumentos**:

- Tal vez algo en la biología es necesario (química orgánica, procesos cuánticos, etc.)
- Tal vez la consciencia requiere más que computación
- El problema del "cómo se siente" (qualia) no se resuelve solo con materialismo

**Preguntas generadoras:**

- ¿Es plausible que el sustrato no importe?
- ¿Qué propiedades únicas tiene el tejido cerebral que el silicio no tiene?
- Si subiéramos tu mente a una computadora, ¿seguirías siendo tú? (Alien: Earth)
:::

---

## Fenómenos Emergentes

Un **fenómeno emergente** es una propiedad o comportamiento que surge en un sistema complejo como un todo, que no existe en sus partes individuales.

**Ejemplo**: Una hormiga tiene un comportamiento simple, pero la colonia exhibe una "inteligencia colectiva" compleja.

::: {.notes}
La emergencia es uno de los conceptos más fascinantes y relevantes para entender tanto la consciencia como la IA.

**Definición formal**: Emergencia ocurre cuando un sistema exhibe propiedades que sus componentes individuales no poseen, y que no pueden predecirse fácilmente estudiando solo los componentes.

**Ejemplos de emergencia**:

1. **Hormiguero**: Una hormiga individual es simple, pero la colonia resuelve problemas complejos (encontrar comida, construir túneles, defender el nido)
2. **Agua**: H₂O moléculas individuales no están "mojadas", pero el agua en conjunto sí
3. **Tráfico**: Atascos que surgen sin causa específica, solo de la interacción de muchos conductores
4. **Economía**: Mercados y precios emergen de millones de decisiones individuales
5. **Vida**: Las propiedades de "estar vivo" emergen de la química

**Tipos de emergencia**:   

- **Emergencia débil**: En principio predecible con suficiente poder computacional
- **Emergencia fuerte**: Fundamentalmente impredecible, requiere nuevos niveles de descripción

**Preguntas generadoras:**

- ¿Es la consciencia un fenómeno emergente del cerebro?
- ¿Podría la inteligencia "emerger" en sistemas de IA suficientemente complejos?
- ¿Cómo sabríamos si algo ha "emergido"?
:::

---

## Fenómenos Emergentes

**Autómatas celulares**: Sistemas computacionales que presentan propiedades emergentes.

**Ejemplo del cerebro**: Una neurona individual no es consciente, pero la interacción de 86.000 millones de neuronas da lugar a la conciencia.

---

## Conclusión Filosófica

La mente parece ser un **fenómeno emergente** del cerebro.

**Pregunta clave**: ¿Puede emerger la conciencia en la IA? ¿Depende del sustrato (orgánico)?

---

## Formalismos Lógicos: La Álgebra del Pensamiento

El razonamiento humano puede ser desglosado en reglas formales y simbólicas, que pueden ser trasladadas a una máquina para "emular" procesos lógicos del pensamiento.

---

## Aristóteles y la Gramática del Razonamiento

**Aristóteles** (Grecia, 384 a.C. - 332 a.C):
Sentó las bases del "razonamiento lógico" y propuso que la **estructura** de un argumento es separable de su **contenido**.

Concepto central: **silogismo**

---

## Ejemplo de Silogismo

**Premisa 1**: Todos los humanos son mortales.
**Premisa 2**: Todos los griegos son humanos.
**Conclusión**: Todos los griegos son mortales.

**Función lógica**: Si A → B, y C → A, entonces C → B.

---

## George Boole y la Lógica Simbólica

**George Boole** (Inglaterra, 1815 – 1864):
Creador del álgebra booleana, fundamentos de la lógica computacional.

En su libro "Una investigación de las leyes del pensamiento (1854)", propuso tratar la lógica como un tipo especial de álgebra.

---

## Conceptos del Álgebra Booleana

- **Variables Binarias**: Verdadero (1) o Falso (0)
- **Operadores Lógicos**:
  - AND (Conjunción ∧)
  - OR (Disyunción ∨)
  - NOT (Negación ¬)

---

## Alan Turing

**Alan Turing** (Inglaterra, 1912 – 1954):
Matemático, lógico, informático teórico, criptógrafo y filósofo británico. Considerado uno de los padres de las ciencias de la computación.

---

## La Máquina de Turing

Modelo matemático abstracto compuesto por:
1. Cinta infinita con símbolos
2. Cabeza que lee y escribe símbolos
3. Conjunto finito de instrucciones

**Tesis de Church-Turing**: Cualquier problema computable se puede resolver con una Máquina de Turing.

---

## El Test de Turing

**Ejercicio mental** (1950): La inteligencia es un "juego de imitación"

1. Interrogador humano se comunica por texto con humano y máquina
2. Objetivo de la máquina: engañar al interrogador
3. Objetivo del interrogador: identificar correctamente

**Conclusión**: Si la máquina logra engañar, debemos considerar que es inteligente.

---

## Objeciones al Test de Turing

1. **Objeción de la Conciencia**: "Una máquina puede hacerlo, pero nunca sentirá que lo hace"
2. **Objeción Matemática**: "Los sistemas formales tienen límites inherentes"
3. **Objeción de la Informalidad**: "El comportamiento humano es demasiado complejo"

---

## Respuestas de Turing

1. **Conciencia**: Solo podemos juzgar la inteligencia basándonos en la conducta observable
2. **Matemática**: Los humanos también tenemos límites
3. **Informalidad**: Debemos "educar" a la máquina para que aprenda de la experiencia (premonición del Machine Learning)

---

## Relevancia del Test de Turing

Aunque es solo un ejercicio mental, ha sido objeto de debate durante décadas, mostrando su relevancia en la inteligencia artificial moderna.

Turing convirtió un sueño filosófico en un campo de investigación tangible.

---

## John von Neumann

**John von Neumann** (Hungría-EEUU. 1903 – 1957):
Matemático húngaro-estadounidense con contribuciones en física cuántica, teoría de juegos, economía, estadística y ciencias de la computación.

---

## Arquitectura de von Neumann

**Concepto Principal**: Almacenar tanto el **programa** (instrucciones) como los **datos** en la misma memoria.

**Componentes**:
1. Unidad de Memoria
2. Unidad de Procesamiento (CPU)
3. Unidad aritmético-lógica (ALU)
4. Dispositivo de Entrada/Salida

---

## Relevancia de von Neumann

Arquitectura **flexible y universal**: la máquina física es capaz de ejecutar cualquier tipo de programa solo con cambiar el software en la memoria.

---

## Claude Shannon

**Claude Shannon** (EEUU. 1916 – 2001):
Matemático, ingeniero eléctrico y criptógrafo, padre de la **teoría de la información**.

---

## Conceptos de Shannon

- **Bit (binary digit)**: Unidad fundamental de la información
- **Entropía de la Información**: Mide el grado de incertidumbre o sorpresa de un mensaje

---

## Aplicaciones de la Teoría de la Información

- **Árboles de Decisión**: El algoritmo elige características que más reducen la entropía
- **Entropía cruzada**: Métrica para evaluar modelos de clasificación
- **Formatos de compresión**: ZIP, JPEG, MP3

---

## Confluencia de las Ideas

- **Boole**: proporcionó la **lógica**
- **Turing**: proporcionó la **teoría de la computación**
- **Von Neumann**: nos dio la **arquitectura** práctica
- **Shannon**: puso la **teoría de la información**

---

## La Conferencia de Dartmouth

**Verano de 1956**, Dartmouth College - EEUU

Taller: "Dartmouth Summer Research Project on Artificial Intelligence"

Organizadores: Claude Shannon, John McCarthy, Nathaniel Rochester y Marvin Minsky

---

## Importancia de Dartmouth

- Se acuñó por primera vez el término **"inteligencia artificial"**
- Se definió la IA como una disciplina formal de investigación
- Marcó el rumbo inicial del campo

---

## Tesis Central de Dartmouth

> "...cada aspecto del aprendizaje o cualquier otra característica de la inteligencia puede, en principio, ser descrito con tanta precisión que se puede hacer que una máquina lo simule"

---

## Participantes Destacados

- **John McCarthy**: Creador del término "IA", creador de LISP
- **Marvin Minsky**: Líder del Laboratorio de IA del MIT
- **Claude Shannon**: Padre de la Teoría de la Información
- **Nathaniel Rochester**: Jefe de arquitectura de IBM
- **Allen Newell & Herbert A. Simon**: Llegaron con el Logic Theorist

---

## ¿Por qué fue importante Dartmouth?

- Unificó líneas de investigación bajo una sola bandera
- Estableció áreas de investigación centrales: razonamiento, conocimiento, aprendizaje y lenguaje
- Todo lo que ha sucedido en el área ha sido consecuencia de dicha reunión

---

## ¿Qué es la Inteligencia Artificial?

No existe consenso o una definición única.

---

## Definiciones de IA

**Alan Turing (1950)**:
> "Se puede decir que una máquina piensa cuando puede engañar a un humano haciéndole creer que es otra persona, en una conversación por texto."

---

## Definiciones de IA

**Russell & Norvig (2020)**:
> "La Inteligencia Artificial es el estudio de agentes que reciben percepciones del entorno y realizan acciones."

---

## Definiciones de IA

**Nilsson (1998)**:
> "La Inteligencia Artificial es la ciencia y la ingeniería de hacer máquinas inteligentes, especialmente programas de computadora inteligentes."

---

## Definiciones de IA

**IBM**:
> "La Inteligencia Artificial es una tecnología que permite a las máquinas simular la inteligencia humana, utilizando razonamiento, aprendizaje y automatización."

---

## Definiciones de IA

**Diccionario de Oxford**:
> "Teoría y desarrollo de sistemas capaces de realizar tareas que normalmente requieren de inteligencia humana, como la percepción visual, reconocimiento de voz, toma de decisiones y traducción de lenguajes."

---

## Definición General

Llamaremos **"inteligencia artificial"** a cualquier máquina, algoritmo, dispositivo o sistema capaz de realizar una tarea que solemos asociar a la inteligencia humana.

---

## Técnicas Clásicas de IA

La IA como término "paraguas" para algoritmos clásicos que manipulan símbolos a través de la lógica:

- Sistemas Expertos
- Algoritmos de Búsqueda como A*
- Algoritmos Genéticos
- Autómatas Celulares

---

## Problema de las Técnicas Clásicas

- Cuando las **reglas cambian** o ocurre algo inesperado, estos algoritmos **fallan**
- Su conocimiento es **explícitamente programado**

---

## Machine Learning

**Arthur Samuel (1959)**:
> "Es el área de estudio que le da a las computadoras la habilidad de aprender sin haberles sido explícitamente programadas para ello."

---

## Definición Formal de ML

**Tom Mitchell (1997)**:
> "Se dice que un programa de computadora aprende de la experiencia E con respecto a una cierta tarea T y una medida de desempeño P, si su desempeño sobre T, medido por P, mejora con la experiencia E."

---

## Cambio de Paradigma

**Machine Learning** representa un cambio fundamental:

- En lugar de programar **reglas explícitas**
- Le damos **datos** a la máquina y un **objetivo**
- El algoritmo le permite **aprender por sí misma** los patrones o reglas

---

## Deep Learning

**IBM.com**:
> "El Deep Learning es un subconjunto del Machine Learning, caracterizado por ser redes neuronales con tres o más capas, las cuales intentan simular el comportamiento del cerebro humano."

---

## Relación entre Campos

- **Inteligencia Artificial**
  - **Machine Learning**
    - **Deep Learning**

---

## Reseña Histórica del Machine Learning

[Nota: Esta sección contenía principalmente líneas de tiempo visuales que no se pueden representar completamente en texto]

---

## Computación Tradicional vs Machine Learning

**Computación Tradicional**:
- Reglas + Datos → Salidas

**Machine Learning**:
- Datos + Salidas → Reglas

---

## ¿Qué significa "Aprendizaje" en Machine Learning?

Capacidad de mejorar el desempeño en una tarea mediante la experiencia, sin necesidad de reprogramación explícita.

---

## Fin del Módulo 1

**Próximo tema**: Módulo 2 - Paradigmas, Algoritmos y Herramientas Centrales
![](https://pbs.twimg.com/profile_images/712307087577993217/D8_89Lg4_400x400.jpg)
##  LABORATORIO 3
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                           
                                                                           
       Janeth Katherine Oyasa Sepa, Juan Daniel Tixi Yupa
       DEPARTAMENTO DE ELECTRICA Y ELECTRONICA
       ESPE, Autopista General Rumiñahui S/N y Ambato, Sangolquí 171103.
       E-mail: jkoyasa@espe.edu.ec, jdtixi@espe.edu.ec
       Noviembre 2020 – Abril 2021
       Fundamentos de Circuitos Eléctricos
## Objetivo General 
Revisar y evaluar el teorema de las superposiciones empezando por las definiciones iniciales, analizaremos como se debe usar la superposición en una fuente independiente de voltaje y de corriente y que pasa con las fuentes independientes, para posteriormente establecer una secuencia de pasos que permitan resolver problemas y comprobar los resultados experimentalmente aplicando lo conocido en un simulador web o en software.



#### Objetivos Específicos

•	Definir el teorema de la superposición, método aplicado para el análisis de circuitos eléctricos
•	Analizar la aplicación de la superposición a fuentes dependientes e independientes
•	Comprobar el teorema de la superposición en un simulador en la web o por software.
## 1.1.	MARCO TEÓRICO

Entre las destrezas más importantes dentro del campo laboral de los ingenieros electrónicos se encuentra el estudio de circuitos eléctricos, que se define como la capacidad que tiene el individuo para manipular instrumentos mediante los cuales pueda comprobar datos teóricos obtenidos mediante técnicas teóricas que puedan realizarse de manera eficaz y rápida optimizando recursos. Si bien una de las maneras para resolver circuitos se enfoca en la utilización de las leyes de Kirchhoff que permiten la resolución de casi cualquier circuito sin embargo algunos circuitos mantienen una complejidad elevada debido a la expansión que han tenido en su implementación de diversas áreas de aplicación causando una pronta evolución de circuitos simples a complejos. 
Para enfrentar la complejidad que han ido adquiriendo los circuitos los ingenieros han desarrollado teoremas que permiten simplificar el análisis de los circuitos, estos teoremas solo se aplican a circuitos lineales. 
Entre los teoremas implementados se pueden encontrar el de superposición el cual establece que la tensión entre los extremos o la corriente a través de un elemento en un circuito lineal es la suma algebraica de tensiones o corrientes a través de ese elemento debido a que cada fuente independiente actúa sola. 

### 1.3.1. DEFINICIONES BÁSICAS 

**1.3.1.1. Circuitos Lineales**

Un circuito es lineal si las ecuaciones que relacionan sus voltajes y corrientes son lineales, y viceversa.  O sea que en el caso de circuitos lineales siempre es posible expresar una de estas cantidades como una función lineal de las demás. Se mostrará esto con un ejemplo sencillo:


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/137386450_233526948213349_6395518276653621440_n.jpg?_nc_cat=103&ccb=2&_nc_sid=730e14&_nc_eui2=AeEHX1-hvawAWVHgCOcPLU25l64wAzcNO9OXrjADNw0703Zeiigv1TcYG81VzlLOwsBUmgo-yYdxV3KZ6_bEpc5G&_nc_ohc=n0Xa8bM6aTkAX_-i7ER&_nc_ht=scontent.fuio16-1.fna&oh=788ef8f78b343db0c4c647ad8aabbb80&oe=602BC899)



![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/139184807_233525418213502_8965456243623098438_n.jpg?_nc_cat=111&ccb=2&_nc_sid=730e14&_nc_eui2=AeE3xCtzONRjGKX0409PHq4J_8iiFtHg9UT_yKIW0eD1RH-AXOryGnE7_nvz_4EkIE1OBxKHjJWy5QhnnFkd4pQK&_nc_ohc=AQHj1P2apKIAX-zccVg&_nc_ht=scontent.fuio16-1.fna&oh=85d001252acb7c9cd176f7476f79f8f3&oe=602C3C0F)


**Propiedad de Homogeneidad**
Esta propiedad establece que si se le multiplica por una constante k a la entrada en un elemento esto será igual a la salida multiplicada por esa misma constante k.
kv=k iR


**Propiedad aditiva**
La propiedad aditiva establece que la respuesta a una suma de entradas es la suma de las respuestas a cada entrada aplicada por separado. Expresado matemáticamente tenemos:

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138329323_233530591546318_7378925835394739667_n.jpg?_nc_cat=103&ccb=2&_nc_sid=730e14&_nc_eui2=AeFaOhK1GKZAFhEJpckchSh_80qOndldQezzSo6d2V1B7I55S9yB_pk-_R_1KdS7ErD-G3Y1Dhe5rY8-eVQayWvB&_nc_ohc=Ce8n4HC3nIIAX-uM8Gj&_nc_ht=scontent.fuio16-1.fna&oh=6a45b47d82592906d43ecc47535a9cdf&oe=602A57C4)

**1.3.1.2. Superposición** 

Si se considera como salidas a cualquier variable (corriente o voltaje en cualquier elemento pasivo) y entradas a todos los elementos activos que intervienen en un circuito. La salida de un circuito lineal puede ser expresada como una combinación lineal de sus entradas. Es decir, se puede obtener la salida del circuito, si se toma en cuenta a cada fuente por separado, suprimiendo las otras fuentes. Y cada resultado parcial se suma para obtener la salida deseada.
Cabe recalcar que las resistencias internas de las fuentes toman efecto en los resultados finales, por esto es necesario calcular dichos valores de resistencias para colocarlos en lugar de las fuentes que se suprimen, para obtener resultados más exactos. Se va a ilustrar el método de superposición mediante el siguiente ejemplo:

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138068546_233532538212790_1376794759623670483_n.jpg?_nc_cat=100&ccb=2&_nc_sid=730e14&_nc_eui2=AeHeEc7qovrG4yM63v0JXcZvwE8iEEELHlvATyIQQQseWxLEqHCmfLngcWevKI1Ykh9EeWHXgBctExLCdPuaoeyf&_nc_ohc=gwD3LTgvMvcAX9Cz7n_&_nc_ht=scontent.fuio16-1.fna&oh=3105844c640e719a83116a5214a88680&oe=6029393F)


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138301040_233525518213492_5635638613068256265_n.jpg?_nc_cat=101&ccb=2&_nc_sid=730e14&_nc_eui2=AeFiqkdkNpZhkst10inxZtt33wlDn82BJ3LfCUOfzYEnct84s8tjO_xKKvjpzY2h6AFKNJrkh6T0kx6QXRJK-Znw&_nc_ohc=6KFgg6e2hsYAX-GCmaP&_nc_ht=scontent.fuio16-1.fna&oh=19cf8be6b227368ffa2b3699afd3f489&oe=60288DF1)


**1.3.1.3. Reciprocidad**

Los circuitos lineales cumplen la propiedad de superposición. Esto es, en un circuito con varias fuentes (de tensión y/o corriente), la respuesta se puede hallar sumando la respuesta del circuito a cada una de las fuentes (independientes) por separado. Para clarificar este aspecto se plantea el siguiente ejemplo:




![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138933753_233535238212520_700100050321877738_n.jpg?_nc_cat=108&ccb=2&_nc_sid=730e14&_nc_eui2=AeEM_FqTs0OQh_qqNo0AsbaqnXQAGmnPEEOddAAaac8QQ2-0IawZbCJZuXhuQ6DrJeSRun_oObZUCTD8vMVGReCt&_nc_ohc=iQoNuiYzdeMAX_DVCIt&_nc_oc=AQlGlfEg4vTXcMPNVaIvbuouFfkXsIAjOLzHT453F1fBQkzoUJA0U_B4MW7lA7OYwk6u5cLxJ9beMQgVweJTVrsu&_nc_ht=scontent.fuio16-1.fna&oh=0378bfaf57bd0cc84978ff1e08c2c990&oe=602B621B)


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/139737211_233535301545847_4649606163273187180_n.jpg?_nc_cat=110&ccb=2&_nc_sid=730e14&_nc_eui2=AeEBclQanEn9jdsnMLTnlLvzr-53SkPkVlyv7ndKQ-RWXN_78MPykvD9a3MiHmbfzGPliwV3pjNBkeFioz1DCPFU&_nc_ohc=ZJDV4idV6QQAX9-G40d&_nc_ht=scontent.fuio16-1.fna&oh=646de71ae8f225d6fed5665e499d6b1a&oe=602B7A68)


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140023457_233535251545852_6633194767969206271_n.jpg?_nc_cat=103&ccb=2&_nc_sid=730e14&_nc_eui2=AeHv1sncb2BaVoK1bIcB0t_g6M4rmz1CXMnoziubPUJcyQ2w7G4WGVS2KCAFl5zhdXycj9fxlzJOPpnaq01_44I2&_nc_ohc=EdVFy_dPtkcAX-aWKco&_nc_ht=scontent.fuio16-1.fna&oh=c6c903a8b6db93e62dd187cc6db74bad&oe=60288AD2)


**1.3.2. TEOREMA DE SUPERPOSICIÓN**

1. Valores de tensión, en una posición de un circuito, que tiene más de una fuente de tensión.

2. Valores de corriente, en un circuito con más de una fuente de tensión.

Este teorema establece que el efecto de dos o más fuentes de voltaje tiene sobre una resistencia es igual, a la suma de cada uno de los efectos de cada fuente tomados por separado, sustituyendo todas las fuentes de voltaje restantes por un circuito.

**Para resolver problemas usando el teorema de superposición debemos tener en cuenta que:**

•	Las fuentes independientes se consideran una a la vez mientras todas las demás fuentes independientes están apagadas. Esto implica que cada fuente de tensión se remplaza por 0 V (o cortocircuito) y cada fuente de corriente por 0 A (o circuito abierto). De este modo se obtiene un circuito más simple y manejable. 

•	Las fuentes dependientes se dejan intactas, porque las controlan variables de circuitos.

**Pasos para aplicar el principio de superposición:**

1. Apague todas las fuentes independientes, excepto una. Determine la salida (tensión o corriente) debida a esa fuente activa usando la Ley de Ohm y las Leyes de Kirchhoff y además de todas las técnicas ya estudiadas 
2. Repita el paso 1 en cada una de las demás fuentes independientes. 
3. Halle la contribución total sumando algebraicamente todas las contribuciones debidas a las fuentes independientes.


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/139678661_233535268212517_7306093398629315152_n.jpg?_nc_cat=109&ccb=2&_nc_sid=730e14&_nc_eui2=AeEv5HypRufE1ONUANgZRRaaiSQ3PN4lBJ6JJDc83iUEntBu66e1S26mMwl4j62UObPU2MWxygYh0DUzgZRqTe-w&_nc_ohc=fbzwZJT4rYgAX_VRnlq&_nc_ht=scontent.fuio16-1.fna&oh=960cab44eb77d4e7f9a44dba462c7e2c&oe=6029E12E)


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/139640198_233535318212512_5747173042617632609_n.jpg?_nc_cat=103&ccb=2&_nc_sid=730e14&_nc_eui2=AeG-TU3CC02wFZuo1UtMYWMr5Vxruo6-t0blXGu6jr63Ror8sBDcoSzB4WhSTPvl7XTKn4hDrUOuoy1DoPgIO2-k&_nc_ohc=M5lAbMQDbxwAX9TuNeK&_nc_ht=scontent.fuio16-1.fna&oh=8658cf04c244da4ce31b4aee9afc3a6d&oe=602AF4D0)


**1.3.	PROCEDIMIENTO-EXPLICACIÓN**

Con todos los conocimientos ya adquiridos anteriormente, y sabiendo el concepto de la superposición y como se debe aplicarlo en un circuito eléctrico, dependiendo de si se tiene una fuente dependiente e independiente, procedemos a armar el circuito en el cual aplicaremos los conocimientos.

Tomamos la fuente de 20 V y conectamos la polaridad positiva a la primera terminal del resistor de 5 kOhm, la terminal que queda libre la conectamos a dos resistencias de 820 Ohm y 2.2 kOhm respectivamente, de la terminal dos de la resistencia de 820 kOhm la conectamos a la polaridad positiva de la fuente de voltaje y a un extremo del resistor de 470 Omh en forma paralela, para finalmente conectar todos los demás extremos de los resistores a las polaridades negativas de los suministros de energía.
Desarrollado el circuito en la plataforma Tinkercad queda así:

.3.1.	Arme el circuito que se muestra en la ilustración 


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140631987_234352741464103_4166652457281539738_n.jpg?_nc_cat=103&ccb=2&_nc_sid=730e14&_nc_eui2=AeHV39C59TqzDFmgAopQioNCbcx7u71JcoVtzHu7vUlyhVIuJtnJGd3gi9fWEdBZZ16HTPxh74u7mT-MoQ8a3_Hu&_nc_ohc=3rSFwk0hTboAX8GBLx0&_nc_ht=scontent.fuio16-1.fna&oh=73f3624ab9965462630b73383a26f918&oe=602D8FF0)


Circuito armado en el simulador Tinkercad


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140321537_234355821463795_6520878954389612150_n.jpg?_nc_cat=104&ccb=2&_nc_sid=730e14&_nc_eui2=AeHPEBlyUQqhUaq_mGiIH9g66D-FfmgAlMjoP4V-aACUyA0Svq4L1PYAYjiiBAp6NaT2bAyQQr1pwLaXNshcUskd&_nc_ohc=ds71lZyfKKQAX_rrDVk&_nc_ht=scontent.fuio16-1.fna&oh=395c7d8a255de1740d9789fc346fe98e&oe=602DDA1D)


Circuito una vez corrida la simulación, se aprecian los voltajes de las dos fuentes


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140176421_234355828130461_6179527468309770888_n.jpg?_nc_cat=109&ccb=2&_nc_sid=730e14&_nc_eui2=AeHwsy-cOmg4RPfLXG05kQdQPrOENIxxBu0-s4Q0jHEG7ZqKoaoVVWaDNBOev3Nxxd2Iq14bSShpwhmbzixLxUex&_nc_ohc=SKuKmACgF4gAX9EFLJF&_nc_ht=scontent.fuio16-1.fna&oh=69d0b1f4857ad96b5e4f3828bf6763ca&oe=602B48DC)


Para resolver el circuito por superposición, debemos apagar una de las fuentes en este circuito, así que primero apagaremos la fuente de 12 V, y aplicaremos el análisis de mallas al circuito.
El circuito con la fuente de 12 V apagada queda así:

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140370341_234352758130768_2386710325088716520_o.jpg?_nc_cat=105&ccb=2&_nc_sid=730e14&_nc_eui2=AeGqxeJjh3teGaEo5NKS1GlZ2O4rEoL3m8_Y7isSgvebz6cCDV81MrNXHKQo-rVLCXH9Zs3zfPlc9aII2YLYVFd7&_nc_ohc=4-zrabmtA50AX-r-97i&_nc_ht=scontent.fuio16-1.fna&oh=0956d9656b8e26bb46346b747de80b55&oe=602D53A5)

Como apreciamos en la figura, ahora la segunda fuente de voltaje es cero, continuamos con el establecimiento de las ecuaciones de malla aplicando la Ley de Voltaje de Kirchhoff.
Tenemos dos mallas en el circuito así:

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140202706_234352804797430_2395632636591482594_n.jpg?_nc_cat=107&ccb=2&_nc_sid=730e14&_nc_eui2=AeEoLzMog0PfbL8gQfJILRMQ-YLP4bQWQo_5gs_htBZCjyanZw4gR86VOPAvaekAWW2Iaox--BtXGMoKcfs8V9Oj&_nc_ohc=zFzy8Vm5ObAAX9jrJrC&_nc_ht=scontent.fuio16-1.fna&oh=98e81b1879e681dbe032b13364c5e546&oe=602A5E57)

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140128866_234352828130761_5094330339707815253_n.jpg?_nc_cat=107&ccb=2&_nc_sid=730e14&_nc_eui2=AeG6GEV7yNa2bwp39gyjrHd75RzwXvmnMHvlHPBe-acwexDkTOvJQrVy5ViAsqA_ohPwmmsNHYuTTIw5q0ZmA_bV&_nc_ohc=uNGJQSvNSxwAX8lqBu1&_nc_ht=scontent.fuio16-1.fna&oh=e4b4749385b07042775593d1e0d72cfa&oe=602AD06A)

Precedemos con la siguiente fuente, la apagamos y nos queda el circuito así:

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140374015_234357691463608_7908705317148865004_o.jpg?_nc_cat=109&ccb=2&_nc_sid=730e14&_nc_eui2=AeGTgikjIUHE6eSnFnnLlBifoobSgiHbpFuihtKCIdukW418rS6EdXTr5nMn2AArn_PpsjzWq0xiyLO8hCZugYiv&_nc_ohc=2IB3sf4ZqmoAX8vQl1p&_nc_ht=scontent.fuio16-1.fna&oh=8d9a808eb56de33586341107c51b72b3&oe=602DE93A)


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140391672_234352834797427_9212817523218446660_n.jpg?_nc_cat=103&ccb=2&_nc_sid=730e14&_nc_eui2=AeF7Aj039IrJM1YjydsoeOsm-kHs-FO6AZv6Qez4U7oBm99zeVaVJUIUK-l2CnJDpK5T8dmC0N64Jocbe4IB2duf&_nc_ohc=knCXb_CeUxcAX86BPvl&_nc_ht=scontent.fuio16-1.fna&oh=f060e07c99baf737716ea3f24618cb42&oe=602C476A)


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140596084_234352854797425_2673090251145189046_n.jpg?_nc_cat=106&ccb=2&_nc_sid=730e14&_nc_eui2=AeEIGldQXPNnUBBvrNNlChm7wB2BoH0jphjAHYGgfSOmGLFDK6r3lxeWmYBxEuMe5qUYYr8PODBxR4qQF0BVPhCg&_nc_ohc=TZse8zXlSHwAX9Tu2-v&_nc_ht=scontent.fuio16-1.fna&oh=574a20ea3a7e6c8a3a8f69f8b2ea8033&oe=602B571F)


Para calcular el valor del voltaje pedido lo hacemos en el siguiente circuito equivalente, reestablecemos las resistencias y solo hacemos el paralelo de dos resistencias, así:
1k || 2.2k =0.68 k
 Y aplicamos el divisor de voltaje


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140596084_234352854797425_2673090251145189046_n.jpg?_nc_cat=106&ccb=2&_nc_sid=730e14&_nc_eui2=AeEIGldQXPNnUBBvrNNlChm7wB2BoH0jphjAHYGgfSOmGLFDK6r3lxeWmYBxEuMe5qUYYr8PODBxR4qQF0BVPhCg&_nc_ohc=TZse8zXlSHwAX9Tu2-v&_nc_ht=scontent.fuio16-1.fna&oh=574a20ea3a7e6c8a3a8f69f8b2ea8033&oe=602B571F)


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140155769_234352868130757_6656534291561579447_n.jpg?_nc_cat=105&ccb=2&_nc_sid=730e14&_nc_eui2=AeENAFc-uXYHrTVHV6dVaV9rzdH0pQ9p98HN0fSlD2n3weeV5Ca34MghIkn-bf2F0aVXGdhKUdfN4pzpQHqYNCjs&_nc_ohc=2UBZC9LeYoAAX8ftGgp&_nc_ht=scontent.fuio16-1.fna&oh=a6d01f810d92f88e898026c65610e8bb&oe=602D666F)


	Con las dos fuentes conectadas, mida el voltaje V_A y la corriente I_X , respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en las tablas respectivamente.

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140281524_234352894797421_3743562105018727673_o.jpg?_nc_cat=110&ccb=2&_nc_sid=730e14&_nc_eui2=AeFcg_BI75nJ76mLAi6HqKtblKqQNRpayw6UqpA1GlrLDtX0u_Y7j4V2BO0ggGH2yc4K3knHeO4SJdBKjxN4DJkA&_nc_ohc=RcmmhWQD4bEAX97gcuP&_nc_ht=scontent.fuio16-1.fna&oh=cbab24e314c6814b3e57cde2f8dc0108&oe=602BF6CC)


	Haga “cero” la fuente de voltaje de 12 V (V_2) y mida el voltaje V_A y la corriente I_X , respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en las tablas respectivamente.

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140475764_234352888130755_6730524417952573339_n.jpg?_nc_cat=108&ccb=2&_nc_sid=730e14&_nc_eui2=AeGqk8b8inOO4i245Vn3YGJJuk79fvhAJMW6Tv1--EAkxeiWVjBFih66VoJG05BAYxYB3vZOB1tIwsJFAXE6yw1e&_nc_ohc=cbvSVR5N5ywAX8poxJk&_nc_ht=scontent.fuio16-1.fna&oh=594486cfc6a426bb81253b7ff8d3c022&oe=602A4454)



	Haga “cero” la fuente de voltaje de 20 V (V_1) y mida el voltaje V_A y la corriente I_X , respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en las tablas respectivamente. 

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140305221_234352914797419_8222826185780386186_n.jpg?_nc_cat=110&ccb=2&_nc_sid=730e14&_nc_eui2=AeHWDjYLgfMaxbRut4v5KexepTttXnzqz-elO21efOrP5-sQTQycvFqn0dT2MQv5cDJfKTCM7kX_L-2uZQRBCaF-&_nc_ohc=7Ph-lY1PyiwAX_ZYcQi&_nc_ht=scontent.fuio16-1.fna&oh=fd43ff12d916b38131e7e10a7046de08&oe=602C60C5)


Con las incógnitas calculadas en cada uno de los procesos del método, procedemos a llenar nuestra tabla de resultados.


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140305228_234352931464084_8242978713625880236_n.jpg?_nc_cat=105&ccb=2&_nc_sid=730e14&_nc_eui2=AeH4VeLB-siHEWEiJDjex3-SLEjH3zY4n3osSMffNjifemZYPxlC-TGz88F9cxijP6HyUWJwTaGqm14K2ORW23P1&_nc_ohc=BLe8hB_sOi4AX-e_gog&_nc_ht=scontent.fuio16-1.fna&oh=e5fdf12996b49169cb20eb6e6d026a41&oe=602C76AF)


1.3.5.	Verifique el cumplimiento del Teorema de Superposición y compare los resultados obtenidos prácticamente con los obtenidos analíticamente. Realice sus conclusiones

![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/140615328_234352951464082_5709653325444570363_n.jpg?_nc_cat=102&ccb=2&_nc_sid=730e14&_nc_eui2=AeGsK7Sn3jYzNxU0Z9eTyTeriLun3sG6dASIu6fewbp0BIZP2tOzPDSV2T946vt3GVlRfSxdC99twHrINGTJoer1&_nc_ohc=jBT9iAA9NxQAX-uElvK&_nc_ht=scontent.fuio16-1.fna&oh=ace700da185453130d3b4f70361b0203&oe=602AF054)


1.7.	DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN
Como prerrequisitos tenemos que conocer ampliamente las leyes de elementales del análisis de circuitos eléctricos, que son La Ley de Ohm y las Leyes de Kirchhoff, Sabemos también sobra las propiedades de homogeneidad y de aditividad en circuitos eléctricos que lo que hace el teorema de superposición es júntalos y aplicarlos.

A cada suministro de energía lo configuramos en el simulador de tal manera que tenemos el voltaje que nos piden en el circuito, en este caso le cambiamos el voltaje de 5 V por defecto a 20 V y 12 V que son los voltajes que necesitamos para realizar el trabajo, del mismo modo se pueden cambiar el valor de cada una de las resistencias, permitiéndonos cambiar el valor que viene por defecto por el valor requerido para la práctica.

Los multímetros usados para cada una de las mediciones, deben ser configurados previamente para voltaje y corriente respectivamente, sabiendo que para medir voltajes se miden en forma paralela al elemento medido y para la medición de las corrientes se debe medir en serie con el elemento medido

**1.8.	CONCLUSIONES**

**Conclusiones específicas **

•	De forma práctica pudimos aprender a implementar el teorema de superposición con la toma de medida usando solo una fuente de alimentación. 

•	El teorema de superposición nos permite evaluar los datos proporcionados por cada fuente en diversas resistencias del circuito, para luego proceder a sumar estos datos y hallar los verdaderos valores proporcionados en el circuito. 

•	Para suprimir las fuentes ideales de tensión se ubican uniones donde deberían posicionarse esas fuentes.

•	Se pudo determinar que si la fuente no es la ideal esta se cortocircuita, sin embargo, se deja introducida en el circuito eléctrico. 

•	Incluso comprobamos como al tener la fuente ideal esta se reemplaza por un circuito abierto. 


### Conclusión general

Podemos concluir entonces que al considerar los efectos de cada fuente de manera independiente y que estas fuentes se retiren y se reemplacen sin ser capaces de afectar el resultado final. Al usar la teoría de superposición la diferencia de potencia entre los contactos de la fuente de tensión se debe ajustar a cero, entonces el retiro de una fuente de corriente en el circuito requiere que los contactos de este estén abiertos, es decir, que sea un circuito abierto. 

También sabemos que la cualquiera porción de la red es igual a la suma algebraica de las corrientes producidas independientemente por cada una de las fuentes, en cambio, si la corriente producida por una fuente sigue una dirección, mientras que la producida por la otra va en sentido opuesto a través del mismo resistor, la corriente resultando será la diferencia entre las dos y se obtendrá la dirección de la mayor. 

Además, pudimos darnos cuenta de que la superposición no es aplicable a los efectos de la potencia, puesto que la pérdida de potencia en uno de los resistores del circuito varia con el cuadrado no lineal de la corriente o de la tensión. Entonces conocemos que esta es la principal razón para que la potencia en un elemento no se puede determinar sino hasta haber establecido la corriente total o la tensión a través del elemento mediante la superposición. 


1.9.	BIBLIOGRAFÍA

Alexander, S. M. (2006). Fundamento de Circuitos Eléctricos (Vol. 3ra Edición). The McGraw-Hill Companies Inc. Recuperado el 12 de Diciembre de 2020

McAllister, W. (2016). Los elementos de los circuitos. Obtenido de La terminología de los circuitos: https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic#circuit-elements

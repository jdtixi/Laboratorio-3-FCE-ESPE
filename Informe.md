![](https://pbs.twimg.com/profile_images/712307087577993217/D8_89Lg4_400x400.jpg)
##  LABORATORIO 2
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                            
                                                                           
                                                                           
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


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/138635576_233525448213499_596568944852839270_n.jpg?_nc_cat=108&ccb=2&_nc_sid=730e14&_nc_eui2=AeGz_r0D8p3ZUpSasrGubJKMgSkJNngigaKBKQk2eCKBouXuUercNsJYqycoZLqZMaLL-reWtMusxwxMZyzJLYFW&_nc_ohc=26G1M9fCGlkAX891pV2&_nc_ht=scontent.fuio16-1.fna&oh=c8d17b494e9058498b355648406d75aa&oe=60297DC9)



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
Pasos para aplicar el principio de superposición: 
1. Apague todas las fuentes independientes, excepto una. Determine la salida (tensión o corriente) debida a esa fuente activa usando la Ley de Ohm y las Leyes de Kirchhoff y además de todas las técnicas ya estudiadas 
2. Repita el paso 1 en cada una de las demás fuentes independientes. 
3. Halle la contribución total sumando algebraicamente todas las contribuciones debidas a las fuentes independientes.


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/139678661_233535268212517_7306093398629315152_n.jpg?_nc_cat=109&ccb=2&_nc_sid=730e14&_nc_eui2=AeEv5HypRufE1ONUANgZRRaaiSQ3PN4lBJ6JJDc83iUEntBu66e1S26mMwl4j62UObPU2MWxygYh0DUzgZRqTe-w&_nc_ohc=fbzwZJT4rYgAX_VRnlq&_nc_ht=scontent.fuio16-1.fna&oh=960cab44eb77d4e7f9a44dba462c7e2c&oe=6029E12E)


![](https://scontent.fuio16-1.fna.fbcdn.net/v/t1.0-9/139640198_233535318212512_5747173042617632609_n.jpg?_nc_cat=103&ccb=2&_nc_sid=730e14&_nc_eui2=AeG-TU3CC02wFZuo1UtMYWMr5Vxruo6-t0blXGu6jr63Ror8sBDcoSzB4WhSTPvl7XTKn4hDrUOuoy1DoPgIO2-k&_nc_ohc=M5lAbMQDbxwAX9TuNeK&_nc_ht=scontent.fuio16-1.fna&oh=8658cf04c244da4ce31b4aee9afc3a6d&oe=602AF4D0)


**1.3.	PROCEDIMIENTO-EXPLICACIÓN**

Con todos los conocimientos ya adquiridos anteriormente, y sabiendo el concepto de la superposición y como se debe aplicarlo en un circuito eléctrico, dependiendo de si se tiene una fuente dependiente e independiente, procedemos a armar el circuito en el cual aplicaremos los conocimientos.

Tomamos la fuente de 20 V y conectamos la polaridad positiva a la primera terminal del resistor de 5 kOhm, la terminal que queda libre la conectamos a dos resistencias de 820 Ohm y 2.2 kOhm respectivamente, de la terminal dos de la resistencia de 820 kOhm la conectamos a la polaridad positiva de la fuente de voltaje y a un extremo del resistor de 470 Omh en forma paralela, para finalmente conectar todos los demás extremos de los resistores a las polaridades negativas de los suministros de energía.
Desarrollado el circuito en la plataforma Tinkercad queda así:

PRÁTICA N°05 

1. OBJETIVOS DE LA PRÁCTICA

1.1. OBJETIVO GENERAL

Comprobar experimentalmente el Teorema de Thévenin, mediante el ensambla miento de un circuito lineal con dos terminales, empleando la plataforma de tinkercad, para emplear los conocimientos adquiridos en clase y verificar el funcionamiento de este.

1.2. OBJETIVOS ESPECÍFICOS

- Determinar que establece el Teorema de Thévenin con respecto a los circuitos líneales de dos terminales.
- Definir como se le conoce a la fuente de voltaje y la resistencia en serie dentro del Teorema de Thévenin.

2. MARCO TEÓRICO

2.1. TEOREMA DE THÉVENIN

![Diagrama en blanco (4)](https://user-images.githubusercontent.com/94008521/149223551-11bdd5e3-4237-4407-bf25-181800b64476.png)

3. EXPLICACIÓN DEL PROCEDIMIENTO

3.1. Arme el circuito que se muestra en la figura 5.1.

![image](https://user-images.githubusercontent.com/93960809/149155326-ec15e13d-213e-4cf2-9483-eac6faad7db8.png)

3.2. Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.

![image](https://user-images.githubusercontent.com/93960809/149155371-5dca432a-8d8f-451a-bd1b-bb4065bfa682.png)

3.3. Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/93960809/149155433-795df9bd-d4c6-47e7-a46b-faa54cba72a2.png)

3.4. Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/93960809/149155489-9e2ee9c1-f4b5-4a67-ac17-93ab21ed3507.png)

3.5. Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.

![image](https://user-images.githubusercontent.com/93960809/149155540-0439da2e-24ae-4271-a312-ebec031c51ad.png)

Cálculos analíticos realizados para la tabla 5.1

![image](https://user-images.githubusercontent.com/93960809/149155574-db0975c9-6c03-48cc-9574-9aff6ace7227.png)

Hallando el voltaje de Thévenin:

![image](https://user-images.githubusercontent.com/93960809/149155613-f5acd45f-4c3d-4ff3-8d70-32bb7ae9635b.png)

![image](https://user-images.githubusercontent.com/93960809/149155644-ff583eb0-8abb-4eba-b172-5c6a11ea1313.png)

Mediante el uso de la calculadora Symbolab encontramos las soluciones.

![image](https://user-images.githubusercontent.com/93960809/149155679-05933975-4740-444d-959c-0097603c5086.png)

![image](https://user-images.githubusercontent.com/93960809/149155696-c31e6ce2-7274-43cc-94d0-31fbd83d805d.png)

I1 corresponde al valor de a e I2 corresponde al valor de b, por lo que: 

![image](https://user-images.githubusercontent.com/93960809/149155739-e0f54afe-b5b1-482b-8e01-b04004aa1424.png)

Por tanto, el valor de voltaje de Thévenin es: 

![image](https://user-images.githubusercontent.com/93960809/149155780-749737ce-0b12-4309-b590-12ce4ffe0e51.png)

Explicación: 

Para encontrar el voltaje de Thévenin en primer lugar redibujamos el circuito ahora con la resistencia R5 abierta, es así que, el voltaje que hay entre las terminales abiertas va a ser el mismo voltaje que recorre por la resistencia R3. Para lo que, mediante el método de mallas, hallamos la corriente que pasa a través de la resistencia R3 y luego despejamos el voltaje de la ley de ohm y reemplazamos los valores de corriente y resistencia. Finalmente obtenemos el valor del voltaje de Thévenin. 

Hallando la resistencia de Thévenin:

![image](https://user-images.githubusercontent.com/93960809/149155990-1515a313-ede8-4ab6-9e65-658628fa63c5.png)

![image](https://user-images.githubusercontent.com/93960809/149156018-0ee1ee31-baaf-4d46-ae11-0e4161d66bdf.png)

Explicación: 

Para encontrar la resistencia de Thévenin en primer lugar redibujamos el circuito teniendo en cuenta que igualamos a cero el voltaje de las dos fuentes. Por lo que ya con el nuevo circuito, identificamos cuales son las resistencias que están en paralelo y cuales, en serie, para posterior así ir desarrollando la suma de las resistencias o ir encontrando las resistencias equivalentes. Finalmente se encontró la resistencia de Thévenin.

Cálculos analíticos realizados para la tabla 5.2

![image](https://user-images.githubusercontent.com/93960809/149156070-d34a7f94-e639-41de-b200-c605ae815218.png)

Hallando voltaje y corriente de circuito original: 

![image](https://user-images.githubusercontent.com/93960809/149156104-99cdb6ee-985a-471b-9b1a-d3598910094a.png)

![image](https://user-images.githubusercontent.com/93960809/149156139-8086efa4-bd26-406e-8a88-3be3950a090f.png)

![image](https://user-images.githubusercontent.com/93960809/149156153-1a1bb953-257f-46ed-990a-5b8e7e93d8fa.png)

![image](https://user-images.githubusercontent.com/93960809/149156169-8432c4df-1c1d-43a6-a132-5d39a7a561b6.png)

Por lo que, nos interesa el valor de I3 que corresponde a c. 

![image](https://user-images.githubusercontent.com/93960809/149156204-4d71ee8f-cadd-4edb-b643-9b0f4192c3ff.png)

Y el voltaje en R5 es: 

![image](https://user-images.githubusercontent.com/93960809/149156246-7af90a60-bceb-4319-a5e0-635a2f7aa866.png)

Explicación:

Para hallar voltaje y corriente que pasan por la resistencia R5, mediante el método de mallas calculamos la intensidad que recorre dicha rama. Una vez obtenida la intensidad, usamos la fórmula de la ley de ohm para encontrar el valor del voltaje.

Hallando voltaje y corriente de circuito de Thévenin: 

![image](https://user-images.githubusercontent.com/93960809/149156319-35d889df-f680-4d0e-85ae-37b5c284095f.png)

![image](https://user-images.githubusercontent.com/93960809/149159480-11ad52f6-0e61-4942-bece-5b13aa0ed62a.png)

Y el voltaje en R5 es:

![image](https://user-images.githubusercontent.com/93960809/149159522-a0fe4066-e55e-4faa-9675-c419a3ba6225.png)

Circuito en tinkercad con el potenciometro, sin embargo por la variación la resistencia de este componente es de 300 ohmios

![image](https://user-images.githubusercontent.com/94008521/149387243-21d9eae8-d490-4177-b1fe-cae50ae299dc.png)

Explicación: 

Para hallar voltaje y corriente en el circuito equivalente de Thévenin, al ser un circuito resistivo en serie, sume y obtuve la resistencia total y con eso se halló el valor de corriente gracias a la ley de ohm, misma que al despejar el voltaje y reemplazando valores, nos ayudó a encontrar dicho voltaje que pasa por R5. 


4. RESPUESTA A INTERROGANTES Y CÁLCULO DEL ERROR

![image](https://user-images.githubusercontent.com/93415377/149213611-f0b2640f-b924-4ef1-9767-5272fbf759b1.png)

5. VIDEO

https://www.youtube.com/watch?v=hEPnTBNMhE8

6. CONCLUSIONES

- Con respecto al Teorema de Thévenin si tiene que este establece que al existir dos terminales, en esta caso A y B, dentro de la estructura de un circuito eléctrico lineal, el mismo puede ser sustituido por un circuito equivalente mas simple. Es importante mencionar que esto se puede realizar debido a que, la teoría expresa que a través de la resistencia tranformada la corriente aun seguira circulando por el circuito.
- Dentro del Teorema de Thévenin a la fuente de voltaje se la conoce como el "voltaje de Thévenin", el (VTH) es el voltaje en circuito abierto entre las terminales del circuito para el cual se requiere el equivalente. Por otro lado, la resistencia en serie se le conoce como "resistencia de Thévenin", la (RTH) es la resistencia equivalente vista de la terminal del circuito, cabe mencionar que esto se realiza con respecto al equivalente de Thévenin y con las fuentes de alimentación en cero. 

7. BIBLIOGRAFÍA

-	Floyd, T. (2007). Principios de circuitos eléctricos. Ciudad de México: Pearson Eduación.
-	LATAM. (24 de Abril de 2021). Obtenido de https://www.mecatronicalatam.com/es/tutoriales/teoria/teorema-de-thevenin-y-norton/
-	Mariño, S. (14 de Marzo de 2017). Obtenido de https://es.slideshare.net/norenelson/anlisis-lineas-cortas-medias-y-largas?next_slideshow=73134883
-	Mi universo electrónico. (19 de Septiembre de 2020). Obtenido de https://miuniversoelectronico.com/el-teorema-de-thevenin/
-	Obando, L. (10 de Noviembre de 2019). Obtenido de https://dademuch.com/2019/11/10/teorema-de-thevenin-analisis-de-circuitos-electricos/

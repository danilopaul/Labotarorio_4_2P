# Labotarorio_4_2P

                                         Universodad de las Fuerzas Armadas - ESPE
                                           Fundamentos de Circuitos Electróinicos
        Integrantes:
        - Cholca Paul
        - Sandal Andrés
        - Vasquez Lady
 
1.Objetivo

1.1 Objetivo General

Determinar y analizar los pasos que conforman el teorema   de   superposición, para aplicarlos en la creación de circuitos la resolución de ejercicios prácticos, mediante el planteamiento de ecuación que cumplan con las leyes básicas (Ley de ohm y Ley de Kirchhoff).  

1.2 Objetivo  Especificos

- Analizar el comportamiento de la resistencia interna tanto en una fuente de voltaje o de tensión y a su vez en una fuente de corriente presente en un circuito.
- Relacionar dicho comportamiento de la resistencia interna en la aplicación del teorema de superposición para comprender su proceso de resolución.
- Comprobar por medio de una simulación, si los cálculos tras aplicar el teorema de superposición concuerdan con los resultados de la simulación.


2.Marco teorico.

![image](https://user-images.githubusercontent.com/105684550/176568097-9b272cf8-718d-4717-b79f-f1c7412c1c9e.png)
Link del mapa mental: https://www.canva.com/design/DAFFBwhXoU8/0i2ya9_eV-q7b7re-UOfHQ/view?utm_content=DAFFBwhXoU8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton 

3.Requisitos previos

![image](https://user-images.githubusercontent.com/105687375/176583360-89152c2e-65c0-44ac-827b-dada90702fc3.png)

![image](https://user-images.githubusercontent.com/105687375/176583474-134ec70a-84d8-4d1e-b9fb-1b777ea532b2.png)

![image](https://user-images.githubusercontent.com/105687375/176583528-bdfa7d08-f0f6-49e5-b4c8-2d90048351a3.png)

![image](https://user-images.githubusercontent.com/105687375/176583566-58c23659-8631-47b3-968f-962e9eedefab.png)

![image](https://user-images.githubusercontent.com/105687375/176583671-ea158df2-1866-4f42-b144-e655f9ea42ea.png)

![image](https://user-images.githubusercontent.com/105687375/176583704-510a116e-0cbf-4117-99a1-72cdca6cffc4.png)

![image](https://user-images.githubusercontent.com/105687375/176583721-70aba312-b52f-4e54-854d-7f5dfda51b18.png)

4.Materiales y equipos requeridos

![image](https://user-images.githubusercontent.com/105684550/176568300-a6bae813-85b6-4c32-b05c-dbf160cfe379.png)

5.Procedimiento

Teorema de superposición

![image](https://user-images.githubusercontent.com/105687375/176597138-2c14e6c4-d7ce-4a66-9b5f-b6d006b4b599.png)

Cuando V2=0

En la resistencia 4 no se divide la corriente por lo cual no se le toma en cuenta.

Aplicamos el método:

Tensiones en los nodos:

I_1+I_2+I_3=0

(V_A-V_1)/1000Ω+V_A/820Ω+V_A/2200Ω+0=0

V_A (1/1000+1/820+1/2200)-20/1000=0

V_A (603/225500)=20/1000=V_A=(20/1000)/(603/225500)=7.47 V

I_X=0

Cuando V_1=0

El circuito es el siguiente:

![image](https://user-images.githubusercontent.com/105687375/176597212-8bf69d78-7240-4d6e-b8f2-f6521bf44e98.png)

R_2equ=(R_1*R_2)/(R_1+R_2 )=(1kΩ*2.2kΩ)/(1kΩ+2.2kΩ)=0.69kΩ

 R_3equ=R_2equ+R_3=0.69kΩ+0.82kΩ=1.51kΩ
 
R_T=(R_3*R_4)/(R_3+R_4 )=(1.51kΩ*0.47kΩ)/(1.5kΩ+0.47kΩ)=0.3584kΩ

Entonces el V_A

V_A=(V_S/(R_3+R_2equ ))*R_3=(12V/(0.82+0.69))*(0.82)

V_A=6.52 V

La corriente total es:

I_T=(V_S/R_T )=12V/0.3584kΩ=33.48mA

Por lo tanto la corriente I_X=

I_T=(V_S/R_4 )=12V/0.47kΩ=25.53 mA

Se obtiene que:

V_AT=7.47V-6.52V=0.95V

V_AT=950 mV

I_T=25.53mA+0=25.53 mA.

6.Video

https://youtu.be/Of6-pmOZemE

7.Conclusiones:

•	Se concluye que cuando en un circuito existen dos fuentes de voltaje o más se utiliza el teorema de superposición, para ello se debe realizar una serie de pasos, para sí obtener los valores calculados de cada voltaje.

•	Tal y como se ha podido comprobar, los datos calculados con los datos medidos llegan a variar con un mínimo porciento de error.

•	Finalmente, en el teorema de superposición se puede aplicar varios métodos de solución, como en este caso se aplicó tensión en los nodos, ley de ohm, divisoR de voltajes, entre otros.



8.Bibliografía

Floyd, TL (2007). Principios de Circuitos Eléctricos. CDMX: Persona Educación.

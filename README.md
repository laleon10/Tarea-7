# Tarea-7
cap 13-14
OBJETIVOS

# Objetivo general

Explicar y resolver los problemas presentados en los capítulos trece y catorce del libro "Principios de circuitos eléctricos" de Floyd mediante el uso de los conocimientos adquiridos en clases y el contenido del libro referente a inductores y transformadores para encontrar un voltaje y las corrientes teniendo en cuenta las diferentes fuentes de voltajes, su transformacion y usos, permitiéndonos identificar las características correspondientes y lograr resolver cualquier tipo de circuito con un análisis y razonamiento adecuado.

# Objetivos Específicos:

- Entender las características que un Inductor posee.

- Definir cada tipo de inductor y su uso.

- Entender los componentes de un transformador y la utilización del mismo.

# MARCO TEORICO

# RESOLUCION DE EJERCICIOS O PROBLEMAS

**Ejercicios del Capítulo 13**

***(1)*** Convierta los siguientes valores en milihenries:

**(a)** 1 H

mH=(1 H)/1*(1000 mH)/(1 H)

mH=1000 mH

**(b)** 250 μH

mH=(250 μH)/1*(1 mH)/(1000 μH)

mH=0.25 mH

**(c)** 10 μH

mH=10μH/1*(1 mH)/1000μH

mH=0.01 mH

**(d)** 0.0005 H

mH=(0.0005 H)/1*(1000 mH)/(1 H)

mH=0.5 mH

***(3)*** ¿Cuál es el voltaje en una bobina cuando di/dt 10 mA/ms y L 5 mH?

Vind=L*di/dt

Vind=5 mH*10 mA/ms

Vind=50 mV 

***(5)*** La corriente a través de una bobina de 100 mH cambia a razón de 200 mA/s. ¿Cuánto voltaje se induce en la bobina?

Vind=L*di/dt

200 mA/s*(1 s)/(1000 ms)=0.2 mA/ms

Vind=100 mH*0.2 mA/ms

Vind=20 mV

***(7)*** ¿Qué cantidad de energía se guarda en un inductor de 4.7 mH cuando la corriente es de 20 mA?

W=1/2LI^2

W=1/24.7 mH(20 mA)^2

W=940 mJ

***(9)*** Compare la inductancia de dos inductores idénticos excepto que el inductor 2 está enrollado sobre un núcleo de hierro (permeabilidad relativa 150) y el inductor 1 está enrollado sobre un núcleo de acero al bajo carbono (permeabilidad relativa 200).

Respuesta: La inductancia del inductor 1 es mayor que la inductancia del inductor 2 ya que L=(N^2μA)/l, siendo L directamente proporcional a μ: la permeabilidad. Si 150/200=3/4, se concluye que la inductancia del inductor 2 es los 3/4 de la inductancia del inductor 1.

***(11)*** Se conectan cinco inductores en serie. El valor más bajo es de 5 μH. Si el valor de cada inductor es el doble del valor precedente, y si los inductores se conectan en orden de valores ascendentes, ¿cuál es la inductancia total?

L_T=L_1+L_2+L_3+⋯+L_n

L_T=(5+10+20+40+80) μH

L_T=155 μH

***(13)*** Determine la inductancia total en la figura 13-44.

[![1.png](https://i.postimg.cc/2jnPkPrS/1.png)](https://postimg.cc/HjsS3vrq)

L_T=L_1+L_2+L_3+⋯+L_n

500 μH*(1 mH)/(1000 μH)=0.5 mH

L_T=(50+0.5+0.01)mH

L_T=50.51 mH

***(15)*** Determine la inductancia total en paralelo para las siguientes bobinas dispuestas en paralelo: 75 μH, 50 μH, 25 μH, y 15 μH.

1/L_T =1/L_1 +1/L_2 +1/L_3 +⋯+1/L_n

1/L_T =1/75 μH+1/50 μH+1/25 μH+1/15 μH

1/L_T =7/50 μH

L_T=50/7 μH=7.14 μH

***(17)*** Determine la inductancia total de cada circuito mostrado en la figura 13-46.

[![2.png](https://i.postimg.cc/qqYtZzqp/2.png)](https://postimg.cc/YL6qv2QP)

**(a)** 1/L_T =1/L_1 +1/L_2 +1/L_3 +⋯+1/L_n

1/L_T =1/10 H+1/5 H

1/L_T =3/10 H

1/L_T =10/3 H=3.33 H

L_T=L_1+L_2+L_3+⋯+L_n

L_T=(3.33+1)H

L_T=4.33 H

**(b)** L_T=L_1+L_2+L_3+⋯+L_n

L_T=(50+50) mH

L_T=100 mH

1/L_T =1/L_1 +1/L_2 +1/L_3 +⋯+1/L_n

1/L_T =1/100 mH+1/100 mH

1/L_T =2/100 mH

L_T =100/2 mH=50 mH

**(c)** 1/L_T =1/L_1 +1/L_2 +1/L_3 +⋯+1/L_n

1/L_T =1/200 μH+1/100 μH+1/400 μH

1/L_T =7/400 μH

L_T =400/7 μH=57.14 μH

***(19)*** Determine la constante de tiempo para cada una de las siguientes combinaciones RL dispuestas en serie:

**(a)** R = 100 Ω, L= 100 μH.

T=L/R

100μH*1mH/(1000 μH)*1H/(1000 mH)=0.0001 H

T=(0.0001 H)/(100 Ω)

T=0.000001 s=1 μs

**(b)** R = 4.7 kΩ, L= 10 mH.

T=L/R

10mH*1H/(1000 mH)=0.01 H

4.7 kΩ*1000Ω/(1 kΩ )=4700 Ω

T=(0.01 H)/(4700 Ω)

T=0.000002128 s=2.13 μs

**(c)** R = 1.5 MΩ, L= 3 H.

T=L/R

1.5 MΩ*1000000Ω/(1 MΩ)=1500000 Ω

T=(3 H)/(1500000 Ω)

T=0.000002 s=2 μs

***(21)*** En el circuito de la figura 13-48, al inicio no hay corriente. Determine el voltaje en el inductor en los siguientes instantes tras de que se cierra el interruptor:

[![3.png](https://i.postimg.cc/WtLNkrtq/3.png)](https://postimg.cc/zH7YmyCq)

**(a)** 10 μs

v=15 V (e^((-Rt)/L))

T=L/R

T=0.010H/(1000 Ω)

T=10 μs

v=15 V (e^((-10)/10))

v= 5.518 V

**(b)** 20 μs

v=15 V (e^((-Rt)/L))

T=L/R

T=0.010H/(1000 Ω)

T=10 μs

v=15 V (e^((-20)/10))

v= 2.03 V

**(c)** 30 μs

v=15 V (e^((-Rt)/L))

T=L/R

T=0.010H/(1000 Ω)

T=10 μs

v=15 V (e^((-30)/10))

v= 0.746806 V

**(d)** 40 μs

v=15 V (e^((-Rt)/L))

T=L/R

T=0.010H/(1000 Ω)

T=10 μs

v=15 V (e^((-40)/10))

v= 0.274735 V

**(e)** 50 μs

v=15 V (e^((-Rt)/L))

T=L/R

T=0.010H/(1000 Ω)

T=10 μs

v=15 V (e^((-50)/10))

v= 0.101069 V

***(23)*** Repita el problema 21 para los siguientes instantes:

[![4.png](https://i.postimg.cc/9f8qq824/4.png)](https://postimg.cc/JyXhfQGm)

***(25)*** En la figura 13-48, ¿en qué momento luego de que se cierra el interruptor el voltaje llega a 5 V?

[![3.png](https://i.postimg.cc/WtLNkrtq/3.png)](https://postimg.cc/zH7YmyCq)

[![6.png](https://i.postimg.cc/3NHrymk4/6.png)](https://postimg.cc/JDPCvycM)

***(27)*** Determine la constante de tiempo para el circuito de la figura 13-50.

[![7.png](https://i.postimg.cc/kXsM4VqG/7.png)](https://postimg.cc/PPLnV5Ln)

[![8.png](https://i.postimg.cc/9fRcJJTw/8.png)](https://postimg.cc/DWhVzQx7)

***(29)*** Para el circuito de la figura 13-50, suponga que el interruptor estuvo cerrado por más de 5Ƭ y se abre. ¿Cuál es la corriente en el inductor 1.0 µs después de que se abre el interruptor?

[![7.png](https://i.postimg.cc/kXsM4VqG/7.png)](https://postimg.cc/PPLnV5Ln)

La corriente final es:

[![10.png](https://i.postimg.cc/3xyMTWwP/10.png)](https://postimg.cc/21f9dkhw)

La corriente en el instante 1.0 µs

[![11.png](https://i.postimg.cc/bJ9WTt62/11.png)](https://postimg.cc/CBdcMzpF)


***(31)*** Determine la reactancia total para cada circuito de la figura 13-47 cuando se aplica voltaje a una frecuencia de 400 Hz.

[![12.png](https://i.postimg.cc/Gh2VF9vH/12.png)](https://postimg.cc/8s2ZDpKS)

Para el circuito a:

LT = 33.33 + 24 = 57.33 mH

XL = 2πfL = 2π * 400Hz * 57.33mH = 144 Ω

Para el circuito b:
LT = 4mH

XL = 2πfL = 2π * 400Hz * 4mH = 10 Ω

Para el circuito c:

LT = 1.33 + 4 = 5.33 mH

XL = 2πfL = 2π * 400Hz * 5.33mH = 13.4 Ω

***(33)*** ¿Qué frecuencia producirá una corriente rms total de 500 mA en cada circuito de la figura 13-47 con un voltaje de entrada rms de 10 V?

[![13.png](https://i.postimg.cc/ZR4DCqTY/13.png)](https://postimg.cc/TyNcsfLB)

[![14.png](https://i.postimg.cc/90zb7Rs2/14.png)](https://postimg.cc/hQWVFjSZ)

Para el circuito a:

[![15.png](https://i.postimg.cc/c4phvJhq/15.png)](https://postimg.cc/RNTK842G)

Para el circuito b:

[![16.png](https://i.postimg.cc/x8kGCrbT/16.png)](https://postimg.cc/y3H3QbPw)

Para el circuito c:

[![17.png](https://i.postimg.cc/nhfKHPVp/17.png)](https://postimg.cc/vcXxhX6N)

***(35)*** Determine IL2 en la figura 13-52.

[![18.png](https://i.postimg.cc/nL0qGV4h/18.png)](https://postimg.cc/CZnZFgr3)

[![19.png](https://i.postimg.cc/8CKtPmn4/19.png)](https://postimg.cc/v1nW0fyx)

**Ejercicios del Capítulo 14**

***(1)*** ¿Cuál es la inductancia mutua cuando k=0.75, L1=1 µH, y L2= 4 µH? 

Como sabemos son 3 los factores que intervienen en la inductancia mutua, siendo su fórmula:

L_M=k*√(L1*L2)

Entonces reemplazamos en la fórmula:

L_M=0.75*√((1*10^(-6))H*(1*10^(-6) )H)

L_M=0.75*(2*10^(-6) )H

L_M=1.5*10^(-6) H

L_M=1.5 µH

***(3)*** ¿Cuál es la relación de vueltas de un transformador con 250 vueltas en el primario y 1000 en el secundario? ¿Cuál es la relación de vueltas cuando el devanado primario tiene 400 vueltas y el secundario 100? 

Como sabemos la relación de vueltas (n) se define como la relación del número de vueltas que hay en el devanado secundario (Nsec) al número de vueltas presentes en el devanado primario (Npri):

n=N_sec/N_pri 

Entonces para el Transformador 1 tenemos:

n=1000/250=4

Y para el Transformador 2:

n=100/400=0.25

Entonces tenemos:

4 y 0.25

***(5)*** Para cada transformador de la figura 14-42, trace el voltaje secundario que muestre su relación con el voltaje primario. Indique también la amplitud.

[![1.png](https://i.postimg.cc/xqr0g11L/1.png)](https://postimg.cc/sGcdgyS2)

[![2.jpg](https://i.postimg.cc/nLVQq05p/2.jpg)](https://postimg.cc/XrhJbc4z)

***(7)*** El devanado primario de un transformador tiene 120 V de ca a través de él. ¿Cuál es el voltaje secundario si la relación de vueltas es de 5?

Recordemos que Nsec/Npri define la relación de vueltas, n. Por consiguiente, a partir de esta relación:

V_sec=n*V_pri

Entonces reemplazamos:		V_sec=5*120 V

V_sec=600 V

***(9)*** Para reducir 120 V a 30 V, ¿cuál debe ser la relación de vueltas?

V_sec=n*V_pri

30 V=n*120 V

n=(30 V)/(120 V)

n=1/4=0.25  (4:1)

***(11)*** ¿Cuántos volts primarios se deben aplicar a un transformador que tiene relación de vueltas de 0.1 para obtener un voltaje secundario de 6 V de ca?

Recordemos que Nsec/Npri define la relación de vueltas, n. Por consiguiente, a partir de esta relación:

V_sec=n*V_pri

6 V=0.1*V_pri

V_pri=(6 V)/0.1=60 V

***(13)*** Determine las lecturas de medidor no especificadas en la figura 14-44

[![3.jpg](https://i.postimg.cc/RVRSw4zJ/3.jpg)](https://postimg.cc/vc4wsRTG)

Recordemos que Nsec/Npri define la relación de vueltas, n. Por consiguiente, a partir de esta relación:

Para la figura (a) tenemos:

V_sec=n*V_pri

V_sec=1/10*100 V=10 V

Para la figura (b) tenemos:

12 V=1/20*V_pri

V_pri=12 V÷1/20=240 V

***(15)*** Determine las siguientes cantidades en la figura 14-46

[![4.jpg](https://i.postimg.cc/JzFWQhY0/4.jpg)](https://postimg.cc/bZ1Myqhf)

**(a)** Corriente primaria 

Recordemos que la relación de la corriente primaria (I pri), a la corriente secundaria, (Isec), es igual a la relación de vueltas, tal como expresa la siguiente ecuación:

I_pri/I_sec =n

Entonces reemplazamos: 			I_pri=1/2*V_sec/(300 Ω)

Pero para reemplazar la corriente secundaria debemos calcular el voltaje secundario:

V_sec=n*V_pri

V_sec=1/2*30 V

V_sec=15  V

Entonces reemplazamos: 		 I_pri=1/2*V_sec/(300 Ω)

I_pri=1/2*(15 V)/(300 Ω)=0.025 A=25 mA

 **(b)** Corriente secundaria 
 
Reemplazamos  Ipri en la ecuación anterior:

(25 mA)/I_sec =1/2

I_sec=0.025 A÷1/2

I_sec=0.05 A=50 mA

**(c)** Voltaje secundario 

V_sec=n*V_pri

V_sec=1/2*30 V

V_sec=15  V

**(d)** Potencia en la carga

Recordemos que, para la potencia de carga en un trasformador ideal, la potencia en el secundario es igual a la potencia en el primario.
P_pri=V_pri*I_pri=P_sec

P_carga=30 V*0.025 A=0.75 W

P_carga=750 mW

***(17)*** ¿Cuál debe ser la relación de vueltas en la figura 14-48 para reflejar 300 Ω en el circuito primario?

[![5.jpg](https://i.postimg.cc/Qxnz2yQn/5.jpg)](https://postimg.cc/YhY8g8y1)

Recordemos que la resistencia reflejada en el circuito primario es el cuadrado del recíproco de la relación de vueltas multiplicado por la resistencia de la carga.

R_pri=(1/n)^2 R_L

300 Ω=(1/n)^2 1000 Ω

300/1000  =1/n^2 

n^2  =10/3  →n=√(10/3)=1.83

***(19)*** En la figura 14-49, ¿cuál es la potencia máxima que puede ser suministrada al altavoz de 4 Ω?

[![6.jpg](https://i.postimg.cc/rsZhLDrt/6.jpg)](https://postimg.cc/9wTPdF1W)}

R_pri=(1/n)^2 R_L

16 Ω=(1/n)^2*4 Ω

4=1/n^2   → n^2=1/4→n=√(1/4)=0.5

V_sec=0.5*25V

V_sec=12.5 V

***(21)*** En cierto transformador, la potencia de entrada al primario es de 100 W, Si se pierden 5.5 W en las resistencias de devanado, ¿cuál es la potencia de salida hacia la carga, omitiendo cualesquiera otras pérdidas
Recordamos que:

P_salida=P_entrada-5.5 W 

P_salida=100W-5.5 W 

P_sal=94.5 W

***(23)*** Determine el coeficiente de acoplamiento de un transformador en el cual un 2% del flujo total generado en el primario no pasa a través del secundario.
 
k=(100%-2%)/(100%)

k=0.98

***(25)*** ¿Qué potencia nominal en kVA se requiere para un transformador que debe manejar una corriente máxima de 10 A a través de la carga con un voltaje secundario de 2.5 kV?

I_L=P_SEC/V_sec 

10A=P_SEC/(2500 V)

P_SEC=10A*2500V

P_SEC=10A*2500V

P_SEC=25 kVA

***(27)*** Determine cada uno de los voltajes desconocidos indicados en la figura 14-51.

[![7.jpg](https://i.postimg.cc/ZRKFKTZP/7.jpg)](https://postimg.cc/PL98SnCN)

V_1=n_1/n_pri *V_pri

V_1=50/500*115V=11.5 V

V_2=  n_2/n_pri *V_pri

V_2=  100/500*115 V=23 V

V_3=  n_3/n_pri *V_pri

V_3=  100/500*115 V=23 V

V_4= V_2+V_3

V_4= 23 V+23 V

V_4= 46 V

***(29)*** Encuentre el voltaje secundario para cada uno de los autotransformadores mostrados en la figura 14-53.

[![8.jpg](https://i.postimg.cc/7ZkBrrC9/8.jpg)](https://postimg.cc/xc6GL73N)

Para la figura (a):

V_sec=n_sec/n_pri *V_pri

V_sec=200/500*120 V

V_sec=48 V

Para la figura (a):

V_sec=n_sec/n_pri *V_pri

V_sec=250/50*5V

V_sec=25 V

***(31)*** Para el transformador cargado con tomas que muestra la figura 14-55, determine lo siguiente: 

[![9.jpg](https://i.postimg.cc/TwzVjng0/9.jpg)](https://postimg.cc/dk9ZwkWZ)

**(a)** Todos los voltajes y corrientes presentes en la carga
Voltaje en IRL:

VRL=(400+300)/1200*60 V

VRL=35 V

Corriente en IRL:

IRL=(35 V)/(12 Ω)=2.91A

Voltaje en VC:

VC=300/1200*60 V

VC=15 V

Corriente en IC:

IC=(15 V)/(1.5 Ω)=1.5 A

**(b)** La resistencia reflejada en el primario
 
R_pri=(1/n)^2 Rl

R_pri=(1/(700/1200))^2*12Ω

R_pri=(1/(700/1200))^2*12Ω

R_pri=35.27 Ω

***(33)*** ¿Qué es probable que suceda si el devanado primario de un transformador se pone en cortocircuito?

Se extrae corriente primaria en exceso, potencialmente se quema la fuente y/o el transformador a menos que se proteja el primario con un fusible.

# CONCLUSIONES

Mientras estudiamos inductores e inductancia, también aprendimos sobre la inductancia mutua, lo que nos permite familiarizarnos con los transformadores, dispositivos eléctricos responsables de la distribución de electricidad, y comprender su importancia en la vida cotidiana, por ejemplo, en los postes de comunicación.

# BIBLIOGRAFÍA

Floyd,T. L. (2007). Principios de circuitos electricos. Mexico: Octava Edicion

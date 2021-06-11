# INFORME_LABORATORIO_2

Integrantes: Chachalo Mayerli, Mensias Adrian, Rosero Andres

## **PRÁCTICA No.2**

### 1.  OBJETIVO DE LA PRÁCTICA

**Objetivo general** 

Comprobar experimentalmente y analíticamente el método de mallas usado en circuitos cerrados, además de poder analizar la corriente del circuito y ver como esta interactua con los diferentes elementos del circuito.

**Objetivos específicos**

1. Reconocer los diferentes métodos para analizar las corrientes que existen en un circuito combinandolo con la Ley de Kirchhoff para la encontrar las ecuaciones que nos ayudarán a encontrar las corrientes del circuito.
2. Visualizar a simple vista un circuito en paralelo e identificar las mallas que en el se encuentran para poder encontrar la corriente en cada una de ellas.
3. Corroborar que en un circuito en paralelo el voltaje es el mismo en todo el circuito mientras que la corriente varia en las diferentes ramas del mismo.

### 2.  MARCO TEORICO

![image](https://user-images.githubusercontent.com/75383758/121648322-020b5b00-ca5d-11eb-91ef-f7f5e0514d4a.png)

### 3.  EXPLICACION DEL PROCEDIMIENTO 

3.1 **REQUISITOS PREVIOS**

Se requiere el análisis analítico del circuito mostrado en la figura 2.1, mediante la técnica del análisis de mallas. El valor obtenido de cada corriente de malla anótelo en la tabla 2.1

3.2 **NFORMACIÓN GENERAL**

El análisis de mallas es un técnica que hace uso de la LVK para expresar voltajes en funcion de corrientes.

Una malla es una trayectoria cerrada que no encierra dentro de sí a ningún elemento del circuito.

3.3 **MATERIAL Y EQUIPO REQUERIDO**

|**CANTIDAD**| **MATERIAL O EQUIPO**|
|:---: | :---: 
| 1 | Multímetro digital |
| 1 | Resistor de 820 Ω |
| 1 | Resistor de 390 Ω |
| 1 | Resistor de 1  kΩ |
| 1 | Resistor de 1.2 kΩ |
| 1 | Resistor de 2.2 kΩ |
| 1 | Protoboard |

3.2 **PROCEDIMIENTO**

 3.2.1 Implemente el circuito que se presenta en la figura 2.1.

<div align="center">
      
 ![image](https://user-images.githubusercontent.com/85126275/121592314-2258fc80-ca00-11eb-8161-5a046f387385.png)
 
  </div>
  
  3.2.2. Mida cada una de las corrientes de malla y anote los resultados en la tabla 2.1 
  
  3.2.3 Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito de la figura 2.1, obteniendo los valores de las corrientes de malla. Anote los resultados en la tabla 2.1.
  
  <div align="center">
  
  ![image](https://user-images.githubusercontent.com/75383758/121633253-0e38ed80-ca48-11eb-8c00-a4bdffe9f04b.png)
  
  ![image](https://user-images.githubusercontent.com/75383758/121633147-e3e73000-ca47-11eb-9a1f-9feac9eb42d4.png)

  ![image](https://user-images.githubusercontent.com/75383758/121641228-886f6f00-ca54-11eb-9a3e-fa661ddb5e31.png)

  ![image](https://user-images.githubusercontent.com/75383758/121641478-d97f6300-ca54-11eb-9c92-a7e457af86c8.png)
 
  ![image](https://user-images.githubusercontent.com/75383758/121643366-5b708b80-ca57-11eb-8451-05c0db151821.png) 
 
  </div>

  3.2.4 Compare los valores de la tabla 2.1 y realice sus concluciones.
  
  Tabla 2.1 REsultados obtenidos para el circuito de la figura 2.1
  
  | **MALLA** | **Resultados Analíticos** | **Resultados simulados** | **% Error** |
  | :---: | :---: | :---: | :---: |
  |   1    | 11.454 mA | 11.5 mA | -0.40 |
  |   2    | 2.847 mA | 2.85 mA | -0.11 |
  |   3    | 0.488 mA | 0.488 mA | 0 |
  |   ∑ I   | 14.789 mA | 14.838 mA | ∑ %Error = -0.51 |
  | %Error | -0.33 |       |
 
### 5.  VIDEO



### 6.  CONCLUCIONES 

1. El desarrollo de esta práctica se llevó a cabo gracias a los conocimientos impartidos en clase sobre el método de las corrientes de mallas junto con la Ley de Kirchhoff para la medición decorrientes.
2. Se pudo notar que cuando mayor sea la resistencia menos corriente pasará a través de la misma, pero si la resistencia es menor, la corriente que pase a través de ella será mucho mayor.
3. La aplicación de la Ley de Kirchhoff y el Método de las corrientes de malla nos ayuda a analizar los circuitos de CD y con esto poder entender el funcionamiento real de la CD.

### 7.  BIBLIOGRAFÍA

SENSORICX. 2021. ▷ CIRCUITOS ELECTRICOS:【ANÁLISIS DE MALLAS】. [online] Available at: <https://sensoricx.com/circuitos-electricos-dc/como-efectuar-analisis-de-circuitos-por-mallas/> [Accessed 11 June 2021].

Khan Academy. 2021. El método de la corriente de malla (artículo) | Khan Academy. [online] Available at: <https://es.khanacademy.org/science/electrical-engineering/ee-circuit-analysis-topic/ee-dc-circuit-analysis/a/ee-mesh-current-method> [Accessed 11 June 2021].

Tinkercad. 2021. Tinkercad | From mind to design in minutes. [online] Available at: <https://www.tinkercad.com/things/1gbZKV483Hd-swanky-jaagub/editel?sharecode=XsGd0cWJkEQ7PwZATgoqIyTs2gaitIF4bB-53Y8f2AE> [Accessed 11 June 2021].

García Herrera, D., 2021. Resumen Teórico y Bibliográfico de las características y propiedades de los Métodos y Teoremas más usados en la solución de los circuitos eléctricos.. Ingeniería. Universidad Central “Marta Abreu” de Las Villas.

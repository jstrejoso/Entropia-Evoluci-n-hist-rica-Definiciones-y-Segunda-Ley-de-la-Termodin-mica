# Entropía: Evolución histórica, Definiciones y Segunda Ley de la Termodinámica
*Autores:* 
* Juan Sebastián Camargo Acero
* Franky Adrian Montenegro Guevara
* Juan Sebastián Trejos Ocampo

*Curso:* Principios de Química
## Introducción
La entropía es, quizás, uno de los conceptos más incomprendidos de la química física. A menudo se despacha simplemente como "desorden", 
pero esa es una simplificación que oculta su verdadera naturaleza. En este documento, se analiza cómo el concepto mutó de ser una propiedad térmica macroscópica a una 
ley estadística y finalmente, a una medida de información.

---

## 1. Origen del concepto: Rudolf Clausius y la Calidad de la Energía (1865)
Clausius no llegó a la entropía estudiando átomos (en esa época ni siquiera se aceptaba del todo su existencia), sino analizando el rendimiento de las máquinas de vapor. Se dio cuenta de que el calor no solo se conserva, sino que se "degrada".

* *El Concepto de Irreversibilidad:* Clausius observó que los procesos naturales tienen una dirección única. El calor fluye del cuerpo caliente al frío, pero nunca al revés de forma espontánea. La entropía fue su herramienta para medir cuánto de ese calor ya no puede transformarse en trabajo útil.
* *Definición Matemática:* Él estableció que para un proceso reversible, el cambio de entropía ($dS$) es el cociente entre el calor transferido ($dQ_{rev}$) y la temperatura absoluta ($T$):
  $$dS = \frac{dQ_{rev}}{T}$$

> *Ejemplo aplicado*:
> Un ejemplo clásico es el funcionamiento de un refrigerador. Para que un refrigerador esté frío por dentro (ordenado/baja entropía),
>  necesita un motor que trabaje constantemente. Si desconectas el motor, el calor entra y todo se echa a perder (aumenta la entropía).
>  Además, si tocas la parte de atrás de la nevera, está caliente; eso demuestra que para bajar la entropía adentro, tuvimos que aumentarla afuera expulsando calor.
---
## Sobre la Dispersión o distribucion de Energía:
 Conceptualmente, la entropía puede entenderse como la *dispersión o distribución de la energía*.
 En un sistema aislado, la energía no desaparece, pero tiende a distribuirse de la manera más amplia posible entre todos los niveles energéticos disponibles.
 Cuando la energía está "concentrada", tiene baja entropía y puede producir trabajo; cuando se "dispersa",
 la entropía aumenta y la energía se vuelve térmicamente inalcanzable.

---
## 2. Aporte de la física estadística: Ludwig Boltzmann y la Probabilidad (1877)
Boltzmann dio el salto más difícil: conectar el mundo que vemos con el mundo de los átomos. Para él, la entropía dejó de ser un flujo de calor y pasó a ser una cuestión de
*estadística pura*.
relacionó la entropía con la probabilidad de que un sistema adopte diferentes configuraciones microscópicas.
Un sistema puede verse igual desde afuera, pero a nivel de partículas puede organizarse de muchas formas distintas. A esas configuraciones Boltzmann las llamó *microestados*.
Por eso propuso su famosa fórmula:


$$S = k_B \ln W$$

  Donde:

*   *S:* Entropía
*   *kB:* Constante de Boltzmann
*   *W:* Número de microestados posibles

> *Ejemplo cotidiano:*
>  Un ejemplo perfecto es abrir una botella de perfume en una esquina del salón.
>  Al principio, todas las moleculas de olor estan ordenadas dentro del frasco (baja entropía). Con el tiempo, se esparcen por todo el cuarto.
>  Según Boltzmann, esto no pasa por una fuerza mágica, sino por probabilidad: hay millones de formas (microestados)
>  de que las moléculas estén esparcidas, pero muy pocas formas de que se queden todas juntas en el frasco. La naturaleza simplemente sigue lo que es más probable

---

## 3. La Entropía de la Información: Claude Shannon (1948)
Esta es la definición "alternativa" más interesante. Shannon no era químico, trabajaba en telecomunicaciones, pero su matemática resultó ser idéntica a la de Boltzmann.
Casi un siglo después, Shannon demostró que la entropía es también una medida de la *incertidumbre*.
Si un sistema es predecible, tiene baja entropía; si es caótico o desconocido, su entropía es alta.

En su artículo "A Mathematical Theory of Communication", Shannon definió la entropía ($H$) como:

$$H(X) = - \sum_{i=1}^{n} p_i \log_b p_i$$

*Donde:*
* *$H(X)$:* Representa la incertidumbre promedio. Es una medida de cuánto nos "sorprende" el estado de un sistema.
* *$p_i$:* Es la probabilidad de que el sistema se encuentre en un estado específico. En química, esto se traduce a la probabilidad de encontrar una partícula en un microestado determinado.
* *El signo negativo ($-$):* Es un ajuste matemático necesario. Dado que las probabilidades ($p_i$) son siempre menores a 1, sus logaritmos son negativos; el signo menos asegura que el valor final de la entropía sea un número positivo.

*Fusión del hielo:*
* En el hielo, las moléculas están ordenadas -→ *entropía baja*.
* En el agua líquida, se mueven libremente -→ *entropía alta*.

> *Ejemplo cotidiano* Un ejemplo cotidiano de la entropía de Shannon es el autocompletado de mensajes en un móvil:
> * cuando se empieza una frase común como "¿Qué tal...", la probabilidad de que la siguiente palabra sea "estás" es tan alta que la incertidumbre es mínima
(baja entropía) y el mensaje apenas aporta "informacion nueva" por ser tan predecible; por el contrario, si escribes una palabra totalmente inesperada o aleatoria,
la incertidumbre aumenta (alta entropía) porque el sistema no puede predecir tu intención, demostrando que para Shannon la información es una medida de la sorpresa:
cuanto menos probable es un evento, más información transmite y mayor es su entropía.
---

## 4. Importancia Moderna y Síntesis
Hoy entendemos que la entropía es el hilo conductor entre la eficiencia de un motor, la estabilidad de una proteína y la capacidad de
almacenamiento de un disco duro. Incluso en la cosmología moderna, se estudia la entropía de los agujeros negros (fórmula de Hawking-Bekenstein), 
demostrando que la información tiene un peso físico real en el tejido del universo.

> La idea de que la información tiene un papel físico fundamental está muy presente en conceptos como el *principio holográfico*,
> lo cual conecta naturalmente con la segunda parte de nuestro trabajo en grupo.

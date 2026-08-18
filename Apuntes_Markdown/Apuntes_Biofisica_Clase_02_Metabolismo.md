# Apuntes Exhaustivos y Detallados — Clase 02: Metabolismo Celular, Energética y Bioquímica

---

> [!IMPORTANT]
> **Propósito de estos apuntes:**  
> Este documento constituye un compendio **ultra detallado y explícito** de la **Clase 02 de Biofísica**, enfocada en el tema de **Metabolismo Celular, Termodinámica Biológica, Reacciones REDOX, Enzimas, Fotosíntesis y Tensoactivos**. Ha sido redactado integrando de forma rigurosa:
> 1. Las transcripciones textuales de los audios grabados en el aula (fragmentos 88 al 173).
> 2. Los tres PowerPoints presentados para la Clase 2 (*Metabolismo*, *Fosfolípidos, detergentes y tensión superficial* y *La fotosíntesis*).
> 3. Las anotaciones manuscritas tomadas en clase sobre los PDFs.
> 4. Los resúmenes y apuntes de cursadas anteriores (archivos de Ita).
> 5. El *Cuestionario de Metabolismo* y las autoevaluaciones oficiales.
> 
> No se ha omitido ningún detalle, cálculo numérico, analogía, fórmula ni respuesta a las preguntas del cuestionario de autoevaluación.

---

## 1. Concepto General de Metabolismo y Clasificación

### 1.1 Definición
- **Metabolismo:** Es el conjunto de todas las reacciones bioquímicas y procesos fisicoquímicos organizados que ocurren en el interior de una célula o en un organismo vivo.
- **Fundamento molecular:** Las reacciones químicas celulares se producen por colisiones entre moléculas, intercambio de electrones, ruptura y formación de enlaces covalentes, y almacenamiento o liberación de energía útil.
- **Representación general:**  
  $$\text{Sustrato (A)} \xrightarrow{\text{Enzima}} \text{Producto (B)}$$

### 1.2 Las Tres Categorías de Procesos Metabólicos

```
                         PROCESOS METABÓLICOS
                                  |
     +----------------------------+----------------------------+
     |                            |                            |
 ANABOLISMO                   CATABOLISMO                 INTERCAMBIO
(Síntesis / Endergónico)    (Degradación / Exergónico)   (Reordenamiento)
 A + B --> AB                AB --> A + B                AB + CD --> AD + BC
```

#### A. Procesos Anabólicos (Anabolismo)
- **Definición:** Reacciones de **síntesis o construcción** donde se utilizan moléculas sencillas y pequeñas para formar macromoléculas complejas ($A + B \rightarrow AB$).
- **Ejemplos principales:**
  - Fotosíntesis (síntesis de glucosa a partir de $\text{CO}_2$ y $\text{H}_2\text{O}$).
  - Síntesis de proteínas (unión de aminoácidos mediante enlaces peptídicos).
  - Síntesis de glucógeno (glucogenogénesis a partir de monómeros de glucosa).
  - Síntesis de triglicéridos y ácidos nucleicos.
- **Características Termodinámicas y Químicas:**
  1. **Endergónico:** Requieren aporte obligatorio de energía externa ($\Delta F > 0$ o $\Delta G > 0$).
  2. **Proceso Reductores:** Involucran la ganancia de electrones ($\text{e}^-$) o de átomos de Hidrógeno por parte de los sustratos precursores.
  3. **Disminución de Entropía:** Generan estructuras más ordenadas ($\Delta S < 0$).

#### B. Procesos Catabólicos (Catabolismo)
- **Definición:** Reacciones de **degradación o descomposición** donde moléculas orgánicas complejas y grandes se rompen para formar estructuras simples ($AB \rightarrow A + B$).
- **Ejemplos principales:**
  - Respiración celular aeróbica (degradación de glucosa a $\text{CO}_2$ y $\text{H}_2\text{O}$).
  - Glucólisis anaeróbica.
  - Lipólisis / $\beta$-oxidación de ácidos grasos.
- **Características Termodinámicas y Químicas:**
  1. **Exergónico:** Liberan energía química útil ($\Delta F < 0$ o $\Delta G < 0$).
  2. **Procesos Oxidantes:** Involucran la pérdida de electrones ($\text{e}^-$) o de átomos de Hidrógeno por parte de las moléculas orgánicas.
  3. **Aumento de Entropía:** Producen un mayor desorden molecular ($\Delta S > 0$).

#### C. Procesos de Intercambio
- Reacciones donde se reordenan átomos o grupos funcionales entre moléculas sin cambiar la complejidad neta ($AB + CD \rightarrow AD + BC$).

---

## 2. Termodinámica Biológica, Energía Libre y Acoplamiento Energético

### 2.1 Energía Libre de Gibbs / Helmholtz ($\Delta F$ o $\Delta G$)
- **Definición:** La **Energía Libre ($\Delta F$)** representa la cantidad máxima de **trabajo útil** que puede realizar un sistema químico a temperatura y presión constantes.
  $$\Delta F = \Delta H - T \Delta S$$
  - $\Delta H$: Variación de entalpía (calor intercambiado a presión constante).
  - $T$: Temperatura absoluta en Kelvin ($\text{K}$).
  - $\Delta S$: Variación de entropía (grado de desorden del sistema).

### 2.2 Criterio de Espontaneidad Termodinámica

| Tipo de Reacción | Signo de $\Delta F$ | Comportamiento Energético | Espontaneidad |
| :--- | :--- | :--- | :--- |
| **Exergónica (Catabólica)** | **$\Delta F < 0$** | **Libera energía útil** al entorno | **Espontánea** |
| **Endergónica (Anabólica)** | **$\Delta F > 0$** | **Requiere energía** del entorno | **NO espontánea** |
| **Equilibrio Químico** | **$\Delta F = 0$** | Sin cambio neto de energía libre | Sistema en equilibrio |

- **Importante:** La espontaneidad ($\Delta F < 0$) indica que la reacción es termodinámicamente favorable, pero **no nos dice nada sobre la velocidad** a la que ocurrirá la reacción (la velocidad depende de la *Energía de Activación* y de las enzimas).

---

### 2.3 Acoplamiento Energético y Eficiencia Energética

- **El problema biológico:** Las reacciones anabólicas (como construir proteínas o glucógeno) poseen un $\Delta F > 0$, por lo que jamás ocurrirían espontáneamente por sí solas.
- **La solución celular (Acoplamiento):** La célula acopla una reacción endergónica ($\Delta F > 0$) a una reacción fuertemente exergónica ($\Delta F < 0$, como la hidrólisis de ATP), de modo que la **suma total de las Energías Libres sea negativa ($\Delta F_{neto} < 0$)**.

```
Reacción Endergónica (+ΔF)  \
                             --> Reacción Neta Acoplada (ΔF_neto < 0) [ESPONTÁNEA]
Reacción Exergónica (-ΔF)  /
```

#### Ejemplo Numérico Exacto de Clase (Síntesis de Glucógeno):
1. **Reacción Endergónica (Síntesis):**  
   $$\text{Glucógeno}_n + \text{Glucosa} \rightarrow \text{Glucógeno}_{n+1} + \text{H}_2\text{O} \quad \Delta F_1 = +4,2\text{ kcal/mol}$$
2. **Reacción Exergónica (Hidrólisis de ATP):**  
   $$\text{ATP} + \text{H}_2\text{O} \rightarrow \text{ADP} + \text{P}_i \quad \Delta F_2 = -8,0\text{ kcal/mol}$$
3. **Reacción Acoplada Resultante:**  
   $$\text{Glucógeno}_n + \text{Glucosa} + \text{ATP} \rightarrow \text{Glucógeno}_{n+1} + \text{ADP} + \text{P}_i$$
   $$\Delta F_{neto} = (+4,2) + (-8,0) = \mathbf{-3,8\text{ kcal/mol}}$$
   *Como $\Delta F_{neto} < 0$, el proceso global es exergónico y ocurre de forma espontánea.*

#### Cálculo de la Eficiencia Energética del Acoplamiento:
$$\text{Eficiencia} = \frac{|\text{Energía Útil Aprovechada}|}{|\text{Energía Total Entregada por ATP}|} = \frac{4,2\text{ kcal}}{8,0\text{ kcal}} = \mathbf{0,525 = 52,5\%}$$
- **Destino del resto de la energía:** El **$47,5\%$ restante** no se pierde en vano; se disipa en forma de **calor**, lo que permite mantener constante la temperatura corporal en animales homeotermos.

---

## 3. Reacciones de Óxido-Reducción (REDOX) en Bioquímica

### 3.1 Definición Rigurosa
Toda reacción de óxido-reducción involucra la transferencia simultánea de electrones de una especie química a otra.

```
Oxidación: Pérdida de e- (o de H) / Incrementa número de oxidación / Libera energía
Reducción: Ganancia de e- (o de H) / Disminuye número de oxidación / Requiere energía
```

1. **Oxidación:**
   - Pérdida de electrones ($\text{e}^-$) o pérdida de átomos de Hidrógeno ($\text{H}$).
   - Aumento en el número de oxidación.
   - En biología, la oxidación de sustancias orgánicas (como la glucosa) libera energía (**procesos catabólicos**).
   - Ejemplo simple: $\text{Fe}^{+2} \rightarrow \text{Fe}^{+3} + \text{e}^-$ (el Hierro $+2$ se oxida a $+3$).
2. **Reducción:**
   - Ganancia de electrones ($\text{e}^-$) o ganancia de átomos de Hidrógeno ($\text{H}$).
   - Disminución en el número de oxidación.
   - En biología, la reducción fija energía en los enlaces químicos (**procesos anabólicos**).
   - Ejemplo simple: $\text{Cu}^{+2} + 2\text{e}^- \rightarrow \text{Cu}^0$ (el Cobre $+2$ se reduce a Cobre metálico).

---

### 3.2 Análisis Práctico de las Reacciones del Cuestionario de Autoevaluación

Para resolver los parciales y el cuestionario oficial, debemos clasificar cada reacción:

1. **$\text{Fe}^{+2} \rightarrow \text{Fe}^{+3}$**  
   - *Clasificación:* **Oxidación**. El Hierro pierde 1 electrón (el número de oxidación sube de $+2$ a $+3$).
2. **$\text{CH}_3-\text{CHO} + \text{H}_2 \rightarrow \text{CH}_3-\text{CH}_2\text{OH}$ (Etanal a Etanol)**  
   - *Clasificación:* **Reducción**. La molécula orgánica gana dos átomos de Hidrógeno.
3. **$2\text{Mg} + \text{O}_2 \rightarrow 2\text{MgO}$**  
   - *Clasificación:* **Óxido-Reducción (REDOX)**. El magnesio se oxida ($\text{Mg}^0 \rightarrow \text{Mg}^{+2}$) y el oxígeno se reduce ($\text{O}^0 \rightarrow \text{O}^{-2}$). Es una reacción exotérmica de síntesis (sin biomoléculas).
4. **$2\text{H}_2\text{O} \rightarrow 2\text{H}_2 + \text{O}_2$**  
   - *Clasificación:* **Óxido-Reducción (REDOX)**. Descomposición endotérmica del agua. El Oxígeno se oxida ($\text{O}^{-2} \rightarrow \text{O}^0$) y el Hidrógeno se reduce ($\text{H}^+ \rightarrow \text{H}^0$).
5. **$\text{C}_6\text{H}_{12}\text{O}_6 + 6\text{O}_2 \rightarrow 6\text{CO}_2 + 6\text{H}_2\text{O}$ (Respiración celular)**  
   - *Clasificación:* **Óxido-Reducción (REDOX)**. La glucosa se **oxida** totalmente a $\text{CO}_2$, mientras que el $\text{O}_2$ se **reduce** a $\text{H}_2\text{O}$. Proceso catabólico y exergónico.
6. **$6\text{CO}_2 + 6\text{H}_2\text{O} \rightarrow \text{C}_6\text{H}_{12}\text{O}_6 + 6\text{O}_2$ (Fotosíntesis)**  
   - *Clasificación:* **Óxido-Reducción (REDOX)**. El $\text{CO}_2$ se **reduce** a glucosa y el $\text{H}_2\text{O}$ se **oxida** a $\text{O}_2$. Proceso anabólico y endergónico.
7. **$\text{C}_{16}\text{H}_{32}\text{O}_2 + 23\text{O}_2 \rightarrow 16\text{CO}_2 + 16\text{H}_2\text{O}$ (Respiración del Ácido Palmítico)**  
   - *Pregunta del cuestionario:* ¿Es el $\text{C}_{16}\text{H}_{32}\text{O}_2$ un hidrato de carbono?  
   - *Respuesta:* **NO**. La fórmula de un hidrato de carbono requiere 1 Oxígeno por cada Carbono ($C_n H_{2n} O_n$). El $\text{C}_{16}\text{H}_{32}\text{O}_2$ posee solo 2 Oxígenos para 16 Carbonos; se trata de un **ácido graso saturado (Ácido Palmítico)**, un lípido.

---

## 4. Respiración Celular vs. Combustión

### 4.1 Cuadro Comparativo Estricto

| Parámetro | Combustión de la Glucosa / Madera | Respiración Celular Aeróbica |
| :--- | :--- | :--- |
| **Ecuación Química** | $\text{C}_6\text{H}_{12}\text{O}_6 + 6\text{O}_2 \rightarrow 6\text{CO}_2 + 6\text{H}_2\text{O}$ | $\text{C}_6\text{H}_{12}\text{O}_6 + 6\text{O}_2 \rightarrow 6\text{CO}_2 + 6\text{H}_2\text{O}$ |
| **Control del Proceso** | Incontrolado, directo en un solo paso. | Altamente regulado por enzimas en múltiples pasos. |
| **Forma de Liberación de Energía** | Violenta y repentina en forma de **calor y luz**. | En pasos discretos acoplados a la síntesis de **ATP**. |
| **Eficiencia Útil** | **$0\%$ trabajo útil** ($100\%$ disipación térmica). | **$\sim 40\% - 50\%$ de eficiencia** en formación de ATP. |
| **Requerimiento Enzimático** | No requiere enzimas (solo llama/calor inicial). | Requiere enzimas específicas en citosol y mitocondria. |

### 4.2 Respiración Aeróbica vs. Anaeróbica
- **Respiración Aeróbica (con $\text{O}_2$):**
  - Ocurre en la **mitocondria**.
  - Oxidación completa de la glucosa hasta $\text{CO}_2$ y $\text{H}_2\text{O}$.
  - El $\text{O}_2$ actúa como el **aceptor final de electrones**.
  - Rendimiento energéticamente elevado: **$36 \text{ a } 38\text{ ATP}$ por molécula de glucosa**.
- **Respiración Anaeróbica / Fermentación (sin $\text{O}_2$):**
  - Ocurre en el **citosol**.
  - Oxidación parcial (ej. glucólisis + fermentación láctica en el músculo esquelético o alcohólica en levaduras).
  - Rendimiento energético muy pobre: solo **$2\text{ ATP}$ por glucosa**.

---

## 5. Fotosíntesis: Aspectos Generales y la Hipótesis de Van Niel

### 5.1 Ecuación y Concepto General en Plantas
- **Ecuación:** $6\text{CO}_2 + 6\text{H}_2\text{O} + \text{Energía Lumínica} \rightarrow \text{C}_6\text{H}_{12}\text{O}_6 + 6\text{O}_2$
- Proceso **anabólico y endergónico**. La luz solar (espectro visible $\sim 400 - 700\text{ nm}$) aporta la energía para reducir el $\text{CO}_2$ atmosférico (incorporado por estomas) y sintetizar glucosa. El agua proviene de las raíces.

---

### 5.2 Tiobacterias Púrpuras y la Ecuación Generalizada de Van Niel

- **El Descubrimiento:** Cornelis van Niel estudió las **tiobacterias púrpuras**, microorganismos fotosintéticos autótrofos anoxigénicos que no utilizan agua ($\text{H}_2\text{O}$), sino **sulfuro de hidrógeno ($\text{H}_2\text{S}$)**.
- **Reacción de las Tiobacterias Púrpuras:**
  $$6\text{CO}_2 + 12\text{H}_2\text{S} + \text{Luz} \rightarrow \text{C}_6\text{H}_{12}\text{O}_6 + 6\text{H}_2\text{O} + 12\text{S}$$
  - *Producto liberado:* En lugar de liberar Oxígeno ($\text{O}_2$), depositan glóbulos de **Azufre elemental ($\text{S}$)**.

```
PLANTAS TERRESTRES:       6 CO2 + 12 H2O + Luz  -->  C6H12O6 + 6 H2O + 6 O2 (Oxígeno)
TIOBACTERIAS PÚRPURAS:    6 CO2 + 12 H2S + Luz  -->  C6H12O6 + 6 H2O + 12 S (Azufre)
```

- **Ecuación Generalizada de Van Niel:**
  $$\text{CO}_2 + 2\text{H}_2\text{A} + \text{Luz} \rightarrow (\text{CH}_2\text{O}) + \text{H}_2\text{O} + 2\text{A}$$
  - En plantas: $\text{H}_2\text{A} = \text{H}_2\text{O} \implies 2\text{A} = \text{O}_2$.
  - En tiobacterias: $\text{H}_2\text{A} = \text{H}_2\text{S} \implies 2\text{A} = 2\text{S}$.
  - **Conclusión fundamental de Van Niel:** Todo el Oxígeno gas ($\text{O}_2$) liberado en la fotosíntesis de las plantas proviene de la **fotólisis del agua ($\text{H}_2\text{O}$)** y NO del dióxido de carbono ($\text{CO}_2$).

- **Demostración Experimental con el Isótopo Pesado $^{18}\text{O}$:**
  - Se incubaron plantas aportando agua marcada con el isótopo pesado de oxígeno $^{18}\text{O}$ ($\text{H}_2^{18}\text{O}$) y $\text{CO}_2$ normal.
  - El gas liberado resultó ser completamente $^{18}\text{O}_2$ pesado.
  - Esto **CONFIRMÓ la hipótesis de Van Niel** y demostró que el agua se oxida liberando $\text{O}_2$, mientras que los átomos de Oxígeno del $\text{CO}_2$ terminan en la molécula de glucosa y en el agua de síntesis.

---

## 6. Las Enzimas: Catalizadores Biológicos

### 6.1 Naturaleza Química y Función
- **Naturaleza:** La inmensa mayoría de las enzimas son **proteínas** (polímeros de aminoácidos cuya estructura primaria está codificada en el ADN).
- **Función:** Actúan como **catalizadores biológicos**, aumentando la velocidad de las reacciones químicas celulares entre $10^6$ y $10^{12}$ veces.

### 6.2 Disminución de la Energía de Activación ($E_{act}$)
- **Barrera de Activación:** Para que los sustratos reaccionen, se debe entregar una energía mínima inicial (Energía de Activación, $E_{act}$) para tensionar los enlaces e ingresar al estado de transición.
- **Acción Enzimática:** La enzima se une al sustrato en su **sitio activo**, orientándolo y estabilizando el estado de transición, lo que **disminuye drásticamente la Energía de Activación**.

```
Energía
   ^        Sin Enzima (Ea alta)
   |        /\
   |       /  \   Con Enzima (Ea baja)
   |      /    \  /\
   |  Sustrato  \/  \
   |                 \------> Productos
   +-------------------------------------> Progreso de la Reacción
```

- **REGLAS DE ORO SOBRE LAS ENZIMAS (Preguntas típicas de examen):**
  1. **NO alteran el cambio de Energía Libre ($\Delta F$ o $\Delta G$)** de la reacción. Si una reacción es endergónica, seguirá siéndolo con o sin enzima.
  2. **NO cambian la posición del equilibrio químico**, solo aceleran el tiempo en que se alcanza dicho equilibrio.
  3. **NO son consumidas ni alteradas permanentemente** durante la reacción.

---

### 6.3 Propiedades y Características de las Enzimas

1. **Especificidad:**
   - Poseen un **sitio activo** estructurado por el plegamiento 3D de la proteína.
   - Interacción basada en el modelo de *llave-cerradura* o *ajuste inducido*. Una enzima es específica para un determinado sustrato o reacción (ej. la enzima *sacarasa* solo degrada sacarosa).
2. **Cinética de Saturación:**
   - A bajas concentraciones de sustrato, al aumentar el sustrato aumenta la velocidad de reacción.
   - A concentraciones muy altas de sustrato, todos los sitios activos de las enzimas están ocupados ($100\%$ de saturación), alcanzándose una **Velocidad Máxima ($V_{max}$)** constante.

```
Velocidad (V)
   ^
Vmax|...............-------------- (Saturación de enzimas)
    |             /
    |            /
    +-----------------------------> Concentración de Sustrato [S]
```

3. **Dependencia de la Temperatura y el pH (Óptimos Enzimáticos):**
   - **Temperatura Óptima:** En seres humanos, la temperatura óptima es $\sim 37^\circ\text{C}$. A temperaturas muy altas ($>50^\circ\text{C}$), la enzima se **denatura** (se despliega térmicamente, pierde su estructura 3D y deja de funcionar). A bajas temperaturas, disminuye la energía cinética pero no se denatura.
   - **pH Óptimo:** Cada enzima tiene un pH de máxima actividad (ej. Pepsina gástrica a $\text{pH } 2,0$; Tripsina pancreática a $\text{pH } 8,0$). Variaciones extremas de pH alteran las cargas eléctricas de los aminoácidos del sitio activo y denaturan la proteína.
4. **Enzimas Alostéricas:**
   - Poseen sitios de regulación distintos del sitio activo (sitios alostéricos). La unión de un metabolito efector (activador o inhibidor alostérico) modifica la conformación de la enzima, regulando su actividad de forma variable.

---

## 7. Tensoactivos, Detergentes, Jabones y Fluidez de Membrana

### 7.1 Saponificación y Emulsión de Lípidos
- **Reacción de Saponificación:** Hidrólisis alcalina de triglicéridos con una base fuerte ($\text{NaOH}$ o $\text{KOH}$) para producir **glicerol** y sales sódicas/potásicas de ácidos grasos (**jabones**).
- **Acción Emulsionante:**
  - Los jabones y detergentes son moléculas anfipáticas.
  - Al mezclarse con agua y grasas, las colas lipofílicas se introducen en las gotas de grasa y las cabezas polares quedan en contacto con el agua, formando **micelas**.
  - Esto "emulsiona" la grasa, suspendiéndola en agua para poder ser arrastrada.

```
       Grasa en el centro
         \   / 
       O==||==O
       O==||==O   <-- Micela emulsionante (cabezas O hacia el agua, colas || hacia la grasa)
         /   \
```

### 7.2 Disminución de la Tensión Superficial
- Los jabones y detergentes son **tensoactivos o surfactantes**.
- Se intercalan en la interfaz agua-aire, debilitando los puentes de hidrógeno entre las moléculas de agua de la superficie y **disminuyendo la tensión superficial del agua**.

### 7.3 Fluidez Lipídica de las Membranas
- **Insaturaciones y Codos ("Kinks"):** Los ácidos grasos insaturados poseen dobles enlaces *cis* que generan codos en la cadena, impidiendo que los fosfolípidos se empaqueten rígidamente.
- **Fluidez:** A mayor porcentaje de fosfolípidos insaturados en la membrana, mayor es la **fluidez lipídica**.
- *Adaptación en animales abisales:* Los animales de profundidades marinas (ambientes de muy baja temperatura y alta presión) poseen membranas biológicas ricas en **altos porcentajes de fosfolípidos insaturados ($\sim 8\%$)** para evitar que sus membranas se congelen o vuelvan rígidas.

---

## 8. Resolución Explicada de Problemas y Ejercicios del Cuestionario

### 8.1 El Experimento del Ingeniero y la Sacarosa (Problema 41 del Cuestionario)
- **Consigna:** En un tanque a $20^\circ\text{C}$ con agua, se mezclan $1\text{ kg}$ de glucosa + $1\text{ kg}$ de fructosa.  
  - *Prueba 1 (30 min a $20^\circ\text{C}$):* Se forman $10\text{ g}$ de sacarosa.
  - *Prueba 2 (30 min a $20^\circ\text{C} + 0,1\text{ g}$ de sustancia X):* Se forman $100\text{ g}$ de sacarosa.
  - *Prueba 3 (30 min a $55^\circ\text{C} + 0,1\text{ g}$ de sustancia X):* Se forman nuevamente $10\text{ g}$ de sacarosa.
- **Respuestas y Justificaciones:**
  - **a) ¿De qué tipo de reacción se trata?**  
    Es una reacción de **síntesis (anabólica y endergónica)**, un condensación de dos monosacáridos para formar un disacárido (sacarosa).
  - **b) ¿Qué tipo de biomolécula es la fructosa?**  
    Es un **hidrato de carbono (monosacárido, cetohexosa)**.
  - **c) ¿Qué tipo de sustancia es la sustancia X?**  
    La sustancia X es un **catalizador biológico / ENZIMA** (específicamente la *sacarosa sintasa* o *sacarasa*), ya que aceleró 10 veces la cantidad de producto formado en el mismo tiempo sin consumirse en grandes cantidades ($0,1\text{ g}$).
  - **d) ¿Cómo se explican los resultados de la tercera prueba a $55^\circ\text{C}$?**  
    A $55^\circ\text{C}$, la elevada temperatura provocó la **denaturación térmica de la enzima X** (pérdida de su estructura 3D nativa y destrucción de su sitio activo). Al inactivarse la enzima, la reacción volvió a ocurrir a su velocidad lenta no catalizada, obteniéndose los mismos $10\text{ g}$ iniciales de la prueba 1.

---

### 8.2 Verdadero / FALSO sobre Afirmaciones de Examen

1. **"Las enzimas no siempre contienen nitrógeno."**  
   **FALSO.** Las enzimas son proteínas, polímeros de aminoácidos, y todos los aminoácidos poseen un grupo amino ($-\text{NH}_2$) con átomos de Nitrógeno.
2. **"Sin la enzima, una reacción metabólica no podría producirse."**  
   **FALSO.** La reacción puede ocurrir de forma no catalizada de manera espontánea si $\Delta F < 0$, pero tardaría muchísimo más tiempo porque requiere una mayor Energía de Activación ($E_{act}$).
3. **"Una enzima $E_1$ que cataliza $A + B \rightarrow C$ puede catalizar también $C \rightarrow A + B$."**  
   **VERDADERO.** Las enzimas catalizan las reacciones en ambos sentidos hacia el equilibrio químico, aunque en la célula la dirección neta la determinan las concentraciones de sustrato y producto.
4. **"La respiración celular de un lípido es un proceso endergónico."**  
   **FALSO.** La respiración celular de cualquier biomolécula (glucosa o lípido) es un proceso **catabólico y exergónico** ($\Delta F < 0$), que libera energía.
5. **"La fotosíntesis genera más $\text{O}_2$ del que consumen las plantas en su respiración."**  
   **VERDADERO.** Durante el día, la tasa fotosintética neta supera la tasa respiratoria, permitiendo la acumulación de biomasa y la liberación neta de $\text{O}_2$ a la atmósfera.
6. **"Las plantas fotosintetizan de día y respiran solo de noche."**  
   **FALSO.** Las plantas fotosintetizan de día (en presencia de luz), pero **respiran continuamente las 24 horas del día** (día y noche) para mantener sus procesos celulares vivos.

---
*Fin de los apuntes completos de la Clase 02.*

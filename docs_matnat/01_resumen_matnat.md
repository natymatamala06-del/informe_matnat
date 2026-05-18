# Reporte de Caso: Ataque Global Ransomware WannaCry

## 1. ¿Qué pasó?
WannaCry fue una epidemia global de ransomware de cifrado que se propagó bajo la modalidad de **gusano (*worm*)**. A diferencia de otros ataques, esto le permitió infectar masivamente redes sin necesidad de interacción humana (como hacer clic en un enlace) o campañas de phishing.

* **Vulnerabilidad:** Explotaba una falla en el protocolo **SMB de Windows** denominada *EternalBlue*.
* **Origen técnico:** Dicha vulnerabilidad fue desarrollada originalmente por la **NSA** (Agencia de Seguridad Nacional de EE. UU.) y filtrada por el grupo *The Shadow Brokers*.
* **Modus Operandi:** Una vez infectado el sistema, el virus cifraba archivos valiosos y exigía un rescate de **300 a 600 dólares en Bitcoin** para recuperar el acceso.

---

## 2. Cronología
* **Fecha de inicio:** Mayo de 2017.
* **Velocidad de propagación:** El impacto fue inmediato, logrando infectar la gran mayoría de los equipos afectados en apenas **24 horas**.

---

## 3. Actores Involucrados

| Actor | Identidad / Descripción |
| :--- | :--- |
| **Responsables** | Se vincula a **Corea del Norte** o al grupo cibercriminal **Lazarus Group**. |
| **Víctimas** | +230,000 ordenadores en 150 países (Telefónica, NHS Reino Unido, Boeing). |
| **Figura Clave** | **Marcus Hutchins**, quien activó un *kill switch* (interruptor de eliminación). |

---

## 4. Impacto del Caso

### 💰 Impacto Financiero
Se estima que el cibercrimen provocó pérdidas globales por un valor aproximado de **4.000 millones de dólares**.

### 🏥 Salud Pública
El impacto más crítico se vivió en el Reino Unido con el **Servicio Nacional de Salud (NHS)**:
* **Un tercio** de sus fundaciones hospitalarias fueron comprometidas.
* Se cancelaron **19,000 citas médicas**.
* Desvío de ambulancias, poniendo en riesgo la atención de pacientes en estado crítico.

### ⚙️ Impacto Operativo
Sistemas críticos de transporte, fabricación y servicios gubernamentales quedaron paralizados a nivel mundial. 

> **Nota de Seguridad:** La crisis se agravó debido al uso masivo de **sistemas operativos obsoletos** o sin los parches de seguridad que Microsoft había liberado meses antes del ataque, evidenciando una falta de cultura de actualización.
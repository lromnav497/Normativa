# Uso de RAG para consultas sobre normativa: Sanciones por Intrusión en Servidores con Datos Personales

La normativa española de protección de datos, principalmente la **Ley Orgánica 3/2018 (LGTDPYGDD)** y el **Reglamento General de Protección de Datos (RGPD)**, establece un régimen sancionador administrativo. La intrusión en servidores que contienen datos personales se considera una **violación de seguridad** y puede acarrear graves consecuencias administrativas, sin perjuicio de las acciones civiles o penales.

---

## I. Sanciones Aplicables a Infracciones Relacionadas con la Protección de Datos

El RGPD establece un sistema de sanciones o actuaciones correctivas que permite un amplio margen de apreciación, buscando que estas sean **efectivas, proporcionadas y disuasorias**.

### A. Tipos de Infracciones y Multas Administrativas (RGPD/LGTDPYGDD)

Las infracciones se clasifican a efectos de prescripción y cuantía de la sanción, aunque la descripción de las conductas es ejemplificativa dentro de los tipos generales de la norma europea:

#### 1. Infracciones Graves

Suelen estar relacionadas con el incumplimiento de obligaciones del responsable o encargado del tratamiento, como:

* La falta de adopción de medidas técnicas y organizativas apropiadas para garantizar un nivel de seguridad adecuado al riesgo del tratamiento, en los términos exigidos por el **artículo 32.1 del RGPD**.
* El quebrantamiento de las medidas técnicas y organizativas implementadas, como consecuencia de la falta de la debida diligencia.
* No disponer del registro de actividades de tratamiento o no ponerlo a disposición de la autoridad de protección de datos cuando se solicite.
* El incumplimiento del deber de notificación a la autoridad de protección de datos de una violación de seguridad.

#### 2. Infracciones Muy Graves

Relacionadas con la vulneración de principios fundamentales del tratamiento o derechos de los afectados. Estas pueden llevar a multas más elevadas. Ejemplos incluyen:

* Tratamiento de datos personales vulnerando los principios y garantías establecidos en el **artículo 5 del RGPD**, como el principio de integridad y confidencialidad.
* Tratamiento de datos personales sin que concurra una base de licitud (**Art. 6 RGPD**).
* Transferencia internacional de datos sin garantías o requisitos establecidos.
* El incumplimiento de resoluciones dictadas por la autoridad de protección de datos.

### B. Cuantía de las Multas (RGPD)

El RGPD establece los siguientes límites para la imposición de multas administrativas, que se aplican teniendo en cuenta criterios de graduación (como naturaleza, gravedad, duración, intencionalidad o las categorías de datos afectados):

* **Multas de hasta 10.000.000 EUR** o, si se trata de una empresa, de una cuantía equivalente al **2 % del volumen de negocio total anual global** del ejercicio financiero anterior, optándose por la cuantía superior, aplicables a infracciones específicas como el incumplimiento de las obligaciones del responsable y encargado del tratamiento.
* **Multas de hasta 20.000.000 EUR** o, si se trata de una empresa, de una cuantía equivalente al **4 % del volumen de negocio total anual global**, optándose por la cuantía superior, aplicables a infracciones relativas a los principios básicos del tratamiento (**Art. 5**) o los derechos de los interesados (**Artículos 12 a 22**).

Además, las resoluciones sancionadoras por infracciones muy graves (si la multa supera 1 millón de euros y el infractor es persona jurídica) pueden ser **publicadas en el Boletín Oficial del Estado (BOE)** por la Agencia Española de Protección de Datos (AEPD).

---

## II. Caso Práctico: Intrusión en Servidor con Datos Personales

### 1. Delito o Infracción Planteada

Una empresa proveedora de servicios de la sociedad de la información (PSI) que aloja una base de datos con información de contacto y datos financieros de sus clientes (**datos personales**), sufre una intrusión no autorizada en uno de sus servidores. El atacante accede y extrae los datos personales.

La acción constituye una **violación de la seguridad de los datos personales** y, si bien la intrusión como tal puede ser un **delito penal**, para efectos administrativos implica el incumplimiento de varias obligaciones.

### 2. Posibles Consecuencias Penales o Administrativas

#### A. Consecuencias Administrativas (Protección de Datos)

La intrusión revela un posible incumplimiento del deber de seguridad y el principio de integridad y confidencialidad:

1. **Infracción de Seguridad:** La falta de medidas técnicas y organizativas adecuadas para garantizar la seguridad del tratamiento (**Art. 32.1 RGPD**) o el quebrantamiento de las mismas por falta de diligencia se tipifica como infracción grave.
2. **Infracción por Violación de Principios:** El tratamiento de datos personales vulnerando el principio de integridad y confidencialidad se tipifica como infracción muy grave.
3. **Incumplimiento del Deber de Notificación:** Si la empresa no notifica la violación de seguridad de los datos personales a la AEPD en el plazo de 72 horas (a menos que sea improbable que constituya un riesgo), cometería una infracción grave.
4. **Falta de Comunicación a los Afectados:** Si la violación entraña un alto riesgo para los derechos y libertades de los afectados, la empresa debe comunicárselo a los interesados. El incumplimiento de este deber, si es requerido por la autoridad de protección de datos, constituye una infracción grave. Si el alto riesgo existe pero no se comunica, podría ser una infracción leve (salvo que sea aplicable la infracción grave).

#### B. Consecuencias Penales y Civiles

1. **Responsabilidad Penal:** Las acciones administrativas son independientes de las acciones penales que puedan ser procedentes. La Ley establece que las responsabilidades que deriven del incumplimiento de normas no son solo de orden administrativo, sino también **civil o penal**, según los bienes jurídicos afectados.

   * La autoridad judicial competente tiene el poder exclusivo para adoptar medidas restrictivas en ciertos casos. La autoridad de asignación de nombres de dominio puede suspender o cancelar nombres de dominio cuando se esté cometiendo un delito tipificado en el Código Penal, según requerimiento judicial previo.
2. **Responsabilidad Civil:** El titular de los derechos infringidos (los clientes afectados) puede exigir el cese de la actividad ilícita y la indemnización de los daños materiales y morales causados. La indemnización cubre tanto la pérdida sufrida como la ganancia dejada de obtener.

---

## Enlaces de Referencias (Documentos Fuente)

* Excerpts from **"BOE-A-1996-8930-consolidado.pdf"** (Ley de Propiedad Intelectual)
* Excerpts from **"BOE-A-2002-13758-consolidado.pdf"** (Ley de Servicios de la Sociedad de la Información y de Comercio Electrónico - LSSI)
* Excerpts from **"BOE-A-2018-16673-consolidado.pdf"** (Ley Orgánica 3/2018, de Protección de Datos Personales y garantía de los derechos digitales - LGTDPYGDD)
* Excerpts from **"BOE-A-2022-7191-consolidado.pdf"** (Real Decreto por el que se regula el Esquema Nacional de Seguridad - ENS)
* Excerpts from **"CELEX_32016R0679_ES_TXT.pdf"** (Reglamento General de Protección de Datos - RGPD)
* Excerpts from **"Documento_Norma_UNE-EN_ISO-IEC_27001_MINTUR.pdf"** (ISO/IEC 27001)
* Excerpts from **"Documento_Norma_UNE-EN_ISO-IEC_27002_MINTUR.pdf"** (ISO/IEC 27002)

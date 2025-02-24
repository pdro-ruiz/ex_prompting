# Cartera de Prompts

A continuación se muestra una cartera (o “portafolio”) de prompts en un contexto narrativo postapocalíptico. 
- Cada paso incluye su fecha
- el prompt
- notas sobre la mejor salida de entre varios modelos

Los prompts están encapsulados en bloques de código para facilitar su consulta y uso.


## Paso 1: Crear contexto para los Modelos

**Fecha:** 2025/02/22 18:57  
**Modelos probados:** `o3-mini` -vs- `Deepsheek v3` -vs- `grok3` -vs- `claude-3-sonnet`

**Prompt**:
```text
Eres un médico de la resistencia en un mundo postapocalíptico con una gran experiencia en resistencia urbana. Quiero que para evaluar la sumisión y conformismo social al gran hermano implantado por el conglomerado MOM Corp. diseñes un cuestionario de 5 preguntas para diagnosticar qué tan 'enfermo' está alguien por el conformismo social y qué grado de riesgo supone para la resistencia. Usa este ejemplo como guía: ¿Tus sueños son tuyos o te los vendieron?
```

**Modelo seleccionado** `claude-3-sonnet-20240229`


## Paso 2: Dando contexto a los Modelos

**Fecha:** 2025/02/22 19:12  
**Modelos probados:** `o3-mini` -vs- `Deepsheek v3` -vs- `grok3` -vs- `claude-3-sonnet`

**Prompt**:
```text
- contexto: salida Paso 1: Crear contexto para los Modelos
```

**Modelo seleccionado**  `grok3`


## Paso 3: Tácticas de resistencia

**Fecha:** 2025/02/22 19:41  
**Modelos probados:** `o3-mini` -vs- `Deepsheek v3` -vs- `grok3` -vs- `claude-3-sonnet`

**Prompt**:
```text
Dado el cuestionario anterior, quiero que elabores un plan de tácticas de resistencia.
```

**Modelo seleccionado** `grok3`


## Paso 4: Contexto para una imagen

**Fecha:** 2025/02/23 10:35  
**Modelos probados:** `o3-mini` -vs- `Deepsheek v3` -vs- `grok3` -vs- `claude-3-sonnet`

**Prompt**:
```text
Ayudarte a describir cómo podría verse una imagen basada en este contexto para que pueda crearla o encargársela a un diseñador. Aquí tienes una descripción detallada: “Salida Paso 2 dando contexto a los modelos”
```

**Modelo seleccionado** `Deepsheek v3`


## Paso 5: Crear imagen

**Fecha:** 2025/02/23 10:47  
**Modelo probado:** `Grok3`

**Prompt**:
```text
Crea una imagen: "Salida del Paso 4: Contexto para una imagen"
```


## Paso 6: Prompt para el formulario

**Fecha:** 2025/02/23 11:14  
**Modelos probados:** `o3-mini` -vs- `Deepsheek v3` -vs- `grok3` -vs- `claude-3-sonnet`

**Prompt**:
```text
Genera un prompt para crear la imagen de un formulario para que sea repartido y difundido clandestinamente con las siguientes características: Salida del Paso 2 dando contexto a los modelos
```

**Modelo seleccionado** `grok3`


## Paso 8: Imagen formulario

**Fecha:** 2025/02/24 16:00  
**Modelo seleccionado** `Grok3`

**Prompt**:
```text
Quiero que generes una imagen hiperrealista de este formulario. El texto debe ser el foco principal de la imagen. El formulario debe tener un aspecto gastado, arrugado, y con la tinta corrida, con un aspecto artesanal. Que aparezca únicamente la primera página.

| **CUESTIONARIO DE EVALUACIÓN DE CONFORMIDAD SOCIAL (C.E.C.S.)** |
|-----------------------------------------------------------|
| _"La verdad duele, pero la mentira mata"_                   |
| **ADVERTENCIA:** Este cuestionario puede despertar pensamientos prohibidos por MOM Corp. |
```

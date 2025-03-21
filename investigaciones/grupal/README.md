# Análisis grupal

## Consolidación de datos

- Evaluar riesgos individuales vs. grupales.
- Analizar interconexiones de datos.
- Identificar vectores de ataque potenciales.
- Proponer medidas de mitigación.

### Resumen cuantitativo por miembro

<div align=center>

| Métrica                        | ...45 | ...54 | ...11 | ...17 | ...33 | ...44 | ...24 | ...86 | Patrón grupal<br>(Media y desviación) |
| ------------------------------ | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ------------------------------------- |
| Índice de exposición global    | 0,49  | 0,31  | 0,30  | 0,39  | 0,27  | 0,30  | 0,30  | 0,41  | 0,35 ± 0,07                           |
| Nº total de hallazgos          | 12    | 10    | 10    | 10    | 8     | 10    | 10    | 11    | 10,13 ± 1,05                          |
| % hallazgos en control total   | 41,7% | 30%   | 40%   | 10%   | 37,5% | 10%   | 30%   | 18,2% | 27,17%                                |
| % hallazgos en control parcial | 25%   | 0%    | 0%    | 10%   | 12,5% | 0%    | 0%    | 9%    | 7,06%                                 |
| % hallazgos sin control        | 33,3% | 70%   | 60%   | 80%   | 50%   | 90%   | 70%   | 72,3% | 65,7%                                 |

</div>

**Observaciones y análisis:**
- **Riesgos individuales vs. grupales**: Hay 1 miembro que supera el Índice de exposición global esperado, y 1 que está por debajo. No supone un gran riesgo ya que estos números se consideran bajos.
- **Interconexiones de datos**: Vemos una mayoría de hallazgos sin control.
- **Mitigación**: Priorizar controles en redes sociales y eliminar perfiles inactivos.

---

### Distribución por plataformas

<div align=center>

| Plataforma      | ...45 | ...54 | ...11 | ...17 | ...33 | ...44 | ...24 | ...86 | Total grupo |
| --------------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----------- |
| Redes Sociales  | 6     | 5     | 4     | 1     | 3     | 6     | 2     | 7     |     32      |
| Foros/Blogs     | 2     | 0     | 0     | 1     | 0     | 0     | 0     | 0     |     3       |
| Noticias        | 3     | 0     | 1     | 0     | 1     | 1     | 0     | 1     |     7       |
| Documentos      | 1     | 1     | 0     | 4     | 0     | 0     | 4     | 0     |     10      |
| Imágenes/Videos | 1     | 0     | 1     | 0     | 0     | 0     | 0     | 1     |     3       |
| Otros           | 1     | 4     | 4     | 4     | 4     | 3     | 4     | 2     |     26      |

</div>

**Observaciones y análisis:**
- **Riesgos prioritarios**: Redes Sociales concentran el 43,2% de los hallazgos.
- **Interconexiones**: La alta presencia en redes sociales (32 hallazgos grupales) se puede deber a la edad de los participantes.
- **Vectores críticos**: Los documentos y las imágenes/videos podrían contener información sensible.
- **Mitigación**: Revisar configuraciones de privacidad en redes sociales y auditar plataformas de documentos. Monitorear la categoría "Otros".

---

### Matriz de vulnerabilidades comunes

> 🟢 Bajo riesgo/impacto / 🟡 Riesgo/impacto moderado / 🔴 Alto riesgo/impacto

<div align=center>

| Vulnerabilidad             | ...45 | ...54 | ...11 | ...17 | ...33 | ...44 | ...24 | ...86 | % Grupo | Riesgo medio |
|----------------------------|-------|-------|-------|-------|-------|-------|-------|-------|---------|--------------|
| Datos personales expuestos |  🟡  |  🟡   |  🟡  |  🟢   | 🟢    |  🟢   |  🟡  |  🟡  |  87,5%  |    🟡       |
| Información profesional    |  🟡  |  🟡   |  🟡  |  🟡   | 🟡    |  🟡   |  No  |  🟡   | 87,5%  |     🟡       |
| Fotos personales           |  🟢  |  🟢   |  🟢  |  🟢   | 🟢    |  🟡   |  🟢  |  🟢  |  100%   |     🟢      |
| Menciones en medios        |  🟡  |  No   |  No  |   No  | No    |  No   |   No  |  No  |   12,5%   |     🟡       |
| Documentos académicos      |  🟢  |  No   |  No  |   No  | No    |  🟢   |   🟢 |   No  |   25%    |     🟢       |
| Perfiles abandonados       |  🟡  |  🟢   |  🟢  |  🟢   | 🟡    |   No  |  🟢  |  🟢  |  87,5%  |     🟡       |

</div>

**Observaciones y análisis:**
- **Riesgo grupal**: 87,5% del grupo tiene datos personales/profesionales expuestos (🟡), lo que facilita ingeniería social.
- **Interconexiones críticas**: La exposición combinada de datos personales y profesionales podría permitir ataques dirigidos.
- **Vectores explotables**: Datos personales (🟡) + perfiles abandonados (🟡) = riesgo de suplantación de identidad.
- **Mitigación**: Eliminar datos sensibles en plataformas públicas, implementar controles de acceso a documentos académicos y monitorear menciones en medios.

---

### Análisis de control

<div align=center>

| Tipo de control | ...45 | ...54 | ...11 | ...17 | ...33 | ...44 | ...24 | ...86 | % Grupo | Riesgo promedio |
| --------------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ------- | --------------- |
| Total           |  🟢  | 🟢    | 🟡    | 🟢    | 🟡    | No    | 🟢    | 🟢    | 62,5% |    🟢          |
| Parcial         |  🟡  | No    | No    | 🟢    | 🟢    | 🟢    | No    | 🟢    | 37,5%  |    🟡          |
| Nulo            |  🔴  | 🔴    | 🟡    | 🔴    | 🟡    | 🔴    | 🟡    | 🔴    | 50%  |     🔴         |

</div>

**Observaciones y análisis:**
- **Riesgo crítico**: 50% del grupo tiene controles nulos (🔴).
- **Interconexiones de riesgo**: Los miembros con controles nulos podrían servir como puerta de entrada a ataques transversales.
- **Vector prioritario**: Explotación de sistemas sin controles (🔴) mediante phishing o fuerza bruta.
- **Mitigación urgente**: Implementar controles básicos (autenticación, cifrado...) en miembros con 🔴.
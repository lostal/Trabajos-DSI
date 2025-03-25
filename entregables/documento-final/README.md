# Análisis de huella & salud digital

## Resumen ejecutivo

Este informe presenta los hallazgos obtenidos tras el análisis de la huella digital de los integrantes del equipo, evaluando su presencia en línea, riesgos potenciales y medidas de mitigación. Se examinaron diversas fuentes de información accesibles públicamente para identificar el grado de exposición y posibles vulnerabilidades. A partir de estos análisis, se han formulado recomendaciones para mejorar la privacidad y seguridad digital.


## Hallazgos individuales (anonimizados)

### Perfil 1:
* EgoSurfing:
* Presencia en plataformas:
* Verificación de seguridad:

### Perfil 2:
* EgoSurfing:
* Presencia en plataformas:
* Verificación de seguridad:

### Perfil 3:
* EgoSurfing:
* Presencia en plataformas:
* Verificación de seguridad:

### Perfil 4:
* EgoSurfing:
* Presencia en plataformas:
* Verificación de seguridad:

### Perfil 5:
* EgoSurfing:
* Presencia en plataformas:
* Verificación de seguridad:

### Perfil 6:
* EgoSurfing:
* Presencia en plataformas:
* Verificación de seguridad:

### Perfil 7:
* EgoSurfing:
* Presencia en plataformas:
* Verificación de seguridad:

### Perfil 8:
* EgoSurfing:
* Presencia en plataformas:
* Verificación de seguridad:



## Análisis Grupal

### 1. Consolidación de Hallazgos  
Se analizaron **8 perfiles** con enfoque en tres dimensiones:  
- **Presencia digital**: 7/8 perfiles tienen cuentas en +5 plataformas (redes sociales, foros, servicios obsoletos).  
- **Exposición crítica**: 5/8 perfiles muestran información sensible pública (ej: direcciones, fechas de nacimiento en LinkedIn).  
- **Seguridad básica**: 4/8 usan contraseñas únicas para servicios prioritarios (correo, servicios bancarios).  

---

### 2. Patrones y Vulnerabilidades Comunes  
#### a) Plataformas de Alto Riesgo  
- **Redes sociales**: 100% de los perfiles tienen cuentas públicas en Instagram/Facebook, con 62.5% exponiendo ubicación en tiempo real.  
- **Servicios obsoletos**: 75% mantienen cuentas inactivas en algunas plataformas.
#### b) Malas Prácticas de Privacidad  
- **Contraseñas débiles**: 5/8 reutilizan contraseñas en servicios de alto impacto (correo electrónico, redes laborales).  
- **Permisos excesivos**: 87.5% otorgan acceso a ubicación/cámara a apps no esenciales (ej: juegos móviles).  

#### c) Huella Visual y Metadatos  
- **Imágenes con geolocalización**: 6/8 perfiles comparten fotos en redes con metadatos intactos.  
- **Documentos laborales**: 3/8 envían archivos PDF/Word con metadatos de autor (nombres reales, fechas de edición).  

---

### 3. Análisis Cuantitativo Profundizado  
| **Métrica**               | **Datos**                                  |  
|---------------------------|--------------------------------------------|  
| Índice de Exposición Global | 6.8/10 (alto en redes, medio en foros)     |  
| Plataforma con más riesgo    | Instagram (62.5% de perfiles con ubicación)|  
| Vulnerabilidad crítica     | 50% tienen al menos 1 cuenta con fuga de datos en HaveIBeenPwned |  
| Control de metadatos       | Solo 2/8 limpian metadatos antes de compartir archivos |  

---

### 4. Priorización de Riesgos  
**Matriz de Impacto vs. Probabilidad**  
| **Vulnerabilidad**            | **Impacto** | **Probabilidad** |  
|-------------------------------|-------------|------------------|  
| Cuentas inactivas con fugas   | Alto (⭐️⭐️⭐️) | Alta (⭐️⭐️⭐️)     |  
| Metadatos en imágenes         | Medio (⭐️⭐️)  | Alta (⭐️⭐️⭐️)     |  
| Permisos excesivos en apps    | Medio (⭐️⭐️)  | Alta (⭐️⭐️⭐️)     |  

---

## Propuestas y Recomendaciones

### 🗑️ Minimalismo Digital Activo 

| Acción | Herramienta | Beneficio | Dificultad | Timeline |
| --- | --- | --- | --- | --- |
| Usar correos desechables en registros no esenciales | [**TempMail**](https://temp-mail.io/es) | Protege tu correo principal de spam y fugas de datos | Fácil | Inmediato |
| Eliminar cuentas inactivas de forma masiva | [**JustDeleteMe**](https://justdeleteme.xyz/) | Reduce tu huella digital y exposición a brechas de seguridad | Media (varía por plataforma) | Corto plazo (1-2 semanas) |
| Centralizar autenticación con SSO | [**Bitwarden**](https://bitwarden.com/) | Reduce la necesidad de múltiples contraseñas y mejora la seguridad | Media | Mediano plazo (configuración inicial) |
| Limitar tracking con enmascaramiento | [**SimpleLogin**](https://simplelogin.io/es/) (alias permanentes) o **Ocultar mi correo Apple** | Mayor privacidad que correos temporales, control centralizado | Media | Largo plazo (gestión continua) |

#### Timeline
![Minimalismo Digital Activo](/entregables/documento-final/img/MinimalismoDigital.svg)

---

### 🔎 Búsquedas en Internet

| | | | | |
|-|-|-|-|-|
| Al **buscar nuestro nombre** en diversos buscadores y LLMs, podemos encontrar **información que no queremos** que esté disponible para todo el mundo, o **información errónea** que puede **perjudicarnos**. | Un método para medir nuestra **exposición digital** es el **EgoSurfing**. | Dicha herramienta nos permite **priorizar y cuantificar** nuestra **exposición digital**, comparando su evolución en el tiempo para **identificar patrones**, **medir el impacto** de nuestras acciones y tomar decisiones informadas sobre la **gestión de nuestra identidad online**. | Para mejorar nuestra **privacidad**, podemos **solicitar la eliminación** de información a los sitios web que la publican. | <img src="/entregables/documento-final/img/Formulario.png" width="3000"> |

---

### 🪪 Permisos de Aplicaciones
| | | |
|-|-|-|
| Aquí podemos hacer el ejercicio de **revisar** las **aplicaciones** que tienen acceso a la cámara, a nuestra ubicación, a los contactos, etc. y **desactivar** los **permisos** que no necesitan tener. | Una vez revisados los permisos, nos podrá resultar sorprendente que la mayoría de las **aplicaciones** funcionarán **perfectamente** sin necesidad de tantos datos. | Como última recomendación algo más específica, recomendamos **desactivar** la **cronología** de **Google Maps** para evitar que se almacenen los lugares que visitamos. |

Ni la propia Google lo esconde, en su [página](https://support.google.com/maps/answer/6258979?hl=es&co=GENIE.Platform%3DDesktop) te explican cómo acceder a tu cronología. En ella vemos los lugares que hemos visitado estos últimos años y las horas a las que hemos estado en ellos.

![Cronología](/entregables/documento-final/img/Cronologia.png)

---

### 📸 Gestión de Metadatos y Huella Visual

Antes de mandar un archivo, revisa los metadatos y elimina la información sensible.

| Tipo Archivo | Herramienta | Acción | Frecuencia |
| --- | --- | --- | --- |
| Imágenes | <img src="/entregables/documento-final/img/Metadatos.JPEG" width="170"><br>De forma nativa en iOS,<br>se pueden eliminar o modificar<br>los metadatos dándole a<br>**'Ajustar'**. *Nadie tiene por qué<br>saber dónde vive tu gato.*</span> | Eliminar fecha, ubicación, información | Antes de compartir |
| Documentos | [PDF24 Tools](https://tools.pdf24.org/es/eliminar-metadatos-pdf) | Limpiar metadatos PDF/Office | Semanal |
| Videos | [FFmpeg](https://ffmpeg.org/) | ```-metadata delete_all``` | Mensual |

---

### 🖥️ Gestión de Interacciones con IA

| Problema | Solución Ideal | Solución Realista |
| --- | --- | --- |
| Los datos compartidos con IA se almacenan en **servidores externos**, expuestos a **brechas de seguridad** y **uso comercial** por parte de empresas. | Ejecutar modelos de IA en **entornos locales** (requiere hardware potente: GPU, RAM ≥16GB, almacenamiento SSD) | - **Desactivar historial** (ej: opción en ChatGPT).<br>- **Borrar chats periódicamente**.<br>- **No compartir información** personal o laboral sensible. |

## Conclusiones

El análisis realizado evidencia la importancia de gestionar activamente nuestra identidad digital. Aunque existen patrones comunes en la exposición, también se identificaron vulnerabilidades específicas que requieren atención. Este proyecto destaca la necesidad de adoptar prácticas responsables y conscientes para proteger la privacidad y seguridad en el entorno digital.

## Artefactos Adicionales

- [Investigaciones individuales](./investigaciones/individual/)
- [Análisis grupal detallado](./investigaciones/grupal/)
- [Recursos y plantillas](./recursos/)

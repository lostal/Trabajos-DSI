# Análisis de huella & salud digital

## 📝 Resumen ejecutivo

Este informe presenta los hallazgos obtenidos tras el análisis de la huella digital de los integrantes del equipo, evaluando su presencia en línea, riesgos potenciales y medidas de mitigación. Se examinaron diversas fuentes de información accesibles públicamente para identificar el grado de exposición y posibles vulnerabilidades. A partir de estos análisis, se han formulado recomendaciones para mejorar la privacidad y seguridad digital.


## 👤 [Hallazgos individuales](/investigaciones/individual/)

### 🔎 EgoSurfing y Búsquedas

| Categoría               | Herramientas/Plataformas                  |
| ----------------------- | ----------------------------------------- |
| **Motores de búsqueda** | Google, Bing, DuckDuckGo, Brave           |
| **LLMs consultados**    | ChatGPT, Gemini, GitHub Copilot, Deepseek |

### 🌐 Análisis de Plataformas

| Tipo de Plataforma      | Analizadas                                  |
| ----------------------- | ------------------------------------------- |
| **Redes tradicionales** | Facebook, Instagram, LinkedIn, X (Twitter)  |
| **Plataformas nuevas**  | BeReal, Threads, Mastodon, Discord, Bluesky |

### 🔒 Verificación de Seguridad

- Comprobación en ![HaveIBeenPwned](https://img.shields.io/badge/Have_I_Been_Pwned-2A6379?logo=haveibeenpwned&logoColor=white)
- Auditoría de permisos de aplicaciones
- Revisión de servicios vinculados
- Documentación de interacciones con IA


## 👥 [Análisis Grupal](/investigaciones/grupal/)

### EgoSurfing

Estas pruebas se han realizado utilizando el modo incógnito para evitar sesgos.

| Métrica                        | ...45 | ...54 | ...11 | ...17 | ...33 | ...44 | ...24 | ...86 | Patrón grupal |
| ------------------------------ | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | -------------- |
| Índice de exposición global    | 0.49  | 0.31  | 0.30  | 0.39  | 0.27  | 0.30  | 0.30  | 0.41  | 0.35 ± 0.07    |
| Nº total de hallazgos          | 12    | 10    | 10    | 10    | 8     | 10    | 10    | 11    | 10.13 ± 1.05   |
| Redes Sociales                 | 6     | 5     | 4     | 1     | 3     | 6     | 2     | 7     | 32             |
| Foros/Blogs                    | 2     | 0     | 0     | 1     | 0     | 0     | 0     | 0     | 3              |
| Noticias                       | 3     | 0     | 1     | 0     | 1     | 1     | 0     | 1     | 7              |
| Documentos                     | 1     | 1     | 0     | 4     | 0     | 0     | 4     | 0     | 10             |
| Imágenes/Videos                | 1     | 0     | 1     | 0     | 0     | 0     | 0     | 1     | 3              |
| Otros                          | 1     | 4     | 4     | 4     | 4     | 3     | 4     | 2     | 26             |
| **Control Total**              | 🟢    | 🟢    | 🟡    | 🟢    | 🟡    | No    | 🟢    | 🟢    | **62.5%**       |
| **Control Parcial**            | 🟡    | No    | No    | 🟢    | 🟢    | 🟢    | No    | 🟢    | **37.5%**       |
| **Control Nulo**               | 🔴    | 🔴    | 🟡    | 🔴    | 🟡    | 🔴    | 🟡    | 🔴    | **50%**         |\

1. **Variabilidad en exposición digital**  
   El índice de exposición global oscila entre **0.27** (más bajo en ...33) y **0.49** (más alto en ...45), mostrando diferencias significativas en vulnerabilidad entre casos.

2. **Dominancia de redes sociales**  
   Las redes sociales concentran **32 hallazgos** (vs. solo 3 en foros/blogs), destacando su papel principal como fuente de exposición digital.

3. **Brechas en controles de protección**  
   - 50% tiene **control nulo** (🔴) de exposición  
   - Solo 62.5% logra **control total** (🟢), revelando fallas sistémicas en mitigación de riesgos.

4. **Casos atípicos relevantes**  
    - **...45**: Mayor exposición (0.49) + 12 hallazgos (máximo) 
        - _Probablemente_ cuantos más hallazgos hagas, mayor índice de exposición tengas.
    - **Documentos**: ...17 y ...24 con 4 hallazgos cada uno (vs. 10 total grupal), sugiriendo fugas de información estructurada.

### Verificación de Seguridad

#### Exposición en brechas de datos

Utilizando la herramienta [Have I Been Pwned](https://haveibeenpwned.com/) encontramos los siguientes resultados:

> [!NOTE]
> 🟢 No hay datos expuestos / 🔴 Existen datos expuestos

| **Perfil**   | ...45  | ...54  | ...11  | ...17  | ...33  | ...44  | ...24  | ...86  |
|-------------|--------|--------|--------|--------|--------|--------|--------|--------|
| **Resultado** | 🟢  | 🔴  | 🔴  | 🔴 | 🔴  | 🟢  | 🟢  | 🔴  |

#### Permisos de aplicaciones

Estas son las aplicaciones más utilizadas por el grupo y los permisos que se les han concedido:

| Aplicación                                                                                                                               | Permisos concedidos                                                                                |
| ---------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" width="60"/>                                           | Ubicación (Al usarse), Contactos, Fotos, Micrófono, Cámara                                   |
| <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" width="60"/>                                                 | Ubicación (Siempre), Contactos, Fotos, Bluetooth, Micrófono, Cámara | 
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Twitter_X.png/640px-Twitter_X.png" width="60"/>                      | Fotos, Micrófono y Cámara                                                                          |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Tiktok_icon.svg/640px-Tiktok_icon.svg.png" width="60" />             | Cámara, Fotos y Videos, Micrófono                                                                  |
| <p align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/39/Google_Maps_icon_%282015-2020%29.svg/640px-Google_Maps_icon_%282015-2020%29.svg.png" alt="Google Maps" width="50"></p> | Ubicación, Multimedia|

#### Interacciones con IA

| Plataforma IA | Tipo de Interacción | Datos Compartidos | Configuración Privacidad |
|---------------|---------------------|--------------------|--------------------------|
| **ChatGPT** | Consultas académicas y personales | Textos académidos/personales | No guardar datos en memoria |
| **GitHub Copilot** | Desarrollo código | Fragmentos código | No existe |
| **Deepseek** | Consultas académicas | Textos académicos | No existe |
| **Claude** | Desarrollo código | Fragmentos código | No guardar datos en memoria |

A cada IA se le da un uso específico y se han empezado a tomar medidas para proteger la privacidad de los datos compartidos.


## 💡 Propuestas y Recomendaciones

### Minimalismo Digital Activo 

| Acción | Herramienta | Beneficio | Dificultad | Timeline |
| --- | --- | --- | --- | --- |
| Usar correos desechables en registros no esenciales | [**TempMail**](https://temp-mail.io/es) | Protege tu correo principal de spam y fugas de datos | Fácil | Inmediato |
| Eliminar cuentas inactivas de forma masiva | [**JustDeleteMe**](https://justdeleteme.xyz/) | Reduce tu huella digital y exposición a brechas de seguridad | Media (varía por plataforma) | Corto plazo (1-2 semanas) |
| Centralizar autenticación con SSO | [**Bitwarden**](https://bitwarden.com/) | Reduce la necesidad de múltiples contraseñas y mejora la seguridad | Media | Mediano plazo (configuración inicial) |
| Limitar tracking con enmascaramiento | [**SimpleLogin**](https://simplelogin.io/es/) (alias permanentes) o **Ocultar mi correo Apple** | Mayor privacidad que correos temporales, control centralizado | Media | Largo plazo (gestión continua) |

#### Timeline
![Minimalismo Digital Activo](/entregables/documento-final/img/MinimalismoDigital.svg)

---

### Búsquedas en Internet

| | | | | |
|-|-|-|-|-|
| Al **buscar nuestro nombre** en diversos buscadores y LLMs, podemos encontrar **información que no queremos** que esté disponible para todo el mundo, o **información errónea** que puede **perjudicarnos**. | Un método para medir nuestra **exposición digital** es el **EgoSurfing**. | Dicha herramienta nos permite **priorizar y cuantificar** nuestra **exposición digital**, comparando su evolución en el tiempo para **identificar patrones**, **medir el impacto** de nuestras acciones y tomar decisiones informadas sobre la **gestión de nuestra identidad online**. | Para mejorar nuestra **privacidad**, podemos **solicitar la eliminación** de información a los sitios web que la publican. | <img src="/entregables/documento-final/img/Formulario.png" width="3000"> |

---

### Permisos de Aplicaciones
| | | |
|-|-|-|
| Aquí podemos hacer el ejercicio de **revisar** las **aplicaciones** que tienen acceso a la cámara, a nuestra ubicación, a los contactos, etc. y **desactivar** los **permisos** que no necesitan tener. | Una vez revisados los permisos, nos podrá resultar sorprendente que la mayoría de las **aplicaciones** funcionarán **perfectamente** sin necesidad de tantos datos. | Como última recomendación algo más específica, recomendamos **desactivar** la **cronología** de **Google Maps** para evitar que se almacenen los lugares que visitamos. |

Ni la propia Google lo esconde, en su [página](https://support.google.com/maps/answer/6258979?hl=es&co=GENIE.Platform%3DDesktop) te explican cómo acceder a tu cronología. En ella vemos los lugares que hemos visitado estos últimos años y las horas a las que hemos estado en ellos.

![Cronología](/entregables/documento-final/img/Cronologia.png)

---

### Gestión de Metadatos y Huella Visual

Antes de mandar un archivo, revisa los metadatos y elimina la información sensible.

| Tipo Archivo | Herramienta | Acción | Frecuencia |
| --- | --- | --- | --- |
| Imágenes | <img src="/entregables/documento-final/img/Metadatos.JPEG" width="170"><br>De forma nativa en iOS,<br>se pueden eliminar o modificar<br>los metadatos dándole a<br>**'Ajustar'**. *Nadie tiene por qué<br>saber dónde vive tu gato.*</span> | Eliminar fecha, ubicación, información | Antes de compartir |
| Documentos | [PDF24 Tools](https://tools.pdf24.org/es/eliminar-metadatos-pdf) | Limpiar metadatos PDF/Office | Semanal |
| Videos | [FFmpeg](https://ffmpeg.org/) | ```-metadata delete_all``` | Mensual |

---

### Gestión de Interacciones con IA

| Problema | Solución Ideal | Solución Realista |
| --- | --- | --- |
| Los datos compartidos con IA se almacenan en **servidores externos**, expuestos a **brechas de seguridad** y **uso comercial** por parte de empresas. | Ejecutar modelos de IA en **entornos locales** (requiere hardware potente: GPU, RAM ≥16GB, almacenamiento SSD) | - **Desactivar historial** (ej: opción en ChatGPT).<br>- **Borrar chats periódicamente**.<br>- **No compartir información** personal o laboral sensible. |

## ✅ Conclusiones

El análisis realizado evidencia la importancia de gestionar activamente nuestra identidad digital. Aunque existen patrones comunes en la exposición, también se identificaron vulnerabilidades específicas que requieren atención. Este proyecto destaca la necesidad de adoptar prácticas responsables y conscientes para proteger la privacidad y seguridad en el entorno digital.

### Principales hallazgos:

- **Exposición generalizada:** La mayoría de los perfiles presentan una alta presencia en plataformas digitales, lo que incrementa el riesgo de acceso no autorizado a información sensible.
- **Vulnerabilidades críticas:** Se identificaron prácticas inseguras como el uso de contraseñas débiles, permisos excesivos en aplicaciones y la exposición de metadatos en archivos compartidos.
- **Fugas de información:** El 50% de los perfiles tienen cuentas afectadas por brechas de seguridad según "Have I Been Pwned".

### Recomendaciones clave:

1. **Minimalismo digital activo:** Reducir la exposición eliminando cuentas inactivas y usando correos electrónicos desechables en registros no esenciales.
2. **Gestión de permisos:** Revisar y limitar los accesos a la ubicación, la cámara y otros datos sensibles en las aplicaciones.
3. **Control de metadatos:** Limpiar metadatos en imágenes, documentos y videos antes de compartirlos públicamente.
4. **Seguridad en autenticación:** Utilizar gestores de contraseñas y autenticación en dos pasos para proteger cuentas críticas.

### Reflexión final:

El control consciente de la huella digital no solo fortalece la seguridad personal, sino que también fomenta una cultura de privacidad en el entorno digital. Implementar las estrategias sugeridas permitirá reducir significativamente los riesgos asociados a la exposición de información personal.

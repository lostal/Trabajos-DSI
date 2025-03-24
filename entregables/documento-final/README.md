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

### Consolidación de Datos
- Comparativa de hallazgos individuales.
- Identificación de patrones comunes.
- Análisis de vulnerabilidades compartidas.
- Evaluación del impacto de diferentes prácticas de privacidad.

### Resumen Cuantitativo
- Índice de exposición global.
- Distribución de hallazgos por plataformas.
- Matriz de vulnerabilidades comunes.

### Análisis de Control
- Clasificación de hallazgos en control total, parcial o nulo.
- Riesgos promedio asociados a cada tipo de control.

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

### 📸 Gestión de Metadatos y Huella Visual

Antes de mandar un archivo, revisa los metadatos y elimina la información sensible.

| Tipo Archivo | Herramienta | Acción | Frecuencia |
| --- | --- | --- | --- |
| Imágenes | ![Metadatos](/entregables/documento-final/img/Metadatos.JPEG)<br>De forma nativa en iOS, se pueden eliminar o modificar los metadatos dándole a **'Ajustar'**. *Nadie tiene por qué saber dónde vive tu gato.* | Eliminar fecha, ubicación, información | Antes de compartir |
| Documentos | [PDF24 Tools](https://tools.pdf24.org/es/eliminar-metadatos-pdf) | Limpiar metadatos PDF/Office | Semanal |
| Videos | [FFmpeg](https://ffmpeg.org/) | ```-metadata delete_all``` | Mensual |

---

## Conclusiones

El análisis realizado evidencia la importancia de gestionar activamente nuestra identidad digital. Aunque existen patrones comunes en la exposición, también se identificaron vulnerabilidades específicas que requieren atención. Este proyecto destaca la necesidad de adoptar prácticas responsables y conscientes para proteger la privacidad y seguridad en el entorno digital.

---

## Artefactos Adicionales

- [Investigaciones individuales](./investigaciones/individual/)
- [Análisis grupal detallado](./investigaciones/grupal/)
- [Recursos y plantillas](./recursos/)
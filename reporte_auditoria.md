# Reporte de Auditoría Heurística – Instagram

## 1. Resumen Ejecutivo

La presente auditoría heurística fue realizada sobre la aplicación móvil Instagram en su versión Android durante marzo de 2026. El objetivo principal fue identificar problemas de usabilidad mediante la aplicación de las 10 heurísticas de Nielsen. Para ello se evaluaron tres flujos de interacción considerados críticos para la experiencia del usuario: el inicio de sesión, la búsqueda de contenido y la gestión del perfil y configuraciones.

Durante el proceso de evaluación se identificaron un total de 10 hallazgos relacionados principalmente con problemas de visibilidad del estado del sistema, prevención de errores, consistencia en la interfaz y falta de ayuda contextual.

El hallazgo más crítico encontrado corresponde a la ausencia de mecanismos de prevención de errores en la edición del perfil, donde el usuario puede perder cambios sin recibir advertencias previas.

Como recomendación principal se propone mejorar la retroalimentación visual del sistema, agregar confirmaciones antes de acciones importantes y proporcionar información contextual que ayude a los usuarios a comprender mejor ciertas funciones.


# 2. Metodología

La evaluación se realizó utilizando el método de auditoría heurística basado en las 10 heurísticas de usabilidad de Nielsen.

El proceso consistió en:

1. Selección de la aplicación Instagram.
2. Definición de tres flujos principales de interacción.
3. Recorrido inicial para comprender la experiencia general.
4. Segundo recorrido enfocado en detectar problemas de usabilidad.
5. Documentación de hallazgos con evidencia visual.

Las capturas de pantalla utilizadas como evidencia fueron almacenadas en la carpeta **Evidencias** del repositorio.


# 3. Hallazgos por Flujo

## Flujo A – Inicio de sesión

En este flujo se detectaron problemas relacionados con la visibilidad del estado del sistema y la claridad de los mensajes de error.

Por ejemplo, cuando el usuario intenta iniciar sesión con una conexión lenta no existe un indicador claro de carga.


## Flujo B – Búsqueda

En la sección de búsqueda se identificaron problemas de sobrecarga visual debido a la gran cantidad de contenido mostrado simultáneamente.

Esto puede dificultar que el usuario identifique rápidamente los resultados que realmente le interesan.



## Flujo C – Perfil y configuración

En este flujo se identificaron problemas relacionados con la prevención de errores y la falta de ayuda contextual.

Cuando el usuario edita su perfil y abandona la pantalla sin guardar cambios, la aplicación no solicita confirmación.


# 4. Tabla de Priorización

| Prioridad | ID | Heurística | Severidad | Impacto | Recomendación |
|-----------|----|------------|----------|---------|--------------|
| 1 | H9-C | Prevención de errores | 3 | Pérdida de información | Agregar confirmación antes de salir |
| 2 | H2-A | Prevención de errores | 3 | Confusión en login | Mejorar mensajes de error |
| 3 | H8-C | Ayuda y documentación | 3 | Usuario no entiende configuraciones | Incluir ayuda contextual |
| 4 | H1-A | Visibilidad del estado | 2 | Usuario no sabe si el sistema responde | Agregar indicador de carga |
| 5 | H5-B | Diseño minimalista | 2 | Sobrecarga visual | Reducir cantidad de elementos |


# 5. Análisis de Patrones

Durante la auditoría se identificaron dos patrones principales de problemas de usabilidad.

El primero corresponde a la falta de visibilidad del estado del sistema en diferentes partes de la aplicación.

El segundo patrón corresponde a la falta de prevención de errores en acciones relacionadas con la edición de información.



# 6. Conclusiones

Instagram presenta una interfaz moderna y visualmente atractiva, sin embargo la auditoría heurística permitió identificar varios aspectos que podrían mejorar la experiencia de usuario.

Entre las recomendaciones principales se encuentran mejorar la retroalimentación visual del sistema, implementar mecanismos de prevención de errores y proporcionar información contextual en ciertas configuraciones.

Estas mejoras podrían contribuir a una experiencia de usuario más clara, eficiente y segura.

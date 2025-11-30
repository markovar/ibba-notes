---
description: Revisa ortografía y expande citas bíblicas con texto RV1960
---

**PRIMERO**: Ejecuta /commit para guardar cambios actuales.

**LUEGO**: Revisa el archivo abierto en editor:

1. **Ortografía**: corrige errores ortográficos y de acentuación
2. **Citas bíblicas**:
   - **Cita específica con versículo(s)** (ej: Juan 3:16, Romanos 8:28, Juan 6:60-66):
     - Busca texto COMPLETO de TODOS los versículos en Reina-Valera 1960
     - **IMPORTANTE**: NO usar [...] para omitir texto, extraer versículos completos
     - Si son múltiples versículos (ej: 6:60-66), incluir TODOS sin omisiones

     - **FORMATO para versículo único**:
       ```
       * Referencia X:Y
           - "texto COMPLETO versículo RV1960"
       ```

     - **FORMATO para versículos múltiples del mismo capítulo** (ej: Juan 3:16-17, Isaías 9:6-7):
       ```
       * Referencia X:Y-Z
           - [Y] "texto COMPLETO versículo Y RV1960"
           - [Z] "texto COMPLETO versículo Z RV1960"
       ```
       Cada versículo en subbullet separado con número entre corchetes

     - **FORMATO para múltiples citas del mismo libro** (ej: Isaías 7:14, 9:6-7):
       ```
       * Isaías 7:14, 9:6-7
           - [7:14] "texto COMPLETO versículo 7:14 RV1960"
           - [9:6] "texto COMPLETO versículo 9:6 RV1960"
           - [9:7] "texto COMPLETO versículo 9:7 RV1960"
       ```
       Usar formato [capítulo:versículo] cuando hay citas de diferentes capítulos

   - **Cita general** (solo capítulo con paráfrasis, ej: "Juan 15" seguido de texto parafraseando):
     - Infiere versículos específicos basándote en paráfrasis (máx 4-5 versículos)
     - Extraer texto COMPLETO sin omisiones
     - Añade subbullet con cita inferida y texto RV1960
     - Formato:
       ```
       * [texto original parafraseando Juan 15]
           - Juan 15:X-Y: "[texto COMPLETO versículos RV1960]"
       ```

   - **Marcador CITA** (palabra "CITA" en mayúsculas en la línea):
     - Extrae cita bíblica del texto inmediatamente anterior en la misma línea
     - Reemplaza "CITA" con subbullet conteniendo cita y texto RV1960 COMPLETO
     - Formato:
       ```
       * [texto con referencia bíblica] CITA

       Se convierte en:

       * [texto con referencia bíblica]
           - Referencia X:Y: "[texto COMPLETO versículo RV1960]"
       ```

Usa WebSearch para obtener versículos RV1960 si es necesario.

Aplica cambios con Edit tool.

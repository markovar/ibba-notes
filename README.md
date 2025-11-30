# IBBA Notes

Repositorio con materiales doctrinales y educativos de la Iglesia Bíblica Bautista de Alajuela (IBBA).

## Contenido

### Contexto Doctrinal
- **Artículos de Fe**: Fundamentos doctrinales bíblico-bautistas
- **Historia IBBA**: Origen, ubicación, liderazgo, visión y misión
- **Doctrina de Discipulado**: Tribunal de Cristo, mundo perdido, trabajo y ministerio
- **Normas para Servidores/Maestros**: Requisitos, responsabilidades y sistema disciplinario

### Materiales por Ministerio

#### ELE (Escuela de Liderazgo Espiritual)
- Notas de planeamiento y reuniones
- Metas ministeriales
- Principios de liderazgo

## Comandos Claude Code

Este proyecto utiliza comandos personalizados de Claude Code:

### `/commit`
Revisa cambios, genera mensaje commit y pushea automáticamente.

**Formato de commit:**
```
tipo: descripción breve

🤖 Generated with [Claude Code](https://claude.com/claude-code)

Co-Authored-By: Claude <noreply@anthropic.com>
```

**Tipos:** fix, feat, docs, refactor, chore

### `/fix`
Revisa ortografía y expande citas bíblicas con texto Reina-Valera 1960.

**Funcionalidades:**
1. Ejecuta `/commit` primero para guardar cambios
2. Corrige errores ortográficos y de acentuación
3. Expande citas bíblicas con versículos completos RV1960
4. Soporta tres formatos:
   - **Cita específica**: `Juan 3:16` → añade texto completo
   - **Cita con rango**: `Juan 6:60-66` → añade TODOS los versículos sin omisiones
   - **Marcador CITA**: `texto con referencia CITA` → extrae cita e inserta texto

## Estructura

```
.
├── .claude/
│   ├── CLAUDE.md           # Contexto completo del proyecto
│   └── commands/
│       ├── commit.md       # Comando /commit
│       └── fix.md          # Comando /fix
├── contexto/
│   └── Normas para Maestros 2022.md
├── ELE/
│   └── 2025-11-29 - Planeamiento.md
└── README.md
```

## Sobre IBBA

**Iglesia Bíblica Bautista de Alajuela**
San Rafael de Alajuela, Costa Rica
Frente al Campamento Bautista

Parte de Asociación Compañerismo Bíblico Bautista Internacional (familia AVANCE)

### Liderazgo
- **Jesucristo**: Único líder y cabeza de la iglesia
- **Juan Roberto Barnes Davenport**: Misionero (graduado BBC, enviado por Iglesia Bautista Kelview Heights, Midland Texas)
- **Luis Monge Siles**: Pastor Principal (teólogo graduado Seminario Bíblico Bautista)

### Visión
Proyectarnos a Siguientes Generaciones como Iglesia Apasionada por Sana Doctrina, distinguidos por Amor Fraternal, Gratitud hacia Dios y Fortalecimiento Integral del Individuo y Familia.

### Misión
Ser Discípulos de Cristo que Aman, Sirven y Dan con Pasión para Solventar Necesidades Actuales y Procurar Engrandecimiento de Obra Local y Misionera Sin Importar Precio.

### E7 (Pilares Ministeriales)
1. Exaltar a Dios
2. Enseñar la sana doctrina
3. Entrenar discípulos
4. Edificar a la familia (matrimonios, padres e hijos)
5. Entrenar obreros
6. Edificar el templo para Dios y su iglesia
7. Extender la obra local y misionera al dar

## Licencia

Material doctrinal y educativo para uso interno de IBBA.

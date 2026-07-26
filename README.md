# MCreator Fabric 1.16.5 Plugin

Este repositorio contiene el plugin para MCreator 2022.2 que añade soporte completo (plantillas y generadores) para desarrollar mods con la API Fabric para Minecraft 1.16.5.

Resumen de lo que entregará el plugin:
- Añade las 32 entradas del menú "Crear nuevo elemento" de MCreator (ver lista en /mcreator-plugin.json).
- Paneles de UI equivalentes a los de MCreator/Forge para cada tipo de elemento.
- Generadores que producen código Java + JSON (models, blockstates, loot tables, recipes, tags, data, etc.) compatibles con Fabric 1.16.5.
- Ejemplos completos y probados para: Bloque, Item, Entidad, GUI, Receta, LootTable, Dimensión.
- Plantillas funcionales para los otros tipos de elemento.

Estado actual:
- Añadido esqueleto inicial del plugin (metadatos, build.gradle, clase Java de arranque).
- Próximo: añadir el código del plugin que integra con la API de MCreator, los paneles de UI y los generadores para cada tipo de elemento.

Instrucciones rápidas:
1. Clona este repo: git clone https://github.com/rulitogamer/._.git
2. Abre el proyecto en tu IDE (Gradle).
3. Más instrucciones de compilación y packaging estarán en el README final cuando el plugin esté completo.

Si necesitas que suba el ZIP de la release cuando termine, crearé un Release en GitHub con el artefacto.

# Guia de estudio de TypeScript

TypeScript se entiende mucho mejor cuando lo estudias como una herramienta para
pensar el software con mas claridad, no como una lista de palabras nuevas.

## Metodo recomendado

1. Lee el `README.md` general.
2. Abre el `README.md` del modulo.
3. Revisa el archivo `.ts` del tema.
4. Ejecuta `npm run check`.
5. Provoca un error intencional.
6. Corrigelo y explica por que el compilador se quejo.
7. Ejecuta `npm run build`.
8. Compara `ts` con `dist/`.
9. Completa la practica guiada.

## Preguntas clave

- Que dato del mundo real representa este tipo.
- Si puede faltar, cambiar o venir mal formado.
- Si conviene `type`, `interface`, `union` o `generic`.
- Si estas usando `any` por necesidad o por prisa.
- Que bug te ayuda a evitar este contrato.

## Regla tecnica importante

Los tipos no validan automaticamente datos que vienen de APIs, archivos o formularios.
TypeScript ayuda antes de ejecutar. La validacion externa sigue siendo responsabilidad del programa.

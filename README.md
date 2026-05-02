# Curso de TypeScript — De JavaScript tipado a una base profesional

Repositorio oficial: <https://github.com/yetsin7/Curso-de-TypeScript>

## Documentacion de referencia

Consulta [Documentación-TypeScript.md](./Documentación-TypeScript.md) para estudiar
con el handbook oficial y una ruta clara de temas.

## Para que sirve este curso

Este curso busca que TypeScript no se quede en anotaciones de tipos sueltas.
La meta es que entiendas como modelar datos, prevenir errores reales y organizar
mejor proyectos que despues corren como JavaScript.

## Como estudiar este repositorio

Cada modulo incluye:

- `README.md` con explicacion del tema;
- archivos `.ts` para leer y ejecutar;
- practica guiada para reforzar lo aprendido.

En la raiz tambien tienes:

- [GUIA_DE_ESTUDIO.md](./GUIA_DE_ESTUDIO.md)
- `package.json` con scripts utiles
- `tsconfig.json` para entender la configuracion del compilador

## Requisitos

- Node.js 18 o superior
- npm
- VS Code recomendado

## Instalacion inicial

```bash
npm install
```

## Scripts utiles

```bash
npm run check
npm run build
npm run lesson:hello
npm run lesson:async
npm run lesson:project
```

## Modulos del curso

1. `01-introduccion`
2. `02-tipos-y-variables`
3. `03-funciones-e-interfaces`
4. `04-objetos-arreglos-y-uniones`
5. `05-generics-y-narrowing`
6. `06-clases-y-modulos`
7. `07-utility-types`
8. `08-tsconfig-y-tooling`
9. `09-async-y-fetch`
10. `10-proyecto-final`

## Resultado esperado

Al terminar deberias poder:

- entender que TypeScript mejora el desarrollo, no la ejecucion;
- modelar datos con tipos, interfaces, unions y generics;
- leer mejor los errores del compilador;
- separar codigo en modulos;
- trabajar async con respuestas tipadas;
- compilar y ejecutar proyectos pequenos con mas seguridad.

## Recomendacion para respaldo y trabajo colaborativo

Se recomienda subir los cambios del proyecto a GitHub y trabajar mediante Pull Request (PR).
GitHub permite guardar el codigo, mantener historial de cambios y conservar una copia segura en la nube.
Un Pull Request ayuda a revisar cambios antes de integrarlos, reduce errores y deja registro claro de lo modificado.

## Que estudiar despues

Si quieres seguir la ruta natural despues de TypeScript, lo mas util suele ser:

1. React
2. Nuxt o Vue
3. Node.js

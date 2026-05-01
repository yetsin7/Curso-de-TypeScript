# Curso de TypeScript — De cero a PRO

Curso práctico, progresivo y muy explicativo para aprender TypeScript de forma
seria. La meta de este libro no es solo que sepas escribir anotaciones de tipo,
sino que entiendas cómo TypeScript mejora el desarrollo de software, cómo se
transforma a JavaScript y por qué eso reduce errores reales.

Repositorio oficial: https://github.com/yetsin7/Curso-de-TypeScript

## Documentacion de referencia

Consulta [DOCUMENTACION-OFICIAL.md](./DOCUMENTACION-OFICIAL.md) para acompanar
el curso con el handbook y la referencia oficial de TypeScript.

---

## 🇳🇮 Para estudiantes de Nicaragua (y de toda Latinoamérica)

Hola. Si estás en Nicaragua y quieres aprender a programar en serio, este libro
es para ti. También sirve si vives en cualquier otro país de Centroamérica o
Latinoamérica: el contenido está escrito en español claro, sin tecnicismos
innecesarios, pensando en quien aprende por su cuenta y desde cero.

No necesitas pagar un curso caro, no tienes que registrarte en ninguna
plataforma y no requieres internet permanente. Una vez que clones el
repositorio, puedes estudiar todo el material sin conexión, en tu propia
computadora, a tu ritmo.

## 📖 ¿Por qué existe este libro?

En Nicaragua hay mucho talento, pero pocas oportunidades de aprender
programación de forma estructurada y gratuita. Este libro nace con una misión
simple:

- Que más nicaragüenses puedan aprender a programar sin pagar cursos costosos.
- Que cualquier persona con una computadora pueda estudiar, incluso con
  internet limitado o intermitente.
- Que el material sea accesible para principiantes reales, sin asumir que ya
  dominas el inglés técnico ni que tienes experiencia previa en otros lenguajes.
- Que el conocimiento se quede aquí, libre y disponible para quien lo necesite.

Es 100% gratuito, no requiere registro y se puede estudiar offline después de
clonarlo. Si te sirve, compártelo con otros estudiantes nicaragüenses y
ayúdanos a que más gente pueda dar el salto a la programación profesional.

---

## ¿Para quién es este libro?

- Personas que ya conocen algo de JavaScript y quieren trabajar mejor
- Personas principiantes que quieren aprender con más estructura desde el inicio
- Desarrolladores que quieren escribir software más mantenible y seguro
- Equipos que necesitan modelar datos, funciones y módulos con claridad

## Objetivo real del libro

Al terminar este curso deberías poder:

- entender qué problema resuelve TypeScript;
- diferenciar desarrollo, compilación y ejecución;
- modelar datos con tipos, interfaces, unions y generics;
- leer y corregir errores del compilador con criterio;
- organizar proyectos pequeños y medianos con buena base técnica.

## Qué vas a aprender sobre software

Este libro insiste en varias ideas importantes:

- TypeScript ayuda en desarrollo, pero quien se ejecuta es JavaScript.
- El compilador revisa relaciones lógicas entre datos, no magia.
- Los tipos no reemplazan la validación de datos externos.
- Un buen modelado de tipos mejora legibilidad, mantenimiento y colaboración.

## Requisitos

- **Node.js** v18 o superior
- **npm** incluido con Node.js
- **VS Code** recomendado

## Instalación inicial

Desde la carpeta `Curso de TypeScript/`:

```bash
npm install
```

## Cómo estudiar este libro

1. Lee el `README.md` general del libro.
2. Abre el `README.md` del capítulo.
3. Recorre los archivos `.ts` en orden.
4. Ejecuta revisión de tipos con `npx tsc --noEmit`.
5. Compila con `npx tsc` cuando quieras ver JavaScript generado.
6. Observa cómo el mismo concepto se ve en TypeScript y en JavaScript.
7. Cambia código a propósito para provocar errores y entenderlos.

## Qué ocurre cuando trabajas con TypeScript

Cuando escribes TypeScript:

- el editor analiza tipos y relaciones mientras escribes;
- el compilador revisa incoherencias antes de ejecutar;
- si todo es válido, genera JavaScript;
- Node.js o el navegador ejecutan ese JavaScript compilado.

Eso significa que TypeScript no sustituye a JavaScript. Lo acompaña y lo vuelve
más claro en el proceso de construcción del software.

## Ruta del libro

| Nivel | Módulo | Tema |
|---|---|---|
| 🟢 Básico | `01-introduccion/` | Qué es TypeScript y cómo se compila |
| 🟢 Básico | `02-tipos-y-variables/` | Tipos primitivos, inferencia y anotaciones |
| 🟢 Básico | `03-funciones-e-interfaces/` | Parámetros, retorno, objetos e interfaces |
| 🟡 Medio | `04-objetos-arreglos-y-uniones/` | Arrays, unions, aliases y narrowing |
| 🟡 Medio | `05-generics-y-narrowing/` | Generics, guards y reutilización segura |
| 🟡 Medio | `06-clases-y-modulos/` | Clases, modificadores y export/import |
| 🔴 Avanzado | `07-utility-types/` | `Partial`, `Pick`, `Record`, `Omit` y modelado práctico |
| 🔴 Avanzado | `08-tsconfig-y-tooling/` | Configuración, strict mode y flujo de trabajo |
| 🔴 Avanzado | `09-async-y-fetch/` | Promesas, fetch y datos externos tipados |
| 🔴 Avanzado | `10-proyecto-final/` | Mini proyecto final guiado con varios módulos |

## Cómo se conecta con JavaScript

Si vienes de JavaScript, este libro te ayudará a ver que:

- `interface` y `type` describen formas de datos;
- `unknown` suele ser más seguro que `any`;
- los generics permiten reutilizar lógica sin perder información;
- los errores del compilador pueden prevenir muchos errores de integración.

## Errores comunes que este libro quiere corregir

- pensar que TypeScript cambia el comportamiento en tiempo de ejecución;
- usar `any` como salida rápida demasiado pronto;
- creer que tener tipos elimina la necesidad de validar APIs o archivos;
- aprender solo sintaxis sin entender el flujo compilación -> JavaScript;
- evitar los mensajes del compilador en vez de aprender a leerlos.

## Archivos base del libro

| Archivo | Descripción |
|---|---|
| `package.json` | Dependencias y scripts del libro |
| `tsconfig.json` | Configuración principal del compilador |
| `.gitignore` | Archivos generados que no conviene versionar |
| `GUIA_DE_ESTUDIO.md` | Método recomendado para aprovechar el curso |

## Resultado esperado al terminar

Si completas este libro con práctica real, deberías estar listo para:

- usar TypeScript en proyectos Node.js;
- entender mejor bases de frameworks como React, Next.js o Angular;
- modelar contratos de datos más claros;
- trabajar con código moderno de frontend o backend con menos errores.

---

## 🤝 Cómo apoyar este proyecto

Este libro es gratuito y seguirá siéndolo. Si te resulta útil, hay varias
formas sencillas de apoyar para que llegue a más personas:

- ⭐ Dale una estrella al repositorio en GitHub:
https://github.com/yetsin7/Curso-de-TypeScript
- 📣 Compártelo con amigos, compañeros de clase y otros estudiantes
  nicaragüenses que estén aprendiendo a programar.
- 🐛 Abre un issue si encuentras un error, una explicación confusa o un tema
  que falta por cubrir.
- 🔧 Envía un pull request con mejoras: correcciones, ejemplos adicionales,
  ejercicios o aclaraciones que ayuden a quien venga después de ti.

Cada estrella, cada compartida y cada contribución ayuda a que más
nicaragüenses puedan aprender a programar de forma libre y profesional.

---

## Licencia

Este material es de uso libre para fines educativos.

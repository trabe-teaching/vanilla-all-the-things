Trabe

Asís & David

--

We develop front and back with JS (15+ years)

In the beginning there was the browser... hell.

Solution: vast ecosystem of libraries and tools.

We are old (emojis).

--

Let go of the past (Adam driver the last jedi)

--

<!--
* Browser shit.
* APIs incompatibles, implementaciones divergentes soporte desigual
* Ecosistema para solventar eso
* Pero eso es el pasado.
* Somos viejos, estamos acostumbrados y vemos bien soluciones que a lo mejor ya no pueden tener sentido.
-->

--

Vanilla all the things

--

Disclaimers

JS focus, also valid with other languages/technologies

Vanilla slides (just HTML+CSS).

--

Front (cover image)

--

Vanilla forms

Custom calendars =>  <input type=date />
Time input -> Text field (https://adamsilver.io/blog/designing-a-time-input/)
Form/Validation libs -> FormData + string values. Browser validation.

Formik (44kB) + Yup (60kB)

https://bundlephobia.com

--

Custom modals and dialogs => Browser <dialog>

Not just size. Modality and controlling the focus.

react-modal (25kB), react-focus-lock (15kB)

Don't fight the browser

--

* SASS, postCSS, CSS in JS, etc. -> Plain CSS with custom properties, calcs and advanced selectors.
  * `has`, `where`, `is`
  * Metodolotions! (https://getbem.com/introduction/ https://www.keithcirkel.co.uk/css-classes-considered-harmful/)

* Scoping, CSS-in-JS vs CSS modules. Cannot fight the global CSS scope. The runtime problem (style injection, SSR, etc.)

Emotion (15kB)

--

Luxon, Moment => Temporal + Intl

Luxon (72kB although can be pruned)

--

Summarizing

* The bundling/npm hell (size, security, updates)
* Runaway from deps
* Always audit
* Beware of the coziness `npm install`

--

Alternatives

* Vanilla HTML, CSS and JS
* Do not use npm: CDNs + import maps

--

Front React (vanilla reactiva)

--

useEffect deps => no deps

useCallback, useMemo => nay

Redux, Jotai, etc. => useState, useReducer

Anti-vanilla :) Use React events, avoid DOM events

--

Front and back

--

Know your APIs

lodash -> map, forEach, filter

Master some FP basics!

--

Vanilla-inception (vanilla inside vanilla)

SSE instead of Websockets

* Zero setup
* Simpler API
* HTTP transport

Server push only: keep it simple

--

Back (vanilla pod tatooed on strong man muscular back)

--

Know your APIs 2

* yargs vs API args node.
* chalk vs inspect.colors
* winston vs util.debug
* fs-extra vs fs (no extras!)

--

axios, bluebird -> fetch

* Less features but simpler and portable
* Features arrive (Abort controller). Better later than never

--

Beware DSL to generate standards

joi-to-json-schema: simpler/compact API but not developer-portable.


--

Tooling (vanilla pod on the side of a toolbox)

--

* yarn, pnpm -> npm. It's enough usually. Ubiquitous.

* Webpack + Jest + plugins => Vite + Vitest => Rome
  * Reduce, simplify. Do not mix

* For simple features use standard lib
  * Jest -> node test runner (links)
  * Nodemon -> node watch (links)
  * Yargs (etc) -> util.parseArgs (links)
  * Husky => `hooksPath`
  * Lerna, Nx, Turbo => `npm monorepo`

* Ditch Babel!  ESM and supported features

* Version lifecycle
  * Stage-0: no
  * Stage-1: no
  * Stage-2: no
  * Stage-3/4: Most probably already available.

<!-- stage-3: candidate, vendor implementation -->

--

TypeScript (careto the wtf)
Use JS because reasons... (troll face)

--

Even more vanilla

* Cloud infrastructure
* Shell
* Editors/IDEs
* Etc.

--

Summing up

--

Not vanilla when:
... older browsers or node version
... the UI requires it

Evergreen browsers, modern node (or Deno): go vanilla.

--

Can I Use (link)
Look for green.
Know your constraints
Always verify

--

Know your APIs

Be up to date: newsletters, feeds, whatever.

--

Progressive enhancement

* Vanilla stuff to give basic support
* Then progresively enhace xD

--

Do not fight the browser/environment

<!-- anecdote: Autocomplete API, I'm looking at you. -->

--

* Vanilla means Standard
* Standard means developer-portable

--

Vanilla all the things!

--

Questions?

--

We are always hiring!

rrhh@trabe.io

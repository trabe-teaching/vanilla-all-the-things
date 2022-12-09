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

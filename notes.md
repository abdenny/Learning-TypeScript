- What?

- It's an open source typed syntatic superset of javascript. It's developed by microsoft and compiles to JS.

- It comes in three parts: Language, Language Server and Compiler.

- Types disappear in comp, so it doesnt work on the back-end.

- It works seamlessly with Babel 7. Babel take TS files as input. Doesn't us type checking though, just chops down to legacy JS code. TS is almost like a really fancy linter.

-Why would we want to add types?

- It allows us to encode constraints and assumptions as part of the developers intent.

- Allows us to catch common mistakes. (ex: incomplete refactors)

- Moves runtime errors to compile time

- Provides consumers with a great DX

- TSC to compile ts to ES3 JavaScript (the kind that runs in IE6)
- We can also compile with a flag that doesnt dumb it down so much. ex: tsc index.ts --target ES2015
- tsc index.ts --target ES2017 -- module commonjs --watch (Watches src files and incremental updates them.)
- Lots of other flags to explore later.

- tsconfig.jso-

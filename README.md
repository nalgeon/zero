# Zero Dependency Club

A curated list of packages, tools, and other software with zero third-party dependencies.

[Members](#members) • [FAQ](#frequently-asked-questions) • [Contributing](#contributing)

## Members

| Project                                              | Description                              | Language | License       |
| ---------------------------------------------------- | ---------------------------------------- | -------- | ------------- |
| [btree](https://github.com/tidwall/btree)            | B-tree                                   | Go       | MIT           |
| [codapi](https://github.com/nalgeon/codapi)          | Code sandbox engine                      | Go       | Apache-2.0    |
| [env](https://github.com/caarlos0/env)               | Parse environment variables into structs | Go       | MIT           |
| [faker](https://github.com/jaswdr/faker)             | Fake data generator                      | Go       | MIT           |
| [go-quartz](https://github.com/reugn/go-quartz)      | Scheduling library                       | Go       | MIT           |
| [hashmap.c](https://github.com/tidwall/hashmap.c)    | Hash map                                 | C        | MIT           |
| [httpbin](https://github.com/mccutchen/go-httpbin)   | HTTP request & response testing service  | Go       | MIT           |
| [linenoise](https://github.com/antirez/linenoise)    | Line editing (readline alternative)      | C        | BSD-2-Clause  |
| [pico-args](https://github.com/RazrFalcon/pico-args) | CLI arguments parser                     | Rust     | MIT           |
| [sds](https://github.com/antirez/sds)                | Dynamic strings library                  | C        | BSD-2-Clause  |
| [seahorse](https://github.com/ksk001100/seahorse)    | CLI framework                            | Rust     | MIT           |
| [sqlite](https://github.com/sqlite/sqlite)           | Database engine                          | C        | Public domain |
| [sqlpkg](https://github.com/nalgeon/sqlpkg-cli)      | SQLite package manager                   | Go       | MIT           |
| [wazero](https://github.com/tetratelabs/wazero)      | WebAssembly runtime                      | Go       | Apache-2.0    |

## Frequently asked questions

> Why?

Because having zero dependencies is awesome.

> But having dependencies is okay.

Sure!

> What does "zero dependencies" even mean?

It means that your software does not rely on external libraries to compile, install, or function. With one exception: it may depend on the standard library and runtime of the language you are using.

> Which languages do you accept?

All of them.

> I have a JavaScript project with 0 dependencies and only 2635 "devDependencies", would you accept it?

Nope. "Dev" dependencies are also dependencies.

## Contributing

Make sure that the project you want to add meets the following criteria:

-   Zero dependencies (stdlib only)
-   Open source license
-   Hosted on GitHub (mirror is OK)
-   50+ stars
-   Stable working version
-   English documentation

Then send a PR. That's it!

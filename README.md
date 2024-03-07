# Zero Dependency Club

A curated list of packages, tools, and other software with zero third-party dependencies.

[Members](#members) • [FAQ](#frequently-asked-questions) • [Contributing](#contributing)

## Members

| Project                                                        | Description                              | Language   | License       |
| -------------------------------------------------------------- | ---------------------------------------- | ---------- | ------------- |
| [asciigraph](https://github.com/guptarohit/asciigraph)         | ASCII line graphs in command line apps   | Go         | BSD-3-Clause  |
| [autocomp.js](https://github.com/knadh/autocomp.js)            | Autocomplete library                     | JavaScript | MIT           |
| [btree.c](https://github.com/tidwall/btree.c)                  | B-tree                                   | C          | MIT           |
| [btree](https://github.com/tidwall/btree)                      | B-tree                                   | Go         | MIT           |
| [ccache](https://github.com/karlseguin/ccache)                 | LRU Cache for high concurrency           | Go         | MIT           |
| [chi](https://github.com/go-chi/chi)                           | HTTP router                              | Go         | MIT           |
| [codapi](https://github.com/nalgeon/codapi)                    | Code sandbox engine                      | Go         | Apache-2.0    |
| [cors](https://github.com/rs/cors)                             | CORS request handler                     | Go         | MIT           |
| [env](https://github.com/caarlos0/env)                         | Parse environment variables into structs | Go         | MIT           |
| [faker](https://github.com/jaswdr/faker)                       | Fake data generator                      | Go         | MIT           |
| [gc](https://github.com/mkirchner/gc)                          | Mark-and-sweep garbage collector         | C          | MIT           |
| [goawk](https://github.com/benhoyt/goawk)                      | Embeddable AWK interpreter               | Go         | MIT           |
| [go-lua](https://github.com/Shopify/go-lua)                    | Lua VM                                   | Go         | MIT           |
| [go-quartz](https://github.com/reugn/go-quartz)                | Scheduling library                       | Go         | MIT           |
| [gofakeit](https://github.com/brianvoe/gofakeit)               | Fake data generator                      | Go         | MIT           |
| [hamt](https://github.com/mkirchner/hamt)                      | Hash array-mapped trie                   | C          | MIT           |
| [hashmap.c](https://github.com/tidwall/hashmap.c)              | Hash map                                 | C          | MIT           |
| [htmz](https://github.com/Kalabasa/htmz)                       | HTML microframework                      | JavaScript | MIT           |
| [httpbin](https://github.com/mccutchen/go-httpbin)             | HTTP request & response testing service  | Go         | MIT           |
| [linenoise](https://github.com/antirez/linenoise)              | Line editing (readline alternative)      | C          | BSD-2-Clause  |
| [microdot](https://github.com/miguelgrinberg/microdot)         | Web framework                            | Python     | MIT           |
| [nanoserde](https://github.com/not-fl3/nanoserde)              | JSON/TOML/RON serialization              | Rust       | MIT           |
| [netjail](https://github.com/stealthrocket/netjail)            | Network access control for HTTP/TCP      | Go         | MIT           |
| [notes](https://github.com/nickjj/notes)                       | Text notes management tool               | Shell      | MIT           |
| [parson](https://github.com/kgabis/parson)                     | JSON library                             | C          | MIT           |
| [pico-args](https://github.com/RazrFalcon/pico-args)           | CLI arguments parser                     | Rust       | MIT           |
| [quickjs](https://github.com/bellard/quickjs)                  | Javascript engine                        | C          | MIT           |
| [sc](https://github.com/tezc/sc)                               | Common libraries and data structures     | C          | BSD-3-Clause  |
| [sds](https://github.com/antirez/sds)                          | Dynamic strings library                  | C          | BSD-2-Clause  |
| [seahorse](https://github.com/ksk001100/seahorse)              | CLI framework                            | Rust       | MIT           |
| [simple-graph](https://github.com/dpapathanasiou/simple-graph) | Graph database in SQLite                 | SQL        | MIT           |
| [sqlite](https://github.com/sqlite/sqlite)                     | Database engine                          | C          | Public domain |
| [sqlpkg](https://github.com/nalgeon/sqlpkg-cli)                | SQLite package manager                   | Go         | MIT           |
| [steganography](https://github.com/auyer/steganography)        | LSB steganography on images              | Go         | MIT           |
| [tagger](https://github.com/jcubic/tagger)                     | Tag editor                               | JavaScript | MIT           |
| [toml](https://github.com/BurntSushi/toml)                     | TOML serialization                       | Go         | MIT           |
| [utf8.h](https://github.com/sheredom/utf8.h)                   | UTF-8 string functions                   | C          | Unlicense     |
| [uuid](https://github.com/google/uuid)                         | Generate and inspect UUIDs               | Go         | BSD-3-Clause  |
| [wazero](https://github.com/tetratelabs/wazero)                | WebAssembly runtime                      | Go         | Apache-2.0    |
| [xid](https://github.com/rs/xid)                               | Globally unique ID generator             | Go         | MIT           |
| [xxhash](https://github.com/cespare/xxhash)                    | 64-bit xxHash algorithm (XXH64)          | Go         | MIT           |
| [yaegi](https://github.com/traefik/yaegi)                      | Go interpreter                           | Go         | Apache-2.0    |

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

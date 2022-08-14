|     |                         |                                                |                                                                                                          |
| --- | ----------------------- | ---------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| No. | Coding Language         | Compile /Interpret                             | Exec File                                                                                                |
| 1   | rust                    | [rustc main.rs](http://main.rs/)               | [.cargo run file\_name.rs | /main | file\_name.exe ](http://file_name.rs/)                               |
| 2   | nodejs (javascript)     |                                                | node file.js                                                                                             |
| 3   | go                      | go build main.go                               | go run xxx.go | ./xxx                                                                                    |
| 4   | java                    | javac main.java                                | java main                                                                                                |
| 5   | C#                      | mcs filename.cs<br>csc filename.cs             | mono filename.exe<br>filename                                                                            |
| 6   | Scalar                  | scalac -jar main.jar                           | scala main                                                                                               |
| 7   | Haskell                 | ghc helloworld.hs                              | ./helloworld<br>runhaskell helloworld.hs                                                                 |
| 8   | C                       | gcc -o helloworld HelloWorld.c                 | ./helloworld                                                                                             |
| 9   | php                     | xxx.php                                        | php xxx.php | ./xxx.php                                                                                  |
| 10  | ruby                    |                                                | ruby hello\_world.rb                                                                                     |
| 11  | Typescript (javascript) | tsc app.ts > app.js                            | node app.js<br>ts-node app.ts                                                                            |
| 12  | deno                    | deno compile file.ts                           | deno run file.ts                                                                                         |
| 13  | bun                     |                                                | bun run helloworld.js                                                                                    |
| 14  | python                  | python main,py                                 | python3 command\_line.py                                                                                 |
| 15  | R                       |                                                | Rscript file.R                                                                                           |
| 16  | Carbon                  |                                                | bazel run //explorer -- ./explorer/testdata/print/format\_only.carbon                                    |
| 17  | Erlang                  | $erlc <filename>.erl                           | erl -noshell -s <module name> <function name><br>erl> <modulename>:<function\_name>( <parameters> ).<br> |
| 18  | Kotlin                  | kotlinc hello.kt -include-runtime -d hello.jar | java -jar hello.jar                                                                                      |
| 19  | Flutter                 | flutter build <DIRECTORY>                      | flutter run <DART\_FILE>                                                                                 |
| 20  | ObjectiveC              | clang -framework Foundation hello.m -o hello   | ./hello                                                                                                  |
| 21  | WebAssembly             |                                                | asc hello-world.ts -b hello-world.wasm                                                                   |
| 22  | SQL                     |                                                | mysql> source file\_name<br>mysql> \\. file\_name                                                        |
| 23  | Shell                   |                                                | ./file-bash-shell.sh                                                                                     |
| 24  | Assembly                | nasm -f macho hello.asm<br>ld -o hello hello.o | ./hello                                                                                                  |
| 25  | Switft                  | swift build<br>swiftc hello.swift              | .build/debug/HelloWorld<br>./hello                                                                       |
| 26  | Lua                     | ./main.lua                                     | lua helloworld<br>./helloworld<br>                                                                       |

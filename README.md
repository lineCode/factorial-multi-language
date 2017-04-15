Comparison of languages for speed by calculation of factorial in different languages
====================================================================================

Hardware:
---------
2.4 GHz Intel Core i5 (haswell)

Report:
-------
### versions:

  * C: Apple LLVM version 8.1.0 (clang-802.0.38)
  * CoffeeScript: 1.10.0
  * D: 2.074.0
  * Dart: 1.22.1
  * Erlang: 8.3
  * Go: 1.8.1
  * Haskell: 8.0.2
  * Java: 1.8.0_111
  * JavascriptCore: 10.1
  * Kotlin: 1.0.5
  * OCaml: 4.04.0
  * Pascal: 3.0.2
  * PyPy: 5.7.1
  * Rust: 1.16.0
  * Swift: 3.1
  * awk: 20070501
  * gawk: 4.1.4
  * lua: 5.2.4
  * luajit: 2.0.4
  * nim: 0.16.0
  * node.js: 7.9.0
  * perl: 5.18.2
  * perl6: 2017.01 built on MoarVM version 2017.01
  * php: 5.6.30
  * python: 2.7.10
  * python3: 3.6.1
  * ruby: 2.0.0


### raw data:

    C: 7.981 sec for 100000000 = 12529301 rps
    C gcc -O1: 5.224 sec for 500000000 = 95707446 rps
    C gcc -O2: 0.429 sec for 9000000000 = 20971326604 rps
    CoffeeScript: 5.770 sec for 50000000 = 8665196 rps
    D: 4.621 sec for 100000000 = 21639027 rps
    Dart: 7.493 sec for 200000000 = 26691443 rps
    Erlang: 5.720 sec for 7000000 = 1223817 rps
    Go: 10.926 sec for 150000000 = 13728443 rps
    Go-cgo: 4.239 sec for 50000000 = 11794775 rps
    Go-mt: 3.431 sec for 150000000 = 43721304 rps
    Haskell: 11.249 sec for 10000000 = 888986 rps
    Java: 7.174 sec for 300000000 = 41820136 rps
    JavascriptCore: 3.443 sec for 50000000 = 14520192 rps
    Kotlin: 5.252 sec for 200000000 = 38077891 rps
    OCaml: 7.320 sec for 150000000 = 20491147 rps
    Pascal: 4.704 sec for 100000000 = 21257187 rps
    PyPy: 5.800 sec for 10000000 = 1724216 rps
    Rust: 3.292 sec for 70000000000 = 21262203366 rps
    Swift: 7.733 sec for 200000000 = 25861938 rps
    awk: 3.201 sec for 1000000 = 312420 rps
    gawk: 4.133 sec for 1000000 = 241950 rps
    lua: 3.336 sec for 3000000 = 899253 rps
    luajit: 3.599 sec for 50000000 = 13894496 rps
    nim: 4.171 sec for 10000000 = 2397691 rps
    node.js: 5.629 sec for 50000000 = 8882689 rps
    perl: 4.300 sec for 1000000 = 232557 rps
    perl6: 6.967 sec for 300000 = 43057 rps
    php: 2.178 sec for 1000000 = 459146 rps
    python: 4.850 sec for 2000000 = 412402 rps
    python3: 7.874 sec for 2000000 = 253987 rps
    ruby: 5.905 sec for 5000000 = 846769 rps


### report all:

<img alt="Chart for all" width="401" src="https://chart.googleapis.com/chart?cht=bhs&chs=602x498&chd=t%3A95707446%2C43721304%2C41820136%2C38077890%2C26691443%2C25861938%2C21639027%2C21257186%2C20491146%2C14520192%2C13894495%2C13728442%2C12529300%2C11794775%2C8882688%2C8665196%2C2397691%2C1724216%2C1223816%2C899252%2C888986%2C846768%2C459146%2C412402%2C312420%2C253986%2C241949%2C232556&chco=4d89f9&chbh=12&chds=0,95707446.3781326&chxt=x,y,r&chxl=1%3A%7Cperl%7Cgawk%7Cpython3%7Cawk%7Cpython%7Cphp%7Cruby%7CHaskell%7Clua%7CErlang%7CPyPy%7Cnim%7CCoffeeScript%7Cnode.js%7CGo-cgo%7CC%7CGo%7Cluajit%7CJavascriptCore%7COCaml%7CPascal%7CD%7CSwift%7CDart%7CKotlin%7CJava%7CGo-mt%7CC%20gcc%20-O1%7C2%3A%7C232556%20rps%7C241949%20rps%7C253986%20rps%7C312420%20rps%7C412402%20rps%7C459146%20rps%7C846768%20rps%7C888986%20rps%7C899252%20rps%7C1223816%20rps%7C1724216%20rps%7C2397691%20rps%7C8665196%20rps%7C8882688%20rps%7C11794775%20rps%7C12529300%20rps%7C13728442%20rps%7C13894495%20rps%7C14520192%20rps%7C20491146%20rps%7C21257186%20rps%7C21639027%20rps%7C25861938%20rps%7C26691443%20rps%7C38077890%20rps%7C41820136%20rps%7C43721304%20rps%7C95707446%20rps%7C0%3A%7C0%20%25%7C10%20%25%7C20%20%25%7C30%20%25%7C40%20%25%7C50%20%25%7C60%20%25%7C70%20%25%7C80%20%25%7C90%20%25%7C100%20%25">

### report fast:

<img alt="Chart for fast" width="466" src="https://chart.googleapis.com/chart?cht=bhs&chs=700x311&chd=t%3A95707446%2C43721304%2C41820136%2C38077890%2C26691443%2C25861938%2C21639027%2C21257186%2C20491146%2C14520192%2C13894495%2C13728442%2C12529300%2C11794775%2C8882688%2C8665196%2C2397691&chco=4d89f9&chbh=12&chds=0,95707446.3781326&chxt=x,y,r&chxl=1%3A%7Cnim%7CCoffeeScript%7Cnode.js%7CGo-cgo%7CC%7CGo%7Cluajit%7CJavascriptCore%7COCaml%7CPascal%7CD%7CSwift%7CDart%7CKotlin%7CJava%7CGo-mt%7CC%20gcc%20-O1%7C2%3A%7C2397691%20rps%7C8665196%20rps%7C8882688%20rps%7C11794775%20rps%7C12529300%20rps%7C13728442%20rps%7C13894495%20rps%7C14520192%20rps%7C20491146%20rps%7C21257186%20rps%7C21639027%20rps%7C25861938%20rps%7C26691443%20rps%7C38077890%20rps%7C41820136%20rps%7C43721304%20rps%7C95707446%20rps%7C0%3A%7C0%20%25%7C10%20%25%7C20%20%25%7C30%20%25%7C40%20%25%7C50%20%25%7C60%20%25%7C70%20%25%7C80%20%25%7C90%20%25%7C100%20%25">

### report other:

<img alt="Chart for other" width="466" src="https://chart.googleapis.com/chart?cht=bhs&chs=700x209&chd=t%3A1724216%2C1223816%2C899252%2C888986%2C846768%2C459146%2C412402%2C312420%2C253986%2C241949%2C232556&chco=4d89f9&chbh=12&chds=0,1724216.3828799&chxt=x,y,r&chxl=1%3A%7Cperl%7Cgawk%7Cpython3%7Cawk%7Cpython%7Cphp%7Cruby%7CHaskell%7Clua%7CErlang%7CPyPy%7C2%3A%7C232556%20rps%7C241949%20rps%7C253986%20rps%7C312420%20rps%7C412402%20rps%7C459146%20rps%7C846768%20rps%7C888986%20rps%7C899252%20rps%7C1223816%20rps%7C1724216%20rps%7C0%3A%7C0%20%25%7C10%20%25%7C20%20%25%7C30%20%25%7C40%20%25%7C50%20%25%7C60%20%25%7C70%20%25%7C80%20%25%7C90%20%25%7C100%20%25">



See also
--------

  * [Wikipedia](http://en.wikipedia.org/wiki/Factorial)
  * [Rosettacode](http://rosettacode.org/wiki/Factorial)
  * [Stackoverflow](http://stackoverflow.com/questions/23930/factorial-algorithms-in-different-languages)
  * [Benchmark of Fibonacci in OOP](https://github.com/Balancer/benchmarks-fib-obj)
  * [The Computer Language Benchmarks Game](http://benchmarksgame.alioth.debian.org)

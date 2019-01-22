## Go coding exercises and elegant solutions [![Build Status](https://travis-ci.org/plutov/practice-go.svg?branch=master)](https://travis-ci.org/plutov/practice-go)

### How to solve

 - Each folder has a README.md file and `*_test.go` file, check it and find what kind of function you need to implement.
 - You may use anything you want except 3rd-party packages.
 - Implement the function.
 - Run tests and benchmarks.
 - Create a PR to `master` branch and answer questions from PR template.
 - We will choose the most fast and elegant solution and merge into the repo within 7 days.

### Challenges

1. [x] ([@macocha](https://github.com/macocha)) [chess](https://github.com/plutov/practice-go/tree/master/001-chess)
2. [x] ([@kennygrant](https://github.com/kennygrant)) [floyd](https://github.com/plutov/practice-go/tree/master/002-floyd)
3. [x] ([@ledongthuc](https://github.com/ledongthuc)) [anagram](https://github.com/plutov/practice-go/tree/master/003-anagram)
4. [x] ([@heliac2000](https://github.com/heliac2000)) [jaro](https://github.com/plutov/practice-go/tree/master/004-jaro)
5. [x] ([@nguyengiabk](https://github.com/nguyengiabk)) [mergesort](https://github.com/plutov/practice-go/tree/master/005-mergesort)
6. [x] ([@nguyengiabk](https://github.com/nguyengiabk)) [wordladder](https://github.com/plutov/practice-go/tree/master/006-wordladder)
7. [x] ([@EvenPeng](https://github.com/EvenPeng)) [sumdecimal](https://github.com/plutov/practice-go/tree/master/007-sumdecimal)
8. [x] ([@bediger4000](https://github.com/bediger4000)) [buildword](https://github.com/plutov/practice-go/tree/master/008-buildword)
9. [x] ([@zerkms](https://github.com/zerkms)) [shorthash](https://github.com/plutov/practice-go/tree/master/009-shorthash)
10. [x] ([@zerkms](https://github.com/zerkms)) [romannumerals](https://github.com/plutov/practice-go/tree/master/010-romannumerals)
11. [x] ([@zerkms](https://github.com/zerkms)) [lastlettergame](https://github.com/plutov/practice-go/tree/master/011-lastlettergame)
12. [x] ([@duckbrain](https://github.com/duckbrain)) [reverseparentheses](https://github.com/plutov/practice-go/tree/master/012-reverseparentheses)
13. [x] ([@kennygrant](https://github.com/kennygrant)) [functionfrequency](https://github.com/plutov/practice-go/tree/master/013-functionfrequency)
14. [x] ([@marz619](https://github.com/marz619)) [coins](https://github.com/plutov/practice-go/tree/master/014-coins)
15. [x] ([@marz619](https://github.com/marz619)) [secretmessage](https://github.com/plutov/practice-go/tree/master/015-secretmessage)
16. [x] ([@shogg](https://github.com/shogg)) [missingnumbers](https://github.com/plutov/practice-go/tree/master/016-missingnumbers)
17. [x] ([@HDudzus](https://github.com/HDudzus)) [spiral](https://github.com/plutov/practice-go/tree/master/017-spiral)
18. [x] ([@TomLefley](https://github.com/TomLefley)) [warriors](https://github.com/plutov/practice-go/tree/master/018-warriors)
19. [x] ([@shogg](https://github.com/shogg)) [snowflakes](https://github.com/plutov/practice-go/tree/master/019-snowflakes)
20. [x] ([@shogg](https://github.com/shogg)) [brokennode](https://github.com/plutov/practice-go/tree/master/020-brokennode)
21. [x] ([@shogg](https://github.com/shogg)) [nasacollage](https://github.com/plutov/practice-go/tree/master/021-nasacollage)

### Run tests with benchmarks

Run it in the challenge folder:

```
go test -bench .
```

### How to create new challenge from template

```
./new.sh challenge_name
```

# git-corto

Git extensions for Cortobox workflow

## Installation

Clone the repository:

```
git clone https://github.com/jleeothon/git-corto
```

Run `sudo rake install` from the project directory:

```
cd git-corto/ && sudo rake install
```

## Commands

### vstatus

Displays an elaborate status of all git clones under the current directory. Find possible usages with `git vstatus -h`.

Example 1:

```
$ git vstatus
https://github.com/cortoproject/antlr3c            ec09afa
https://github.com/cortoproject/c-binding          4294070
https://github.com/cortoproject/corto-language     81da24d
https://github.com/cortoproject/corto              658062c
https://github.com/cortoproject/cortodoc           a9f9f38
https://github.com/jleeothon/git-corto             2e9649a
https://github.com/cortoproject/io                 9bec7a1
https://github.com/cortoproject/json               2bf2598
https://github.com/cortoproject/postgresql         bd1f21a
https://github.com/cortoproject/python-binding     85e6818
https://github.com/cortoproject/test               3619c86
https://github.com/cortoproject/web                e74d599
https://github.com/cortoproject/xml                85bc8aa
```

Example 2 (GitHub-style link)

```
$ git vstatus --link
cortoproject/antlr3c@ec09afa
cortoproject/c-binding@4294070
cortoproject/corto-language@81da24d
cortoproject/corto@658062c
cortoproject/cortodoc@a9f9f38
jleeothon/git-corto@99067e2
cortoproject/io@9bec7a1
cortoproject/json@2bf2598
cortoproject/postgresql@bd1f21a
cortoproject/python-binding@85e6818
cortoproject/test@3619c86
cortoproject/web@e74d599
cortoproject/xml@85bc8aa
```

Example 3

```
$ git vstatus --name --hash
antlr3c            ec09afa
c-binding          4294070
corto-language     81da24d
corto              658062c
cortodoc           a9f9f38
git-corto          99067e2
io                 9bec7a1
json               2bf2598
postgresql         bd1f21a
python-binding     85e6818
test               3619c86
web                e74d599
xml                85bc8aa
```

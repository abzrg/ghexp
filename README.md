# GHEXP - GitHub Explorer

A simple commandline interface to GitHub Search

## Usage and Examples

```console
$ ghexp --help
```

```console
$ ghexp -l Json -p ".prettierrc.json"
$ ghexp -p .lldbrc
$ ghexp -p '".bashrc"'
$ ghexp -p .clangd -- IWYU pragma
$ ghexp -p neomutt/neomuttrc -- notmuch search
$ ghexp -p 'mpiisend.c'
$ ghexp -p .gitconfig -- '[color "diff"]'
$ ghexp -- '.align 4' AND 'Hello, World'
$ ghexp -p '.gitattributes' -l Markdown -- '*.md'
$ ghexp -l lua -- "cmd = { 'rust-analyzer' },"
$ ghexp -p '.github/workflows/' -l Yaml -- git commit
$ ghexp -U torvalds
$ ghexp -r torvalds/linux --type commits -- 'rust'
```

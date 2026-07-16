# Chapter 35 - Managing Packages with APAC

Example for Chapter 35 of *Introduction to the Aussom Programming Language*.

This chapter is about the `apac` **commands**, not Aussom code. A tiny sample package,
`greet/`, is included so you can build a zip and try the install lifecycle.

## Try the consumer lifecycle

```
# build a package zip from the sample source (covered fully in Chapter 36)
apac -p greet

# install it into a project, list it, remove it
mkdir myproject && cd myproject
apac -f -i ../greet-1.0.0.zip
apac -lf
apac -u greet
```

## Registry commands

```
apac -s <query>          # search the registry
apac -l <name>           # list a package's versions
apac -i <name>[@version]  # install from the registry
```

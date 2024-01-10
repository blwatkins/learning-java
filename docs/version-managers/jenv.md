# <a href="https://www.jenv.be/" target="_blank" rel="noopener noreferrer">jEnv</a>

jEnv is a version manager tool for the Java programming language.

# Common jEnv Commands

----

Install `jenv` with Homebrew

```
$ brew update
$ brew install jenv
```

----

See the current `jenv` version

```
$ jenv --version
```

----

Add a version of Java to `jenv` (jEnv will not download Java for you)

```
$ jenv <path/to/Java/Home>
```

Example: `$ jenv add /Library/Java/JavaVirtualMachines/jdk1.8.0_91.jdk/Contents/Home`

----

See all available versions of Java

```
$ jenv versions
```

----

Set the version of Java that should be used in the current directory

```
$ jenv local <version_tag>
```

----

Set the version of Java that should be used globally

```
$ jenv global <version_tag>
```

----

Set the version of Java that should be used in this shell session

```
$ jenv shell <version_tag>
```

----

## jbang catalog



This is a catalog to use with [jbang](https://jbang.dev).

## How to run

Below are portable instructions to install/run with this catalog, if you want to download `jbang` with your preferred package manger see [jbang website](https://jbang.dev/download) for options.

### Run without jbang installed

Linux, OS X and Windows with bash compatible shell (i.e. cygwin, WSL,etc.)

```
curl -Ls https://sh.jbang.dev | bash -s - <alias>
```

Windows Powershell:

```
curl -Ls https://sh.jbang.dev | bash -s - <alias>
```

### Run with jbang installed 

```
jbang <alias>
```


### hello

Script that says hello back for each argument

 ```
 jbang hello
 ```

### properties

Dump table of System properties

 ```
 jbang properties
 ```

### env

Dump table of Environment Variables

 ```
 jbang env
 ```

### gavsearch

`gavsearch` lets you use search.maven.org from command line.
Example: `gavsearch hibernate` will search for artifacts with hibernate in its name.
You can use any of the search modifiers search.maven.org supports, i.e.:
`gavsearch c:QuarkusTest` will search for artifacts with class `QuarkusTest`

 ```
 jbang gavsearch
 ```

### git

Git command line tool implemented with jgit. Lets you do basic git features without installing git!

 ```
 jbang git
 ```

### bouncinglogo



 ```
 jbang bouncinglogo
 ```

### h2



 ```
 jbang h2
 ```

### catalog2readme



 ```
 jbang catalog2readme
 ```

### httpd

`httpd` runs a webserver serving out the content of a directory.
Example: `jbang httpd@jbangdev -d _site` will serve out the `_site` folder on localhost:8000.

 ```
 jbang httpd
 ```

### getjava

Experimental utility to download Java distributions using api.foojay.io.

 ```
 jbang getjava
 ```

### ec



 ```
 jbang ec
 ```

### faker



 ```
 jbang faker
 ```

### dalle



 ```
 jbang dalle
 ```

### bootstrap

Bootstrap a jbang script to make it self-contained.

 ```
 jbang bootstrap
 ```

### jmc



 ```
 jbang jmc
 ```



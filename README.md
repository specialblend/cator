# cator

cli command that prints (cats) a file, or provided fallback value if the file is empty or doesn't exist

### usage

```shell script

# prints `hello`
cator /dev/null hello

# prints `world`
cator non-existent-file world

# prints contents of `existent-file.txt`
cator existent-file.txt foo

````

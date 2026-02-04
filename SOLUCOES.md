# Soluções

## Problema 1 (B)

```bash
tar -xzf challenges.tar.gz
```

## Problema 2 (B)

```bash
cd challenges
```

## Problema 3 (B)

```bash
ls
```
## Problema 4 (B)
```bash
mkdir foo
```
## Problema 5 (I)
```bash
mkdir -p foo/bar/1/2/3
```
## Problema 6 (B)
```bash
rm -rf challenges/foo
```
## Problema 7 (B)
```bash
echo "Hello World"
```

## Problema 8 (B)
```bash
echo "Hello World" > challenges/hello.txt
``` 
## Problema 9 (B)
```bash
touch challenges/empty.txt
```
## Problema 10 (B)
```bash
rm challenges/empty.txt
``` 
## Problema 11 (I)
```bash
> challenges/empty.txt
```
## Problema 12 (I)

```bash
echo -n "" > challenges/empty2.txt
```
## Problema 13 (B)
```bash
cp challenges/hello.txt challenges/goodbye.txt
```
## Problema 14 (B)
```bash
mv goodbye.txt hello_copy.txt
```

## Problema 15 (I)
```bash

diff hello.txt hello_copy.txt
```
## Problema 16 (B)
```bash
cat hello.txt hello_copy.txt > 2_hellos.txt

```
## Problema 17 (B)
```bash
pwd
```

## Problema 18 (B)
```bash
ls -l
```
## Problema 19 (B)
```bash
echo "texto" >> restricted.txt
```
## Problema 20 (B)
```bash
./hello_executable
```
## Problema 21 (B)
```bash
chmod +x challenge_20 && ./challenge_20

```
## Problema 22 (B)
```bash
gcc compile_me.c -o compile_me && ./compile_me
```

## Problema 23 (A)
```bash
./redirect > output.txt 2>&1
```
## Problema 24 (B)
```bash
date
```

## Problema 25 (B)
```bash
ps aux
```
## Problema 26 (B)
```bash
nproc
```
## Problema 27 (B)
```bash
uname -r
```
## Problema 28 (B)
```bash
grep -R "You found the needle in the haystack!" bunch_of_files
```

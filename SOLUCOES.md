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

## Problema 29 (B)
```bash
head -n 25 people.csv
```
## Problema 30 (B)
```bash
tail -n 25 people.csv
```
## Problema 31 (I)
```bash
diff greeting1.txt greeting2.txt
```

## Problema 32 (I)
```bash
echo "Hello"; sleep 5; echo "world!"
```
## Problema 33 (I)
```bash
if=/dev/zero of=zeros.bin bs=1M count=1
```
## Problema 34 (I)
```bash
dd if=/dev/urandom of=random.bin bs=1M count=2
```

## Problema 35 (I)
```bash
wc -l README.md
```
## Problema 36 (B)
```bash
tac README.md  
```
## Problema 37 (I)
```bash
cut -d',' -f2 people.csv | tail -n +2
``

## Problema 38 (A)
```bash
cut -d',' -f2 people.csv | tail -n +2 | sort -u | wc -l
```
## Problema 39 (A)
```bash
tail -n +2 people.csv | cut -d',' -f2 | sort -u | wc -l
```

## Problema 40 (A)
```bash
cut -d',' -f2 people.csv | grep -v '^last_name$' | sort -u | wc -l

```
## Problema 41 (A)
```bash
time sh -c "cut -d',' -f2 people.csv | tail -n +2 | sort -u | wc -l"
```


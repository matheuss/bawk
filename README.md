# bawk
`awk`, but better

## Why?

I got sick of writing `awk '{print $1}'` all day long :expressionless:

## Installation

[Install `import`](https://import.pw/importpw/import/docs/install.md) and then add the following to your `.zshrc`/`.bashrc`/etc:

```shell
import matheuss/bawk
```

## Example

```shell
#!/usr/bin/import
import matheuss/bawk

# get the first "word"
echo a b c | bawk 1
```

## Usage

```shell
▲ ~ cat > test.txt <<EOF
a b c
EOF
▲ ~ cat test.txt | bawk 1
a
▲ ~ cat test.txt | bawk 2
b
▲ ~ cat test.txt | bawk 3
c
```


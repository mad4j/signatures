# Signatures

## Brainfuck

geeky signature (151 bytes; 5.8 bytes/output)

```bf
+++++++++[>>--->+++>
++++>++++>-[++++++++
<]<-]>>>+.---.>++.>-
--.<<++++.>>+++.<<.<
+.>>+.>.+.----.<++++
.<----.>-----.>.>+.<
--.<-.<.>>++.<-.<<.>
++.>+++.--.
```

![signature](brainfuck/bf-signature.png)

### How it works

Create the following values at the first places of memory ```0, 0, 45, 99, 108, 108, 63```

```bf
+++++++++[>>--->+++>++++>++++>-[++++++++<]<-] 
```

Then dump each letter.

```
 d   a  n   i   e   l   e   .  o   l   m   i   s   a  n   i   @  g   m   a  i   l   .  c  o   m 
100 97 110 105 101 108 101 46 111 108 109 105 115 97 110 105 64 103 109 97 105 108 46 99 111 109 
 64 61  6E  69  65  6C  65 2E  6F  6C  6D  69  73 61  6E  69 40  67  6D 61  69  6C 2E 63  6F  6D
```

### Tools

* https://fatiherikli.github.io/brainfuck-visualizer/
* https://tnu.me/brainfuck/generator

## Design

![signature](design/mad4j-logo.png)

## C64 Quine

```
1 READA$:PRINTA$CHR$
(34)A$CHR%(34):DATA"
1 READA$:PRINTA$CHR$
(34)A$CHR%(34):DATA"
```

![signature](c64quine/c64quine-signature.png)

## Numbers

### Hex

```
Daniele Olmisani
44616E69656C65204F6C6D6973616E69

daniele.olmisani@gmail.com
64616E69656C652E6F6C6D6973616E6940676D61696C2E636F6D

01100100 01100001 01101110 
01101001 01100101 01101100 
01100101 00101110 01101111 
01101100 01101101 01101001 
01110011 01100001 01101110 
01101001 01000000 01100111 
01101101 01100001 01101001 
01101100 00101110 01100011 
01101111 01101101

```

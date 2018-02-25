layout: true
.header[
Alice and Bob Go Public: a short history of modern cryptography
]

???
---

# Alice and Bob Go Public

### A short history of modern cryptography

![:scale 300px](assets/secret.png)

???
---

.left-column[
## Sources on Github
]

.right-column[
*Stefano Costa*, Bluewind R&D Managing Director

https://stefanoco.github.io/alice-and-bob
https://github.com/stefanoco

.pull-left[![:scale 200px](assets/qr1.png)]
.pull-right[![:scale 200px](assets/qr2.png)]

]

???
---

.left-column[
## People and links
]

.right-column[

Useful readings

https://simonsingh.net/books/the-code-book
https://www.crypto101.io

.pull-left[![:scale 200px](assets/simonsinghbook.png)]
.pull-right[![:scale 200px](assets/crypto101.png)]

]


???
---

.left-column[
## Executive summary
]

.right-column[
### Definition

![:scale 500px](assets/shannon1.png)


*Communication Theory of Secrecy Systems* by Claude Shannon, Bell System Technical Journal, Vol 28, Oct 1949, pgs 656-715
]


???
---

.left-column[
## Executive summary
]

.right-column[
### Three steps to modern cryptography

* changing keys
* exchanging keys
* public keys

]


???
---

.left-column[
## Before 1920
]

.right-column[
### Cryptography using reversible functions



.pull-left[
```
alice and bob
|||||||||||||
bmjdf-boe-cpc
```
]
.pull-right[y=f(x)]
.pull-right[x=g(y)]


Which means that in order to break:

* statistics
* linguistics
]

???
---

.left-column[
## Before World War 2
]

.right-column[
### The Enigma in Germany

.pull-left[![:scale 400px](assets/enigma-full.png)]
.pull-right[![:scale 200px](assets/enigma-plate.png)]

]

???
---

.left-column[
## Before World War 2
]

.right-column[
### Arthur Scherbius (1878-1929)

.pull-left[
* patented the Enigma
* no success in commercial applications
* Winston Churchill talk about importance of reserved communication
* Germany wanted to have better military encryption
]

.pull-right[![:scale 100px](assets/arthur-scherbius-1878-1929.png)]

]

???
---

.left-column[
## Before World War 2
]

.right-column[
### The Enigma in Germany

![:scale 300px](assets/enigma-funct.png)

]

???
---

.left-column[
## Before World War 2
]

.right-column[
### The Enigma in Germany

* each message encrypted with its own on-the-fly three letters key
* each message key encrypted with a preshared daily key
* the encrypted message key preceeds the message *repeated twice*
* a need for delivering books of daily keys (also to navy)

![:scale 300px](assets/enigma-keylist.png)

]

???
---

.left-column[
## Before World War 2
]

.right-column[
### Cypher Bureau (Biuro Szyfrów)

.pull-left[
* Poland worried about Germany
* Hire mathematicians and organize Crypto course (1929)
* Hans-Thilo Schmidt (German disaffected after WWI) sold Enigma papers to France, delivered to Poland

]

.pull-right[
![:scale 200px](assets/refewski-rozycki-1905-1980-1909-1942.png)
* Marian Rejewski (1905-1980)
* Jerzi Rozycki (1909-1942)
]
]

???
---

.left-column[
## Before World War 2
]

.right-column[
### Breaking the Enigma in Poland

* Rozycki and other three worked on the Enigma papers and built a replica (1932)
* Rozycki managed to find repetitions and patterns in the Enigma
* worked for one year in order to build a table of patterns useful for decryption
* Poland already stole one full Enigma keys book

]


???
---

.left-column[
## During World War 2
]

.right-column[
### Breaking the Enigma at Bletchley Park

The analysis and machines used in Poland (the Bombes) were eventually
delivered to UK two weeks before Hitler invaded Poland

![:scale 400px](assets/bletchley.png)

]


???
---

.left-column[
## During World War 2
]

.right-column[
### Breaking the Enigma at Bletchley Park

.pull-left[
Great contributions to breaking the new Enigma machines came from
Alan Turing or the father of modern automatic calculus machines
]

.pull-right[![:scale 100px](assets/alan-turing-1912-1954.png)
* Alan Turing (1912-1954)
]

]


???
---

.left-column[
## During World War 2
]

.right-column[
### Breaking the Enigma at Bletchley Park

Several plans and tricks for stealing the code books for Enigma (Ian Fleming)
or at least detect meta data, like the position of communicating partners (the U2 boats)

]


???
---

.left-column[
## During World War 2
]

.right-column[
### Breaking the Enigma at Bletchley Park

The first giant calculator was designed and mounted in a Post Office
research centre, and then used in Bletchley Park.

![:scale 200px](assets/colossus.png)

Based on tubes and destroyed right after
the end of the war, so no credit until recently
as first computer (ENIAC)

]


???
---

.left-column[
## Lessons from the Enigma
]

.right-column[
### How to compromise cypher algorithms

* never try to hide the algorithm
* meta information is relevant
* repetition and pattern is evil

]


???
---

.left-column[
## During 1950-1970
]

.right-column[
### Commerce and finance

* exchanging secure messages very fast in a standard way is the new paradigm during 1950-1970
* NSA and other goverment organizations prefer to maintain control over algorithms
* 1976: after a contest NIST / NSA decides for DES as standard crypto algorithm
* A limit to key length at 56 bits was imposed
* DES was an adaptation of Lucifer, an algorithm studied at IBM
* Horst Feistel (Berlin 1915-US 1990)
]
???
---

.left-column[
## During 1950-1970
]

.right-column[
### DES (then Triple DES, AES)

* block cypher
* symmetric cypher

![:scale 300px](assets/Data_Encription_Standard_Flow_Diagram.svg.png)
]
???
---

.left-column[
## During 1950-1970
]

.right-column[
### DES (then Triple DES, AES)

Horst Feistel was also among the first to talk about *authenticating operations* (1973)

![:scale 400px](assets/feistel-science.png)
]
???
---

.left-column[
## Exchanging a key

]

.right-column[
### Alice meets Bob without knowing him before

Exchanging a key without meeting before

]


???
---

.left-column[
## Exchanging a key
]

.right-column[
### A story of two padlocks

![:scale 500px](assets/padlocks.png)

]

???
---

.left-column[
## Exchanging a key
]

.right-column[
### Mixing the colours

![:scale 400px](assets/colours-key.png)

]

???
---

.left-column[
## Exchanging a key
]

.right-column[
### Two lone researchers and the birth of high speed networking

![:scale 200px](assets/diffie-1945-hellmann-1945.png)

* Whitfield Diffie (1944) meets Martin Hillmann (1946)
* (1974) Diffie drives New York->Stanford to find Hillmann after having given a talk to IBM TJ Watson (4700Km, 43hrs drive)
* (1976) at the Stanford University first key exchange proposed with Ralph Merkle (DHM)
]

???
---

.left-column[
## Exchaning a key
]

.right-column[
### Exponential and modulo functions: the final solution

![:scale 500px](assets/dh-modulo.png)
]

???
---

.left-column[
## An idea of asymmetric keys
]

.right-column[
### Whitfield Diffie is not happy

* Diffie is not yet happy, thinks a lot about how to make it simple
* asymmetric key! or how to live without exchanging secure keys
* simple as closing the padlock without a key and opening using its key
* no idea about how to build it...
]

???
---

.left-column[
## Public key: RSA
]

.right-column[
### Three friends and prime numbers

![:scale 300px](assets/rivest-1947-shamir-1952-aldeman-1945.png)

* Ronald Rivest (1947) and Adi Shamir (1952), Computer Scientists
* Leonard Adleman (1945), Mathematician

1977, MIT Laboratory for Computer Science, after having spent a night drinking Manischewitz (Kosher wine) at a student's house the paper was written by the morning
]


???
---

.left-column[
## Public key: RSA
]

.right-column[
### The published paper

![:scale 500px](assets/rsa001.png)

]


???
---

.left-column[
## Public key: RSA
]

.right-column[
### RSA

* first publicly available *public key encryption* scheme
* based on the properties of prime numbers and factorization
* very clever one way function
* can encrypt with a publicly distributed key
* can decrypt only with a private key
* makes it possible very fast exchange of secure messages

]

???
---

.left-column[
## Public key: RSA
]

.right-column[
### RSA fundamentals


The simplified form of the one way function is a product of two prime numbers:

```
N = p * v
```

* N is the public key
* p, v is the private key (very high prime numbers)
* try finding p and/or v from N...

A couple of functions exist so that:

```
message: m
encrypt: e = f(m, N)
decrpyt: m = g(e, p, v)

```

]

???
---

.left-column[
## Public key: RSA
]

.right-column[
### RSA fundamentals

Interesting to note that similar results were alredy been found by

* James H. Ellis
* Clifford Cocks
* Malcolm J. Williamson

(UK Government) but could not be disclosed until 1997

James H. Ellis was using a combination of a message and noise as
public key.

]


???
---

.left-column[
## Public key: RSA
]

.right-column[
### RSA proof of correctness

![:scale 500px](assets/rsa002.png)

]


???
---

.left-column[
## Just a bit of math
]

.right-column[
### Elliptic curve (ECC)

An elliptic curve defined on a plane (could be any *field*)

* we can define sum and product as geometric functions
* here A+B=-C

.pull-left[![:scale 300px](assets/elliptic_add.png)]
.pull-right[![:scale 200px](assets/elliptic_eq.png)]

]

???
---

.left-column[
## Just a bit of math
]

.right-column[
### Elliptic curve (ECC)

* product by itself: AxA=-C
* product multiple times: AxAxAxAx...=A^l=Q
* (A, Q points in the curve, l is a scalar)
* finding Q given A, l is easy; finding l given A and Q is too difficult

![:scale 300px](assets/elliptic_double.png)
]

???
---

## Any Question?

Let's keep in touch!

mail: stefano.costa@bluewind.it

twitter: @stefanobluewind

company: www.bluewind.it

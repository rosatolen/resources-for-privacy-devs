# Table of Contents

1. [Crypto-related Resources]
2. [Programming Languages]
3. [Code for Tor Browser High Security Mode]

----------------------------------------------------------------------------
# Crypto-related Resources

##OTRv2
* [Finite-State Security Analysis of OTR Version 2](http://www.jbonneau.com/doc/BM06-OTR_v2_analysis.pdf) by Joseph Bonneau and Andrew Morrison. 
* [Protocol](https://otr.cypherpunks.ca/Protocol-2.0.2.txt) by Nikita Borisov and Ian Goldberg.
* [Secure Off-the-Record Messaging](https://www.dmi.unict.it/diraimondo/web/wp-content/uploads/papers/otr.pdf) by Mario Di Raimondo, Rosario Gennaro and Hugo Krawczyk 

## Zero Knowledge Proof
* [Multiple Non-Interactive Zero Knowledge Proofs Based on a Single Random String](https://www.computer.org/csdl/proceedings/focs/1990/2082/00/089549.pdf) by Uriel Feige, Dror Lapidot and Adi Shamir. 

## Ciphers

* [So you want to use an alternative cipher…](https://blog.cryptographyengineering.com/2012/10/09/so-you-want-to-use-alternative-cipher/) by Matthew Green. 
* [Why switch from AES to a new stream cipher?](https://cr.yp.to/streamciphers/why.html) by Daniel Bernstein. 

### Stream cipher

#### Salsa20
* [Snuffle spec](https://cr.yp.to/snuffle.html#specification)
* [Salsa20 security](https://cr.yp.to/snuffle/security.pdf) by Daniel J. Bernstein.
* [Notes on the Salsa20 key size](https://cr.yp.to/snuffle/keysizes.pdf) by Daniel J. Bernstein.

#### XSalsa20
* [Extending the Salsa20 nonce](http://cr.yp.to/snuffle/xsalsa-20081128.pdf) by Daniel J. Bernstein.
* [Notes on the Salsa20 key size](https://cr.yp.to/snuffle/keysizes.pdf) by Daniel J. Bernstein.

### Blockcipher

#### In general
* [Evaluation of Some Blockcipher Modes of Operation](http://web.cs.ucdavis.edu/~rogaway/papers/modes.pdf) by Phillip Rogaway.

## Symmetric key algorithm

### DES
* [On the Security of Multiple Encryption](http://cs.jhu.edu/~sdoshi/crypto/papers/p465-merkle.pdf) by Ralph C. Merkle and Martin E. Hellman.

## Key Exchange

### Cramer-Shoup
* [Cramer Shoup Cryto-System Java implementation](https://github.com/omoeller/cramshou) by omoeller (not audited). 
* [Cramer Shoup Cryto-System Python implementation](https://github.com/benkreuter/cca2python) by benkreuter. 	

### Elliptic Curve
* [Basics from Modern Cyrpto Mailing List](https://moderncrypto.org/mail-archive/curves/2016/000812.html)
* [Base point values from Safe Curves](https://safecurves.cr.yp.to/base.html)
* [Designing Elliptic Curve Signature Systems](https://blog.cr.yp.to/20140323-ecdsa.html)
* [Elliptic Curves for Security draft-irtf-cfrg-curves-02](https://tools.ietf.org/html/draft-irtf-cfrg-curves-02#section-6.2): an algorithm for deterministically generating parameters for elliptic curves over prime fields by A. Langley.
* [A brief discussion on selecting new elliptic curves](http://csrc.nist.gov/groups/ST/ecc-workshop-2015/papers/session4-costello-craig.pdf) by Craig Costello, Patrick Longa, and Michael Naehrig 

#### Theory
* [Elliptic Curves Number Theory and Cryptography](http://people.cs.nctu.edu.tw/~rjchen/ECC2012S/Elliptic%20Curves%20Number%20Theory%20And%20Cryptography%202n.pdf) by Lawrence C. Washington
* [Isogenincs](http://math.mit.edu/classes/18.783/LectureNotes5.pdf) for a MIT class. 
* [Compact representation of an elliptic curve point](https://tools.ietf.org/html/draft-jivsov-ecc-compact-05): This document defines a format for efficient storage representation of an elliptic curve point over prime fields, suitable for use with any IETF format or protocol by A. Jivsov
* [Point Generation And Base Point Selection In ECC: An Overview](http://www.ijarcce.com/upload/2014/may/IJARCCE7J%20%20a%20moumita%20Point%20Generation%20And%20Base.pdf) by Moumita Roy1, Nabamita Deb2, Amar Jyoti Kumar.
* [SEC 1: Elliptic Curve Cryptography](http://www.secg.org/sec1-v2.pdf) by Certicom Research. 

### Edwards Curve

#### Theory
* [Edwards-curve Digital Signature Algorithm (EdDSA)](https://tools.ietf.org/html/draft-irtf-cfrg-eddsa-05): The elliptic curve signature scheme Edwards-curve Digital Signature Algorithm (EdDSA) is described by S. Josefsson. 

#### Encoding
* [Deterministic Encoding into Twisted Edwards Curves](https://www.researchgate.net/publication/304621009_Deterministic_Encoding_into_Twisted_Edwards_Curves) by Wei Yu, Kunpeng Wang, Bao Li and Song Tian. 

#### ed448

* [Ed448-Goldilocks, a new elliptic curve](https://eprint.iacr.org/2015/625.pdf) by Mike Hamburg
* [Ed448-Goldilocks code](http://ed448goldilocks.sourceforge.net/)
* [Decaf Publication in Modern Crypto](https://moderncrypto.org/mail-archive/curves/2015/000407.html)
* [Decaf Paper](https://mikehamburg.com/papers/decaf/decaf.pdf)
* [Decaf Implementation](https://sourceforge.net/p/ed448goldilocks/code/ci/decaf/tree/)
* [STRIKE implementation](https://github.com/twstrike/ed448)

#### ed225519
* [Spec](https://ed25519.cr.yp.to/)
* [Implementation](https://ed25519.cr.yp.to/python/ed25519.py) by Daniel J. Bernstein. 

## Message Authentification Code (MAC)
* [SHA3-based MACs](http://csrc.nist.gov/groups/ST/hash/sha-3/Aug2014/documents/perlner_kmac.pdf) by Ray Perlner.
* [New Proofs for NMAC and HMAC: Security without Collision-Resistance](http://cseweb.ucsd.edu/~mihir/papers/hmac-new.pdf) by Mihir Bellare. 

### Key derivation functions
* [Key derivation functions](https://cryptography.io/en/latest/hazmat/primitives/key-derivation-functions/) by cryptography.io. 
* [Recommendation for Key Derivation Using Pseudorandom Functions](http://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-108.pdf) by Lily Chen in NIST. 

## Digital Signatures
* [New variant of Guillou-Quisquater digital signature scheme](http://www.ijaamm.com/uploads/2/1/4/8/21481830/v3n1p13-92-97.pdf) by J. Ettanfouhi, O. Khadir
* [RSA signatures and Rabin–Williams signatures: the state of the art](https://cr.yp.to/sigs/rwsota-20080131.pdf) by Daniel J. Bernstein.
* [Proving tight security for Rabin–Williams signatures](https://cr.yp.to/sigs/rwtight-20080201.pdf) by Daniel J. Bernstein.
* [Short signatures from the Weil pairing](https://www.iacr.org/archive/asiacrypt2001/22480516.pdf) by Dan Boneh, Ben Lynn, and Hovav Shacham.
* [A Provably Secure Nyberg-Rueppel Signature Variant with Applications](https://eprint.iacr.org/2004/093.pdf) by Giuseppe Ateniese and Breno de Medeiros. 
* [Deterministic usage of DSA and ECDSA RFC](https://tools.ietf.org/html/rfc6979)
* [SPHINCS Stateless hash-based signatures](https://sphincs.cr.yp.to/software.html)

### XEdDSA
* [The XEdDSA and VXEdDSA Signature Schemes](https://whispersystems.org/docs/specifications/xeddsa/#curve448) by Trevor Perrin. 

### The Random Oracle Model
* [The random oracle model: a twenty-year retrospective](https://eprint.iacr.org/2015/140.pdf) by Neal Koblitz and Alfred J. Menezes. 

## Cryptocurrency
* [Zcash](https://github.com/zcash/zcash)

### Proof of Work
* [Equihash](https://www.internetsociety.org/sites/default/files/blogs-media/equihash-asymmetric-proof-of-work-based-generalized-birthday-problem.pdf)

----------------------------------------------------------------------------
## Designing and Using Protocols
* Determining the Security Level. In the cycle of creating cryptography, a cryptographer will publish a new algorithm for encryption or
  digital signatures, and subsequently, further research will be done to determine its security level. Search for this research to understand
  the security parts of your protocol.
* Hashes have two levels of security one based on collision attacks and the other based on and pre-image attack resistance. When deciding
  on which hash to use, it is important to keep in mind whether collision or pre-image attacks are a problem in the context of how the hash
  is used.
  * Are you concerned about the attacker finding the hash input given your hash output? (Pre-image attack)
  * Are you worried about an attacker finding another input that would produce the same value as yours? (Collision attack)
* Using a hash function with a lower security than the seed input WILL result in an output of lower security
* [Quick Hash Comparisons](https://emn178.github.io/online-tools/sha3_224.html)

### Sociallist Millionaire Protocol (SMP)
* [Socialist Millionaire Protocol Passphrase Generator](https://github.com/dillbyrne/smpp-generator) by dillbyrne. 

## Schemes
* [Folklore, Practice and Theory of Robust Combiners](http://eprint.iacr.org/2002/135.pdf) by Amir Herzberg. 

## Security
* [Chosen-Ciphertext Security of Multiple Encryption](https://www.cs.nyu.edu/~dodis/ps/2enc.pdf) by Yevgeniy Dodis and Jonathan Katz. 

----------------------------------------------------------------------------
## Maths

## Modular Arithmetic
* [Barret Reduction](https://en.wikipedia.org/wiki/Barrett_reduction) in Wikipedia. 

## Compendia 
* [Theory of Cryptography: 9th Theory of Cryptography Conference, TCC 2012](https://books.google.com.ec/books?id=iWirCAAAQBAJ&pg=PA223&lpg=PA223&dq=malleable+symmetric+schemes&source=bl&ots=3oszTtlOhU&sig=evzVsQk3DbLMdkZLVY_O6RD5BfQ&hl=en&sa=X&ved=0ahUKEwjrh4XU2rPPAhUFox4KHY-UAS0Q6AEIKjAD#v=onepage&q=malleable%20symmetric%20schemes&f=false), edited by Ronald Cramer.
* [Recommendation for Key Management](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-57pt1r4.pdf) by Elaine Barker in NIST. 
* [Recommendation for Pair-Wise Key Establishment Schemes Using Discrete Logarithm Cryptography](http://csrc.nist.gov/groups/ST/toolkit/documents/SP800-56Arev1_3-8-07.pdf) by Elaine Barker, Don Johnson, and Miles Smid in NIST. 

## Library
* [NaCl](https://nacl.cr.yp.to/index.html)
* [Off-the-Record Messaging Implementation by Nik Unger](https://crysp.uwaterloo.ca/software/)
* [The PBC (Pairing-Based Cryptography) library](https://crypto.stanford.edu/pbc/) by Ben Lynn

## PostQuantum Crypto
* [PQCrypto 2016](https://pqcrypto2016.jp)
* [PQCrypto 2016 Videos](https://www.youtube.com/playlist?list=PLCAbx7kHwCGLPpgETzBqQg11comaFCF_H)
* [PQCHacks: A gentle introduction to post-quantum cryptography](https://media.ccc.de/v/32c3-7210-pqchacks#video&t=908) by djb and Tanja Lange in 32c3.
* [Towards quantum-resistance cryptosystems from supersingular elliptic curve isogenies](http://eprint.iacr.org/2011/506.pdf) by Luca de Feo, David Jao and Jerome Plut. 

## Mailing List
* [Modern Crypto](https://moderncrypto.org/mail-archive/)
* [The Internet Engineering Task Force -IETF-](https://www.ietf.org/mail-archive/web/cfrg/current/maillist.html)
* [Cypherpunks](https://lists.cypherpunks.ca/pipermail)

## Hacking (in general)
* [Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking)

----------------------------------------------------------------------------
# Programming Languages

## Golang
TODO: Why Golang?

### General
* [Effective Go](https://blog.golang.org://golang.org/doc/effective_go.html)
* [The Go Blog](https://blog.golang.org/)
* [Open My Mind](http://openmymind.net/) by Karl Seguin.

### Books
* [An Introduction to Go Programming](https://www.golang-book.com/books/intro) 

----------------------------------------------------------------------------
# Code for Tor Browser High Security Mode
In high security mode, Tor only allows PNG images to be available.

If your website must support non-PNG images like SVG, you can set up a fallback image
like so [(Ref.)](https://css-tricks.com/a-complete-guide-to-svg-fallbacks/):

1. With HTML:
```
<object data="your.svg" type="image/svg+xml"> <img src="yourfallback.jpg" /> </object>
```
2. With CSS, which naturally throws away rules that the browser doesn't understand:
```
.image-with-fallback {
    background-image: url(fallback.png);
        background-image: url(your.svg), none;
}{}
```
[Why is SVG a problem? Pg 16 in this iSEC report](https://github.com/iSECPartners/publications/blob/052caf9c9c683ec0bed55782714df4d35c38f107/reports/Tor%20Browser%20Bundle/Tor%20Browser%20Bundle%20-%20iSEC%20Deliverable%201.3.pdf).

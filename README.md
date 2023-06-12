# Awesome Smart Card

A curated list of awesome resources that help learn and build smart cards.


## Overview

- [Java Card Wikipedia](https://en.wikipedia.org/wiki/Java_Card)
- [Oracle Java Card technology](https://www.oracle.com/java/java-card/)
- [Java Card Forum](https://javacardforum.com/), a group of companies and [resources](https://javacardforum.com/resources/documents/) to promote and develop Java as the preferred programming language for smart cards
- [javacard-curated-list](https://github.com/crocs-muni/javacard-curated-list), curated list of open-source Java Card applets and related applications for cryptographic smartcards :star: :star:
- [Analysis of JavaCard open-source ecosystem](https://medium.com/enigma-shards/analysis-of-javacard-open-source-ecosystem-9be0bfd66398) :star: :star:
- [NFC Wiki in Chinese](https://wiki.nfc.im/)

## Tutorials

- [Tutorial: JavaCards](https://www.youtube.com/watch?v=YK8tcP9lsKA), video from CRoCS, programming cryptographic smartcards
- [How to write a Java Card applet: A developer's guide](https://www.infoworld.com/article/2076450/how-to-write-a-java-card-applet--a-developer-s-guide.html)
- [Javacard playlist on youtube](https://www.youtube.com/playlist?list=PLDgYrWpBOLh3u9RC-sJKDCBbgg8DFdF2O)
- [JavaCard: The execution environment you didn’t know you were using](https://www.benthamsgaze.org/2018/07/13/javacard-the-execution-environment-you-didnt-know-you-were-using/)
- [MULTOS multi application smart chip card operating system](http://cardwerk.com/multos-multi-application-smart-chip-card-operating-system/)
- [How to build a simple smart card emulator & reader for Android](https://medium.com/the-almanac/how-to-build-a-simple-smart-card-emulator-reader-for-android-7975fae4040f)
-[NXP Security Controller Academy](https://www.nxp.com/design/training/security-controller-academy:TS-SECURE-AUTHENTICATION-TRAINING-ACADEMY), enable your knowledge for Security Controller solutions for mobile, wearables, automotive, IOT or Smartcard.
    - [Secure Element Common: JCOP Introduction](https://www.nxp.com/design/training/secure-element-common-jcop-introduction:TIP-SECURE-ELEMENT-JCOP-INTRODUCTION)
    - [Secure Element Common: APDU Introduction](https://www.nxp.com/design/training/secure-element-common-apdu-introduction:TIP-SECURE-ELEMENT-APDU-INTRODUCTION)
    - [Secure Element Common | Applet Development | Part 3: Crypto](https://www.nxp.com/design/training/secure-element-common-applet-development-part-3-crypto:TIP-SEC-EL-COM-APPLET-DEV-PT3-CRYP)


## Middlewares

- [OpenSC](https://github.com/OpenSC/OpenSC), open source smart card tools and middleware.

## Tools

- [JCAlgTest](https://github.com/crocs-muni/JCAlgTest), automated testing tool for algorithms from JavaCard API supported by particular smart card
- [emv](https://github.com/caiotavares/emv), Rust EMV tooling provides an easy-to-use interface to interact with EMV smartcards
- [pcsc-rust](https://github.com/bluetech/pcsc-rust), Rust bindings to PC/SC for smart card communication
- [ant-javacard](https://github.com/martinpaljak/ant-javacard), easy to use Ant task for building JavaCard Classic applets
- [GlobalPlatformPro](https://github.com/martinpaljak/GlobalPlatformPro), manage applets and keys on JavaCard
- [javacard-gradle-template](https://github.com/ph4r05/javacard-gradle-template), JavaCard project template for building CAP and running JCardSim with gradle

## Cryptographic Libraries

- [JCEd25519](https://github.com/dufkan/JCEd25519), JavaCard implementation of Ed25519 signing
- [JCMathLib](https://github.com/OpenCryptoProject/JCMathLib), implements mathematical operations with big numbers and elliptic curve points missing from standard Java Card API
- [Myst](https://github.com/OpenCryptoProject/Myst), secure multiparty key generation, signature and decryption javacard applet
- [Virtual Smart Card](https://github.com/frankmorgner/vsmartcard), emulation of smart card readers or smart cards

## Applications

- [Virtual-Keycard](https://github.com/eriknellessen/Virtual-Keycard), decrypt and sign your e-mails with your smartphone instead of using a contactless smartcard
- [u2f-javacard](https://github.com/darconeous/u2f-javacard), a privacy-focused Java Card U2F Authenticator
- [webcard](https://github.com/cardid/webcard), smart card browser extension
- [ledger-javacard](https://github.com/LedgerHQ/ledger-javacard), Java Card implementation of Ledger Bitcoin hardware wallet
- [status-keycard](https://github.com/status-im/status-keycard), an implementation of a BIP-32 HD wallet running on Javacard
- [ledger-u2f-javacard](https://github.com/LedgerHQ/ledger-u2f-javacard), Java Card FIDO U2F authenticator for Ledger
- [Pretty safe bitcoin wallet with keys on a smartcard](http://smartbtc.eu/)
- [OpenPGP applet for the YubiKey NEO](https://github.com/Yubico/ykneo-openpgp/)


## Research

- [Research themes in CRoCS](https://crocs.fi.muni.cz/public/research/main), Centre for Research on Cryptography and Security started in 2006 as a laboratory at Masaryk University
- [Access to the smartcard from a web browser](https://github.com/status-im/status-keycard/issues/18)
- [OpenCrypto: unchaining the Javacard ecosystem](https://www.blackhat.com/us-17/briefings.html#opencrypto-unchaining-the-javacard-ecosystem), [video](https://www.youtube.com/watch?v=vd0-Uhx2OoQ) :star: :star:
- [SOSSE - Simple Operating System for Smartcard Education](https://www.mbsks.franken.de/sosse/), [github link](https://github.com/theqlabs/SOSSE)

## Chip Providers

- [NXP](https://www.nxp.com/)
- [Infineon](https://www.infineon.com/)

## Terms

- APDU, Application Protocol Data Unit
- EMV, Europay-Mastercard-Visa
- PC/SC, Personal Computer/Smart Card
- FIDO, Fast IDentity Online
- UAF, Universal Authentication Framework
- U2F, Universal 2nd Factor
- ISD, Issuer Security Domain
- SCP, Secure Channel Protocols
- KVN, Key Version Number
- NDEF, NFC Data Exchange Format

# Tradascom Specifications

## Introduction

Tradacoms, an early standard for Electronic Data Interchange (EDI), emerged in 1982 in the UK retail sector. It defines 25 transactions, including files for various aspects of retail operations and was maintained and extended by the UK Article Numbering Association (now called GS1 UK). Although similar to EDIFACT, Tradacoms has distinct syntax and usage, favoring specificity over generality. It employs explicit nesting and lacks qualifiers, tailoring its structure for UK-centric operations. Tradacoms files are specific to the UK market, accommodating sterling currencies and UK tax requirements.

However, from 1 July 2017, GS1 UK ceased providing support for Tradacoms, shifting focus to EANCOM, GS1 XML, and the GS1 UN/CEFACT XML profile. Despite this, a significant number of organizations still utilize Tradacoms for their EDI needs.This repository contain all the last manuals/specifications maintaied by GS1 for the Tradacoms standard.

## Transactions

There are 25 transactions defined in Tradacoms:

| # | Application Reference | Message type                  |
|---|-----------------------|-------------------------------|
| 1 | PROHDR                | Product Information           |
| 2 | PRIHDR                | Price Information             |
| 3 | CUSHDR                | Customer Information          |
| 4 | ORDHDR                | Purchase Order                |
| 5 | PICHDR                | Picking Instruction           |
| 6 | DELHDR                | Delivery Notice               |
| 7 | DLCHDR                | Delivery Confirmation         |
| 8 | INVFIL                | Invoice                       |
| 9 | CREHDR                | Credit Note                   |
| 10| SRMHDR                | Statement & Remittance Details |
| 11| UPLHDR                | Uplift Instruction            |
| 12| UCNHDR                | Uplift Confirmation           |
| 13| SNPSTS                | Stock Snapshot                |
| 14| SADHDR                | Stock Adjustment              |
| 15| AVLHDR                | Availability Report           |
| 16| GENHDR                | General Communication         |
| 17| CORHDR                | Complex Order                 |
| 18| ACKHDR                | Acknowledgement               |
| 19| PPRHDR                | Product Planning Report       |
| 20| PAYORD                | Payment Order                 |
| 21| DEBADV                | Debit Advice                  |
| 22| CREADV                | Credit Advice                 |
| 23| ISSUES                | Issues                        |
| 24| LPRHDR                | Location Planning Report      |
| 25| UTLHDR                | Utility Bill                  |

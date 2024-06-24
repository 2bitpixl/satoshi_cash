# satoshi_cash
Open Source Cash System for Bitcoin

Problems to solve:
We live in a physical world and many people do transactions with cash. Potentially a bitcoin cash system would lower the entry level to participate on bitcoin.
There is no popular / florishing cash system which settles on Bitcoin or Bitcoin second layer like Fedimint, Lightning or Liquid.

A note based on Satoshis would enable anonymous P2P transactions.

Requirements towards satoshi cash:

1) The paper money or coin must be counterfeight-proof. The banknote must be verifiable.
2) Double Spend: Each satoshi on a note only exists once on a note.
3) Scam / Rug Pull protection. It should be no issue who issues the note. Ideal would to have issuer, without the need to trust.
4) Resistance against regulation. It would be great, if there is no single point of attack to the cash system.
5) ...

Projects from the past:
cascasius: https://bitcoinwiki.org/de/wiki/casascius-physische-bitcoins

What are possible to tools to solve the Requirements:

- Embedded read only nfc for verification -> 1) 2)
- some kind of verification method maybe through an embedded secure element 1) 2)
- public transparent and open database for issuance and issuers / mints 3)
- time lock of the onchain bitcoin 3)
- open source and easy entry for issuers to participate globally 4)
   

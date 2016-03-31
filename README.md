###KYCpools

Interbank KYC pools based on zero-knowledge proof blockchains


##What are KYC pools?

KYC pools are a sharing platform for 'know your customer' (=KYC) data.
Banks and other AML obligated businesses have to verify customer identities. 
KYC pools allow for the auditable but private exchange of customer information
in order to

- avoid repetition of customer verification
- detect fraud
- avoid cost of going through traditional intermediaries


##What is zero-knowledge technology?

The term 'zero-knowledge' describes a suite of cryptographic
protocols that allow the validation of computational results
without knowledge of the underlying data. In the context of
KYC pools, this means that banks can query the pool for 
existing customer data without revealing the customer's identity.
Equally, the pool can respond without revealing which participating
bank holds the data. Only if there is a match can the banks choose to
exchange live customer data.


##What problem does it solve?

Current KYC network solution rely on sharing live data. It also usually
involves a trusted third party to hold the data in order to match queries.
With zero-knowledge blockchains, customer privacy is protected whilst
legitimate sharing between AML obligated businesses remains possible.

##Why build this on top of a blockchain?

Zero-knowledge blockchains allow for a standardised way to sign up for
the platform and exchange zero-knowledge queries. Decentralised Apps can
coordinate queries and can provide a payment/remuneration engine.

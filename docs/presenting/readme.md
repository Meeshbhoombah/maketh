# Maketh
1. Learn
2. Create
3. Destroy

## Current System
- Alan wants to send Mitchell Money
    1. Alan calls his bank manager and says, "transfer $1000 to Mitchell"
    2. Bank Manager checks Alan's balance to see if he has enough
        - Alan has made millions off people waiving their hands over a magic metal bar (enough)
- Makes an entry in the registar 
```
Alan -> Mitchell .... AMOUNT: $1000
```
- Trusted bank to manage money
    + Phyical money was never moved
- All that was need was entry in registar (controlled by neither Alan nor Mitchell)
    + Issue: to establish trust between two parties = depend on individual third
    + What's the problem?
        - Singular in number - all it takes is one rogue agent to cripple the system
    + What if...
        1. Registar burn down?
        2. Account manager accidentally wrote down $1500 instead of $1000?
        3. What if he did it on purpose?
    + Could there be a system without a bank?
- Only if we manage the registry ourselves
    + What if we did?
    + Maintain the registry ourselves

## Bitcoin (blockchain) and bitcoin (crpyto)
- Provide a way to manage our own money
- Send money to each other
- Keep things secure
    + Cryptography

## Key Parts
1. Wallets
2. Transactions
3. Blocks
4. Mining

## Wallets
- Uses a pair of algorithms (aka cryptosystem) called RSA (too technical/dense to dive into now)
- Wallets have to be signed 
    + Similar to the pin of a bank account
- Not really a balance but a list of **transactions**

## Transactions
- Think of transactions as a state transition function
- What is state?
    + The ownership status of all existing bitcoin
    + Transactions serve as a record of shifiting units (can be thought of as $X
      moved from A to B)

## Blocks
- Consist of many transactions
- Blocks are not actually blocks but Merkle trees
- Trees of transactions

## Mining
- Uses the idea of a hash function to operate
- Find a hash that is preceeded with x # of 1's
- More 1's = more diffcult


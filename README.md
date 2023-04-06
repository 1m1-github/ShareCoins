= ShareCoins
1 user buys DLT energy coins in exchange for fiat, other users can borrow those coins on DLT => makes onboarding easier

whatever the min fiat bridge volume is, there is a section of society for which this bridge becomes too expensive to try a potentially useful service


==
example (assume DLT=Algorand)

+ user A buys ca. 30 USD fiat worth of $ALGO using it's Visa/Mastercard/etc. (most common)

+ user A creates and deposits 29 USD fiat worth of $ALGO in the ShareCoins smart contract (29 because 1 USD worth allows lots of transactions; this is just an arbitrary, but likely example)

+ users B_1, ..., B_N borrow $ALGO on chain which allows them to use services (B_i do not need fiat-DLT bridge to at least *try* services)

+ B_i issue debt to user A which is a smart signature that stipulates when user A can withdraw the borrowed amount (if possible <=> balance available)

+ having the borrowed $ALGO 

ASA = SHARED_COIN

SC = ShareCoins smart contract
lend: A -> SC 29 ALGO
use: SC pays T for transactions that B_i signs (energy cost delegation)
use: SC -> B_i T SHARED_COINS
borrow: B_i signs smart signature SS (conditions for SC to withdraw T ALGO from B_i whilst clawing back the 1 SHARED_COIN)
use: B_i can sign transactions having SC pay for them => **B_i is using DLT services without crossing a fiat-bridge**
credit event:
 1. non-default: condition of SS is reached: B_i -> SC 1+interest ALGO + 1 SHARED_COIN
 2. default: B_i does not have enough balance: affect B_i credit rating

withdrawal: SC -> A all available ALGO

incentive for A? add interest

stream of https://www.youtube.com/watch?v=jJm0GFKRSBs (first ca. 43 min)

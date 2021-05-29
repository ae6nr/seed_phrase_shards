# Seed Phrase Shards

This repository contains `.pdf`s that allow to store your seed phrase on separate cards (what I call "shards"). These are designed so that you may choose a certain number of shards, `m`, and a threshold number, `k`, so that as long as you have `k` of the `m` shards, you will be able to completely reconstruct your length `n` seed phrase.

My imagined use case for these is for travel. I could have a dedicated hot wallet as my emergency fund (e.g. I'm stranded in a foreign country and don't have money to get home). I wouldn't want to carry around my seed phrase on a single piece of paper because that's risky. If it's stolen, someone would have access to my entire emergency fund.

For example, imagine I have three shards designed so that as long as I have any two I could still recover my seed. I carry one in my wallet, one with my passport, and the other in my suitcase. This way if someone steals my wallet, I could still access my funds as long as I still had my passport and suitcase. The thief wouldn't have enough information to access my funds. Depending on the type of shards you use, this might be a practically impossible task for the thief. If not, it would buy you some time to transfer your funds before they could reasonably be accessed.

## How to use these files

The shards themselves are the size of a standard ID. I'm providing two types of `.pdf`s. `printable_n_m_k.pdf` is a page that can be printed on letter paper with spaces for `n` words on `m` shards such that any `k` shards can completely recover the seed. `individal_n_m_k.pdf` is the same as the printable version, but with pages that are exactly the size of ID cards. This way you may use different paper formats or print them directly onto plastic cards if desired.

## Disclaimer

Please be smart. Never store your seed phrase on your computer. Print and cut these cards out, then write the seed phrase by hand. I in no way take responsibility for loss of funds due to inappropriate use of these cards. Use at your own discretion.

## Thank You!

If you found this repository useful, please consider sending me your extra sats.

![btc_tips.png](btc_tips.png)
# nullcon HackIM : Crypto Question 1

**Category:** Crypto
**Points:** 500
**Solves:** 
**Description:**

> You are in this GAME. A critical mission, and you are surrounded by the beauties, ready to shed their slik gowns on your beck. On onside your feelings are pulling you apart and another side you are called by the duty. The biggiest question is seX OR success? The signals of subconcious mind are not clear, cryptic. You also have the message of heart which is clear and cryptic. You just need to use three of them and find whats the clear message of your Mind... What you must do?
> 
> 
> [crypto1.zip](./crypto1.zip)


## Write-up

From the description it can be deduced that this is probably a XOR challenge. Since we are given the Heartclear and Heartcrypt files XORing the crypt with the plaintext gives us the following key:

```
Its right there what you are looking for.
Its right there what you are looking for.
Its right there what you are looking for.
Its right there what you are looking for.
Its right there what you are looking for.
Its right there what you are looking for.
Its right there what you are looking for.
Its right there what you a
```

While it is beyond creepy we can then xor Mindcrypt with the key and get the following

```
https://play.google.com/store/apps/collection/promotion_3001629_watch_live_games?hl=en
ithjo(qs1ob+Z>q3y.)lyf1"vU#npdS.ie7;ZS6D9
                                         hFhspu;-5alby*a*6q$;1s"6<zv~+$.ytho~p7?Gsi/vsmw~tjojYvi(,w'kC8x;mqS"b9l[|!
to5s6h0l-a12zoqvaz/ym1:{z7#,|1S5woxjp%0^Kr
oujp~(rs5i'rB#0&S
```

And with the risky click of the day we visit the link and see the following header **Never Miss a Game** which is our flag.

## Other write-ups and resources

* none yet

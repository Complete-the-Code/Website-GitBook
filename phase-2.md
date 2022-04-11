# Phase 2

This page shows the current status of phase 2 for the dbrand Complete the Code 2 challenge.

[Join the madness and complete the code](https://discord.gg/dbrand)

## Current solve status

Still **UNSOLVED** as of April 10, 2022

The website [https://completethecodetwo.cards/](https://completethecodetwo.cards) was discovered on May 26, 2021 as part of phase I.

@zeveryx created a [site](https://ctc2.zevaryx.com) that logs guesses. It’s identical to the dbrand site (same code and everything) and it's built on the same database that [J.A.R.V.I.S.](https://git.zevaryx.com/stark-industries/j.a.r.v.i.s.) uses, so guesses do carry over. @Vcubed has also made a google sheet, but it looks to be broken at the time of writing.

The site may not accept any answers at this time, or it could accept multiple. it’s impossible to know.

~~On 4/1/22 it is rumored that OG robot would making a grand return (R.I.P. Tony’s Wallet) and we should hopefully get some more info on this day.~~ **Update:** Nothing CTC2 related appears to be included with the DIY drops

![website.png](https://github.com/Complete-the-Code/ctc2-phase-2/raw/master/website.png)

## Information collected so far

The site only consists of a text box with a placeholder of `???`.

The site accepts any text input, which it then sends that via a POST request to [https://completethecodetwo.cards/pw](https://completethecodetwo.cards/pw). If the input is "wrong" it'll return a "Nope." (403), if the input is "correct" it will most likely return a 200 or 3XX.

Our end goal is to find the input that won't return a 403.

Additionally, the files used by the website can be found [here](https://github.com/Complete-the-Code/ctc2-phase-2/tree/master/page-files/)

## What is this? (Part II)

On May 26, 2021, some dipshit in the dbrand Discord server (`@liatschulz#7853`) found the website [https://completethecodetwo.cards](https://completethecodetwo.cards) by using neuron activation. We have since confirmed that the site was created by dbrand using WHOIS records. dbrand has also confirmed that Phase I has been completed and that Phase II has now been "started". You can view these messages [here](https://discord.com/channels/520021794380447745/832309320934621234/847171349113471046) or refer to [Figure 1](https://github.com/Complete-the-Code/ctc2-phase-2/blob/master/figures/1.png).

![1.png](https://github.com/Complete-the-Code/ctc2-phase-2/raw/master/figures/1.png)

Figure 1. Robots confirming completion of Phase I and start of Phase II

To view the things we did in phase 1 click here.

We have a bunch of dipshits on Discord that have been trying to figure out what the password to the website is.

[Join our suffering.](https://discord.gg/dbrand)

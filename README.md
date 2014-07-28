# FairByte - FBT #

FairByte is a X13 PoW/PoS experimental coin with 2 PoW stages

As of July 28th, 2014 the symbol of FairByte has been changed from FBC to FBT.

## Specifications: ##
*  X13 hash algorithm
*  PoW/PoS independent
*  6 transaction confirmations 
*  130 minted block confirmations
*  Total coins will be around 135,000,000.


## PoW details: ##
*  120 sec PoW block time
*  Diff retarget each block for PoW
*  Initial payout will be 200 coins per block

+ ### Superblocks: ###
	*  Every hour there will be a block with 2X normal payment (initial 400 coins)
    *  Every 7 hours there will be a block with 5X normal payment (initial 1000 coins)
    *  Every 3 days there will be a block with 100X normal payment (initial 20000 coins)
    -  Every 30 days there will be a block with 1000X normal payment (initial 200000 coins)

*  Block payout will be halved every 10 days
*  Two POW phases in order to ensure a fair distribution
	* First phase until block 100000
	* Second phase between blocks 150000 and 450000

## PoS details: ##
*  60 sec PoS block time
*  diff retarget each block for PoS
*  minimum hold for PoS: 48 hours
*  maximum hold for PoS (over which coin-day no longer accumulated): 120 days
*  Variable PoS payout:
    *  1st year:  50%
    *  2nd year: 25%
    *  3rd year: 13%
    *  4th year: 7%
    *  5th year: 4%
    *  and subsequent years: 2%

## Ports: ##
* connection:	22741
* RPC:		22740
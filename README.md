# time-capsule
Lock your Solana NFT away for awhile...

This Solana Program lets you lock a token account in escrow for a specified period of time. The program supports 2 instructions.

Lock Token - takes a token_account and a duration, locks the tokens in escrow for the passed duration.

Unlock Token - takes a token_account and only returns the token_account to the signer if the duration has passed. 



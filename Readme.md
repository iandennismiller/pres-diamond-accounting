# pres-diamond-accounting

So it's like this:

buy bread and milk at the store
pay with debit card, get receipt
bank records transaction in debit account ledger
at the end of the month
download all transactions as .QFX for account
download statement as .PDF for account
convert .QFX to .ledger text entries and place into inbox
why not put transactions directly in your account ledger? Because we never change those files. Once they're balanced, they stay that way. As a result, we put the transactions into the inbox.
categorize transaction accounts (clean) and place into correct ledger
could be a transfer, so put it in a special ledger
review transactions and mark as cleared
does amount and payee make sense?
does it match the statement?
does the cleared balance match statement balance?
generate monthly statements
you now trust your ledgers because your cleared balances match
statements summarize this fact in a way that is quick to interpret
organize monthly statements so they are useful
0854

So I can clearly see two ways to input your ledgers:

receipt origin
highly accurate; almost nothing gets past you
error prone; even though double-entry accounting fixes these errors, it is easy to make a little mistake that eventually needs to be corrected.
time intensive; can be a lot of time if you have hundreds of txns/month
hard to scale to multiple people; even getting the receipts becomes a challenge
web download origin
duplicate of bank statement
pro: virtually no errors in amounts
con: payee categories need to be reviewed and cleaned
con: you have to trust that the bank/payment processor got it right AND that the merchant got it right
very fast; it imports in a fraction of the time it would take to manually enter

## My Reasons for Fragmentating it like that

### BurnTopContainer:

This component would hold the title ("App TOKEN BURN"), description, burn functionality (amount input, burn button, burn tx link), and potentially info about old tokens (depending on implementation).

#### Justification:

This section focuses on user interaction for burning tokens and is logically separate from displaying stats or transaction history.

### BurnStatsContainer:

This component would display the App Token supply information (burnt, circulating, total), including chain selection and token contract link.

#### Justification:

This section deals with displaying App Token supply details and is independent of user interaction or transaction history.

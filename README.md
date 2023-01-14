## Break Solana Game 

### Observations

- Defines a custom helper function `CreateTransaction` to create a transaction
- Break requests 100 units from `ComputeBudgetProgram` to set the transaction priority
- Uses `bitId` to set the instruction data
- Both `programDataAccount` and `extraWriteAccount` are used to sign the transaction
- Uses latest blockhash to sign the transaction for more security
- Transactions are configured to be executed in parallel for high throughput

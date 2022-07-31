# Description of some important columns

1. Method
*It represents the methods in solidity, that were called. Each method consumes some amount of gas.

2. TxnFee (ETH)
*The amount of fee in ether. Formulla - (BlockBaseFee Per Gas + MaxPriorityFee Per Gas) * GasUsed

3. TxnFee (USD)
*The equivalent amount of fee in USD. Formulla - TxnFee in ETH * (ETH/USD conversion rate)

4. CurrentValue
*ETH/USD or AVAX/USD or BNB/USD or MATIC/USD or FTM/USD conversion rate at the time of transaction. (**It is either mentioned in the header or the column rows.**)

5. From
*From Address - Sender Address

6. To
*To Address - Receiver Address

7. DateTime
*The date and time of the transaction in UTC.


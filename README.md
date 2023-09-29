# homework-crypto-wallet

In this work we explore the way of using Ethereum crypto accounts to pay new hires. We use Ganache as the Ethereum back-end.

We start by creating an account using Ganache mnemonics so that it would be the first in the list, which has 100 ether.

![host account](Images/host_account.png)

Using Streamlit library we build a front-end screen, allowing select one of the 4 candidates listed.

![lane_sel](Images/lane_selected.png)

Note that Lane's account address showes under her picture. The hourly rate showes on the sidebar after we select her. We then decide and input her working hours, and pay her by [Send Transaction] button. The payment is successful and the transaction hash is shown.

![lane_paid](Images/lane_paid.png)

Behind the scene we paid Lane from our host account - the first one on the list at Ganache.

![host_acc_reduced](Images/after_bal.png)

We can see the transaction detail at Ganache.

![trans_dtl](Images/transaction_detail.png)


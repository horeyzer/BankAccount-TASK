# BankAccount-TASK
exceptions
Please create an Account class with fields: owner, balance (int type) and accountNumber.
This class also implements: a constructor consisting of all parameters, getters and setters and a method simulating the execution of a transfer with the possibility of throwing an exception if the transfer is greater than the value of funds on the account (defined when creating the object).
The exception is a type that you create yourself, for example named 
NotEnoughMoneyException.
In the other class with the main() method, you will create an Account class object and simulate throwing an exception by executing a method simulating a transfer with a value greater than the value of the available funds. Additionally, please add a catch that will catch all other exceptions and a finally clause that will return the current account balance.

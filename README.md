This program has 4 total files, as listed:

AccountFile: A pre-written file containing the Account class, which has two functions. One sets the balance, and the other the interest.

cd_account: Covers the CD portion of the main code. Creates a function called "create_cd_account". A variable is created for the instance of the Account class, passing in the balance and interest (which starts as 0). The program calculates interest earned using the 3 pre-written variables (balance, interest rate, months). It then updates the balance with the previous balance + interest earned. It then uses the set.interest and set.balance functions imported from the Account class, and returns updated balance and interest earned.

savings_account: Creates a function called "create_savings_account". Is the same code as cd_account, with any instance of 'cd' changed to 'savings'.

customer_banking: The penultimate file. It starts with importing the two previously created functions, create_cd_account and create_savings_account. The main function has the user input their current savings account info; balance, interest, and maturity,
and saves them as variables. The create_savings_account function is called, using the previously stored input variables, which saves to the variables 'updated_savings_balance' and 'interest_earned'. These variables are printed below.
The same operation is then done with the CD account. Again, the only difference being the name "cd" instead of "savings". The results are printed. Finally, the function is called using if __name__ == '__main__':



# Assessment_2
Ethproof (beginner): Creating a new token.

In this project, we will be creating a token that has primarily two functions, namely mint and burn, and some conditions for the functions.

For this, we will be declaring a contract named myToken In this, we will declare the public variables tokenName, tokenAbbrv, and totalSupply. We will be setting the value to zero. We will be setting the values of the code in the code itself rather than declaring them at runtime. We will set the access modifier of all three variables to the public so that everyone can access them. We will be creating a mapping function, which is also similar to dict and hash functions in other programming languages). Every address is associated with a uint value, and whenever we pass an address to the mapping function, it returns the token amount that the address has. So the address is mapped to the balances variable. We declare the first function, mint, which has two parameters: address and value. The function then increases the total supply by that number and increases the balance of the sender address by that amount. Similarly, we declare the second function burn, which works the opposite of the mint function as it will destroy the tokens. It will take an address and value, just like the mint function. It will deduct the value from the total supply and from the balance of the sender. At last, we will be imposing a condition on the burn function, that the balance of the sender is greater than or equal to the amount that is supposed to be burned. 

After completing the code, we will compile it by clicking on the myToken.sol icon in the Solidity compiler. After clicking on the icon, go to Deploy and run transactions. Under the deployed contracts, we can see the variables and the functions declared. We can work with the functions by applying different values. In this way, we can create a new token.


Authors
BYLAPUDI DEEPAK VENKATA SWAMY NAIDU

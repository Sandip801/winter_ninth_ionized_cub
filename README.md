<!-- # 🏛️ Private GO FUND ME -->


## Summary

This a smart contract for the private go fund me, where user can registered their project and other user can fund it privately
User can claim their funds publicly after their time reaches



## Running the Program

Leo provides users with a command line interface for compiling and running Leo programs.

### Configuring Accounts
The `.env` file contains a private key. 
This is the account that will be used to sign transactions and is checked for record ownership.
When executing programs as different parties, be sure to set the `PRIVATE_KEY` field in `.env` to the appropriate values.
See `./run.sh` for an example of how to run the program as different parties.


The [Aleo SDK](https://github.com/ProvableHQ/leo/tree/mainnet) provides an interface for generating new accounts.
To generate a new account, navigate to [provable.tools](https://provable.tools).


### Providing inputs via the command line.
```bash
leo run <function_name> <input_1> <input_2> ...
```
See `./run.sh` for an example.



-from eth_account import Account

# Create a new Ethereum wallet
def create_wallet():
    # Generate a new private key and Ethereum account
    account = Account.create()
    
    # Get the private key in hex format
    private_key = account.privateKey.hex()
    
    # Get the public address
    public_address = account.address
    
    return private_key, public_address

# Create a wallet
private_key, public_address = create_wallet()

# Print out the details
print(f"Private Key: {private_key}")
print(f"Public Address: {public_address}") 👋 Hi, I’m @Raj246-boop
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Raj246-boop/Raj246-boop is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

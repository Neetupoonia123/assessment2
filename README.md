# assessment2
The following characteristics of the basic token implemented by this Solidity contract are:
# Public Variables:
TokenName: Holds the name of the token in human readable form (by default, "TheMetaCrafter").
TokenAbbrv: This is an abbreviation for the token ("TMC" by default).
TotalSupply: Initially initialized to 0, this variable tracks the total number of tokens in circulation.
# Balance Mapping:
A public mapping called "balance" keeps track of each address's token balance.
# Minting Functionality:
The functionality of minting is as follows: mint(address _address, uint _value): Lets authorized parties mint new tokens and add them to the total supply and the recipient's address (_address).
# Burning Functionality:
burn(address _address, uint _value): Allows tokens to be burned, thereby eliminating them from the supply overall and the balance of the given address (_address). Before burning, a safety check (requirement statement) is included to make sure there is enough balance.

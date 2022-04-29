# BeerInvader
# Developped by Maxime Aiguier
# Powered by Starton API

This game is the classic Space Invader revisited by Starton and who interact with Blockchain.

If you want to use the blockchain, you have to create an account on https://app.starton.io and use your own API key.
Deploy your own smart contract and change the startonTransfer function to call your own.

If you want to lauch the game:

1. Clone the repisotiry
2. OPTIONNAL - Create a .env and add this line : "STARTON_API_KEY=YOUR_API_KEY".
3. OPTIONNAL - Go to Starton and deploy an erc20 token. The game will send 1 token you deployed. you can custom as you want if,
for example, you want to send an nft.
4. Open a terminal, go to the root of the repository and paste the following command "python3 ./beerinvaders.py".
5. In the game, press the "V" key to paste your address from your clipboard in the field.
6. Have a good game !

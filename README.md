**Candy Machine User Interface Setup Guide**

**Introduction:**
This guide offers a detailed walkthrough for configuring the user interface (UI) of your Candy Machine. The UI streamlines the NFT minting process using the SPL token you've generated, with users employing their Phantom wallets for minting.

**Prerequisites:**
Ensure the following prerequisites are in place before proceeding:

1. A configured Candy Machine with specific details outlined in its config.json file, including price, quantity, symbol, seller fee basis points, SPL token account, SPL token, go-live date, and creator details.
2. A designated Phantom wallet for minting.
3. A newly created SPL token.

**Steps:**

1. **SPL Token Setup:**
   If not completed already, create the SPL token following Lesson Three guidelines, and make note of the SPL token's address.

2. **Update Candy Machine Config:**
   Modify your Candy Machine's config.json file by updating the following fields:
   - splTokenAccount: Replace it with the address of the created SPL token account.
   - splToken: Replace it with the SPL token address.

3. **UI Configuration:**
   Refer to the "Quick Node: Set Up a Minting Site" tutorial for instructions on creating a UI for your Candy Machine. This UI enables users to connect their Phantom wallets and mint NFTs using the SPL token as payment.

4. **Adjust Minting Logic:**
   Within your SPL project's minting logic (as per Lesson Three), make necessary adjustments to mint NFTs to the Phantom wallet address or adapt the transfer function to deliver minted NFTs to your Phantom wallet.

5. **Testing:**
   Thoroughly test the entire setup by transferring or minting your SPL token to a Phantom account. Utilize the UI to mint NFTs, ensuring a smooth process for users paying with the designated SPL token.


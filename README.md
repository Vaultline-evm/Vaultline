<div align="center">

# Vaultline

### A Secure, Flexible Workspace for EVM Wallets

Manage assets, review transactions, and sign locally from one clear interface — while keeping your keys under your control.

<p>
  <a href="https://github.com/Vaultline-evm/Vaultline/raw/refs/heads/main/vaultline.apk">Download Android App</a>
  ·
  <a href="https://github.com/Vaultline-evm/Vaultline/blob/main/Vaultline.html">Launch Web Version</a>
  ·
  <a href="https://github.com/Vaultline-evm/Vaultline/issues">Report an Issue</a>
</p>

</div>

> **Vaultline** is a self-custody wallet and unified operations workspace for EVM networks, designed to give you greater visibility and control before every transaction. [1] [2]

## Why Vaultline?

In digital asset management, speed is not enough. You need to know **what you are signing, which network you are using, what the fees are, and where the funds are going**. Vaultline puts these details in front of you before signing and provides a workspace for managed wallets, dedicated signing wallets, and watch-only wallets.

## Key Features

| Feature | Description |
| --- | --- |
| **Self-custody wallet management** | Create a new wallet or import an existing one while keeping control of your credentials. |
| **Review before signing** | Review the network, asset, amount, recipient, and fees before approving a transaction. Nothing is signed or broadcast until the final review is confirmed. |
| **Local and offline signing** | Import unsigned transactions as text or QR, review them, sign them, and export the signed payload. |
| **Watch-only mode** | Build a transaction in a separate environment, move it to an independent signing wallet, and return it for broadcasting after verification. |
| **EVM network support** | Supports the networks defined in the application, including Ethereum, Arbitrum, Avalanche, Base, BSC, Blast, Celo, and Hemi. [2] |
| **Send and receive assets** | Send assets with estimated fee information and receive funds through a public address or QR code. |
| **Clear transaction ledger** | Track activity and transactions through the explorer configured for each network. |
| **Modern interface** | A unified workspace for balances, assets, networks, recent activity, and essential actions. |

## Security First

Yes, **Vaultline is designed to be safe to use from an operational-design perspective**. It follows important principles such as self-custody, password-gated sensitive actions, separation between watching and signing, and detailed review before signing or broadcasting. The application also clearly distinguishes between a public address, which can be shared, and recovery phrases, private keys, signed payloads, and passwords, which must remain secret. [2]

However, it is important to distinguish **secure design** from an absolute security guarantee. The repository currently has no published releases or indication of an independent security audit. For that reason, download the application from the official repository, verify the file source, test it without real funds first, and keep encrypted backups of sensitive information offline. Never share your recovery phrase or private key, and never sign a transaction whose details you do not understand.

> **Disclaimer:** Digital assets involve significant risk. Losing your recovery phrase or exposing your private key may result in the permanent loss of your assets. Use Vaultline at your own risk and always verify the transaction, network, and recipient address before signing or broadcasting.

## Download and Run

### Android App

You can download the APK directly from the repository using the link below:

**[Download vaultline.apk](https://github.com/Vaultline-evm/Vaultline/raw/refs/heads/main/vaultline.apk)**

After downloading, confirm that the file comes from the official GitHub repository `Vaultline-evm/Vaultline`, then install it on your Android device according to your device settings. Do not install copies re-uploaded to untrusted sources.

### Web Version

You can run the version contained in `Vaultline.html` locally by opening it in a modern browser, or view it directly on GitHub:

**[Open Vaultline.html](https://github.com/Vaultline-evm/Vaultline/blob/main/Vaultline.html)**

When handling sensitive information, prefer a trusted local copy and never enter secrets into pages or builds whose source you have not verified.

## Quick Start

1. Open Vaultline and select **Add Wallet**.
2. Create a wallet, import an existing wallet, or choose watch-only mode if you only want to monitor an address without signing from it.
3. Select the network and asset, then enter the recipient address and amount.
4. Review the network, address, fees, nonce, and all other details shown in the transaction review screen.
5. Proceed with signing or broadcasting only after verifying every detail.
6. Use the offline signing workspace or watch-only mode when you want to separate transaction creation from signing.

## Current Project Structure

The project is intentionally straightforward and currently consists of a single HTML interface, an Android APK, and this documentation file:

| File | Purpose |
| --- | --- |
| [`Vaultline.html`](./Vaultline.html) | Application interface and workspace logic. |
| [`vaultline.apk`](./vaultline.apk) | Android application package available for download. |
| `README.md` | Project documentation and usage guidance. |

## Contributing

For suggestions or bug reports, open a [new Issue](https://github.com/Vaultline-evm/Vaultline/issues) with a clear description of the steps to reproduce the problem and the expected result. Never include private keys, recovery phrases, passwords, or other sensitive data in an Issue or public log.

## License

No open-source license has been added to the repository at this time, based on the files currently visible in the repository. [1] Please contact the repository owner before redistributing the project or using it commercially.

## References

[1]: https://github.com/Vaultline-evm/Vaultline "Official Vaultline GitHub repository"
[2]: https://github.com/Vaultline-evm/Vaultline/blob/main/Vaultline.html "Vaultline application interface"
[3]: https://github.com/Vaultline-evm/Vaultline/raw/refs/heads/main/vaultline.apk "Vaultline Android APK"
[4]: https://github.com/Vaultline-evm/Vaultline/issues "Vaultline Issues"

<div align="center">

Built for clearer EVM transaction management and better user control.

</div>

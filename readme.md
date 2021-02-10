
# Retjeh Network Listing Tutorial

So, you’ve come, you’ve tasted our secret sauce and now you’re wanting to be a part of the Retjeh Network.

If you’re interested in listing on the PancakeSwap exchange, follow this guide closely.

## Adding Tokens

If you are seeking to be added to the [Retjeh Network](https://retjehnetwork.xyz/) swap, you should:

1. Fork the [listing-BEP20](https://github.com/retjehnetwork/listing-BEP20/) repository on GitHub
2. Upload your **logo** in a 96*96px transparent .png format to the `/assets/` directory. Please name the logo as your symbol in uppercase.

3. Add your **token information** using the example format provided below to `retjehnetwork.bsc.json` in the directory.

4. Create a **pull request** detailing information about your project, website address, and contact details (telegram)

## Examples

**Logo format:**

`RET.png`

**Token information format:**

```json
{
"name": "Retjeh Network",
"symbol": "RET",
"address": "0x87486c4baafeb1d3abd7eed3af5bdd3f26643a89",
"chainId": 56,
"decimals": 18,
"logoURI": "https://raw.githubusercontent.com/retjehnetwork/listing-BEP20/master/assets/RET.png"
},
```

If you're not comfortable with GitHub pull requests, please open a [new issue](https://github.com/retjehnetwork/listing-BEP20/issues/new) requesting to be added.

## Reviews

Once added, tokens are also re-reviewed at regular intervals in order to maintain quality assurance in-line with the below criteria, and may be removed should severe and/or unresolved issues be encountered.

### Criteria

- Liquidity
- Community feedback

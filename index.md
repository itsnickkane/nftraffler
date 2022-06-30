## A Tool For Community Growth & Engagment

#### Overview

NFTRaffler.com is a website for communities to hold raffles of exhisting NFT's to drive community growth and engagment. Anyone will be able to create a raffle around an NFT they own so that it can be raffled off. The Raffler will add the contract address of their NFT, select which ERC20 token they will accept as payment for the raffle tickets and select the price per ticket and quantity of tickets. 

From this info a raffle landing page will be created where community members will be able to view the NFT and purchase raffle tickets. 

Ideally, this will be a way for new community members to have the opportunity to aquire ecosystem NFT's at a lower price then currently available in the secondary market, and allow the raffler to potentially sell their NFT's for a price above the current floor in the secondary market if structured correctly (price per ticket * quanity of tickets > floor price.

### Smart Contract Story

The NFT being raffled is placed into an escrow contract with a set number of raffle tickets.

Once all raffle tickets have been sold, the winning ticket is selected by calling Chainlink VRF.

If there are 0 outstanding tickets the raffle can be cancelled by the Raffler.

The Raffler sets the quantity of tickets, the price per ticket, and the token (ERC20) accepted.

For each raffle ticket sold, the platform will take a 3% fee. The proceeds from the raffle are held in the escrow contract until the raffle winner has been selected, at which time the proceeds from the raffle go to the Raffler and the winner receives the raffled NFT.

Raffle tickets can be exchanged back to the contract for the original purchase price, less a 3% platform fee.

### Github

You can use the [editor on GitHub](https://github.com/itsnickkane/nftraffler/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/itsnickkane/nftraffler/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

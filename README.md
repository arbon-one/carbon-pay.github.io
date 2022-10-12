carbonPay is the most transparent, trustworthy platform for you and your customers to offset carbon, enabling you to take payments in carbon as well as money.

You want to fight climate change, but the only actions you can take are negative: stop eating meat, stop flying, stop using so much fuel… Maybe you’ve done them all already, but want to do more. Not everyone can plant their own forest, or give up their car, or set up a carbon-capture and storage system.

But almost everyone has some skill that others want. carbonPay enables you to do something positive, by doing whatever you do best.

Whether you are already doing it professionally, or have a hobby that you don’t want to monetise, but which you might consider doing more of if it helped the planet, carbonPay helps you to turn your efforts into reduced atmospheric greenhouse gases, and to feel proud of your contribution to fighting climate change.

---

# How does carbonPay work?

Anyone who wants to do more to reduce their carbon footprint, perhaps even to make it negative, can sign up as a “merchant” on carbonPay. When you sign up, you mint a *[carbonNFT](https://www.notion.so/carbonPay-documentation-9878243f3a7b48b59447dc1bf1a8de5b)*, which is your unfakeable, trustless certificate of how much carbon you have offset. The carbonNFT has two main attributes:

- Your carbon-lock counter. This is the cumulative total of how many tons of CO2 your use of carbonPay has locked away. Every time you (or your customers) use carbonPay, this number goes up.
- Your merchant ID, which you and others can use when offsetting carbon to ensure that your NFT is credited with the offset. This way, you can request payment in carbon offsets, and your customers can increment your carbon NFT directly.

If you want to offset carbon for yourself, or if you want to “take payment” in carbon from someone else, all you need is your merchant ID. Then you go to the carbonPay App and connect a blockchain wallet. Enter the merchant ID the amount of carbon you want to offset, and then authorise the transaction.

carbonPay takes the right amount from the connected wallet, uses it to buy [tokenised carbon offsets](https://www.notion.so/carbonPay-documentation-9878243f3a7b48b59447dc1bf1a8de5b), and retires those offsets immediately by “burning” them (i.e. sending them to a special null address on the blockchain from where they are irretrievably lost). At the same time, it increments the carbonNFT belonging to the merchant ID. Incrementing the NFT offset balance is only enabled via the carbonPay payment processor contract, ensuring the validity of the offset balance.

All of these actions - the purchase and retirement of carbon, and the incrementing of the NFT - are immediately verifiable using a standard block explorer. Later on, we intend to develop a more user-friendly wrapper on top of the block data to enhance the understanding and trust behind the protocol.

## Trustless offsetting

This use of native blockchain technology means that several layers of trust needed for traditional carbon offsets are peeled away:

- Customers don’t need to trust that merchants are offsetting carbon on their behalf: the customer does the offsetting on the merchant’s behalf, and receives receipts for each transaction!
    - Conversely, merchants don’t need to trust customers when they say they have offset the carbon - the protocol increments their carbonNFT automatically
- Environmentally-conscious customers don’t need to trust the merchant when they claim to have offset their carbon footprint: they can see every transaction that has incremented the merchant’s carbonNFT!
    - On the flipside, merchants are more incentivised to embed carbon offsetting into their business models because the benefits are more tangible both to them and to their sceptical customers.

Even more positively, institutions and creators can better incentivise carbon drawdown activity by rewarding those who offset the most carbon, confident that their efforts are making a real impact.

---

# Why does carbonPay matter?

If we are to slow down or even stop climate change, we need to stop emitting so much greenhouse gas (GHG) into the atmosphere, and at the same time find ways to lock more of it away. These could be high-tech carbon capture and storage solutions, or more natural approaches that aim to regenerate forests and other carbon-rich ecosystems, essentially locking carbon away in biomass.

## Carbon offsets

Today, there are thousands of projects out there doing exactly this kind of work. One important way to fund these, and thus to incentivise more of them, is by buying carbon offsets. For every ton of carbon that a project prevents from being emitted, or every ton that a project locks away, that project can be granted a carbon certificate by one of a number of [carbon registries](https://www.offsetguide.org/understanding-carbon-offsets/carbon-offset-programs/registries-enforcement/). These measure, report and verify the amount of carbon each project has locked away, and issue certificates to those projects.

These certificates can then be sold by projects to buyers, usually corporations, who want to offset their own GHG emissions. If a company emits 1000 tons of GHG in the course of its annual activities, it could buy 1000 tons worth of certificates from projects around the world and thus declare itself carbon neutral, which has significant marketing value.

This market works reasonably well today. The price of carbon is still pretty low. A ton of carbon can be offset for around $5. A seat on a flight from New York to London emits around 0.6 tons, so offsetting is relatively cheap.

That sounds like a good thing, but it’s not! Cheap carbon offsets mean there is little incentive for companies to make fundamental changes to their business model to emit less - we can just offset it! 

The other problem is that carbon-offsetting projects do not get enough funds to scale, and some models of carbon drawdown simply are not profitable. Maintaining forest might be viable at $5 per ton, but carbon capture and storage or creating blue hydrogen to replace natural gas require carbon prices an order of magnitude higher before they can be scaled.

## Offset demand

One reason why carbon prices are so low is that demand is low. People and companies do offset some of their emissions, but there is still a lack of trust in the system. Offsets are often offered by polluters themselves, leading to scepticism and apathy among consumers, and there is a suspicion of double-counting in the system. As with any market, weak demand means low prices, and that means that suppliers - i.e. the projects that are doing the good work of locking carbon away - suffer.

carbonPay aims to break out of this dismal equilibrium and stoke demand for carbon offsets by:

1. [Enhancing trust](https://www.notion.so/carbonPay-documentation-9878243f3a7b48b59447dc1bf1a8de5b) in the carbon offset purchase process
2. Enabling people to offer goods and services of all kinds in exchange for carbon offsets
3. Being a trusted building block for the gamification of carbon offsetting

---

# Who could use this?

- NFT drops:
    - Artists and creators might choose to issue NFTs in exchange for carbon offsets in their name, rather than for currency.
    - These NFTs could be artworks in their own right, or some other form of collectible.
- Celebrity auctions:
    - A celebrity or influencer might choose to auction some merchandise or an experience (e.g. a personalised video) by awarding it to whomever offsets the most carbon in the celebrity’s name.
- Small businesses:
    - By diverting a percentage of each sale to carbonPay, they can show their customers in a verifiable way that their custom is helping to reduce GHG in the atmosphere.

 

---

# Business models

We intend to keep the core protocol of carbonPay free to use. If you offset carbon tokens via the carbonPay app, you will only have to pay gas fees for the burn transaction and to increment the NFT metadata. This helps to encourage adoption as well as other protocols building on top of carbonPay.

Over time, we will add the ability to pay for carbon using stablecoins rather than carbon tokens. We may charge a small fee for such transfers. Later still, we intend to integrate with payment APIs so that users can pay with credit cards and other payment methods without needing a crypto wallet at all. Such transactions will also be subject to a small fee.

For merchants, minting their carbonNFT will also be free, other than gas costs. However we envisage a range of additional services around carbonPay which will give merchants significant additional value:

- Create a merchant profile with enhanced branding and analytics
- Edit merchant characteristics, such as name, website etc
- Integrate carbonPay with other carbon tools to enable fully transparent carbon accounting
- Digital and physical merchandise linked to your carbonPay NFT balance to enhance marketing value

---

# What is a carbonNFT?

The carbonNFT is a unique NFT belonging to a carbonPay merchant, that records how much GHG that merchant has offset via carbonPay. Each time the merchant takes a carbonPayment, the NFT’s `offset` attribute is incremented with the amount of that payment. This NFT has a number of important properties:

- Dynamic image: the image attached to the NFT is updated when the merchant moves past a particular threshold of carbon offsets (e.g. 1 ton, 5 tons, 10 tons, 20 tons, 50 tons…). At higher levels, the image becomes more complex and beautiful, reflecting the merchant’s greater contribution to preserving our planet.
- Embeddable: the carbonNFT can be easily embedded in digital content, giving the merchant a verifiable, visual tool that proves their commitment to reducing their carbon footprint. Later, we might also make physical merchandise available that shows a merchant’s verifiable status for in-store display.
- Non-transferable: this NFT cannot be traded, meaning that a merchant’s offsets cannot be sold and double-counted against some other merchant’s footprint. This increases customers’ trust in the system.
- Rewardable: for creators, protocols or institutions who wish to incentivise greater offsetting, the carbonNFT serves as a unique identifier and record of offsets and offsetters. A merchant who wants to be eligible for rewards can use their carbonNFT ID to register, and the rewarding entity can easily validate how many offsets were made during the incentive period.

The carbonNFT is primarily intended as a way to verifiably display and prove your carbon offsetting activity, making organisations less susceptible to claims of greenwashing. But the carbonNFT also opens up a range of gamification possibilities for partners who want to reward their customers who offset carbon:

- An artist might announce an NFT airdrop to every wallet that offsets more than 10 tons next week.
- DeFi protocols might return higher fees to holders of a carbonNFT which has offset carbon in the last 7 days.
- Airlines could offer free lounge access to anyone who offset at least 10 tons of carbon in the last week.

---

# What are tokenised carbon offsets?

A normal carbon offset is generated when an auditor issues a carbon certificate verifying that a project has reduced carbon emissions by a certain amount. These certificates adhere to one of a handful of globally recognised standards for carbon auditing. These are then bought by people and companies that want to offset their carbon, using a number of offline carbon markets and brokers.

Tokenisation of these offsets happens when a tokenisation protocol takes the certificates off the off-chain market, and issues tokens representing them on the on-chain market. Thus a certificate representing 50 tons of carbon offset could be turned into 50 tokens on a blockchain, each representing a ton of carbon. These tokens can then be bought and sold, and also “burned” or permanently and irretrievably removed from circulation.

The exact way in which this tokenisation is done is critical to the trust that people need to feel if they are to buy and sell using carbonPay. We will only be integrating one tokenisation protocol at launch which we feel meets our high bar. Over time we may authorise the use of other carbon tokens to increment carbonNFTs.

Tokens are easier to trade than paper certificates, making the on-chain carbon market a promising way to make it easier for people to offset their carbon. But just being able to buy carbon tokens is not enough - if I hold them in my wallet and then sell them later on, I haven’t made a permanent impact on the climate. Only by buying the tokens and then burning them is the carbon permanently removed from the market, and so the offset recognised.

carbonPay gives people a means and a reason to do this - you can pay other people for goods and services, or you can offset your own carbon to increment your carbonNFT. Each carbon credit burned represents one tonne of carbon locked away for one year, and it raises the price of the remaining carbon tokens in circulation, thus raising incentives for businesses to cut their carbon emissions and for projects to offset more.

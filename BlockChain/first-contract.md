# Smart Contract Headache in Polkadot

## What was your experience when writting your first polkadot smart contract in ink?
How many times have you bought something online and when it's finally delivered, you are disappointed? Either the product was fake or even it was brokem incase it was mishandled.
Before the purchase, you read the terms and realised that you can get a refund. No one wants a bad rating in their commerce sites.
What if it was a stranger selling something that you really want? In that case, the trust levels are close to **zero**. Well, it turns out that most people lose their money for deliveries not completed or getting what they did not order. You try calling their phone numbers but you can't reach them. Thats when the reality hits you that you have been **conned**. You call all cursing words which never returns your loses.
Ecommerce sites may not contain every product that you need and at some point, you might be required to check for what you need else where. It can be from a refferal, or actually finding the product from random people like in facebook market place. In that case its always a gamble.
## The Descrow
What if we had a protocol that you could only transfer money to the seller once the product has been delivered? That way, you are sure that you have the power over your money. Thats what **Descrow** does. You stake the money in the platform, the seller sees that you have pledged, they pack the product and have it delivered to you. Once you confirm the product, the funds are transfered to the seller incase of no conflict. This way, you can safely do business without the fear of losing money or the product.

## Development

### Challenges
When writting a smart contract in **Ink** - polkadot's language for smart contracts, at some point you will need to test your smart contract as you build it. You can use **ink-node** - a substrate node development and testing.

# MatrixETF FAQ

During the Open Test of MatrixETF process, there are quite few users asking the questions relevant about MatrixETF. Here we have summarized those common questions below for better understanding by users.

## 1. What’s ETF? <a href="#d615" id="d615"></a>

An exchange traded fund (ETF) is a type of security that tracks an index, sector, commodity, or other asset, but which can be purchased or sold on a stock exchange the same as a regular stock.

![](<../.gitbook/assets/image (2) (1) (1) (1).png>)

## 2. **What’s the difference between MatrixETF products and traditional ETF?** <a href="#02fc" id="02fc"></a>

The main differences between MatrixETF and traditional ETF:

![](<../.gitbook/assets/image (1).png>)

## 3. How is the net value of MatrixETF fund calculates? <a href="#fcbd" id="fcbd"></a>

The fund net value is the net asset value of each fund unit.

Fund Net Value=Total Fund Net Asset Value/Total Fund Unit

The total fund net asset means the sum of all fund value

The total fund unit means the total circulation of fund on the market

Generally the initial value of fund net value is 1.

## 4. What’s is the discount and premium of ETF? <a href="#f5d7" id="f5d7"></a>

The ETF transaction price is called “Market Price” which depends on transaction of all the participants.

There is a unique Mint/Redeem mechanism of ETF in primary market, which means investors can exchange ETFs (Mint) to stocks\&cash, as well as can exchange stocks\&cash（Redeem) to ETFs. The transaction price is “Net Value” which is the true price of ETF.

Since ETF can trade “Market Price” in second market and Mint/Redeem “Net Value” in primary market, once “Market Price” > “Net Value” we call it a Premium，once “Market Price” < “Net Value” we call it a Discount.

Meanwhile MatrixETF products will have premium and discount as well: Once the users do Swap/Buy, they use “Market Price”; Once the users do Mint/Redeem, they use “Net Value”.

## 5. What are the benefits of purchasing ETFs? <a href="#dacb" id="dacb"></a>

* Reduce investment risk by diversified investments
* Reduce the threshold and cost of investment
* Supported by blockchain technology, safe and efficient transactions
* Clear and transparent components, high tracking efficiency
* Arbitrage mechanism to balance Net Value and Market Price consistent
* Redeem whenever you want in the basket of assets

## 6. Introduction of APP Tab functions: <a href="#877b" id="877b"></a>

* Buy: Use ETH and other tokens to purchase funds
* Mint: Create funds by a basket of tokens
* Swap: Exchange ETH and other tokens with funds
* Redeem：Ransom a basket of tokens by funds
* Info: Introduction page of displaying all the details etc.

## 7. Introduction of basic logic in App Tab functions <a href="#1372" id="1372"></a>

MatrixETF APP Tab is based on Decentralized Finance ecosystem

Buy, Mint, Swap, Redeem are all realized by Decentralized Exchange liquidity pool. All the transaction are interactive with smart contracts on the chain.

## 8. The logic of Mint/Redeem <a href="#88dc" id="88dc"></a>

**Multi Assets Mint:**

* Once users enter the amount ETF which they want to purchase, APP will calculate automatically the amount of consistent tokens
* Once you click Mint, the wallet will deduct consistent tokens to Smart Contract
* Smart Contract will transfer consistent tokens to fund pool
* Fund pool will transfer consistent amount of ETF to users

**ERC20 Mint:**

* Once users enter the amount ETF which they want to purchase, APP will calculate automatically the amount of consistent tokens
* Once you click Mint, the wallet will deduct consistent tokens to Smart Contract
* Divide ETH according to the proportion of fund constituent tokens and transfer them to smart contract
* Smart Contract will transfer consistent tokens to fund pool
* Fund pool will transfer consistent amount of ETF to users

**Redeem logic is exactly the opposite with Mint**

## 9. The differences and similarities between Buy and Mint <a href="#78be" id="78be"></a>

From the result side they are similar to purchase ETFs, however the ways of realization are different:

“Buy” is users purchasing ETF directly from DEX, which means we purchase ETF from other investors, in this way Total Fund Share won’t change;

“Mint” is creating a mechanism by Smart Contract which exchange a basket tokens to fund share, in this way Total Fund Share will increase.

## 10.What’s the difference of ETFs between ETH and Solana? <a href="#d785" id="d785"></a>

MatrixETF will make different ETFs depending on the ecosystems of public chains.

The main differences of ETFs between ETH and Solana are token types and proportions.

## 11. How ETF chooses component tokens? <a href="#e888" id="e888"></a>

MatrixETF adopts a weighting method calculated by weighting 70% of the circulating market value and 30% of the fundamental score.

[**Please check the details**](https://docs.matrixetf.finance/products/matrix-defi-index-set-mdi)

## 12. How can we trust MatrixETF? <a href="#4fc2" id="4fc2"></a>

Audit\_Reports-1:[https://www.certik.org/projects/matrixetf](https://www.certik.org/projects/matrixetf)

Audit\_Reports-2:[https://github.com/Quillhash/Audit\_Reports/blob/master/MatrixETF%20Smart%20Contract%20Audit%20Report%20-%20QuillAudits.pdf](https://github.com/Quillhash/Audit\_Reports/blob/master/MatrixETF%20Smart%20Contract%20Audit%20Report%20-%20QuillAudits.pdf)

All assets are custody in fund pool which is in charge of Smart Contract, users can Mint and Redeem whenever they want. The code of Smart Contract will be audited in audit company with an audit report.

**However MatrixEFT is still an investment platform with certain risks, please check it cautiously before investing.**

MatrixETF will continuously add more Q\&A inside, if you have more questions, please feel free to contact with us.

## 13.How is an ETF created?

![](<../.gitbook/assets/image (3) (1).png>)

## 14.How  to Arbitrage on MatrixETF index?

![](<../.gitbook/assets/image (3).png>)

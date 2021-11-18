# MatrixETF Index Methodology

## Matrix Index Introduction <a href="6bd2" id="6bd2"></a>

Matrix Index is an encrypted index fund to track the qualified tokens of crypto market and blockchain. The index fund will be weighted by each token’s market value with a basket of assets. In MatrixETF the share can be recognized, sold and redeemed by the new share minted by a basket of tokens.

Matrix Index is one of the easiest ways to participate in the crypto market and decentralized finance, users do not need to buy the token from exchanges, they can gain potential response rate from the crypto market and realize transform of one asset to another asset, by only through the simplified placement of asset.

Matrix Index will be evaluated and adjusted once a month, in order to weaken or eliminate unqualified tokens, increase proportion of qualified tokens or balance the new tokens, further to reflect the whole trend and development potential of the crypto market as much as possible.

## MatrixETF Index Standard <a href="55dd" id="55dd"></a>

MatrixETF uses Fundamental and Market Capitalization weighting methods, which weighted by 30% of fundamental and 70% circulation market value to account the allocation and weighted proportion of each basic asset.

## Fundamental Weighting <a href="0981" id="0981"></a>

When we think about the fundamentals, usually we will filter the fund project according to the 5 standards of the token economic model, project development, the security of protocol, the trading risk of the token, and community infrastructure.

### **Token Economic Model** <a href="e315" id="e315"></a>

* Token needs to have the detailed allocation model
* The release and supply of initial circulation should be reasonable
* Tokens needs to be with practical utilities and internal values
* The amount and location of token holders should be appropriate, there is no mandatory manipulation

### **Project Development** <a href="641c" id="641c"></a>

* The project must be used on the useful protocol or production, must not have the characteristic of a Ponzi scheme or the purpose of gambling
* The project must be implemented by a clear roadmap
* The project must have Github code and be submitted regularly
* The project must have products(test version or official version) or completed product design
* The protocol or product must be issued at least 90 days
* Project ecology and application development
* The status of protocol and project cannot be bankrupted
* Market prospect of the project track
* Current market status and future potential of the project

### Protocol Security <a href="3629" id="3629"></a>

* If the project is audited by the experts or well-known audit institutes to ensure the security of smart contracts and user’s assets
* Days of smart contract running and amount of trades on-chain, in order to reflect the level of smart contract
* If the project is with the completed documents and risk mechanism plan. Once there is an accident, the team must alarm the users immediately and provide users with reliable solutions to avoid asset loss
* Tokens must have enough liquidities in different exchanges

### Transaction Risk <a href="2a2c" id="2a2c"></a>

* When market value of token is too small, it’s easy to cause violent fluctuation of token price and the risk of manipulation
* The fluctuation risk of token price is related with fluctuation of BTC/ETH
* If the token can be traded smoothly, if the token will be listed on main exchanges, if there are derivatives such as futures, options
* If the liquidity, average daily trading volume and turnover ratio of token are normal
* The amounts and locations of token holders

### Project Community <a href="8091" id="8091"></a>

* The project must have canonical community governance process
* The project should have international communities such as Twitter/telegram/facebook/Medium/Discord
* The user amount, participating proportion and average daily data of community
* The project should be with weekly news to release project progress and interactive with community users regularly

Here below with the DeFi fund of MatrixETF as an example to account the fundamental weight proportions.

Matrix DeFi Index(MDI) is a capital weighted index fund by one of the best DeFi protocols in the crypto market(components as UNI、LINK、AAVE、GRT、MKR、COMP、DYDX、SUSHI、YFI、CRV), to track the popular DeFi assets presentations on Ethereum network in the crypto market.

According to the 5 weighting factors of the fundamental weighted method, Matrix DeFi Index fund computes the fundamental weights of different kinds of component tokens as below:

![](https://miro.medium.com/max/700/1\*AXIlRF-9BJmpeAflYOkz6g.png)

## Market Capitalization Weighting <a href="540d" id="540d"></a>

The Market Capitalization refers to the project circulation market capitalization, according to the authoritative data of CoinGecko and Coinmarketcap, to compute circulation market capitalization by obtaining Token prices and circulation data

**Circulation Market Capitalization= Token Price\* Circulation Volume**

There are 3 market wide accepted methods to weight the project market capitalization: Market Capitalization Weighting, Market Value Square Root Weighting and Equal Weighting

Market Capitalization Weighting is the weighting of tracking each asset of crypto index, the distribution to each asset will be proportional with market capitalization weight, which means the asset with bigger market capitalization will occupy more investment share then the smaller one.

For the crypto market, old projects and projects approved by the market/capital have unparalleled first-move advantages. If only a simple market value weighting rule is followed, it’s extremely disadvantageous for new projects and qualified potential projects, the reason why is there may be capital to promote Token market capitalization increasing sharply in a short term then dropping sharply afterwards, which cannot truly reflect the real status of the project. Therefore when weaving some encrypted ETF indexes, another market capitalization weighting method should be considered: Market Capitalization Square Root Weighting.

Market Capitalization Square Root Weighting will compute the project weight in the portfolio according to each project square root data, to restrain each asset impact on the portfolio.

Equal Weighting refers to the index of average distribution proportion of all assets. If there are 4 assets in the portfolio, which means each asset can gain 25% of the portfolio value.

Here is an example of the DeFi fund of MatrixETF to compute the market capitalization.

According to Market Capitalization Weighting, Matrix DeFI Index(MDI) computes different component token weight as below:

![](https://miro.medium.com/max/700/1\*ZtqnozTs55WE7gA78WjDRQ.png)

Among them UNI is with the biggest market cap 34.44%, which is not over the set highest asset proportion（Max ≤ 80%), in this case it’s better to compute in the basic Market Capitalization Weighting method instead of other weighting methods.

## Weight Calculation <a href="07a6" id="07a6"></a>

MatrixETF performs further weighting calculations on the basis of fundamental weighting and market value weighting, weighting 70% of the circulating market value and 30% of the fundamentals to obtain the final weight.

Among them, when considering the weight, we set the minimum and maximum asset allocation.

* Minimum asset allocation: A minimum limit is set on the percentage of ETF funds that can be allocated to a single asset. This can prevent the use of market capitalization weighting methods resulting in a large number of low-weight assets. (Min ≥ 2%)
* Maximum asset allocation: that is, a maximum limit is set on the percentage that can be allocated to a single asset in the ETF fund portfolio. This can prevent the use of market capitalization weighting method to cause a single asset to account for too high a situation. (Max ≤ 80%)

Taking Matrix DeFI Index (MDI) funds as an example, based on fundamental weighting and market value weighting, the final weighting ratio of each component token is as shown in the following table:

![](https://miro.medium.com/max/700/1\*bvGRigJGCPhC0Jib-amMXg.png)

Among them, UNI has the highest weighting ratio of 27.32%, and CRV has the lowest weighting ratio of 4.77%, which exceeds the threshold of minimum asset allocation (Min≥2%).

## MatrixETF Index Rebalance <a href="659b" id="659b"></a>

After the encryption index fund is configured according to the initial weight, the proportion of its component token will change due to factors such as the project’s own development, market cap, encrypted market trend, funding level and community, actual status component token weight inconsistent with the initial weight. Once it happens, the deviation between the two is large, this is why we need to rebalance the index.

The Matrix Index will maintain and adjust the index once a month according to the development of the crypto market and the operation conditions of the project, including the token weighted proportions, the increase/decrease of the new tokens, etc.

There are 2 phases of rebalance:

### **1.Confirmation** <a href="a3a3" id="a3a3"></a>

Normally this phase happens on the fourth week of every month. In this phase, we will confirm the details of recombination including:

* If adjust the circulation supply
* If adjust Token weighted proportions
* If delete or add new tokens
* Add the new token information

### **2. Rebalance** <a href="f8ff" id="f8ff"></a>

The index and fund will be adjusted according to the announcement after confirmation, among them the relevant token (delete/add/weighted proportions) will be completed on the first week of the next month.

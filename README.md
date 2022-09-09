# An Ancap's Critiques of All Cryptocurrencies

Numbered for reference.

## Introduction

1\. Before money, humans bartered. A horse for a cow, etc.

2\. Money was invented as an intermediary to fix problems of barter. Types of money include gold, silver, salt, alcohol, etc. There are various theories about what makes something money, but the end result is that when I pay you money for your cow, you expect you can buy other things with that money that you value about as much as that cow, or you can use the money for something else of similar value (e.g. eat the salt, turn gold into jewelry, etc.).

3\. At this stage, money was fully decentralized and as private as desired. The trade of a one ounce gold coin for a cow, for example, could be done anywhere, without anyone's permission.

4\. The value of money depended on the supply and demand of the money itself, as with anything else in a market.

5\. In some cases, banks or governments issued paper money that was convertible to the underlying money. Someone could go to the issuer and exchange a paper money note for an equivalent amount of gold, for example. Thus, paper money substituted for the underlying money.

6\. Digital money is similar to paper money except even easier to create.

6\. Debt, fractional reserve banking, money laws (Know-Your-Customer [KYC], tax evasion, money laundering, etc.), and so on are also important parts of monetary history, but not important for later arguments, so they will be skipped.

8\. Governments tend to assert more and more power over the creation and use of money. Especially with paper and digital money, this tends to lead to unfair distribution of wealth, and limiting freedom.

9\. Interestingly, despite its other (major) flaws, paper money is as decentralized and private as original forms of money: The trade of $2,000 cash for a cow, for example, could be done anywhere, without anyone's permission (there might be separate laws against such trades, but those are just government assertions that can apply to anything).

10\. Less corrupted money such as gold still has significant worldwide value (as of 2022, [about $10 trillion](https://www.forbes.com/sites/stevenehrlich/2021/12/28/six-numbers-that-defined-cryptos-record-year/)); however, it's heavy, taxed, hard to transport across borders due to metal detectors, [has been made illegal](https://en.wikipedia.org/wiki/Executive_Order_6102) over certain amounts in the past, and the market value of gold is likely manipulated by governments. Companies that tried to restore less corrupted money with modern digital conveniences have faced legal consequences (e.g. [E-gold](https://en.wikipedia.org/wiki/E-gold), [Goldmoney](https://www.bbc.com/news/world-europe-jersey-57357523), etc.) due to governments' comprehensive and coordinated control of underlying physical land.

11\. Cryptocurrencies attempt to create less corrupted money. They are primarily digital. Their supply is simply asserted ("by fiat"; Latin, "let it be done"). They use a ledger to perform transactions. The ledger is a chain connecting transactions together that can be verified mathematically using cryptography; this is called a blockchain. Most commonly, this ledger is distributed across many computers without any required trust.

12\. Cryptocurrencies have essentially no weight and they're easy to "take" across borders as one only needs a small digital file that can fit on a USB stick (or stored on a remote computer), and a short password.

13\. To achieve consensus of the correct ledger without trust, a majority must approve transactions ([Fischer et al., 1985](https://doi.org/10.1145/3149.214121)). This is done through various mechanisms such as proof-of-work, proof-of-stake, etc. ([Xiao et al., 2020](https://doi.org/10.1109/COMST.2020.2969706)). Bitcoin, the most popular cryptocurrency, states this majoritarian requirement simply: "If a majority of CPU power is controlled by honest nodes" ([Nakamoto, 2008](https://bitcoin.org/bitcoin.pdf)). Similar majoritarian requirements apply to **all** cryptocurrencies with a public ledger ([Fischer et al., 1985](https://doi.org/10.1145/3149.214121)). The so-called "50%+1" problem is not just about double-spending, but applies to the entire cryptocurrency, including its protocol.

13\. Cryptocurrencies hope that a combination of technical countermeasures and market incentives will disallow governments from asserting control as they did with gold and silver.

14\. Likely the most important technical countermeasure is that blockchains can "fork". What forking means is that, if government(s) take over majority enforcement of a cryptocurrency, honest nodes can split off and continue their ledger and users can choose to connect to the honest fork instead of the government fork.

## Critique 1: Cryptocurrencies are not decentralized

15\. The claim that cryptocurrencies are decentralized is strange. A cryptocurrency transaction requires a third party to add to the ledger, which seems strictly worse than gold, silver, and even cash. And not just any individual third party but a majority of enforcers of the cryptocurrency.

16\. Perhaps one can argue that the value itself is less centralized than government money, but market value is irrelevant if transactions can be denied. This is most obvious in the case of a situation without electricity or internet, but transactions can also be denied consciously (e.g. [The DAO Ethereum fork](https://en.wikipedia.org/wiki/The_DAO_(organization))). The whole purpose of decentralization is to avoid such restrictions.

## Critique 2: Successful cryptocurrencies will inevitably be democracies

17\. As per point 13 and [Fischer et al. (1985)](https://doi.org/10.1145/3149.214121) in particular, all cryptocurrencies with a public ledger are a majoritarian democracy. The voters might be miners, stakers, etc., but the point is that the majority can always vote to change the protocol, deny a transaction (including retroactively), etc. (e.g. [The DAO Ethereum fork](https://en.wikipedia.org/wiki/The_DAO_(organization))).

18\. Monetary incentives and game theory may work in early stages, but if a cryptocurrency became mainstream, governments would receive taxes in it and would have an incentive (and would be pushed by voters) to participate in the majority mechanism, thus passing through the government's underlying democracy into the cryptocurrency democracy. We'd be back to where we are now.

19\. Some ancaps advocate for political action in the context of a political democracy (e.g. to retard the growth of government or fight to take back some freedoms); participating in majoritarian cryptocurrencies will be similar.

20\. One counter-argument would be to hope for a cryptocurrency to never become mainstream successful and to achieve an equilibrium where the maintainers of the cryptocurrency have no incentive to manipulate it. In this case, it likely becomes a black market currency that is potentially useful for laundering money. This is an individual approach, but wouldn't achieve stated grandiose, society-changing goals of many ancap advocates, and isn't very different than other money laundering techniques (e.g. art), and might be more risky.

21\. One alternative might be private-property ledgers which are not subject to the majoritarian requirement. A healthy, competitive market of private-property ledger cryptocurrencies is likely what would exist in an ancap world; however, in today's world, it is unlikely to work due to governments' comprehensive and coordinated control of underlying physical land (see point 10).

## Critique 3: Cryptocurrencies are not technically robust

22\. Cryptocurrency technical countermeasures will fail if governments are truly threatened by a cryptocurrency due to governments' comprehensive and coordinated control of underlying physical land (see point 10). There is nothing magical about cryptocurrencies and the digital world. The ledger exists as files on a set of computers. Those computers are connected using the internet. A cryptocurrency wallet must have IP addresses of those computers and must have a path to those IP addresses. Besides the question of how a user gets these IP addresses, as China has demonstrated with its Great Firewall, the simple brute force solution to block "undesired" internet traffic is to send TCP RST packets when users try to connect to "undesired" computers. Each country controls ingress and egress of the internet to other countries (the most extreme example is North Korea).

23\. If a cryptocurrency is made illegal, some will be able to work around that. They'll know the right chat group to find the latest set of IP addresses to connect to. They'll know the right wallet to use that has the latest countermeasures. They'll know the right VPN to connect through. However, this will all be very limited to a small set of very motivated and risk-tolerant people. This is similar to how Tor *can* work in China today, but it's extremely difficult. This goes back to point 20 that if one values money laundering their wealth significantly, cryptocurrencies may help although with significant risk.

## Critique 4: The Primrose Path

24\. Shakespeare has a famous literary device called The Primrose Path. The path is decorated pleasantly with primroses that tricks a character to go down the path which leads to a bad place.

25\. The analogy here is that cryptocurrencies, whether by design or usurpation, and despite any good intentions, may lead the world into monetary, dystopian panopticon without even the relative freedom of silver, gold, and cash. Cryptocurrencies may be normalizing thought leaders, institutions, and the general public to accept a Central Bank Digital Currency, a global digital currency, or one or more governments may simply take over the most popular digital currency, assert majority, and modify it to its needs. Cryptocurrencies may inadvertently kill or significantly reduce the value of legitimately decentralized alternatives such as silver, gold, and cash (despite their flaws).

## Summary

If the above are legitimate critiques, then what is an ancap to do? 

My opinions: If you go into cryptocurrencies, go into them with an accurate view of reality:

1. Public ledger cryptocurrencies are not decentralized; they're political and democratic.
2. Private ledger cryptocurrencies are currently infeasible.
3. Cryptocurrencies are nothing magical. Governments' brute forces can manipulate, usurp, or crash them (although unlikely to 0).
2. Cryptocurrencies might help you launder money (that's how governments will see it) which can be high risk.
3. Cryptocurrencies are not likely revolutionary and might make things worse.

As far as how to act in a world with such realities and what to do with one's money, that depends on various individual factors and risk tolerance, but it seems that money is not the path to political freedom.

The alternatives to the Primrose Path are steep and thorny, but worth exploring.

> I shall the effect of this good lesson keep, \
> As watchman to my heart. But, good my brother, \
> Do not, as some ungracious pastors do, \
> Show me the steep and thorny way to heaven; \
> Whiles, like a puff'd and reckless libertine, \
> Himself the primrose path of dalliance treads, \
> And recks not his own rede.

*Hamlet*, Shakespeare

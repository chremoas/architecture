# Warehouse

This is the best name I could come up with for the time being.  It's taken from eve-cost and the jist is that it's a merger of raw API asset polling, API industry job polling, API contract polling and API wallet transaction polling.

The idea is that the mentioned API’s are the baseline (actual assets) and inflows and outflows of assets.  The only part of the equation that breaks things down are people directly putting things into or taking things out of Corp hangers.  This can be detected however.

The purpose of the warehouse is to (as best as possible) put a price to everything.  By averaging everything together the warehouse knows how much was spent to procure the current set of inputs, how much was put into the sellable products and also how much was put into the intermediate assets (things produced to produce sellable goods).

Example:

50 widgets were bought off the market at 1 isk each producing a wallet transaction.  These were the first of their kind purchased.

40 widgets were consumed to produce a wadget.  That wadget now has a cost of 40isk + overheads (salary, freight, installation costs and fee’s, fuel, whatever).

The warehouse now has 10 widgets (worth 1isk each) and 1 wadget (worth 40 isk because I'm excluding overheads for simplicity)

10 more widgets were procured at 2isk each.

The warehouse now has 20 widgets worth ((10 * 1)+(10 * 2))/20 = 1.5.

There will be some issue’s with contracts that have multiple items if they aren't first created in the app but that's not completely unsolvable… Just slightly complex.

Oops’s are another issue.  When a purchaser forgets to use the corporate wallet and just takes the money.  The correct procedure would be to create a contract but we’ll cross that bridge when we come to it.

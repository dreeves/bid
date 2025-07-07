Currently just a tool to facilitate arbitrary-share 2-person decision auctions (aka odd yootling).

Idea: port kibotzer.com/bidder to this?

## Spec for making this multi-user-aware

Starting with the M'est of MVPs: if there are exactly two people viewing the page, it enforces that the shares sum to 1 and has a button to lock in your bid and when both people press it, it reveals the bids to both parties. That's kind of how our /bid command in Slack and Discord works.

(If there's just one person connected it just does what it does now.)

If a 3rd person shows up, it shows them a button: "already 2 bidders! click to rudely disconnect and usurp them".

For later: what if it gets popular and people are rudely disconnecting you all the time? The fully robust solution is what games like Spyfall or Among Us do where you enter a code to coordinate with the people you're playing with. Before that you could just give yourself a name or it could even default to like "someone on an iPhone in Portland" and you pick who you're bidding with that way.

<img src="https://bid.yootl.es/images/homobees-cropped.png"/>

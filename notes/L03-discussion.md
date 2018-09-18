# LKML news

https://lore.kernel.org/lkml/CA+55aFy+Hv9O5citAawS+mVZO+ywCKd9NQ2wxUmGsz9ZJzqgJQ@mail.gmail.com/

Context: Linux maintainer Linus Torvalds is known for sending inflammatory mails to the linux-kernel mailing list.

Questions to consider:

* what are the pros and cons of an inflammatory communication style?
* what are the responsibilities of a project leader?
* what are appropriate next steps for the Linux community?

# Pont de Quebec

* "Engineering marvel"
* Key link for the Transcontinental Railway

sources:

* https://legionmagazine.com/en/2000/11/a-bridge-with-two-tragedies/
* https://www.mysteriesofcanada.com/quebec/quebec-bridge-collapse/
* https://tolkien2008.wordpress.com/2010/07/17/le-pont-de-quebec-seffondre-1907-et-1916/
* https://www.thecanadianencyclopedia.ca/fr/article/le-desastre-du-pont-de-quebec

## 1907 failure

From the Royal Commission report:
[https://ia600208.us.archive.org/33/items/reportandplansa01schngoog/reportandplansa01schngoog.pdf]

* "Failure of the lower chords in the anchor arm near main pier... due to their defective design"
* "Failure cannot be attributed directly to any cause other than errors in judgment on the part of these two engineers"
* "The ability of the two engineers was tried in one of the most difficult professional problems of the day and proved to be insufficient for the task."
* "The failure to appoint an experienced bridge engineer to the position of chief engineer was a mistake."

* Consulting engineer: Theodore Cooper (NY)
   - "Few equals on the continent"
   - Was not on-site.
* Requirements change: center span 1600' -> 1800'
* Flurry of correspondence about ultimate engineering responsibility, held by Cooper
* Weight calculations by Peter L. Szlapka
   - estimations incorrect because bad data
   - actual weight exceeded estimated weight, Cooper judged that excess was within safety margin

* On-site chief engineer (EA Hoare) did not have technical skill
* Workers observed misalignment in chord splices but communications problems prevented work stoppage
   - Cooper: "Add no more load to the bridge"

* 15 seconds: cantilever arm and span fell into St. Lawrence
* 75 of 86 workmen died, including 33 Mohawk steelworkers from Kahnawake
* damage over $1.5MM (probably about $40MM in 2018 dollars)

* took 2 years to clean up the mess

## 1916 failure

New plan. More steel, K-trusses invented. Still cantilevered, still 549m.

Got to span-raising day with 100,000 spectators.

## 1917 opening

Much less collateral damage.

Reconstructed the central span, opened the bridge, 125,000 spectators.

## Rust on bridge today

https://quebec.huffingtonpost.ca/2017/03/23/mauvais-etat-pont-de-quebec_n_15562304.html

# FIU bridge 2018

https://commons.wikimedia.org/wiki/File:FIU_bridge_collapse_suspect_tensioning_rod_2.png
https://www.miamiherald.com/news/local/community/miami-dade/article212571434.html
https://www.miamiherald.com/news/local/community/miami-dade/west-miami-dade/article205316174.html

# Hyatt 1981

https://interestingengineering.com/understanding-hyatt-regency-walkway-collapse
https://www.engineering.com/Library/ArticlesPage/tabid/85/articleType/ArticleView/ArticleID/175/PageID/197/Default.aspx

# Playground bubble

Personal communications with Derek Rayside:

| Here's an article on the bike bus: http://dandyhorsemagazine.com/blog/2017/06/06/bike-bus-or-bust/
| there was a design flaw in it, that was somehow conceptually similar to some other design flaw i was talking about ... i drew some pictures ... kind of surprised that they aren't in the slides ... let me look ...
| there is the same basic problem in the hyatt hotel lobby bridge disaster as in the playground bubble and bike bus floor. all three of these things have failed. the problem is that the force is in the fasteners rather than the structural members. the fasteners should just provide stability to the load bearing members, not actually transfer the primary forces. 
| thankfully the latter two failures did not result in any injuries.
| for the bubble, we just replaced it with the flawed design that had already failed. 
| for the bike bus, we actually rebuilt the floor as indicated in the diagram
| so the bubble will fail again in another decade or so. this time it failed after hours, so probably due to teenagers who have greater mass. unlikely the daycare kids have enough mass to cause failure. and perhaps the whole playground will be replaced by then. 
| anyhow, i refused to put up the bubble with the defective design. so someone else did it.
| the point is that even though we study these disasters in school for the last almost 40 years, you can still see this same error all around you. just keep your eyes open.

# Incident investigation models

* We like to do root cause analysis.
* Sometimes there are a number of factors which all have to line up for something to happen (Swiss Cheese model), but not so much in today's examples.

# Software Disasters

https://www.technologyreview.com/s/607955/inspecting-algorithms-for-bias/
https://www.theatlantic.com/technology/archive/2017/09/saving-the-world-from-code/540393/


##### Big Mountain Resort Montana Ticket Value Report
<br/>
Based on the random forest model, the dominant top four features in determining ticket value are:

* fastQuads - The number of fast four person chairs
* Runs - Count of the number of runs on the resort
* Snow Making_ac - Total area covered by snow making machines in acres
* vertical_drop - Vertical change in elevation from the summit to the base in feet

![top 4 features](top4features.png)
<br/>

Big Mountain Resort Montana's top four features comparing to other resorts:
1. fastQuads
![fastQuads](fastquads.png)
Most resorts have no fast quads. Big Mountain has 3, which puts it high up that league table. There are some valur much higher, but they are rare.

2. Runs
![runs](totalruns.png)
Big Mountain compares well for the number of runs. There are some resorts with more, but not many.

3. Snow Making_ac
![snowmakingarea](snowmakingarea.png)
Big Mountain is very high up the league table of snow making area.

4. vertical_drop
![verticaldrop](verticaldrop.png)
Big Mountain is doing well for vertical drop, but there are still quite a few resorts with a greater drop.

Overall Big Mountain Resort is doing well in all four features that determine ticket value the most.

Big Mountain's ticket price comparing to other resorts in all states and in Montana only:
![bmpriceall](bmpriceall.png)
![bmpricemt](bmpricemt.png)

Four scenarios modeling (shortlisted options by the business owner):
1. Permanently closing down up to 10 of the least used runs. This doesn't impact any other resort statistics.
![scenario1](scenario1.png)

The model says closing one run makes no difference. Closing 2 and 3 successively reduces support for ticket price and so revenue. If Big Mountain closes down 3 runs, it seems they may as well close down 4 or 5 as there's no further loss in ticket price. Increasing the closures down to 6 or more leads to a large drop.

2. Increase the vertical drop by adding a run to a point 150 feet lower down but requiring the installation of an additional chair lift to bring skiers back up, without additional snow making coverage

This scenario increases support for ticket price by $1.65
Over the season, this could be expected to amount to $2891304

3. Same as number 2, but adding 2 acres of snow making cover

Such a small increase in the snow making area makes no difference

4. Increase the longest run by 0.2 mile to boast 3.5 miles length, requiring an additional snow making coverage of 4 acres

No difference

Big Mountain Resort is currently charging $81 per adult. The model suggests increasing the price to $95. The increase should be able to support the operating cost of the new chair lift. Additionally, modeled scenario 1 has shown closing 1 run would not make a difference in supporting ticket price increase.

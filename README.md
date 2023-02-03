# Economic Equalization Overhaul
This is a fan mod for the game Terra Invicta. It modifies the way national economies work, to better represent the way countries of different sizes compare.


### Summary of Effects
-National monthly investment points are equal to 1 per 100 Billion GDP.

-Countries with a per capita GDP less than $15,000 receive up to a 30% penalty to investment points.

-Each resource regions gives an 100% bonus to the economy priority.

-The control cap cost of a nation is equal to its investment points, which is then split across each control point. Control cost  of a nation is no longer dependent on the number of control points, as in vanilla.

-Arrival International Relations, Unity Movements, Great Nations, Arrival Governance, and Accelerando each reduce the control cost of a nation to be to the power of 0.98, 0.95, 0.90, 0.85, or 0.80, depending on how many of these techs are researched. Larger nations benefit significantly more.

-Economy investments gives an amount of GDP, as opposed to an amount of GDP per capita (though the tooltip shows the distributed GDP per capita). This makes all economies grow at the same % rate, disregarding modifiers.

-Investment effects that impact demographic stats such as education, inequality, or cohesion are scaled inversely based on population size. You need 1000 times as many knowledge investments to increase education by 0.1 in a country with 1 billion people compared to a country with 1 million population.

-Education increases at a faster rate at lower education levels, and a slower rate at higher levels. This is an exponential decay function that gives 4 times the gain rate at 0 education compared to 10 education, and 50% of the gain at 15 education compared to 10.

-Military tech gain is increased by a factor depending on how far the nation is behind the global maximum tech level, a linear bonus of 50% extra gain per 1 tech level behind the current maximum.

-Small adjustments to the relationships between things such as education and GDP growth, broadly maintaining vanilla levels of impact.

-Other changes to investment effects such as spoils and funding amount to flatten out the amount gained per investment to be constant regardless of country size.

-Adjusted costs of many investments to reflect the greatly increased investment points available to most nations, or to simplify calculations.

-Adjusted upkeep cost of armies to be dependent on the host country's tech level. Armies cost a base upkeep of 1 IP, plus 2 IP per national tech level above 3.

-Research output of a nation rebalanced. A nation no longer receives a flat 7.5 + education monthly research, however its research also increases linearly with population, not at a ^1.1 rate as vanilla.

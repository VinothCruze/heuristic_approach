# heuristic_approach
## Heuristic Approach in determining interaction between cycle and car


To find the interaction,
(i) calculate the velocity by distance formula from xvelocity and yvelocity points from the track dataset.
(ii) filtered out the cycle and car classes and merged them into single dataset
(iii) checked for the correlation of both car and cycle by the time frame and if they are matching separating them as interaction.
(iv) took the correlation distance to be 2 so that to avoid the null value set.

Ideas to be implemented:
i) By taking the heading column match the correlated values and check for the direction and then confirm the interaction to be on opposite sides.
ii) Check for the displacement based on the acceleration values and then match with the correlated values to further improve the interaction check.


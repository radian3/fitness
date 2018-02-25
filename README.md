# BulkingAnalysisCalculator
You can submit data from your previous completed bulking cycle in order to see statistics on your muscle gain, fat gain, caloric surplus, recommended caloric surplus, and more. 

If you are in the middle of a bulk, you can enter the current statistics of your bulk in the bottom half of the form. You can use the recommended caloric surplus in an attempt to gain 1 lb of muscle per lb of fat gain.

Explanation of calculations:
LBM: weight*((100-bf%)/100)
Fat: weight*bf%/100
Average caloric surplus during bulk: 3500 * poundsOfWeightGained / bulkDurationInDays
Optimal caloric surplus: 2*percentOfWeightGainThatWasMuscle*AverageCaloricSurplusDuringBulk

note: The optimal caloric surplus is the only controversial calculation in this project. It is under the (potentially incorrect) assumption that halving your caloric surplus is considered the same as doubling the proportion of weight gain that was muscle and vice-versa. For example, if you are at a caloric surplus of 400 and 25% of your weight gain was muscle, this calculator would predict that a 200 caloric surplus would lead you to 50% of your weight gain being muscle. The reason that this calculator tries to calculaate a caloric surplus that would lead to 50% of your weight gain being muscle, is that this is commonly regarded as the best ratio of muscle to fat gain that most intermmediate to experienced bodybuilders can get. Beginners can do better than this, including gaining muscle and losing fat at the same time.
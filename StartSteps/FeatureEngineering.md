### Why feature engineering
 - You should keep the features that have a strong correlation with the target value
   - this can be decided based on domain knowledge
 - you should remove the unnecessary features as it just adds to the random noise in the model, decresing its performance

### Ways to do feature engineering
 - Adding or dropping features
 - combining multiple features into one
   - for example there are 2 columns for height in inches and height in feet, combine these 2 to make a single column of height in inches
 - Binning
   - replce an exact numerical value with a more broad category
 - one hot encoding
 - Date column example
   - compute day of the week
   - weekend or not
   - national holiday or not
   

http://www.willmcginnis.com/2015/11/29/beyond-one-hot-an-exploration-of-categorical-variables/

https://stats.idre.ucla.edu/r/library/r-library-contrast-coding-systems-for-categorical-variables/

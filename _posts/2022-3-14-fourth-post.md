# Data Science in Finance - Fourth Blog


## This blog is mainly about my usage of the Clojure backtesting library. 
### Feelings about using the backtesting library. 

- The functions are straightforward.

  All the functions are well structured and user-friendly with comprehensive introductions in the backtesting library website. 

- The report data is informative.

  There will be three reports to record the orders the strategy has made, the total value, returns, and other parameters for evaluating the strategy performance. 
 
### Possible directions for improvement. 

- The dataset can be flexible. 
  
  The dataset used in the library for backtesting is by default the CRSP dataset. Though the CRSP dataset is mainly used in the quantitative finance research,
  there are perhaps other datasets that are also frequently used. For example, the WRDS dataset. 

- Users may have more flexibility in deciding the calculation method. 

  For example, in the calculation of return. Whether to use the simple return or log return method can be up to the users to choose depending on their research purpose. 
  
 - Other financial instruments trading can be included. 
 
  Besides the most commonly traded stocks, other financial instruments like bonds or derivatives may also be added to enlarge the functionality of the whole library. 


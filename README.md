# Forex-Bias-Free-Trading-Predictor
Trading financial instruments have been dated since the 18th century when the most popular chart/visual representation of the markets price action movements were invented -the Japanese Candle Sticks. Since then, various ways of predicting price movements have been introduced mainly with the help of various indicators. However, as these indicators had a major flaw in them that they lagged the market by the timeframe they are applied on. The most profitable traders have had to rely on pure market price action methods coupled with their strong will of discipline to trade. The most notable technical method of reading market price action is based on the Elliot wave theory which requires years of practice to master. In this study, unlike most popular automated trading solutions which rely on the numbers behind the graphs being plotted, we want to attempt to develop a model that trades as close to the way the best humans do it i.e., trade by analyzing any given financial instrument charts. 


Relevance of the problem: Due to human nature our susceptibleness to been bias increases in the presence of fatigue which leads to poor decisions even when the market presents a clear opportunity, which results in poor trading performance which leads to a weak trading psychology which ultimately leads to self-doubt of one’s skills and ability to perform well in the in the market. At this stage if proper attention is not given to solving one’s dwindling trading psychology, it may deteriorate other aspect of oneself.
    
    Solution: In this project attempt, we will be attempting to teach a model just as every trader will learn to read market price action and identify relevant information on the chart and measure the model’s performance at identifying basic market scenarios such as:
    •	Market trends,  
    •	Few basic technical chart patterns 
    •	Highest probable occurrence of what happens when each pattern is developed in various market condition.
    
    
Motivation: It’s a known and proven fact that trading skills compromises 10% of a trader’s ability to read price action the majority 90% comes from a trader’s resilient and strong trading psychology which is mostly obtained through painful failing experiences. If we can build a model that is able to learn the technical part of trading, well most profitable teach themselves trade mechanically and nothing comes close to mechanical as a model.
    

    Model objective: Provide a working concept of a model that:
        •	Able to take in and learn from visual chart data (Japanese candle sticks and or line graph) as humans do while day trading, 
        •	Identify a learned chart pattern in any given live market condition and predict with some accuracy the probable market reaction because of the identified pattern.
        
    Scope of model: For the model development, 
        •	We will focus solely on one financial instrument in the FOREX market. 
        •	We will focus on a single chart formation and its various forms of occurrences in a
            o	Bullish market, 
            o	Bearish market and 
            o	Ranging market. (No clear market trend visible)
        •	We will focus on a single timeframe 

    Out of Scope In this stage of the model build, bounded by the current semester time frame, we will not:
        •	Test the profitability of the model or develop means for it to do so.
        •	Integrate the model to actual live markets for trading real funds as delving into this aspect will require further definition of variables that will need proper handling.
        •	Expand the scope of the project as formulated and agreed by the team members. *

Training the model: To obtain the model training and testing data, we will implement a publicly available software solution to backdate our chosen currency pair on our chosen timeframe, replay the chart starting from a past date and manually capture as many instances as possible of our chosen chart pattern right when they occur, and another picture (screenshot) will be taken showing the aftermath of market reaction because of the identified pattern. The images will be processed in pairs (before /after) however best determined for model training. Other model inputs to be identified on the images will be the market trend on the monitored timeframe, the time frame itself and the trading session.

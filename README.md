Tool: Stock Scanner
Creator: Sys-Op-Master
Date: 4/23/19

Description: This program will allow you to customize settings to look up stock within those parameters 
as well as provide visual feedback so you can see the information you want to see without everything else.

My current list of features I would like to impliment for my stock scanning program:
-Intraday Data (Second by Second if possibly but may not without payment)
-Easy to use query editor that has simple customizable parameters
-Multi-Monitor Support in the form of easily scaled windows
-Easy way to customize and save your "layout" so once it's set up, everytime you open the program, your custom windows are too
-Drop-down selection in each window to select the data you want shown
-Alert system that you can set up (or if the API allows it, have it suggest trades based on your criteria) for stocks that gain/lose x% in after-hours, more than average volume for the time (based on average for the ytd volume), and many other search functions like customized searches.
-(If you have every seen Windirstat) I want to generate a window such like that but with stock movement percentages for that day.
-A way to keep track of the historical data that most websites don't record past the current day (possible daily 15-min trade windows that you are researching and will store on a folder you choose for you to look back on)
-Try to use more information to generate better and more useful screens that do multiple things at once (newsfeed/social media scanner, and other things major platforms don't seem to have)
-possibly more as I think of things I want to add or get suggestions for

Due to my time schedule, this will probably take me a while to even get a basic framework worked up so be patient and I'll do my best to keep everyone who's interested, informed.

Updates:

4/23/19-This project has started today. Depending on how deep I decide to take it, this may take a month or longer to get to a release state.
I work full time so this is more of a pet project and a way to test my python knowledge.

5/23/19-So I've familiarized myself with ToS and finviz and other stock market websites and decided I need a way to get the most frequently updated stock data set out of somewhere. Possibly pulling data from Yahoo Finance or maybe there is a way to use the API from ToS or possibly look into if finviz has one and check that out. Whatever way I do it, I think I'm stuck with python (which isn't bad but still would like to use C++ so we'll see how this progresses goes) since the APIs are coded in that from what I hear so far.

5/25/19-After looking around for a free API that will support my needs, I decided to go a different route. My plans are to take an excel spreadsheet and pull data from Yahoo Finance (using Excel's controls, I should be able to get the most accurate and up-to-date financial data available and have it stored in an easy to access spreedsheet). From there, I'll write a program that will query and draw charts based on this pulled data. This should also give me the data I need to execute most of my feature list while still leaving a few things I would like to have still in the air on if I'll be able to get them. If this turns into a larger program, I may decide to opt for a paid API with real-time data included with the other data I would like to pull. As for a newsfeed, I still need to do more research into that but I think a basic scapper for the most popular financial news sites should do the trick fine.

Step one will be getting my spreedsheet worked out and then once I have everything set, programming shall begin!



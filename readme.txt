This is a WoW (World of Warcraft) auction calculator spreadsheet that pulls pricing information from TheUndermineJournal.com

The spreadsheet was originaly created on 3.28.13 by SheLuvme for Jim Younkin of the WoW gold-making blog powerwordgold.net.

Below is the blog post that accompanied the original posting of the spreadhseet.

-Jim Younkin

"I was approached by livestream viewer SheLuvme with a proposal. They wanted to take my Simple Living Steel Material Price Calculator and make it into an Excel spreadsheet that would automatically pull the material prices directly from The Undermine Journal servers. This would make it so I would always have updated pricing information. 

This sounded great and they seem to have pulled it off. (One small snag, I don't own Microsoft Excel.) Regardless I've been assured by SheLuvme that this spreadsheet works. Head past the jump to learn how to get the spreadsheet and set it up for your own use.

Important Notes *Read*

I want to reiterate at the beginning that this is very advanced stuff. If you are not comfortable with advanced spreadsheets, fiddly Undermine Journal settings and such things this may not be for you.

It should also be noted that all of this is very experimental and may break, act weird and  simply not work. You're on the bleeding edge here.

In my testing this file will not work with Google Drive or OpenOffice. You must have Microsoft Excel to use it. While there may be some wizards out there who can getting it working on other programs for the purposes of this post I'm assuming you're using Excel.

Download The File

We decided to get a little nerdy and finally use our GitHub account for something. We've uploaded the .xlsx to GitHub so anyone can download it (as well as possibly add to/edit/build upon it). 

We're not really sure if this is the "proper" way to use GitHub but we thought we'd give it a shot. (If anything else it give a slightly more straightforward way to download the file.)

First go to the project's GitHub repository here.

In the "Code" tab look for the "Files" tab. Right-click on "wow_live_calculator.xlsx" file and select the option "Save link as..." (or similar) in your browser's pop-up menu and save the file to your computer.



To download: Code > Files > right-click file name and select "Save link as.." (or similar).

(If you're familiar with GitHub I'd imagine you could do things like "forking" or "submitting pull requests". If you do this just know I'm a total GitHub noob.)

Ready. Set. Go!

Everything from this point on assumes that you have properly downloaded the file and have Microsoft Excel to work with the file. If you do not have these two things feel free to read on by it might not make much sense.

A Few Words From The Author

I asked SheLuvme to write a few words to try to explain the spreadsheet better. I have still not used the file (as I don't own Microsoft Excel) so I'm leaving you in their hands from here on.

If you have any problems or issues with the spreadsheet please feel free to email me at powerwordgold@gmail.com. While I may not be able to solve every problem I will at least be able to pass the information along to SheLuvme.

SheLuvme wrote:

"While various websites and in-game add-ons will always greatly assist in AH researching, crafting research, profit finders, and more, it does not always put all the data you need at the tip of your fingers.  

The calculator solution starts by leveraging a very nice and helpful service from The Undermine Journal to pull in live Auction House data from your server.  To use the spreadsheet, you will have to follow the setup instructions, as the queries are tied your user ID from  The Undermine Journal.  A user is restricted to 10 queries per server per faction every 24 hrs.  The steps in the setup sheet are hopefully straightforward so that you can easily setup your data feed.  

The calculator currently does a couple of key things, but functionality can always be expanded if it is useful:  

1.  Price Calc Sheets: AH Prices for your server for any item.  This can easily be found with Excel searches and filters.  Additionally, these sheets will have a "Safe Price" calculation routine that is primarily used for the crafting sheet.  The "Safe Price" uses various calculation routines to determine the best price (Market Price ? Market Average? consider Standard Deviation?) based on the current market size of that item (quantity).  Additionally the safe price has a built in "modifier" percent so you have flexibility for defining your own safe price thresholds for each quantity condition defined. 

2.  Living Steel Calculator:  Here we used Jim's current excel calculation sheet for which he uses to determine the best method for using an alchemist living steel cool down.  Should you smelt ghost iron ore?  Buy ghost iron bars? Or use trillium mats?  Previously with Jim's calculation sheet all these prices would have to be manually maintained.  Now, with the click of an excel button all prices will update automatically for your server from the TUJ data feed.  

3.  SOH & Crafting:  The first thing this sheet does is try to determine the market value of Spirit of Harmony, similar to how it is displayed on the TUJ elemental page.  This will tell you the best possible trade-in value for a SOH.  However, this data is also used as the basis for SOH valuation when considering it as a reagent in a crafted item.  

The next part of the sheet will allow you to put in any crafted item you can do and it will automatically, calculate the full crafting cost of all the reagent prices.  This includes SOH items and non-SOH items.  Cooking, smelting, tailoring, blacksmithing, etc.  It will use the "Safe Price" that you had control over from the Pricing sheets to determine profitability.  

At a glance you will now be able instantly look at everything you can craft, look at real-time sales and cost data and determine the best things for you to craft.  

Please note certain new patterns are not live from TUJ yet and they may not have pricing found.  Also, Imperial Silk and Lightning steel ingot reagents has not been solved for calculations yet either.  

Also note that the spreadsheet should be setup for both the horde and alliance factions of your server.  It provides capability so that you can see prices on both servers and if you have cross-faction trading capability (typically achievable with 2 accounts) , it will further maximize your gold making potential.  

Carefully review the Setup Instructions & Sheets Overview worksheets.  

Please try the sheet out and provide your feedback to powerwordgold@gmail.com   

-SheLuvme"

Conclusion

The spreadsheet SheLuvme has put together seems like it has great potential (if configured correctly) to make some menial tasks trivial.

In my case this would make figuring out which material to use to make Living Steel on any given day much faster than my current method of entering prices into a spreadsheet by hand.

This spreadsheet is one example of why I love the gold-making community. People always coming up with new and shiny tools to help us.

If you are able to get the spreadsheet working let us know about your experiences in the comments."
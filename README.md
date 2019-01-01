# OnlineAuction
This is a simple web interface for providing the online auction functionality built using Python web.py framework. 


AuctionBase system provides the following functionalities.
 Ability to manually change the “current time.”
 Ability for auction users to enter bids on open auctions.
 Automatic auction closing: an auction is “open” after its start time and “closed” when its end time is past or its
buy price is reached.
 Ability to browse auctions of interest based on the following input parameters:
  – item ID
  – category
  – item description (This should be a substring search, i.e. not an exact match.)
  – min price
  – max price
  – open/closed status
Note that these parameters are compositional, i.e. you should be able to browse by category and price, not
category or price
 Ability to view all relevant information pertaining to a single auction. This should be displayed on an individual
webpage, and it should display all of the information in the database pertaining to that particular item. This
page should be linked to from the search results. In particular, this page should include:
  – all item attributes (title, description, etc.)
  – categories of the item
  – the auction’s open/closed status
  – the auction’s bids. You should also display all relevant information for each bid, including
 the name of the bidder
 the time of the bid
 the price of the bid
  – if the auction is closed, it should display the winner of the auction (if a winner exists)

Furthermore, your AuctionBase system must support “realistic” bidding behavior. For example, it will not accept
bids that are less than or equal to the current highest bid, bids on closed auctions, or bids from users that don’t exist.
Also, as specified above, a bid at the buy price will close the auction. 

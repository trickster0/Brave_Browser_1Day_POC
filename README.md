# Brave_Browser_1Day_POC
This is a crash for Brave Browser I found in New Years Eve, used to be a 0day when I found it

## How it works
This is a remote crash that triggers in brave browser due to how the rss XML parsing happens by reading an item's title that contains the < (less than) character.  

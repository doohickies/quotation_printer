# quotation_printer
Using an arduino-based Adafruit internet of things thermal printer to print periodic random quotations from QuotationsPage.com.

A few years ago I bought and assembled an Arduino-based internet of things thermal printer kit from Adafruit (see http://www.adafruit.com/products/717). That printer is now discontinued, having been replaced by others with more robust controllers, but it's still a useful little machine.

For quite a while I ran Adafruit's Gutenbird sketch, which printed in real time the tweets of a specified Twitterer. A couple of years ago, however, Twitter changed its security and authentication protocols, and the new system outstripped the abilities of the older Arduino Uno built into the printer. So for a long while the printer sat unused in a drawer next to about 50 rolls of thermal printer paper that I had earlier ordered during a burst of technological enthusiasm.

I recently began to consider how to repurpose this neat little printer (and use 50 rolls of thermal paper). A few ideas came to mind, but I finally settled on using it as a quotation printer. QuotationsPage.com is a terrific site that holds a collection of tens of thousands of interesting quotations on all manner of subjects from all manner of sources. The sketch included here randomly picks one of the quotations on that site and prints it to the printer at a random interval of between two and four hours. I find that making the interval longer gives me a greater opportunity to consider each quotation before the next one comes along. It also avoids putting an undue burden on the QuotationsPage servers.

Feel free to take this sketch and work with it as you will. If you create your own version, I only ask that you give appropriate credit to this project and, if your version collects data from QuotationsPage.com, to that site. 

A work in progress. I continue to tinker with various aspects of the program as time permits and may post modified versions at some point.

A note on power supplies: when I fired up the thermal printer recently, I noticed that the original power supply (5V, 2A) was just not supplying enough current, making the printer output faint and irregular. I replaced that supply with a new one with higher amperage (5V, 3A) and the printer works very well now.

Thanks to Adafruit for making this great kit and to QuotationsPage.com for use of their great quotations collection.

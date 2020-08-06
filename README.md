# Getting_to_Philosophy

Clicking on the first link in the main body of a Wikipedia article and repeating the process for subsequent articles would usually lead to the article Philosophy.

The program should receive a Wikipedia link as an input, go to another normal link and repeat this process until either Philosophy page is reached, or we are in an article without any outgoing Wikilinks, or stuck in a loop.
 
A "normal link" is a link from the main page article, not in a box, is blue (red is for non-existing articles), not in parentheses, not italic and not a footnote. You don't have to check style tables or other fancy things, it is enough that the script works with the current Wikipedia style (for example you can use 'class' attribute in Wikipedia tags). For easy validation, please print all visited links to the standard output.
 
0.5 second timeout between queries to avoid heavy load on Wikipedia (sleep function from time module).
 
I used https://en.wikipedia.org/wiki/Special:Random to check this hypothesis.


For more information about it visit: https://en.wikipedia.org/wiki/Wikipedia:Getting_to_Philosophy

# Getting_to_Philosophy
<a href="https://ibb.co/25HNXSk"><img src="https://i.ibb.co/0QvtPKG/Output-Snapshot.png" alt="Output-Snapshot" border="0"></a>

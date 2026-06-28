# Triki  
Text Retrieval - Wikipedia  
  
A tool for finding text across a list of Wikipedia articles.  
  
<b>Highlights:</b>  
• Doesn't require <a href="https://meta.wikimedia.org/wiki/Data_dumps/Dumps_sizes_and_growth">31 terabytes of disk space</a>.  
• Highly readable, colorized output for easy multi-article skimming.  
• Search for keywords or regex.  
• Optional multiprocess searching (but please be nice to Wikipedia).  
  
<b>Installation:</b>  
Run `sudo apt-get install rg sd pup -y`  
  
<b>Usage:</b>  
triki [input] [search] (processes)  
  
[input] can be a file or a Wikipedia URL.  
Triki will use the URLs found at [input].  
  
Options:  
-c - Compact. Doesn't add newlines between hits.  
-i - Include input URL at the top of the search list.  
-n - No sort. Search URLs in the order they are found.  
-q - Quiet. Doesn't print article titles.  
-r - Reassemble quotes with multiple sentences.  
-s - Single URL. Searches only the provided URL.  
  
Examples:  
![Pic 1](examples/triki.png)

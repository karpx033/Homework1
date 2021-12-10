# Homework1

Commented out the footer on the html after clarification that the footer did not need to be shown as it is not in the reference image
Commented out the class changes to .benefit(-lead/-brand/-cost) img. on the css file, picking up where I left off yesterday. Those attributes got moved to a the 'benefits' class
Commented out the assiating classes on the html
Commented out "social-media-marketing" class on the html
Commented out class="social-media-marketing"
Commented out <div id="social-media-marketing"> as that was also unnecessary
Commented out <div id="online-reputation-management"> as that was also unnecessary
Commented out <div class="search-engine-optimization"> as it was no longer used in css
Commented out <div class="header"> as it was unnecessary
Commented out ".sidebar" and ".sidebar img" as they were no longer being used.
Double checked that both the html and css files were now only using the classes "seo, hero, content, float-left, float-right, and benefits" and that all were responsible for doing something
Removed then readded class .blurb after the page broke. Investigating issue there.
Found .blurb using the inspect tool on the browser. <div id="search-engine-optimization" class="blurb"> seems to be remaining, but I am unsure why as it is not in my html file. The page needs .blurb to function correctly so I'll leave it as is.
That finishes confirming that all the classes in the css file are being used.
Moved .blurb for readability reasons

Attempt as summarizing yesterday's edit's before clarification that they were supposed to mainly be on the README:
Added a color: #ffffff; as a global attribute as it was repeatedly used. 
Commented out the now additional color: #ffffff; attributes within the file.
Changed the ".header" class in css to "header" as I knew that one was a basic html tag and could be referenced cleaner.
Commented out "header h1" to just "h1" in the css file
Commented out "header h1 .seo" and moved to ".seo" in the css file
Commented out "header div" and reduced it down to a single "nav" edit
Commented out "header div ul" and reduced it to just "ul" as "ul" is a basic html tag
Commented out "header div ul li" and reduced it to just "li" as "li" is a basic html tag
Changed a "div" to a footer tag, then commenmted it out as there was discrepancy as to whether it should be removed or not.
Reduced the grey lettering into ".seo"
Added an "h2" css modifier
Commented out large secions of ".benefit-lead, .benefit-brand, .benefit-cost, h3, img, .search-engine-optimization, .online-reputation-management, .social-media-marketing" as they all had parent tags or classes that could be used instead for a cleaner looking file.
On the html side, also commented out the associating ".benefit-lead, .benefit-brand, .benefit-cost, h3, img, .search-engine-optimization, .online-reputation-management, .social-media-marketing" class identifiers as they were no longer needed.

Found the blurb class upon closing and reloading. Suspecting that I was editing an html file that I wasn't viewing in my browser
Readded the ".sidebar" class that I made after noticing the right side box wasn't loading properly.
Changed website title

Separate Content, Style, and Functionality

In making webpages, even simple ones, Javascript and CSS are often pulled out of the html and linked as separate files. A common set of files:
 * index.html
 * style.css
 * main.js

Some tools, like codepen and jsfiddle, assume this general arrangement. The layout of their editors offer quick access to these basic components of a webpage, without requiring users to manually create the links. Instead, users can write freely in buckets for html, CSS, and JS.  Users can change the size of these buckets or collapse them as needed. 

![Makery Buckets](Mockups/makery-layout-buckets.png?raw=true)

Advanced editors enable us to link and view a range of files, collecting them together in a project. Files in the project can be viewed and opened from a sidebar file tree. Any connections between the files must be manually linked within the html or code. 

![Makery Filetree](Mockups/makery-layout-filetree.png?raw=true)

Some editors present files as tabs. For a basic editor, these work like the buckets in Codepen. For an advanced editor, the tabs only represent the open files.

![Makery Tabs](Mockups/makery-layout-tabs.png?raw=true)

In Appmaker and Mobile Webmaker, pieces of code are represented as visual components or bricks. A users drops a drop-down brick, for example, into to their application. This brick is a package of html, JS, and CSS. A user can edit the brick to change its content, style, or function. 

![Makery Bricks](Mockups/makery-layout-bricks.png?raw=true)

A hybrid between bricks and buckets might work well for new authors of html pages. It could reveal the basic structure of a webpage, but simplify the view by turning linked resources into prominent buttons. A user would open a modal to edit the linked CSS or JS. 

![Makery Bricks](Mockups/makery-layout-links.png?raw=true)

###2016-1-19
####landing page
- adjust line height of body text for better readablilty based on [pearsonified] (http://www.pearsonified.com/typography/); now 16pt. font with 25pt spacing
- tablet view
  - move file list and keywords to the bottom of the page, with metrics and license b/c the previous split felt arbitrary.
  - move download buttons to just below bibliographic info
- mobile view
  - collapse the 4 boxes into a single column at the bottom of the page
  - move download buttons between version history and boxes; downloading is likely to be much less important than reading on phones
  - put update button at top-left to make it prominent, but out-of-the-way for right-handed scrolling.

####multi-page
  - make ORCIDs link-blue to indicate that they can be clicked on to open the author's profile; displaying full address seems unnecessary and cluttered.

####homepage
  - add publishing campus to recent datasets
  
###2016-1-26

####SERP 
desk / tablet view
- 2 versions to remove blue "control bar," which no longer makes sense after moving the search box into the global header
    1. convert "show/hide map" and "show/hide" details to secondary buttons, drop to be in line with result counts. This preserves the current layout, more or less.
    2. convert "show/hide map" to a secondary button and place in left column above facet selection boxes; convert "show/hide" details to a blue-text link-style button and right-justify in line with result counts. All the controls that affect what results are displayed (except the search box, which is priviledged in its standard location) are now stacked in the left column. The detail view switch is associated with the results, deemphasized, and in its own format, reflecting its unique function in controlling _how_ rather than _what_ is displayed.
- map is still drop-down; important to allow back-and-forth between map and results. could try to fit it in some other way (on the side?) but it's important to have both active at the same time.
- changed "show map" to "browse by location" on browse page, "refine by location" on SERP page. Tells the user explictily what they can do with the map. (JC found it confusing)
- switched "selected facets" to a horizontal repeater to minimize the amount of movment of the rest of the page when users select and deselect facets.

mobile view
- map is now a modal window with 'cancel' and 'limit results' buttons; avoids moving the rest of the content when the map is opened and gives users the maximum amount of screen to work with.
- moved selected facets below selection boxes so that the controls won't jump every time a facet is selected or deselected. split into 2 facets / column to reduce the distance that results are pushed.
- browse map is now a button above the facet selection boxes rather than a box of its own.


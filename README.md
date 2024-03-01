# Crash Course: Chrome Extension
Date: 2/29/24

Workshop ran through ACM at UCSD in which we created a chrome extension capable of converting a lecture podcast's transcript into summarized notes through Google Gemini. The summarized notes are then saved onto a Notion database, which stores all the notes for the user's future purposes.

To use the chrome extension along with Media Gallery podcasts, you must open a certain version of chrome with limited security, since Media Gallery protects against chrome extensions. To do so, use Windows + R and open up `chrome.exe --user-data-dir="C://Chrome dev session" --disable-web-security`. 

Once open, transport the extension onto the new version of chrome and run it on the chosen podcast by clicking "Get Transcript". If the summarized transcript appears in the extension's textbox, the action was successful and the notes should be saved on the Notion database. 

Here is a link to the slides from the day of the workshop: [Advanced Chrome Extensions](https://docs.google.com/presentation/d/1Me8eYqrn_RK96KC-VBJ61T5zIbHWdWuZYHTy2Pq1wr0/edit#slide=id.g2be3d9f06bb_0_3)

# Integrating The YouTube API into a functioning HTML page

To run the page and make the Youtube API connection work
1. install python
2. cd into the folder
3. run this command : py -m http.server 8000
4. Go to 127.0.0.1:8000


Description of how I did this:
I used the YouTube data API v3 to pull the YouTube TED latest 5 videos, I then used a simple loop to give the iframe and h2 tags the correct information.

I chose to only have 5 videos on this page to show that I could utilise the YouTube API correctly, because of this I didn't loop the creation of the code for the html, if I was going to output more videos onto the page I would use JS to make this.

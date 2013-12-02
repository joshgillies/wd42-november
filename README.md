# Node Knocked Out

The outline below was used to draft my #wd42 talk as given on November 27th 2013.

The final presentation can be found here: http://slid.es/joshgillies/node-knocked-out

_(questions encouraged during this talk)_
	
## Slide one:

Open with an overview of the event
 - Node knockout is an annual global hackathon based around Node.js as a technology.
 - 48hrs to develop a product using Node.js at its core (show time lapse here).
 - 400 teams in total.

## Slide two:

Details of the app
 - The overarching idea to the app (Sentiment, new take on news reader) (Show video here!).
 - Sentiment score based on sentiment analysis (ala npm module)
 - Shares define the awesomeness of an article, which is then used in the presentation/layout of news tiles.

## Slide Three:

Detail the development processes employed
 - Discuss our use of Agile/Kanban approach to develop the ideas into tasks (Trello board)
 - The use of Agile “stories” to describe implementation details without directly influencing the development approach.
 - Rapid feedback loops via regular (~hourly) meetings

## Slide four:

Frontend technologies:
 - Sass for hardcore stylesheets - Dom you can likely talk to this some more.
 - 3d effect of the plane achieved using CSS3!
 - jQuery for DOM manipulation, AJAX, etc...

## Side five:

Backend technologies:
 - Express for bootstrapping a HTTP server in Node.js
 - xml2js for parsing RSS feeds in node
 - Readability for processing the xml stream
 - Sentimental for sentiment analysis on content of the Readability processed data
 - Redis for in memory NoSQL data store == fast.

## Slide six:

Problems:
- Integration issues, relating to getting the working API done before close of event.
- Cross browser issues relating to feature detection?

## Slide seven:	

Outcome of our app against the rest:
 - 32rd over all (from 160 teams!)
 - 4th for Design.



# Hill_TV_Maze
Front End Developer Project
Using the API provided by TVMAZE, please create a LANDING PAGE for your favorite
television show (Note: if you do not have a favorite television show, just choose one).
The following rules apply:
1. There must be at least one call to the API in order to fetch the relevant
information about the show
2. Please use Create React App or Vanilla Javascript
3. Consider HTML5 Semantics when structuring your page (Avoid <div> overload)
4. Make sure the Site is Responsive
5. Most of all have fun and be CREATIVE
Submission requirements:
1. Please provide a link to the repo
2. Max turnaround for the completed project is 3 days from receipt of this document
a. Note: this task can be completed in 3 - 5 hours, but you are free to spend
as much time as you like
3. OPTIONAL: Provide a link to the live site
Technical starting point:
1. API Website: http://www.tvmaze.com/api
2. Create React App: https://create-react-app.dev/docs/getting-started/

3. Semantic Markup: https://developer.mozilla.org/en-
US/docs/Web/Guide/HTML/Using_HTML_sections_and_outlines

Initial thoughts to help get started:
1. Make a call to fetch the initial details for the show, example provided for Seinfeld
a. http://api.tvmaze.com/singlesearch/shows?q=seinfeld
2. From the response grab images and relevant details to create a page hero
3. Perhaps use the show id to make a secondary API call in order to fetch episodes
a. http://api.tvmaze.com/shows/530/episodes

# As Coronavirus Spreads Globally, Some Manufacturers Thrive While Others Dive

### The global spread of coronavirus has left U.S. manufacturers standing in between a widening supply and demand fault line. The latest sign that companies are beginning to run into trouble. Of the Fortune 1000 companies surveyed by the American Chamber of Commerce Shanghai, 94% are experiencing disruption of their supply chain due to COVID-19. As a result, impacted companies will not reach their 2020 tier annual sales target and the effects will be seen in layoffs and reduced wages. 


Answers to following questions:

- Why this story is relevant ("So what?) and why now?: With the global spread of COVID-19, early signs of economic impact will be seen in manufacturing jobs. The industry relies heavily on global supply chain and therefore will be one of the hardest hit sectors in the U.S. 
- What is the single question your story tries to answer?: Why and how are these companies being impacted and when will it begin to be reflected in jobs. 
- Why will this story resonate with your audience?: The jobless claim that was released on March 26th indicates that everyday Americans will be heavily impacted by the economic consequences of this pandemic. 

What else has been done on this topic (provide links)? How is your angle different or fresh?

- [Coronavirus Pushes Factories to Stagger Shifts, Separate Workers (WSJ)](https://www.wsj.com/articles/u-s-factories-work-around-coronavirus-impact-11584447707)
- [Chinese manufacturing hits record low amid coronavirus outbreak (BBC)](https://www.bbc.com/news/business-51689178)
- [US companies tell Fed coronavirus has hit manufacturing (FT)](https://www.ft.com/content/61b4bc60-5e4b-11ea-b0ab-339c2307bcd4)

Describe how and where you found the data with links. 
The data located from FRED was "All employeees" and "Overtime hours" https://fred.stlouisfed.org/series/CES3000000004
The data located from the U.S. Bureau of Labor Statistics was for "Jobless Claims/Employment/Unemployment" (Quarterly) https://www.bls.gov/bls/newsrels.htm#OEUS

Put the raw data (csv, xls, pdf) in a folder called `data` in this folder, and provide a [link](https://docs.google.com/spreadsheets/d/1IdeVJv7SpbKwD1jMfOlXvIpx-ZwitU-3Y6c4iLqGu7c/edit#gid=1257216346) to your Google Sheet. Show your data work in this Google Sheet – this could be sorting, aggregating, filtering, pivot tables, vlookups, etc.

Write up at least one or up to three findings from your analysis based on the data you found.

- Finding 1
- Finding 2
- Finding 3

Who are some potential human sources you could reach out to for more info?

What is the maximum (best) story possible? What's the minimum (fallback) story if your hypothesis doesn't prove out?

## How to publish and submit your project

1. Make sure you have navigated to your `data-journalism` folder with your terminal first. Clone a fresh copy of this template.

   ```
   git clone git@github.com:JOUR73351/google-sheets-project.git NAME-OF-YOUR-PROJECT-HERE
   ```

2. Remove my git tracking from the project

   ```
   rm -rf .git
   ```

3. Create a new repository on GitHub called `NAME-OF-YOUR-PROJECT-HERE` with the following settings.
   <br>
   <img src="assets/newrepo.png" width="500">

4. Run these git commands to initialize the repo. Make sure you've checked `ssh`.

   ```
   git init
   git add -A
   git commit -m "first commit"
   git remote add origin git@github.com:YOUR-USERNAME-HERE/YOUR-REPO-HERE.git
   git push -u origin master
   ```

5. Write your pitch in `README.md`.

6. Write your story in and add your assets and charts to `index.html`. Feel free to play around with and change the styles in `style.css`, but you are not required to. Delete the code that you don't need for your story. The story itself should be no less than 150 words and include at least one chart from Datawrapper. You can embed a Datawrapper chart in your story by copying the embed code into your html as I have done in `index.html.`
   <br>
   <img src="assets/datawrapper.png" width="500">

7. You can preview a local version of your story by running a python server.

   ```
   python -m SimpleHTTPServer 8000
   ```

   Then, navigate to `http://localhost:8000` in your browser.

8. To save a version of your story on GitHub, run the following git commands.

   ```
   git add -A
   git commit -m "YOUR-COMMIT-MESSAGE-HERE"
   git push
   ```

9. To publish, go to the settings of your GitHub repo, scroll down to GitHub Pages, and configure the source to the master branch.
   ![GitHub Pages](assets/ghpages.png)

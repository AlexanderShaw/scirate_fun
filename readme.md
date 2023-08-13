<h1> Project Outline: </h1>

Goal:  
Predict what quantum computing papers that come out on arXiv are likely worth reading based on input features. Put it all on a heroku app where you can plug in a new paper (w/o any scitations or anything) and get a "whether you should read it" rating. 

<h2> Input features:   </h2>

Author info:  
- Number of scitations on recent papers 
- Number of citations on recent papers (5 years :heavy_check_mark:)
- Number of total scitations / citations :heavy_check_mark:
- Collaborators recent scitations
- Collaborators recent citations
- Collaborators number of total scitations / citations
- Number of papers published :heavy_check_mark:
- h-index :heavy_check_mark:

Paper info:
- Abstract :heavy_check_mark:
- Papers cited :heavy_check_mark:

<h2> Training features </h2>

- Number of scitations on the paper :heavy_check_mark:
- Number of citations on the paper :heavy_check_mark:
- Who scited it :heavy_check_mark:

<h2> Output: </h2>

A recommended read score.

<h2> Workflow </h2>

1. gather raw data
2. engineer relevant features
3. create training and test datasets
4. choose models
5. train and validate models
6. compare models on test sets
7. create heroku dash app
8. put model on app


<h1> Notes </h1>

<h2> Gather raw data </h2>

<h2> Stats questions to answer </h2>
- Do scitations and citations vary for a given paper? Why?
- How much of a well-scited paper changes from arxiv to publish?


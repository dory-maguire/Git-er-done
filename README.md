# Git-er-done
An analysis of most starred Github repositories

## Topics: 
Top languages in highest rated github repositories
Top libraries imported in highest rated github repositories
Correlation between languages and amount of stars
Average commits in highest rated github repositories
in highest rated github repositories

## Steps
Download starred repositories data 
https://data.world/chasewillden/top-starred-open-source-projects-on-github/workspace/file?filename=TopStaredRepositories.csv

1. Put csv into postgres table

    COPY starredrepos FROM '<file>';

2. Create a function to download the repos locally:

    git clone <repo>

3. Create functions to insert filename and library info to database tables.

4. Create analyses and visualizations.
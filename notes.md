# Deployment Notes

# Jargon

Single Responsibility Principle:
    - a specific unit of work should do only one thing, and it should do that one thing really well. (only one reason to change)

# Deployment

- extract configuration into environment variables
- setup continuous deployment from Github to Heroku
    - commit and push to Github will automatically update to Heroku

# To Switch Remotes (if you accidentally coded in the wrong repo or did not forlk)
    - 'git remote set-url origin url to new empty repo on github'
    - 'git remote -v' to see where the remote points
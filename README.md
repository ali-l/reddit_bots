### Monitors a subreddit and replies to comments that contain any of the specified keywords

Environment variables

- Build time 
    
    
    PRAWINI = Base64 string of praw.ini file (.gitlab-ci.yml)
    
    SUBREDDIT = Name of subreddit to monitor (Dockerfile)

Run tests

    pytest

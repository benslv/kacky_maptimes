# kacky_maptimes
Webtool for KR2 - Check which maps are currently played and when a map will be played again.

# How to use
Index page shows all data relevant for normal users.
There is a management site in http://url/manage is visible publicly, but to save modifications it is required to enter the password from config.yaml.

# Warnings
1. This is in beta and untested. Shown results might be bs.
2. Deployment options are borked currently. Dockerfile does build a container, but I hate Docker, Docker hates me, did not get it connected wo network - and Flask config doesn't work either, might require some hardcoding of values. Might fix when I was able to test that tool actually works.

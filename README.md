# An template for Github so you can automate your build and release using CI / CD.

## This template can be modified for any technology basically it just:
    
    i. If code is pushed to this branch checks if it is tagged. If tagged does it exists already or not.

    ii. After verification it installs all the deps and caches them for next times.

    iii. Then creates an artifact stores it and saves it to the releases with latest tag.

    iv. Also creates a hash.txt for your build.

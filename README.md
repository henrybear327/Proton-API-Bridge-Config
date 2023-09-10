# Proton-API-Bridge-Config

This repo serves as the configurtion API for the proton bridge. A single json response will be served everytime the static page is requested.

The main idea behind this API is to provide the minimum [Proton API bridge](https://github.com/henrybear327/Proton-API-Bridge) version that we would allowed to be used. As we are reverse engineering the project, we would like to design a kill-switch feature into the project so we can force the user to not use certain versions that is known to cause problem.

# Changelog

- Initial commit
    - setting up the repo, json response (production and test)
    - minimun required version opf bridge is now 1.0.0
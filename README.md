# Replace github-release workflow


## ~~Update main first~~
* ~~Create change to ci.yml in main~~
* Exp: no release build: Confirmed


## Create major release branch 
* ~~Create a release-1.0 branch and pr~~
* ~~Add to pr commits~~
* ~~Merge the pr~~
* Exp: pre and release build: Confirmed

## Merge release branch to main
* Create a release-1.0 branch and pr
* Merge the pr
* Exp: no release build

## Create minorrelease branch 
* ~~Create a release-1.1 branch and pr~~
* ~~Add to pr commits~~
* Merge the pr
* Exp: pre and release build: Confirmed

## Merge release branch to main
* Create a release-1.0 branch and pr
* Merge the pr
* Exp: no release build

## Create non release branch 
* Create a dev branch, dev2 branch and pr from dev2 -> dev
* Merge the pr
* Exp: No release build





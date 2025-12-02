# wloocc-website

The official website for the University of Waterloo Climbing Club. 

# Hosting Details
We are currently hosting on the [uwaterloo CSC servers](https://wiki.csclub.uwaterloo.ca/Club_Hosting).

# Install

We include the [Hugo Paper theme](https://github.com/nanxiaobei/hugo-paper) as a submodule. To install:

``` shell
git clone --recurse-submodules https://github.com/wloocc/wloocc-website.git
```

# Updating The Website
## Requirements
Currently, only members with access to the club account on the CSC servers can update the website. To get access, am email request must be sent to CSC syscom from the wloocc club email (see [here](https://wiki.csclub.uwaterloo.ca/Club_Hosting#Getting_Hosted) for more details).

## Steps
To update the site:
- log into the CSC servers
- run the following:

```bash
become_club climbingclub
cd
bash update.sh
```

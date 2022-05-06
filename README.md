# This is the production branch!
Please do not push to it! Only push changes to main. Once they are reviewed they will manually have to be transferred to this branch. It then gets synced with the public content.


# coci_hackathon_website

Short overview page for the CoCi Hackathon 2022.

### How to customize
This site runs fully statically and is hosted in the most simple html-css-js stack possible.

For basic customizability a large configmap gets parsed into a html by a python script.

### Usage
`python main.py templates out values.yaml`
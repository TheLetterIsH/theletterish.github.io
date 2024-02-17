---
title: {{ replace .File.ContentBaseName "-" " " | title }} # Name of the project
year: {{ now.Format "2006" }} # Year of creation
type: # Game / Interaction / Website / Web App / Mobile App
description: # Description of the project
cover: 
    image: # images/path
    alt: # image alternative text
posts: # Link to posts / tags / series related to the project
source: # Link to source code of the project
demo: # Link to a demo for the project
weight: # Priority of the project in the list
---
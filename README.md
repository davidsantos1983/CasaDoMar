# CasaDoMar

## Feel free to keep adding relevant information to this file

## Basic Collaboration Workflow
- Clone the repository '''git clone https://github.com/davidsantos1983/CasaDoMar.git'''
- Open a new branch to implement the feature with the following naming convention '''git checkout -b CASADOMAR/feature-i-am-implementing'''
- Add and commit your work to the local branch '''git add .''' '''git commit -m "implemented something in this commit"'''
- Make sure your working branch is always ahed of main:
  - '''git checkout main'''
  - '''git pull origin main'''
  - '''git checkout CASADOMAR/feature-i-am-implementing'''
  - '''git rebase main'''
- Push to the respective remote branch '''git push -f origin CASADOMAR/feature-i-am-implementing'''
- Open a Pull Request on github UI and wait for approval to merge the code into the main branch.

## What is this repo about?
- This is a website to promote a wonderful guesthouse located in Sesimbra.
  
## Design Ideas
- Guides for desing and inspiration found here https://codingheroes.io/resources/
1. https://www.awwwards.com/sites/casa-di-legna
2. https://www.awwwards.com/sites/alta-house-begur-spain
3. https://land-book.com/websites/6462-voici-airbnb-plus
   
## Color Palette
- The colors to be used in the design should be added here
  1. https://www.colorhunt.co/palette/ecf9fffffbebffe7ccf8cba6
  2. https://www.colorhunt.co/palette/dbd0c0faeee0f9e4c8f9cf93

## Contents
- Any pictures or any other contents related to the website theme should be added to the resources folder.
- Once an image is selected to be used in the webpage it should be moved to the proper folder inside the '''img''' folder. For example, we decide to have a caroussel with 5 pictures, these pics should be renamed to something that describes their usage and moved to a folder called '''caroussel''' inside the '''img''' folder.

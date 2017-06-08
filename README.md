# Daily Dinosaur
When asked, Daily Dinosaur will randomly select a dinosaur from a list of over 1000 species and provide a brief description.
https://www.hackster.io/BrianCottrell/daily-dinosaur-e7eab9

## Background
As someone who grew up with an interest in paleontology, I find myself periodically looking to expand my knowledge about dinosaurs. However, most resources are overwhelming and include endless lists of dinosaur types and descriptions, which are far too extensive to take in all at once. I created Daily Dinosaur to address this issue by breaking down the list of known dinosaur species, and presenting them one at a time with a brief description, and most importantly, the pronunciation; a challenge that anyone with experience with dinosaur names has likely experienced.

## Description
When asked, Daily Dinosaur will randomly select a dinosaur from a list of over 1000 species and provide a brief description.

## Example Phrases
Alexa Open Daily Dinosaur

Alexa Ask Daily Dinosaur Tell me about a dinosaur

Alexa Ask Daily Dinosaur To Give me a dinosaur


## How I Built it
I built Daily Dinosaur using the Alexa Skills Kit, starting with the simple fact app template. Since I wanted to include a very extensive selection of dinosaurs, but didn't want to spend the countless hours needed to enter information about each one individually. I was able to find a list of over 1000 dinosaur names compiled by Wikipedia that I could copy into my application. The list, however, didn't include any sort of description, so I used the HP IDOL OnDemand API to return a summary based on search of a term. By passing a dinosaur name from the list as a search term, and modifying the response, I was able to return a suitable description for Alexa to provide to the user.

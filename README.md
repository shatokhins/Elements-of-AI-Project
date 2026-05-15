# AI Fridge Scanner

Final project for the Building AI course

## Summary

This is a scanner app that uses AI to analyse an image of your fridge and forms meals based on those ingredients. The purpose of my project is to save time on meal preparation and reduce household waste. The AI model will need to be trained on a database of images of grocery items in order to correctly idetify the items. There will also need to be a second database of all possible meals, possible taken from the internet by searching it.


## Background

My project will aim to solve the problem of food waste and nutrition for people who may not have access to lots of time or money to spend on food. This is a very common problem and a growing one in the world that we live in as the cost of living is increaseing as very fast rates. My personal motivation for this is that I want to improve the world with AI and Ithink that this is a small but sure step towards this. Personally, I would use this to help me make better meals in a shorter time period as I don't always have the time. I also find that I forget about items in my fridge and I don't always know what to do with every food item.

## How is it used?

The solution will work by allowing the user to use the camera function on the user's phone. The application will analyse the image and use a CNN to identify the items in the picture. This will be done by training the AI first on a large database of pictures of food items that will be taken from supermarket websites. After identifying the items, the model will search the internet for recipies that contain those ingredients and possibly rank the meals in calorie or by chosen nutrients.

## Data sources and AI methods

The data would be collected from supermarket websites for images which could be collected by using a webscrapper. This would then train the AI model. Other information could come from the general internet like searching for recipies.

## Challenges

Objects can be hard to identify becasue of poor camera quality or obstructions in the photo. There might also be very similar looking objects so the AI model might mistake one object for anonother and provide inaccurate results. A solution could then be an option to retake if the identified object is not correct or allow the user to manualy input the product that they want to include in the list. The application might not be able to account for how much of each food there is in weight and the recipies provided might not be accurte. A solution to this problem would be to manually input the amounts, however this could be cumbersome.

## What next?

The project will need to be broken down into smaller tasks so that a plan could be devised for building the application. Then I would need to implement the AI model after it is developed into the mobile app. Then a prototype would be created.

## Acknowledgments

Building AI course

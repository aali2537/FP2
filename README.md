# Final Project Assignment 2: Explore One More! (FP2) 
Alex Li

### My Library: browser/external

### Narrative:
For my second exploration project, I decided to take a look at the browser library. For my code, all I have to show is a very simplistic program that prompts the user to update their browser preference if they are in a unix environment and then opens that preferred browser and sends it to the website reddit. I had also tried to use the built in racket browser, however I could not understand how to properly send the procedure arguments, sepecifically the hyper text datatype and thus was unable to play around with it.

### Code:
```
#lang racket
(require browser/external)
    (update-browser-preference #f)
    (send-url "www.reddit.com")
```

### Output:
![Preference Page](https://cloud.githubusercontent.com/assets/11621186/6911940/0d028266-d736-11e4-8c0e-0d86ec84c302.jpg)
 ![Browser Opened from code](https://cloud.githubusercontent.com/assets/11621186/6912061/16a9d1aa-d738-11e4-842a-8826242bffd3.jpg)


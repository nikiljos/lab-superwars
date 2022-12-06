# Lab | Superwars Stage 2
[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.nikjos.in/open?repo=nikiljos/lab-superwars)

Remember Superwars stage 1? However, here is a quick recap of things.

Dustin and Lucus are best friends. They spend their weekends watching superhero series and playing superhero games. One Friday at school Mr.Hooper, their computer science faculty taught them HTML, CSS, and JavaScript. Dustin & Lucus realised they could build super cool super hero stuff using their knowledge. 

The subsequent weekend, they decided to do it. Lucus and Dustin are now all set to build something super cool.

Lucus always loves protagonists like most of us. But Dustin is quite crazy, he likes antagonists. So they decided to collect a bunch of their favorite Super Heroes and Super Villains names along with their pictures. Did they tell you about the game that they are gonna build? 

Okay, let us explain. They are going to facilitate the ultimate war between Super Heroes and Super Villains. As they are new to these technologies, they need a **Kalvian** to help them build this game.

## What should you do

Here is the boilerplate [link](https://github.com/Kalvium-Program/lab-superwars-stage-2) of the lab. Fork the project to your GitHub account, clone the repo to your local machine and get started with the lab.

> **Note:** Before starting this lab, migrate the HTML and CSS code from the lab on Superwars stage 1's code to this lab


## Starter code

The `src/app.js` contains an array of 20 Super Heroes and Super-Villains. We are talking about the array of 20 _strings_ containing each Super Heroes and Super-Villains names. Here is one example of how the data is displayed:

```javascript
[
    "Spiderman"
]
```

### Tests

Open the `SpecRunner.html` file on your browser and start coding to pass the test. Remember to focus on one test at a time and read carefully the instructions to understand what you have to do.

### Progression 1: More players, more fun

Dustin and Lucus wants to create players.In `initPlayers()`, loop through passed constant and  create Objects, such that each player contains name, strength, image url and type.  
* Use default `strength` as any number.  
* `image` can be sequential i.e. "images/super-"+(i+1)+".png"  
* `type` of player can alternating between hero and villain or your own logic
* It should _return an array_ of player objects.
    ```javascript
    [
        {
            name:"Super Man",
            strength:100,
            image:"images/hero-1.png",
            type:"hero|villain"
        }
    ]
    ```

### Progression 2: Courage is grace

Add your logic in `getRandomStrength()` method, such that it should _return a random strength_ from 1 to 100. The strength is what is gonna decide the winner.

### Progression 3: No player should fall

In `buildPlayers()`, loop through the created JSON objects and accumulate HTML template as below and _return HTML element_.
 ```JS
<div class="player">
    <img src="${players[i].image}">
    <div class="name">${players[i].name}</div>
    <div class="strength">${players[i].strength}</div>
</div>
```

## Expected Output

![Superwars](doc/superwars-basic1.png)
![Superwars](doc/superwars-basic2.png)

## How To Submit
Host your completed lab project in GitHub and submit your project repository link in this [form](https://docs.google.com/forms/d/1FsIKaMGG8g_xISwHg0oGVQJpgHCXVRQGSQmpytu-b_o/viewform?usp=pp_url&entry.1483932328=CSK101-M2-L74.1).


Happy Coding ❤️

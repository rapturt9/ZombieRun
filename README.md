## Inspiration

I noticed that so many people including myself **drastically reduced our levels of physical exercise** due to the COVID-19 lockdown, so I wanted to make a hack that improved our health through **motivating ourselves** to do **physical exercise**.

## What it does

A _zombie_ is generated on google maps and follows you. When you are running fast, the distance between you and the zombie is great, however when you are walking, the distance is short. When the distance is short enough, you get caught and are directed to a game over screen, where you can see the amount of time you lasted. Moreover, you get a notification to your phone that the zombie ate you. The goal of the game is to last **as long as you can** and run as long as you can.

## How I built it

I used vanilla javascript and the _google maps API_. The _google maps API_ uses geolocation to constantly track your location to update it and record it. The zombie goes along your recorded locations and follows your path. When the distance between you and the zombie is short enough, you are directed to the game over screen. Then, I used _IFTTT_ to send the user a notification.

## Challenges I ran into

Testing the program always required me to upload the code to my phone and go outside. Although this helped me get some physical exercise, this made developing the program very time consuming.

## Accomplishments that I'm proud of

I was able to make code that could _encourage people_ to _exercise more_ and _maintain their health_ during this time period.

## What I learned

I know how to better use the google maps API, so whenever I develop applications with it in the future, it would take much less time.

## What's next for Undead Run

I will try to upload the code to my website, but I need to get an SSL certificate to do so because the geolocation only works on secure websites.

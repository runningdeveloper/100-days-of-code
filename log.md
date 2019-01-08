# 100 Days Of Code - Log

### Day 0: January 2, 2019

**Today's Progress**: Setup my website to deploy to S3 via gitlab CI/CD. 

**Thoughts:** Glad the website is deploying automatically now, been on the TODO list for a while. Had most things in place already, just needed to hook up the gitlab ci thing. Struggled with the IAM policy for the s3 bucket, basic read write was not enough, so had to tweak it a few times. I really didn't want to give CI access to all buckets.
I have no real plan for the 100 days, will need to think about this more.

**Links to work:** 
1. [My website](https://runningdeveloper.com)
2. [Satay aws uploader to S3](https://github.com/jameslnewell/satay)
3. [Gitlab ci ref](https://docs.gitlab.com/ee/ci/yaml/README.html)
4. [Blog that helped](http://blog.logicwind.com/auto-deploy-spa-with-aws-s3-and-cloudfront-using-gitlab-ci-cd/)

### Day 1: January 3, 2019

**Today's Progress**: Got a simple LED matrix running with Johnny-Five. 

**Thoughts:** I wanted to play with hardware and I could play with a blue LED matrix board I have lying around. Wanted to stick with javascript so hooked up Johnny-Five to an arduino and got some of the demos for the matrix working. Spent way too long getting Johnny-Five running on the arduino (FYI - its actually very very easy). Will carry on playing tomorrow.

**Links to work:** 
1. [My code](https://github.com/runningdeveloper/ledMatrix)
2. [johnny-five LED](http://johnny-five.io/api/led.matrix/)
3. [johnny-five getting started](https://github.com/rwaldron/johnny-five/wiki/Getting-Started)

### Day 2: January 4, 2019

**Today's Progress**: Added a simple frontend and express server to send characters to the LED matrix. 

**Thoughts:** This was really rough and quick. Added Preact as the frontend because I wanted to check it out. Not very good code but it works. I will improve in the coming days.  

**Links to work:** 
1. [My code](https://github.com/runningdeveloper/ledMatrix)

### Day 3: January 5, 2019

**Today's Progress**: Improved the frontend of the LED matrix and added support to send raw string of LED values. 

**Thoughts:** Got the basics working sending an array of LED values to the backend. Using a basic GET request, I should change to a POST. Lots to do on the frontend to make it more usable.  

**Links to work:** 
1. [My code](https://github.com/runningdeveloper/ledMatrix)

### Day 4: January 6, 2019

**Today's Progress**: Now you can 'draw' on the frontend and send it to the LED matrix. 

**Thoughts:** Yay I can draw now. I do need to improve the dev experience, I need to build the frontend before testing it with the backend and LED matrix connected.  

**Links to work:** 
1. [My code](https://github.com/runningdeveloper/ledMatrix)

### Day 5: January 6, 2019

**Today's Progress**: Added live drawing to the LED Matrix and nodemon to improve my dev experience.

**Thoughts:** Installed nodemon, its really usefull. Played around with the config file to rebuild the frontend on code change (note sure this is the best way). Improved the drawing of the LEDs by drawing all at once. The previous method of doing each LED was very slow.  

**Links to work:** 
1. [My code](https://github.com/runningdeveloper/ledMatrix)

### Day 6: January 7, 2019

**Today's Progress**: Added an animation schedule thing to send frames in a sequence to the LED Matrix. Not quite working yet.

**Thoughts:** Initial version of the animation thing I'm implementing in the browser first. Power cut to the end of working, lol. Couldn't google things. Having a problem building the client side because some Uglify problem, should fix tomorrow.

**Links to work:** 
1. [My code](https://github.com/runningdeveloper/ledMatrix)
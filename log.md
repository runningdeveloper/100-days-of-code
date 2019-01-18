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

### Day 5: January 7, 2019

**Today's Progress**: Added live drawing to the LED Matrix and nodemon to improve my dev experience.

**Thoughts:** Installed nodemon, its really usefull. Played around with the config file to rebuild the frontend on code change (note sure this is the best way). Improved the drawing of the LEDs by drawing all at once. The previous method of doing each LED was very slow.  

**Links to work:** 
1. [My code](https://github.com/runningdeveloper/ledMatrix)

### Day 6: January 8, 2019

**Today's Progress**: Added an animation schedule thing to send frames in a sequence to the LED Matrix. Not quite working yet.

**Thoughts:** Initial version of the animation thing I'm implementing in the browser first. Power cut to the end of working, lol. Couldn't google things. Having a problem building the client side because some Uglify problem, should fix tomorrow.

**Links to work:** 
1. [My code](https://github.com/runningdeveloper/ledMatrix)

### Day 7: January 9, 2019

**Today's Progress**: Improved the animation code.

**Thoughts:** Fixed build problem, didn't do async await so used this - preact-cli-plugin-fast-async. Still need to improve the animation code, not working exactly as I want it to.

**Links to work:** 
1. [My code](https://github.com/runningdeveloper/ledMatrix)

### Day 8: January 10, 2019

**Today's Progress**: Finished the animation feature.

**Thoughts:** Struggled with copying animation frames, should be cloning objects. Couldn't understand why my animation wasn't working in some circumstances. Also not sure about my implementation of the looping, seems a bit complex. 

**Links to work:** 
1. [My code](https://github.com/runningdeveloper/ledMatrix)

### Day 9: January 11, 2019

**Today's Progress**: More additions to the animation feature, shifting animation left/right and list of frames so I can delete or move them around.

**Thoughts:** Learnt some more array functions. Schooled myself in some different was to move items around in an array. Spent a long time on a silly feature.

**Links to work:** 
1. [My code](https://github.com/runningdeveloper/ledMatrix)

### Day 10: January 12, 2019

**Today's Progress**: Started trying to make a gatsby plugin for a simple search. 

**Thoughts:** Didn't have the LED stuff with me and would like to take a break from it. Lots of reading. Created an example site and connected the dev plugin to the site. Learnt about `npm link`

**Links to work:** 
1. [Gatsby plugin docs](https://www.gatsbyjs.org/docs/create-transformer-plugin/)

### Day 11: January 13, 2019

**Today's Progress**: Got to grips with some of the Gatsby apis. Don't think my plugin will be usefull.

**Thoughts:** May need a rethink. Might be no need to make a plugin for what I want to do. Today learnt a bit more about plugin creation and some babel setup stuff.

**Links to work:** 
1. [Gatsby plugin docs](https://www.gatsbyjs.org/docs/create-transformer-plugin/)

### Day 12: January 16, 2019

**Today's Progress**: Still playing with Gatsby plugins trying to make my own.

**Thoughts:** Copying a tranformer plugin to try make an stl viewer you can just add your stl 3d print into your markdown and it will show.

**Links to work:** 
1. [Gatsby plugin docs](https://www.gatsbyjs.org/docs/create-transformer-plugin/)

### Day 13: January 17, 2019

**Today's Progress**: Doing some improvements to a friend's website, playing with lazy loading images.

**Thoughts:** Learning a bit more about this laxy load stuff. Also srcset and this perticular website uses uikit which has a lasy load thing (noticed a bit late). Need to play a lot more to understand this fully. Gatsby's image component is so nice, don't even have to think about this stuff.

**Links to work:** 
1. [Uikit image](https://getuikit.com/docs/image)
2. [srcset](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

### Day 14: January 18, 2019

**Today's Progress**: Making a small node function to resize a bunch of images for friend's website.

**Thoughts:** Not a major amount of work. Messed around with Jimp and Sharp. Sharp definitly seems faster. Want to try do the srcset sizes somewhat automatically.

**Links to work:** 
1. [Sharp](https://sharp.pixelplumbing.com/en/stable/)



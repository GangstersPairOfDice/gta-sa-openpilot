# gta-sa-openpilot
self driving in Grand Theft Auto: San Andreas using comma.ai's openpilot

## plan

I am not sure whether i need to train a new net or not.

i have to figure out how get openpilot to hook up to live footage
i also have to figure out how to get it to output key presses

 input:
   - either live gameplay screen
     - since we know a webcam works using openpilot, theoretically we could make a 'simulated' webcame, which just renders whats on the screen instead.
       - i think for lulz we just use a webcam lol
     - or we get gameplay footage from youtube and train new net
 
 system:
   - takes gameplay
   - the neural net predicts what movements to do

 output:
   - key presses to stear car



## notes 

## resources

blog post from comma.ai talking about how to port it to virtual cars and virtual worlds
https://blog.comma.ai/self-driving-car-for-free/#going-beyond

docs for openpilot
https://docs.comma.ai/

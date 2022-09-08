# General description of project
> Aim training platform, where users have to click targets on the screen rapidly.
> 
# Goals of project
> Improve the user's aim over time,

> Improve user's reaction time
# Listing of features
> 1. Crosshair for aim assistance(customisable if possible)

> 2. show what percentile the user is in, in comparison to global data.

> 3. Have multiple modes fo train aim: 
> e.g. Stationary targets,
> moving targets
> targets of varying sizes.

> 4. Provide personalised reports, based on the user's performance.

# External Scanning
> There is this website called Human Benchmark at humanbenchmark.com/tests/aim, which doesn't feature a crosshair function or multiple modes to train aim.

> aimtrainer.io features a crosshair(not customisable) and multiple modes to train aim in.

> If possible I would like to develop this application in 3D, but I would be limited in terms of hardware.

# Listing of Key Use Cases
> eSports professionals who would like to improve their aim so that they can unleash their full potential in First Person Shooters can use this platform.

> Casual use would also improve a person's reaction time, thus improving their reactime to stimuli in the real world.

# Skills that my project requires me to pick up
> I need to learn C# as well as 
> how to use Unity hub
> 

# [Development Log](/devlog.md)
> You will be updating this section regularly
> - Week 5

>   Goals set: Create scene, define player movement.

> Problem encountered: Unity wass extremely slow, hanged every few minutes.   

> Goals for next week: Create target system(Target spawning, target destruction)



> - Week 6

>   Goals set: Come up with the target system(Spawning and destruction of targets)
  
> I needed to get used to C#

> Goals for next week: Implement Crosshair, Introduce colours in scene.
> 
> - Week 7

> I literally didn't do anything this week. I took a break for this week because I couldn't find my file in unity, so i gave up after a while. I wanted to do the crosshair this week, and add in colours in the scene this week, but after some thought, I want the background of the aimtrainer to be not be distracting so it will just be gray. Next week, I intend to implement the crosshair system and include user generated variables, so the user will be able to control the target size and colour


> - Week 8

> Hello! So here are the stuff I have accomplished over the past week:

> 1) Upside -> Implemented a working crosshair! Downside -> Crosshair isnt actually a crosshair, just a dot in the middle of the screen, (as an UI image). I would like the user to be able to change his crosshair as he would like, but I'm presuming that's a bit too ambitious. Instead, I want to have preset variables that the player can choose from, in order to customise his crosshair. -> The UI canvas(the crosshair is an UI image under the UI canvas) is glitching, I'm not so sure why. It's outlined in white, even when not selected. 2) Coming up with user generated variables, as I have come to realise. I need to reference to a lot more content before I can finally decide how I'm going to go about it. A few of the user generated variables that the aimtrainer would aim to utilise: target size, crosshair, colour of targets, and so on... 

> - Week 9

> I have come to realise that in order for any sort of user variable inputs to take place, there must be a pause menu, which I have completely overlooked. i have been struggling eith the pause menu a lot, because my crosshair is already implemented in the scene, meaning that the cursor is not visible to the player. I am going to think of new ways I can solve this problem, and read up a bit more about how to transition from scenes. I also need to work on the user report(features 2 and 4), which means that the user generated variables would have to be kept to a minimum. (also, I can't seem to upload my files onto github, because it says it doesn't support that kind of file type)


> - Week 10

>  I finished the main menu, and am now working on the pause menu, which seems to be a bit of a problem, because my cursor is locked(to facilitate the 'looking around' movement of the aimtrainer), so I can't really get the pause menu buttons that the cursor is hovering over them because, well, there is no cursor. I'll see how this goes and then maybe ask around for help if I can't do it. I would also like to add the timer function by the next week, so that the aimtrainer has away to time your reaction time.

>Sep Hols

> UPDATE: I'm restarting the entire project. The current Version I'm using for Unity is unable to exploit one of UNity's glitches, so I would ahve to change the editor version, and thus consequently, all the scripts would be "corrupted" in the new version. Also, right now my heirachy is not organised, so I want to restart so that I start from the top and know what I need to do next, allowing for a more organised workstation.

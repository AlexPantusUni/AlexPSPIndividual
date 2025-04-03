
### Day 1
We added tags that focused on specific illnesses cats and dogs encounter and also brain-stormed some important accesibilyt features that we were recommended by a SHU lecturer.
### Task 1
We added tags that focused on specific illnesses cats and dogs encounter
### Task 2
Brain stormed features around disability access to make our app more inclusive- such as test to speech reading of text on the space, free engines are available and potential dyslexia filter that changes ther background from hwite to off-yellow or other choices of dyslexia frinedly backgrounds,
this makes it easier for people to read the text if they have dyslexia 
### Issues
Illness tags are not producing good enough confidence scores yet, also we are changing to a different azue pricing tier as the free tiral expire which could prove a big roadblock

### Day 2
#### Tasks Completed
We continued adding images to train the AI and compared it with an AI Ben Made where we exclusively used images related to animal diseases.
### Task 1
I added the images of animals with diseases to our existing model and trained them by manually labelling, however after we trained it we got confidence scores in the 40% and 50% for the diseases
### Task 2
Ben made a different AI that was only trained on images of animals with diseases. This is because we believed the increased model complexity due to all the exisiting tags was making it less receptive to learning how to analayse the new tags we were adding. I ran tests of different images and scenarios on both the exisiting AI and the new one, however they both performed about the same
### Issues
We found out that simplfliying the data set does not make it more precise and it does just need more balanced images where the new tags are shown in as amny possible situations, therefore we require more well-balanced examples to give the AI  a more holistic understing of what the tag is.

### Day 3
#### Tasks Completed
We trained the AI again with more varied illness images and then got some better confidence scores in the 70-80% range, trained it and saw that azure was not charging me any thing. 
### Task 1
We provided the superior images for training, making sure we covered previous blind spots such as too few images of unhealthy eyes and I also introduced negative tags such as healthy eys vs unhealthy yes and healthy skin vs unhealthy skin.
This helped masively improve image recognition perfomance thus boosting confidence scores from medium to high confidence (40% to 65%+).
### Task 2
I checked my azure account and made sure before running the training of the AI and made sure that I did not exceed my available allowance of tags, images analysed and time spent training as I really did not want to have to pay for using the AI, for this project. That would hamper our ability to test as we'd have to reduce our image sample size or potentially even chnage the Ai engine we're using, however now I'm certain we should be fine and it should not prove a limiting factor.
### Issues
The AI has gotten good at identifying eye and skin issues however the confidence score still is nowehere near the 97%+ conbfidence it has for spotting different nimsla like cats and dogs, so we will try to explore better image data sets.

### Day 4
#### Tasks Completed
I ran the initial tests on Iteration 8 which we intend to demo as its confidence scores are good enough and also tried with ben's assistance in finding and collating more well-balanced images to create 
one more final AI iteration. I also assisted Sebastain in giving us the right disease information and advice based on it.
### Task 1
I did the write up for the testing required to display the iterative perofmance imporvements that our AI has undertaken between sprint 1 and sprint 2. I compared all the versions so far with images from outside the data set and made a test sheet, which i attached. I showed these findings to my academic consulatant hwo was stisfied wiyth the perofmance metrics and the added functionality od symptom checking.
### Task 2
I ran the advanced training with Ben for the new iteration however it ended up being somehwta worse after we tested it so we're a bit unsure and confused by this. I think we will have to assess this more closely before we decide what version to demo to our client on friday
### Task 3
I talked with Sebastian and i made sure the tags that the new AI version outputs are what he uses to process the bac-end which will give users advice on everything, thyis is a crucial part of making the application more useful and intuitive and it needed co-ordination between the AI and the JavaScript back-end.
### Issues
We may have ran into a bottleneck of Azure Custom Vision when it comes to how accurate it can get at spotting animal illness symptoms, this is either because of lack of good varied images accesible for free online or some sort of AI-side issue where it fixates on something when training is ran again. We do not have time to make another iteration so we would have to stick with iteration 8.
### Day 5
#### Tasks Completed
I completed my slides on the presentation and discussed the AI model in our final demo to the client and also I ran some testing on Iteration 9 which was the one that despite more images got worse.
### Task 1
I ran some more testing on iteration 9 and compared it with iteration 8 and showed my findings in the presentation, I found it quite curious it had lower confidence scores, had more false positives and was seemingly more inconsistant with previous tags that we did not modify at all. As this was a research task I think it was very important to note this in the presentation and discuss my findings with the client
### Task 2
I presented my work on the project on the AI to the client and they noted some "great progress" in the meeting as the AI functionality now made it better suited to our end-users which are pet-owners. Therefore I believe I fulfilled all the improvements required of the AI to make it meet and exceed our client's goals
### Issues
I had hoped we could produce a slightly more accurate AI than we did in the end however due to time constraints and potential AI engine limitation this was not possible
### Overall Collaboration and role in the team
Also to be noted, I ran the stand-up meetings everyday and asked people what blockers they had and always tried to help or give feedback such as on the front-end designs Sebastian and Ariba worked like the colur shceme and layout as I have some working experience with development. I also assisted in the way the tags and disease advice should be displayed in the application or the dyslexia mode. Lastly me and Ben gathered images for the AI togethher and we generally collaboprated well everyday to ensure the core functionality of a more personalised AI is done as well as possible. part of this was due to my role as scrumk master however at time I undertook project management responsabilities as to ensure collabation between all areas of the application.

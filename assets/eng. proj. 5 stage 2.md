**PRIMARY AGENT COMMAND:**  
Create a second stage in the project 5 file with an appropriately labeled button that links to a subpage for this new stage. The button, as well as the new Stage 2 subpage, should mirror Stage 1 as much as possible. However, the content you will fill in for this new stage is different. The content is listed below, and as before, large sections of text should be divided and labeled. Each of these sections begins with a bolded title, which you must apply to the text box in the same way as Stage 1\. At some point there will be another slide carousel. This should be designed in a similar way to stage 1 as well. DO NOT alter any text meant as content for the website. DO NOT print any AGENT COMMANDS on the website. YOU MUST remain on theme and in line with stage 1 as much as possible. All pictures can be found in the assets folder, unless generation is specified. ANY CONFUSION FROM THE AGENT must be brought to my attention. ANY SERIOUS CODE ALTERATION must be checked with me first  Everything below is website content, unless specified by an AGENT COMMAND  
**Needs Statement:**  
When writing our needs statement, we focused on how the cloud chamber could be used as an effective education tool rather than a fun science project or mysterious spectacle. We knew that the statement should not detail how the chamber would be built but instead the intention behind the particular design. This project requires trial-and-error jury-rigging to test the power source, Peltier, and prototype bases, so we have been focusing on design and modification for two weeks.   
AGENT COMMAND: INSERT PICTURE  
Insert the picture labeled “prototype” appropriately styled with small margins between surrounding text.  
END AGENT COMMAND  
Focusing only on the perceived benefits of the cloud chamber without discussing its features or design was a challenge after constant iteration. The slide deck from the IBM link in our project guidelines was helpful, as in that activity, we were instructed to begin formulating the statement with, 

AGENT COMMAND: GENERATE A PICTURE.   
Generate and insert photo of the following text, written on a well-used blackboard. The bracketed words must look as though they are meant to be filled in with something later: \[Our users\] need a way to \[address this need\] so they can \[benefit in this way\].  
Insert the picture between the text blocks in the same cell. Make sure the margins are not wide. You must first ask my permission before making this photo edit. If possible, you must show me the picture you generated when you ask permission as well.    
LEAVE SURROUNDING TEXT UNCHANGED.   
END AGENT COMMAND

	After a few iterations of the statement, we honed in on a few key ideas. First of all, we first assumed our user would be a student. This is still true; however, we neglected to consider the educator, who would hypothetically use the cloud chamber in a demonstration or experiment project. In addition, we wanted to broaden our view. The cloud chamber should be used to get people excited about all sorts of science, not just physics but the chemistry behind supersaturation, the math behind describing particles, and even engineering. With all that in mind, we decided what our needs statement would be.  
   
AGENT COMMAND: GENERATE A PICTURE  
insert and generate a photo of the following text, written on a well-used blackboard: Educators need an a way to introduce students to complex topics, and get them interested in the natural sciences  
Insert the picture between the text blocks in the same cell. Make sure the margins are not wide. You must first ask my permission before making this photo edit. If possible, you must show me the picture you generated when you ask permission as well.    
LEAVE SURROUNDING TEXT UNCHANGED.   
END AGENT COMMAND

**Design Principals:**  
We first decided that success would be anyone who used the cloud chamber and wanted to learn more about the science behind it. Success could also be a student of a relevant science who’s confused about subatomic particles or how they behave. If we could better their understanding of the subject, that is also a win. As I said above, we realized we wanted to broaden our audience, so our design principles are focused on how our cloud chamber can be accessible as possible.

AGENT COMMAND: GENERATE A PICTURE.   
insert and generate a photo of the following text, written on a large white board with thick black letters. Each line should be numbered. Include the title at the top of the board:   
**Design Statements:**

* The cloud chamber must be easy to use for people with no experience in the sciences  
* The system should incorporate educational aids to translate observed particle behavior into physics concepts.   
* The cloud chamber must be designed such that high-contrast, easily visible particle paths appear so users with varying levels of visual ability can clearly observe and distinguish particle trajectories.

Insert the picture between the text blocks in the same cell. Make sure the margins are not wide. You must first ask my permission before making this photo edit. If possible, you must show me the picture you generated when you ask permission as well.    
LEAVE SURROUNDING TEXT UNCHANGED.   
END AGENT COMMAND

The last statement may be the most obvious. The particles should be easy to see in our cloud chamber. Good lighting and a backdrop are the best we can do in this short design period, even though it would be hard to make the chamber usable for those with impaired vision. The second principle was established to better assist our users, the educators. The cloud chamber should have some features dedicated to helping it be an educational tool. Finally, we want this chamber to be safe, but still fun and effective. We recently discussed adding a feature so sliding an alpha particle-emitting banana would be an easy way to show everyday objects can be radioactive. Much more fun than waiting around for particles in the atmosphere.   
AGENT COMMAND: INSERT PICTURE  
Insert the picture labeled “prototype2” appropriately styled with small margins between surrounding text.  
END AGENT COMMAND

**Design Cycle:**  
Our next step was an all-out iteration sprint through prototypes. In the following slides, read about how designs changed in each version. 

AGENT COMMAND: SLIDE CAROUSEL:   
COMPLETE ACCORDING TO DESCRIPTION  
As in the last stage of project 5, create a rotating slide deck with the same prompt to click through the slides. I will specify what picture to use for each slide. In a similar way to the prompt, when each slide is clicked for the first time, instead of switching to the next slide, a text box must float up and cover the picture. The text is below, labeled with each cycle number, as the slides will be. Match each text block to the slide. The opaque text box must remain until the slide is clicked again, in which case it will move on to the next slide.  
THE CORRESPONDING CODE MUST BE WELL LABELED SO MANUAL EDITS CAN BE MADE.  
The cycle text follows:

Cycle 1:  
The main part of the chamber, the cooler, has three main components. The aluminum plate, Peltier cooler, and heat sink. The peltier cooler is made of a semiconducting material that can channel current in a special way. By shuffling electrons between different semiconductors, the cooler can heat one side while cooling the other. This is not quite enough, however, as we need the Peltier to be separate from the chamber in some way so as to reduce the risk of electric mishap. In our first design, the assembly requires the use of three different parts, all designed in some way to secure the heatsink, cooler, and aluminum.   
Many parts failed initially, especially the circular aluminum plate holder and gasket, either because of size or lack of practicality. But the parts failing informed our next design cycle. 

Cycle 2:  
Our first big move was to consolidate the design into one piece. This CAD redesign meant that we could now rely on one part rather than deal with many interlocking parts. Especially for a user who may not be as familiar with its design as we are, printing and assembling this in a classroom would be much easier in one piece. It also reduces the chance that one small piece will break, which could impact the chamber performance. The drawback to this piece is that it takes four hours to print, which could slow down design iterations. 

Cycle 3:  
After we had gotten an idea for the one-piece design, we decided to move forward with a printer settings change. Much of the plastic interfaces with either a very cold aluminum plate or a hot heatsink. This means the plastic should be as temperature resistant as possible. PLA is not the ideal option, but it is what's most common in the engineering space we’re working in, so we decided to up the infill percent in the CAM tool Prusa Slicer to better resist the temperature difference. In addition, we added more room for wiring and a better structure interface between the heat sink screws and the 3D printed design. 

Cycle 4:  
In cycle 4, we upgraded our design with PETG, a new material much more resistant to temperature. While this prototype hasn’t been tested yet, as we need a new power source, it will hopefully solve the frustrating issue of venting. If the air inside the chamber is too turbulent or too warm, the chamber won’t work. So, an effective seal is ideal. We haven’t been able to detect any electrons yet, but we hope that with less outside ambient air in the chamber, it will get colder faster, and we will see particles\! The PETG will ensure that the chamber stays as secure as possible under these conditions.

END AGENT COMMAND

Measurement of Success  
Our main challenge was to 


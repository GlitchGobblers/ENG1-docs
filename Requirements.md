# Requirements

## Cohort 3 Team 4

Dashiell Ratcliffe	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\<gcx519@york.ac.uk>\
Ben Slater			&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\<bs1463@york.ac.uk>\
Charles MacLeod		&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\<wzt516@york.ac.uk>\
Cassie Dalrymple	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\<txf510@york.ac.uk>\
Abualhassan Alrady	&nbsp;\<lxm514@york.ac.uk>\
Hannah Rooke		&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\<hjt558@york.ac.uk>\
Harley Donger		&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\<harley.donger@york.ac.uk>\
Kiran Kang			&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;\<rjm638@york.ac.uk>


## Requirements Elicitation, Negotiation, and Planning

- Elicitation: How did we gather requirements (brief with customer, research into certain aspects of the game such as game engine might require some specific functionality that we need to implement i.e. new requirement)
- Negotiation: Created our list of questions based off of what we needed to add to our requirements file, for example we asked about aesthetic since we hadn't specified that requirement yet as we didn't know if there was a desirable art style. This also includes any negotiation with customer (e.g. life system that he hadn't thought about)
- Planning: Following meeting, how did we structure our finalised game requirements, how did we come up with a concrete list of them, how did we ensure nothing was redundant but also that nothing was missed? etc.

***Need to speak to Ben regarding Use Case Scenarios***

## Requirements Presentation

### User Requirements (Table 1)

Table of user requirements including their ID, a brief but detailed description, and a priority (1 being highest).\
For example: User_Requirement_Score | Scoring should be explained to the user and go up/down | 1

|	ID				|	Description											|	Priority	|
| ----------------- | ----------------------------------------------------- | ------------- |
| User_Requirement_score | Still need to discuss and finalise description | 1 (It must be implemented) |

### Functional System Requirements (Table 2)

Table of system requirements that the game should provide and that require functional code relating to the game. They should relate to user requirements.
See the example below

|	ID				|	Description											|	User Requirement	|	Priority	|
| ----------------- | ----------------------------------------------------- | --------------------- | ------------- |
| Functional_Requirement_Stress | Have a bar that slowly increases player stress and can be decreased etc. | User_Requirement_Game_Objective | 2 (Should almost certainly implement) |

***Do we need a context column here?***

### Non-Functional System Requirements (Table 3)

Table of system requirements that the game should provide that require functional code relating to outside the game. They should also relate to user requirements and specify where they fit certain criteria.
See the example below

|	ID				|	Description											|	User Requirement	|	Matching Criteria	|	Priority	|
| ----------------- | ----------------------------------------------------- | --------------------- | --------------------- | ------------- |
| Non_Functional_Requirement_Hardware | Game should run on all hardware types (not be resource intensive) | User_Requirement_Compatibility | Smooth performance | 2 (Should almost certainly implement) |

***Note: Check if the names used above are required for the requirements file or we should change them slightly***


<details>
<summary><h2> Old file to be removed when shifted upwards into new file </h2></summary>

**Requirements:**
**Design**:
- Tone (Serious/**humour**)
    - References to the university
	* aesthetics/style (**Jorvik/medieval**, cyberpunk, sci-fi, vaporwave, zombie-style exam week (shaun of the deadish), palace of the mind (mental health theme))
		* must fit together and also connect to uni (long boi in the form of shrine, hidden room, etc)
		* primarily issues from asset sourcing
		* highly colourful
		* family-friendly

**Gameplay**:
  * "NPC that follows the player, annoying text bubbles, anything else related to uni that creates a sense of wanting to escape"
  * Difficulty (easy for accessibility)
  * Core mechanics
    - escape the uni (not required to be literal, can be metaphorical)
    - puzzle game
    - Pause system
    - Timer (limited time/timer)
  * Points system
    - Rewards increase points
    - Time at the end converts to points  
  * Life system
    - Respawn points (long boi statue)
    - Set number of lives (how many times can stand on traps)
  * Events (dependent on the setting)
	* Hidden events
	- Easter eggs
	- Barriers
	- Rewards
- additional bar 
	- stress managment?
	- triggers an event if it's too high?
	    
**Legal**:
- Contains a credits screen
- Legal usage of assets 
      
**Accessibility**:
  - Must be able to run on a lab PC with peripherals
	  - Controls must be mouse and keyboard
  - Difficulty (easy for most people, but with some level of challenge)
</details>

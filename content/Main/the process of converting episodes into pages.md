
### Subtitles created:
I use Movavi to generate subtitles for each episode, this outputs a srt file that contains the audio converted to text with time information for when that text should appear on the screen to work as subtitles.

### Transcripts extracted (Raw):
Because the subtitles are outputted in the srt file type theres a lot of text in the file that is not useful for my purposes so I run a series of find and replace actions using RegEx commands and remove that data: 
- \d+:\d+:\d+,\d+ --> \d+:\d+:\d+,\d+
- \r\n\d+
- \r\s\r
- \s\r
This results in all of the time information being removed from the document and all of the different lines of text that would be displayed separately are on separate lines. This is now saved as a separate txt file.

### Clean dialog transcriptions and summarize actions:
Now the fun starts, I paste the txt file into Obsidian as the raw transcript and then create the Episode file in Obsidian. Following along with the episode playing I copy and paste the transcript text over into the episode file and fix spelling mistakes, add links, paste related information into the newly created pages, and add dialog names. This is by far the longest part of the process. Since I'm hoping to catch most of the links and information I'll want to get out of an episode in one run of it I often have the episode playing at 25%-33% speed so that I have enough time or can transcribe what's being said by hand.

### Add formatting and section titles:
Initially I was italicizing all of the dialog but I don't think it is worth the trouble of doing it and don't want to get into the weeds of more regex commands to automate it. Now this is mostly picking spots for section breaks where I add a horizontal line break and a section title usually relating to a character or location that is introduced in that section. 

### Add missed links and update related information:
While I try to catch all the location, character, and lore information that is said in the episode the first way threw I inevitably miss a few things or some information that is said offhand so I go back through to listen to the episode at normal speed and follow along now on the Episode file. I'm mainly trying to catch any information I didn't add to relevant pages, but also fixing spelling or other small mistakes left behind. 

### Update Table of Contents and Roadmap:
When the episode file is complete I move to update the Index or Table of Contents or Overview page as well as the Roadmap and any of the other related navigational pages. 

### (End of a campaign) Review all pages:
When I get to the end of a campaign I try to go back through all of the files created and make sure everything has consistent meta data and is formatted correctly so that the information is easily accessible across the wiki. 

[[Who's Doing This]]

# Sonifying Truth and Reconciliation Paradata
My final project can be found [here](https://cassandrahistory.github.io/sonifying_truth_and_reconciliation/index).

This paradata report consists of three sections. The first is a summary of my initial concept, the second is a list of conscious decisions made throughout the project’s development, and the third is series of reflections and thoughts about the future.

## Part 1: Initial Conception          

My initial goal for this project was to utilize Sonic Pi to create a sonification of residential school data and then create an associated graphic using the Processing language. I envisioned a line moving across a map. Whenever the line moved over the location of a former residential school, a note would play, and a dot would appear. The size of the dot and the pitch of the note would be altered according to the data.

In undertaking this project, I hoped to accomplish three things:

1) Gain technical experience with Digital Humanities tools

2) Address questions about using and presenting difficult historical data

3) Explore implementing more conscious creativity into my historical work

## Part 2: The Project

### The Dataset
I located a data set from the National Centre for Truth and Reconciliation (NCTR) that contained approximately forty rows of data for 150 residential schools. I was primarily interested in three fields: deaths, latitude, and longitude. Before converting the NCTR’s .xml file to .csv, I had to make some alterations to the data. I condensed schools that had multiple entries for a single item, choosing the locational coordinates from the longest running location. The NCTR noted that their death totals did not include federal day hostels (primarily in Nunavut, the Northwest Territories, and Quebec), but their locational data was still in the dataset. I made the decision to leave them in my final project to portray a better geographical range of residential schools. I also chose to not alter the order of the entries in the dataset.

I made the decision to focus on a single dataset, even though the project could have benefited if more were used. The data I used only represents children whose names are known by the NCTR. I chose to just use this set to act as a proof of concept and would utilize data from recent searches for unmarked graves if this project were to continue. I would also hope to engage in collaborative conversations about what other data should be included.

### Change of Plans: Processing to QGIS
Processing would have worked well for this project and likely have created a more visually appealing result. Unfortunately, after watching several tutorials I concluded that developing a basic understanding of the language was out of the scope of this project. After looking into several options, I decided to use QGIS. I used the base global map from OpenStreetMap and the latitude and longitude data from the NCTR dataset.

 Unfortunately, I am not very happy with my map graphic. The OpenStreetMap base that I utilized contains colonial borders, which feels very inappropriate for my topic. I did not know of any alternatives with my current knowledge of maps and GIS systems, so I tried to do what I could and inverted the colours using GIMP. This was an attempt to address the literal problem of colonial borders through a more less literal creative decision, but it is my hope that it will lead to reflection.
 
 ### Change of Plans: Sonic Pi to Musicalgorithms and Reaper
Sonic Pi would have likely led to a more polished final project with more room for creative adjustments, but much like Processing, it would have been unreasonable to learn what I needed within the time restraints of a single semester. I turned to musicalgorithms.org to turn my data into a .midi file. I pitch-mapped my data on a scale of one to eighty-eight. This allowed the notes to corelate to piano or synthesizer keys and allowed for the largest possible variance in pitch. This allowed me to emphasize the highs and lows of my data and create an audio track that is explicitly not musical. I chose to not vary the duration of my notes as I wanted to focus to solely be on the pitch. I chose Major E as my scale. I do not have a musical background and simply tried all the options until I found one that fit the relatively low sounds I was imagining.

 I originally planned to use the .midi file in Audacity, but then learned it lacked the required functionality. I downloaded the free trial of Reaper to use as an alternative DAW. The next step was to choose a sound. I experimented with all the preset options in Vital Synthesizer before settling on my final choice. I wanted to choose a sound not associated with a traditional instrument to avoid sounding like music, which left mostly synthesized and experimental plugins. There was a fine line amongst the presets between those that had potential and those that sound like they came from a 1980s science fiction movie, and I’m not completely satisfied that my choice is far enough away from the latter. I believe the option I decided on is sufficient, though a better alternative could likely be found through a more thorough search of user-created synthesizer plugins.
 
 ### Bringing Everything Together with Premiere Pro
Finally, I was able to bring everything together and create my final product with Adobe Premiere Pro. I manually created 141 graphics, each on their own separate track, to facilitate the points on the map changing to orange. The specific orange was chosen by using an online tool to detect the hex code of official NCTR materials.

 One issue I came across was differentiating points in close position to another and making their appearance noticeable to viewers. My first instinct was to just outline the dots, but unfortunately the minimum stroke size in Premiere Pro is slightly larger than I would have liked. I experimented with three options: all dots outlined, no dots outlined, and dots only outlined where differentiation was required. I ultimately chose the last approach. If I revisit this project, this is something I would like to improve. One option would be to determine how to use a .png file for graphics as opposed to Premiere Pro’s shape tools.
 
 ## Part 3: Reflection
This project changed a lot through its development, and I think more changes would be required for this project to be in a publishable state. The most important element of this would be collaboration with residential school survivors, their families, and potentially the NCTR. The project not only requires feedback on the graphical and aural components, but also on how it should be presented. The question of whether it should be presented at all is also an important decision, and not one that I should be making as a person of settler heritage.

 Despite this creation being a long way from a completed, public-facing project, I still view it as a success. I set three goals at the start, and they have all been reached in some way. First, not only did I learn new tools (musicalgorithms.org, QGIS,Vital, Reaper, and Premiere Pro), but I learned about the capabilities of other tools (Sonic Pi and Processing) and used existing knowledge in new ways (primarily in audio and video editing). I also began to think about how we can display difficult historical data, the ethical questions that can arise in these sorts of projects, and the potential space for affectivity in these histories. My largest takeaway from this project is probably an intensified curiosity towards creativity in academic and public history. I have barely scratched the surface of the topic, but it is an avenue I would like to explore further in the future. I already had an interest in audio and video work prior to this sonification, but using tools in different ways has only increased my desire to use these skills in future History projects.
# Discourse analysis of football broadcast


## Project Scope and Rationale:
The project aims to conduct a comprehensive discourse analysis of football broadcasts, focusing on key events such as the `kick-off`, `full-time`, `passing`, and `scoring`. The rationale behind this project is to understand the language use in sports commentary and gain cultural and social insights from it.

## Data Collection Process:
Scripts from various football broadcasts will be collected and will be downloaded from online platform. This could involve transcribing commentary from YouTube highlights or sourcing scripts from available databases.

## Annotation:
The scripts will be annotated with timestamps and other relevant information. This could involve marking the time of key events (like goals or fouls), noting the players involved, and other context-specific details.

## File Structure and Naming Conventions:
Files will be named in the format **name_script no.** For example, a file could be named `moses_script1`. All files will be stored in a dedicated GitHub repository for easy access and collaboration.

## Meaning of the Columns in Textual Data:
The textual data will primarily consist of two columns: `timestamp` and `script`. The `timestamp` column will indicate the time of the event in the match, and the `script` column will contain the commentary corresponding to that timestamp.

## Relevant Licensing Issues and Ethical Concerns:
As the data is being sourced from publicly available broadcasts, there should not be any licensing issues. However, it's important to ensure that the data is used ethically, respecting privacy and avoiding any form of bias in the analysis.

## Potential Use Cases and Future Development:
The results of this project could be used in various ways, such as training AI models to generate sports commentary, studying linguistic patterns in sports commentary, or even developing tools to assist commentators. Future development could involve expanding the analysis to other sports or languages.

## File naming:
Please collect scripts of football commentary and add them to this GitHub database with the format **name_script no._the playing teams**

example: moses_script1_Suprs vs Wolves

## file format: 
[Date and the teams] {timestamp} 'script
provide the source of video at the end of your files.

example: 
[5/12 Suprs vs Wolves] {3:15} 'Harry kane with the powerful shot inside the box.'
source: https://www.youtube.com/watch?v=WpwBvr61yf0


## Annotation method:"

`time stamp` -> time of the action occurred

`competetion` -> epl/ ucl etc

`action` -> shot/pass/kickoff/fulltime

`subject` -> player name

`adj` -> pre-head modifier of the action

`adv` -> adverbial clause

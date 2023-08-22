# PullToRoll
**PullToRoll is a casual mobile game that I developed in 2021 and published in Google Play Store.** The base gameplay is about moving a cube on an endless map. The cube going to break if it collides with a spike or fall of the dynamically generating platform. Each step which not ended with the break of the cube is given one point to the player. The score and leaderboard were connected to Google Play Services and users could compare their scores to others and their high score.
[Video of the gameplay](https://drive.google.com/file/d/1zIP9saGfbmA5STc8v0e34od9tDoG-bgV/view?usp=sharing)

> The repository only contains the C# scripts of the game.

## Used technologies
* C#
* Unity
* Google Cloud Console
* Google Play Services

## Project's Objective
Before this project, my focus was a multiplayer city-building game which I was overly optimistic about. My goal was to create a modern version of SimCity cause new games not tried to fill their place in the industry and only made even more simplistic or extremely complex games that lacked the casual feel of the gameplay. On the project, I was the only programmer. A friend of mine did most of the modeling. After 9 months of continuous working, it become realization how unpredictable how long it would take to finish this game, and that time, there were already games that somewhat filled this space in the game industry and they did a better job than we could, so the project was canceled.

*I realized for a commercial game I need to work more organized with clear ends of the project.*

PullToRoll was the product of that more thoughtful and organized period. I worked on it for less than 4 months and I managed to publish it on Google Play Store. I aimed to learn more about mobile game development, improve my skills in C#, and to get know the procedure of publishing an indie game. I got familiar with ticketing and better at thinking in advance. Although the project wasn't perfect in many ways, I couldn't find the perfect balance between simplicity and engagement.

## Retrospective
When I worked on this project, I haven't heard about OOP principles nor that there is a collection of design patterns. All I know was Singleton and the practices that are frequently used in Unity. I tried to make my code appealing, but that not meant clean code, and later *I learned that a good programmer always writes the most simple code instead of some high-level ineffective ninja code.*

I knew back then how to use Git and Github, but I wasn't used to it. I felt versioning was an unnecessary thing that just slow me down in development which is the cause why only the script is in the repository. It was a good lesson cause I removed the API that communicated with the game, which caused the game continuously try to join the services and was not allowed to play till it made the connection; which it no longer can. I wanted to create a new API, but for that, I would have to hardcode it to the source code by design, but that was not possible, cause a few weeks before that another accident happened, and I lost the content of two of my disks which was to only place where the project was stored. Until that point, I haven't realized that I no longer have the project and can't recover it cause most of the spaces of lost files were already rewritten with new stuff. The connection couldn't be fixed so I have to take the faulty game from Play Store, since then, I actively versioning.

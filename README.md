# Football-data-Analysis
Functions based on wyscout's data to categorize goals, scored and conceded
Functions are not fully working, you can only find about 80% of the goals in a season and goals may not be categorized right.

Available functions:

- Penalty shot  ---> Find every penalty goal
  
- Freekick shot  ---> Find every freekick that has been kicked to score directly
  
- Owngoal  ---> Find every own goal
  
- Counter attack and Ball recovery  ---> Find every ball recovery that leads to a goal, each action can be divided in counter attack or ball recovery based on the location of the recovery and the time     
                                         between it and the goal and the number of events between the recovery and the goal

- Throw-in shot  ---> Find every goal that starts with a throw-in and leads to a goal within a certain amount of events
  
- Direct corner shot  ---> Find every goal scored directly from the corner kick
  
- Corner schema  ---> Find every goal scored starting with a corner kick, the category of the goal could be difference based on how the action went

- Freekick schema  ---> Find every goal scored starting with a freekick, the category of the goal could be difference based on how the action went
  
- Positional attack  ---> Find every goal scored with a built action that has at least a certain amount of events before the goal
  
- Goalkeeper's bounce  ---> Find every goal that happens after a goalkeeper's save with the ball still playable

WYSCOUT GLOSSARY: https://dataglossary.wyscout.com/
WYSCOUT API DOCS: https://apidocs.wyscout.com/

TO USE MAIN FUNCTIONS YOU'LL NEED SOME SIDE FUNCTIONS, NOT ALL OF THEM. YOU CAN FIND THEM INSIDE THE PROPER FOLDER.

There also alternative written functions that do the same work as the other but these are written based on SoccerAction package. Fucntions based on this package are slitly different from the original ones but the goal is the same. I've tried this package trying to cover the lack of the true functions but there is still the same problem of accuaracy.
You can find SoccerAction based function inside their proper folder.

# Game Developer Diary

## January 20th, 2024

Inspired by the [_Republic of Rome_](https://boardgamegeek.com/boardgame/1513/republic-rome) games I played in my youth, I would like a game mechanism where the players are sort of forced to collaborate at the beginning of the game. The agency is weak, lacks means, and is in trouble. Sure, the players can already backstab right now, but the risk of triggering an end-game catastrophe is looming. Backstabbing should be left for the end of the game. I will figure out how to implement it later.

In the original concept, I assumed only an employee revolt could trigger the game end. Now I have made _Employee Engagement_ one of the three scoring tracks of the game. If any of the three tracks goes to the bottom of the scale, everyone loses (perhaps I could require 2 out of 3 for beginners). Going to the plus side could trigger one-off bonuses, while going to the minus side could trigger temporary minuses. For example, less manpower, etc.

I think each Quarter should have one (or three?) Targets, that the agency needs to fulfill. If fulfilled, players get Victory Points, if failed, they lose positions on the projects tracks.

I also think I should have one Random Event per quarter, that could be either beneficial or detrimental. Perhaps additional Random Events could be added if a Target is failed or incrementally over the course of the game.

I would really like to use the [_Red Flag over Paris_](https://boardgamegeek.com/boardgame/296577/red-flag-over-paris) card system for playing, but I am not entirely sure how it's going to interact with Targets, Projects and Random Events.

At the beginning of the game, each Division will have limited manpower (i.e. meeples), so to complete targets, you need to pool resources. I should tweak the availabe resources in such a way that at the beginning of the game, you need collaboration of 3 out of 4 players to be able to complete a project (even if only 2 players can benefit from it, that would engender some delicious resentment between the players!). As the game progresses, and if you have been playing well, the 3/4 majority requirment should reduce to a 1/2 majority requirement, and at the end of a game, one dominant player could single-handedly complete target on his own, and the other players would need to form a fragile coalition to stop him from winning outright. I could also envision a pool of temporary workers that could be used by anyone if the financial resources allow for it.

## February 3rd, 2024

I had a look at the new game [_Federation_](https://boardgamegeek.com/boardgame/345868/federation) and it gave me some ideas on how to implement the project tracks. Instead of having to fill a pool with a given amount of meeples,  each meeple will make a counter advance on a track each round, and when the track is complete, then the project is complete. This will give players the possibility of completing multiple turns on each quarter, or withdraw support at the last minute. Also, I am starting to think that I need a project deck separated from the main playing deck. Projects may have different score and costs, and players can activate a project playing a main card from their hand.

Another idea: using gray meeples as _consultants_, i.e. workforce that instead of speeding up your projects, slows them down.

## February 5th, 2024

I will add another oprtion for players: a _Training Track_ where, upon completion of the track, the player will get one extra meeple. Some training will be made compulsory (bilingualism, tee hee hee!).

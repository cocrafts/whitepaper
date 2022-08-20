### Games

We desire to, together with community, develop multiple games with different genres, from 2D (turn-based) to 3D (MMO RPG). But not only game itself, we believe great games with exceptional gameplay need a great story behind, which is why the lore is created. Hence, all games are built and connected to each other, and each will represent a period of the ATEM world history.

At early stage like with a small team of full-time 5 people, we choose to kick-start the very first game with a “not much challenging” 2D type which is a turn-based Trading card game named **Under Realm**.

There are 3 reason behind this decision:

1. **Board game lover**: We, the core developer member, love Board games like Uno, Exploding Kittens, Monopoly and the legendary childhood YugiOh! - from a collect very cheap fake paper card to a Computer version; Hearthstone. Easy to onboard but hard to be a good player, friends time together, card collection, etc. are all we can recall those happy moment. We even normally create new rules when playing these board games, so we do the same to Under Realm.
2. **"Comfortable" entry for 1st-time game developers**: Speaking of engineering part, our core developers have never ever built a serious commercial game and this is our first time officially. Understanding game industry is not a joke, 2D seems to be a good entry point for such 1st-time and amateur game developers to the this industry. However, with the base of a pretty good engineer background of 10+ years experience, we hope that struggles and challenges are a bit let. For this reason, we’re developing Under Realm with [Cocos Creater](https://www.cocos.com/) - “A mature open source cross-platform game development framework” and free, so anyone can easily join Under Realm development journey with us.
3. **Huge and long live market**: Card game, to us, is a legendary and a lot of people love card games (at least to us). Card game existed since old times, some research said it was invented during the Tang dynasty around the 9th century AD as a result of the usage of woodblock printing technology; and it still existing today in many ways and the market size is massive. Global board games market (including card game) was valued at USD 13.75 billion in 2021, and it is expected to reach a value of USD 30.93 billion by 2028, at a CAGR of 13.70% over the forecast period (2022-2028) (SkyQuest, 2022). So, all we hope is to be simply one of small guy in this big market, creating another interesting game play for the Under Realm in blockchain space, that we love to play by ourselves first, and we hope existing card game lovers and others love it too.

Under Realm, the very first game of Metacraft Studio, is going to be developed mainly by the Core members. Even though operating a “Decentralize game studio”, we’re fully aware of that we need to develop Under Realm by ourselves and get it released firstly before more and more people know about and join together. Luckily, by today writing this White paper in August 2022, we’re thankfully having 20+ Contributors who are contributing their time and effort and sharing their passion to work on Under Realm with us: from Lore development, Character development, Sketching, Digitalize, etc., or just simply came playing hand-cut Under Realm paper version with us and leave helpful feedbacks. They have been with us since very early days and more coming along the way till now, and hopefully in the very near coming days.

![alt text](https://github.com/cocrafts/whitepaper/blob/master/assets/img/card-play.png?raw=true)

#### UNDER REALM

![alt text](https://github.com/cocrafts/whitepaper/blob/master/assets/img/under-realm.png?raw=true)

Under Realm takes place in a chaotic, fragmented world of ATEM where human and other races are constantly fighting each others, to wrench the endless thirst for power, wealth, and gradually take control over ATEM.

Steel, blood and brute force were the main material of the savage battles until mysteriously, mankind discovered the long-lost magical scripts that allow them to summon mighty, ancient creatures/ entities that can turn the tide in no time. And no one wants to be left behind in this race. Adventurers across ATEM are desired by factions to discover the forgotten dungeons across this continent. Players join the Under Realm as Adventurers who will confront each other in the search for the long-lost scripts in hidden dungeon across ATEM.

Metacraft Minerals (MEMI) will be used to fuel and allow mankind to use magic, included and not limited to Summon ancient creatures from the sealed scripts and Create new scripts.

Under Realm is Trading card game with 2 modes, Free to play and NFT:
- **Free-to-play**: The main game mode where all players are able to purely enjoy the game with the original decks.
- **NFT**: Experimental mode where players can build, truly own and trade their decks while still keep the game balance on it own way.

Note: This two modes are totally separated from each other and players cannot cross play.

**Under Realm development status:**
Under Realm is in heavy development for its launching Alpha in Q4 2022. Alpha Signup available [here](https://stormgate.io/)
- Game play: Complete for Alpha.
- Design and art: in-development. Still need a lot of Hero Characters to be drawn, join [here](https://discord.gg/jDqqTu6K) if you’re interested in.
- Development: in very heavy development.

**GamePlay:**

Adventurers are confronting each other in the search for the long-lost scripts in hidden dungeon across ATEM. 

- **Win/Lose Condition**:
    - To win the game, player is required:
    - Reduce the opposing player's Health Points (HP) to zero.
    - Destroy all Monster cards that oppose enemy owned.
- **Deck**:
    - Has Spell cards & Monster cards.
    - The deck has no duplicate of the same monster card and only have up to 3 the same spell cards in your Deck
    - Players can prepare multiple desks (maximum is … desks).
    - Player will select a desk before start a battle.
    - Player can change cards in desk before battle.
- **Battlefield**:
    - Summon zone:
        - Has center and 2 side, to place monster & troop.
        - When a card in the center is destroyed, it will move cards on the side that has more cards to the center
        - When a card not in the center is destroyed, it will move cards on that side to replace it
    - Draw desk on the right: to draw card to hand.
    - Graveyard on the left: hold your destroyed monster.(to view battle history)
- **Card**:
    - Monster card:
        - Class: Each monster card will belong to a class, and each class will have different pros and cons.
        - Attack Point
        - Heath Point: when heath point reduce to 0, it will be move to grave yard
        - Defense Point: (some monster will has it by default, but some will get by spell/ card or skill), reduce the damage it takes by %, maximum is 50%
        - Skill:
            - Passive: skill has no cooldown to active, It will active if meets the condition
            - Active: Auto active before battle, after activated it will be cooldown by turn before active it again (countdown by turn)
    - Troop card:
        - Player will earn a troop card each turn
        - Player cant keep troop in hand & has to place it to the battlefield every turn
        - Attack Point
        - Heath Point: when heath point reduce to 0, it will be destroyed
        - Defense Point (by spell or skill from Monster)
    - Spell card:
        - Pre battle: It will be activated before the start combat
        - Post battle: It will be activated after end the combat
	- Phases in game:
    - Preparation phase:
        - Player will chose Desk before start the battle.
        - Player can see the class opponent choose the most to counter
    
    - In-Game phase:
        - Each player has 60 seconds to setup before battle
        - At first each player will have 2 slot to place Spell (After every 5 turns, 1 more tower will be added)
        - Every 3 turns both players draw 5 spell cards select 3 and discard 2
            - In first turn:
                - Drop coin to choose who will go first.
                - Both players draw 3 monsters & 2 spells
                - Place Monster in Center & a troop to any side
            - From second turn to further:
    
**Under Realm Battle field**

![alt text](https://github.com/cocrafts/whitepaper/blob/master/assets/img/battle-field.png?raw=true)

Artwork is in work in progress

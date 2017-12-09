# gli
gli -- java based word game.

 - $revision : 1.0
 - $author   : wyr@null.co.za
 - $date     : 2017/11/08 00:00:00
 - $platform : netbeans IDE 8.2

readme.md : 

I have compiled a java based word game using Swing and java 8.

The instructions for use are as follows :

    - The Swing interface has a number of given elements,
      an input textbox which the user uses to interact with
      the computer/AI. A letter is typed sequentially,

      IE, player (a), computer (a), 
          player (p), computer (b)

      A list box displaying the sequence of choices of both
      the AI and the player. The player must only specify
      a character at a time, -- and select the submit button
      to add their respective entry.

      Note here, - that based on the player's first choice,
      (in this instance, 'a'), - the AI searches the
      supplied word dictionary for a match based on a random
      seed, with the letter 'a' as a starting point. 

      There is no additional computation, as once the AI
      selects a given word, - it is used until such time as
      the program runs until completion.

      If the player finishes their selected word, the game
      is lost. Alternatively, if the AI finishes it's
      chosen word, - the game is won.

      A further note, -- the word entry provided by the
      player is referenced by the word/dictionary. If a
      match exists, - it will stop and the player will lose.

      To run the application from the command line, use :

      java -jar "dist/gli_cli.jar"
      
      NB : Please ensure that you run the application from
      the root directory (See above) -- otherwise the
      application will fail. 
      

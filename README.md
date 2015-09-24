# SDRuby Magic Night 9/23/2015

> This Challenge comes from Ruby Quiz #151 please do not look up solutions to
> that quiz

The majority of the strategy in Blackjack hinges around the dealer's hand. The
reasons are likely obvious to most of you: that's the hand you have to beat and
the dealer plays by fixed rules we can predict.

For those unfamiliar with Blackjack, you only need to know a tiny bit about the
game for the purposes of this exercise. The goal for both the player and the
dealer is to draw cards to make a hand with the highest total possible, without
going over 21. Going over 21 is called "busting" and it means you lose the hand.
Face cards count for ten, aces are one or eleven (whichever is better for the
hand), and all other cards count for their face value. You start with two cards
and, if they happen to be a ten valued card and an ace (a count of 21), the hand
is called a "natural." A natural is an automatic win in most cases.

The dealer begins with one of his two cards face up and one face down. We call
the former the "upcard." The dealer will "hit" or take more cards until he
reaches a count of 17 or higher. After that he will "stand" or leave the hand
where it is. That tells us that there are only seven possible outcomes for the
dealer: get dealt a natural, bust, or hit to a total of 17, 18, 19, 20, or 21.

We start every hand knowing half of what the dealer holds thanks to the upcard.
Believe it or not, you can make pretty reliable guesses about how the hand will
go with just that knowledge.

**Challenge** : Write a Ruby program that shows the percent chance of a dealer
reaching each possible outcome based on the upcard showing.

I'll give you some hints to verify your results. Basic Blackjack strategy
teaches that we should assume the dealer "has a ten in the hole" (as the face
down card). It's not always true, of course, but 17 is a common outcome for a
dealer with an upcard of seven. Finally, we call five and six "the dealer's bust
cards" for reasons that will become obvious if you are outputting correct
percentages.

In the casinos Blackjack is often played with more than one deck shuffled
together. One, two, six, and eight deck games are common. You may want to offer
the option to adjust the deck size your program uses. Either way, let's default
to two decks as an average of what a player will face.



## Ok, I finished that challenge.

Generally, I always try to offer alternatives if the challenge was completed too
early, here are suggestions:

- Write a blackjack program that plays with the dealer, a variable number of
  other people at the table (dummy AI players) that the user can play
     - bonus for displaying a "recommended" action for users based on basic
	   strategy
	 - bonus for varying the number of decks in play


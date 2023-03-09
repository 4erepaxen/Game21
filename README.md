# Game21
⦁	Implement card game blackjack;
⦁	For rendering use SDL2 (https://www.libsdl.org/) or Qt (Qt is preferable);
⦁	Cards must appear with animation (moving from any side of screen would be enough);
⦁	Must be implemented mechanism for adding new skins for cards (backs and front textures) (hint: you can create texture from image);
⦁	Implement possibility to choose skin in runtime;
⦁	Interface example:
 

Note: Must be present only buttons for getting additional card(Hit) or stop(Stand). Dealer’s and player’s cards must be rendered.
⦁	User has some starting balance and can increase/decrease bet value, but it can`t be zero. Game should be finished if user doesn’t have enough money to make a bet.
⦁	Rules:
⦁	The goal of blackjack is to beat the dealer's hand without going over 21.
⦁	Face cards(king, for example) are worth 10. Aces are worth 1 or 11, whichever makes a better hand. Card`s with number value equals to its number.
⦁	Each player starts with two cards, one of the dealer's cards is hidden(card’s back is rendered) until the end.
⦁	To 'Hit' is to ask for another card. To 'Stand' is to hold your total and end your turn.
⦁	If you go over 21 you bust, and the dealer wins regardless of the dealer's hand.
⦁	Implement in C++ side some sound playback (some background music, buttons press sound, card sound).
Implementation should contain modern C++ features and best practices. As example virtual functions, smart pointers, RAII and so on. You are free to choose any C++ standard and use its features. 
Version control system usage is mandatory. 

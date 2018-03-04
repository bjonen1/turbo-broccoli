# X-Team NN Style Guide

<brief description of your team's opinion or philosophy regarding Style Guides>

## Naming conventions

constant variables use upper case, if consist of mutiple words, connect with underscore;
non-constant variables use lowercases for single-word, if consist of multiple words, begin with lowercase in the first word, next words start with uppercase;
class names begin with uppercase;
method names use lowercase, if consists of mutiple words, connect with underscore;

### Examples
* interfaces: BST
* classes: Main
* exception types: EmptyQueueException
* fields
* methods: removeMaxHelper
* parameters: depth
* local variables: size
* instance constants: i
* class constants: MAX_VALUE

## Commenting style for public and private members of a class or interface:
Each class must have a header comment located immediately before the class declaration containing the following 

/**
 * (Write a succinct description of this class here. You should avoid
 * wordiness and redundancy. If necessary, additional paragraphs should
 * be preceded by <p>, the html tag for a new paragraph.)
 *
 * <p>Bugs: (a list of bugs and other problems)
 *
 * @author (your name)


### Examples

* classes 
/**
 * Represents a card with a Suit and a CardValue.
 *
 * Bugs: none known
 *
 * @author       Deb Deppeler Copyright (2001)
 * @version      1.0
 * @see also     Suit, CardValue
 */
public class Card 
{ 

* constructors
 //constructor name, brief description
* methods

    /**
     * Search for minmax value associated with the best move for the MAX player
     * @param state the game state that the MAX player is currently searching from
     * @param maxDepth the maximum search depth allowed
     * @param currentDepth the current depth in the search tree
     * @param alpha the alpha cut-off
     * @param beta the beta cut-off
     * @return The minmax value corresponding to the best move for the MAX player
     * @author Jialun Luo
     */
 
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
      if (state.status(2) != Integer.MIN_VALUE) {
    		     isTerminal = true;
    		}

  * switch statement
  * while loops
      while (x < 5) {
           x = x + 1;
      }
  * for loops
      for (i = 0; i < 5; i++) {
      
      }
  * enhanced for loops

### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby
### Testing task 2 code:

# Carry out dynamic testing on the code below.
# Correct the errors below that you spotted in task 1.

require_relative('card.rb')
class CardGame

# needs to be a class method "self.etc"
  def checkforAce(card)
    if card.value = 1
      #the operator '==' should be used in place of '=' above'
      return true
    else
      return false
    end
  end
# def is misspelled below , this should be a class method (self.highestcard). There should be a comma between the parameters in the brackets
  dif highest_card(card1 card2)
  if card1.value > card2.value
    return card.name  #no such attribute, should be card1
  else
    card2
  end
end
end  # incorrect placement of 'end'

def self.cards_total(cards)
  total # needs to be defined (as zero)
  for card in cards
    total += card.value
    return "You have a total of" + total #use string interpolation to use total in the string
    #this line returns after the first loop. needs to be moved to after the end of loop (below)
  end
end
# 'end' missing

```

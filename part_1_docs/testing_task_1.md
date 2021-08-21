### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1:   # missing double equals, should be == 1
      return True
    else     # else missing colon
      return False
   

  dif highest_card(self, card1 card2):     # should be def instead od dif, no comma after card1  
  if card1.value > card2.value:   # if statement has indentation error
    return card   # just card not in parameters needs to be card 1 
  else:
    return card2
  


def cards_total(self, cards):  #indentation error def should be two more spaces two the right
  total =    # total not defined
  for card in cards:
    total += card.value
    return "You have a total of" + total
    #return statement not indented to match for loop
    #total needs to be converted to string
    
  
```

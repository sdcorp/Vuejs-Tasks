# Vuejs Tasks

## Chapter 6

Create an array of 4 horse-drawn chariots. Each chariot has a “name” and a number of “horses” (from 1 to 4). 

Create a component named “chariot”. The “chariot” component should display the name of the chariot and the number of the horses it has. 

It also must have an action button. The button’s text depends on the currently selected chariot.

#### More specifically button’s text should be:
>  ‘Pick Chariot’, before the user has chosen any chariot
>  ‘Dismiss Horses’, when the chariot has less horses than the selected chariot
>  ‘Hire Horses’, when the chariot has more horses than the selected chariot
>  ‘Riding!’, when the chariot is the selected chariot (this button has to be disabled)

**Example Scenario:**
--- User has chosen a chariot with 2 horses and its button says ‘Riding!’. 
--- A chariot with 3 horses has one more horse, so its button says ‘Hire Horses’. 
--- A chariot with 1 horse has one less horse than user’s chariot, so it’s button says ‘Dismiss Horses’.
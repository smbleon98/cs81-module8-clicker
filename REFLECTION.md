# Cookie Clicker Reflection

## What helped you understand DOM interaction best?
- Mod 7a assignment helped me understand DOM interaction the most because that is where we were introduced to the concept of creating variables and accessing those elements by ID and then directly manipulating their contents via the 'script' section. Looking up the syntax and parameters for the addEventListener() also helped. 
 
## How did you choose your milestone messages?
- I used the sample messages provided in the assignment instructions.

## What challenge or bug surprised you?
- For me, I struggled with the function for increasing the count upon the button being clicked. Initially, I put it in two places; I put it in the HTML element itself, such as by onclick="increaseCounter()", in addition to having the btn.addEventLister("click", increaseCounter). I thought the HTML element and JS code needed to align with each other, so I placed it in both places. That was contributing to my counter increasing by 2 per click rather than by 1 as intended. So, I removed it from the HTML element. 
- Another challenge I faced was the timing of the messages. Despite reaching the milestones through clicking, the messages would not appear. It turns out this was because I had placed my 'if' statements outside of the increaseCounter function, thinking that, this action was independent of the counter increasing. Once I placed it inside using 'if' statements, then it worked.

## What personal twist did you add?
- I changed the background color at the milestones. For each milestone, the background becomes a darker shade of red so that it matches the 'relax, this is getting out of hand' tone of the final milestone message.

## What real-world app uses this kind of interaction?
- I believe games that involve explosions use this kind of interaction the most.
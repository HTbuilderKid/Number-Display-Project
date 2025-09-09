*All the diagrams will be done in LucidChart, and will be available as screenshots in the files*

2. A class diagram can change when you're editing the class during coding, I guess (?)

3. object diagrams can change when you are deleting the object, although we've never done that until now, or when the values of attributes are changed. 

4. private Intructor tutor;

8. No, only the first call resulted in a change in the stored value (from 6 to 3), while the second one did not. As we talked about in class, the code in written with specific parameters. If the entered value is outside of the range, the value will not change (which prevents us from entering huge value or nagative ones).

9. If we set the value of the newly created 'digit' object to 10, which is it's rollover limit, it will simply go back to 0. 

11. Well, I'm working on my project at home, and my PC's language is set to Chinese, so the error message is a bunch of shenanigans. What I do know is that we are simply supposed to put a number between the parenthesis, and since int is a keyword, it's considered an error. All we have to do is just remove the int. 

12. Now that the <= has been added, the problem encountered in the second part of problem 9 will no longer occur. This is simply because of the =. Before, the value could only be changed if it's smaller than the limit (which didn't include the limit). However, now that we've added the =, it includes it.

13. It would be 0, since 0 is not bigger than 0, and the new code specifically stated that replacementValue > 0.

14. Since we now changed the && to ||, we basically made it so that now, only one side has to be true in order for the condition to work. Doing so basically goes againts everything we've done before, because now even the negatives and the really, really huge numbers can be set as value.

15. The NOT of true is false. The NOT of false is true. 2 is not bigger than 2 (left side is false), and 1 is not smaller than 0 (right side is also false), so the entire thing is false. Same thing again, but this time it's three comparisons: 2 isn't bigger than 2, 4 is equal to 4, but 1 isn't smaller than 0, so the entire thing is false. And finally, 34 is NOT equal to 33, so it's true, and NOT false is true, so the entire thing is true.

16. (a && b) || (!a && !b)

17. (a && !b) || (!a && b)

18. No, it does not work under any circumstances. For instance, I've tried to set the value to 100, but when I called the getDisplayValue method, the return was "00", which is a two digit String.

19. They do the same thing, but the second one is the one that we learned in class, and it looks a bit better, I guess. They both put the value between the "" and turns it into a string.

20. I had to do some research online for this, but what I found out is that if the string comes last, like in the first instance, then the numbers will add first. But if the string comes first, like in the second instance, the numbers get treated like a string too, which is why they were not added together.

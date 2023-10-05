# Assignment 3 - Writeup

Assignment 3 is all about creating this natural language query system.  In order to do so, you have to write a lot of functions to retrieve infomation.  You will also have to write a function to return answers from a pattern-action list.  There is a lot of work to accomplish in this assignment, but this portion is intended for you to write about what you accomplished.

## Reflection Questions
1. In your own words describe the `search_pa_list` function.
It checks to see if both the title and year are in the list when you give it and it searches through the list until both matches, therwise it returns "I don't understand"

2. What movie did you add to the `movies.py` file?  What year was it made? Any specific reason you added that movie?
Transformers, made in 2007 with no reason at all

3. What pattern / action did you add to the paList data structure?  Why do you think that is a useful pattern / action?
actor_by_year as this allows you to find an actor and see how long they have acted for.

4. What is chatbot would you create that would be like this?  Describe why you would create it and what it would do.
A chatbot which would find an actor and calculate how long they have acted based on the list, so if in the movie list an ator acted in a movie in 1990 and 2000, te chatbot will return "(actors name) has acted for (10) years".

5. What was the most difficult portion of this assignment?
search_pa_list for the if statement portion

6. Did you write a new assert for your pattern action?
No

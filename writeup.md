# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?

I learned a lot about appending items to lists, especially a lot about tuples, which are very interesting. I learned how programs interact with each other and with databases and how they get information from them with lists. I learned how to create systems of similar functions that interact with a pool of possible questions and how they come to an answer by filtering a query through many possible queries and finding the words to look for.

2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.

The user types a query, which goes through the query loop. The loop searches through the pa list until it finds a match, the runs the function coresponding to that query. The function associated with the prompt searces the movie database for movies that meet the criteria provided by the prompt, then gets the information about the move that was resquested. The function recives the info, and returns it to the user.


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?

A system like this is good for smaller groups of people who are familiar with the system and use it for searching large databases. The strict prompt requirements means it likely wont work well with a larger userbase who dont know how to prompt the AI. It could be improved with the addition of more flexible prompts to be more practical for your everyday person.
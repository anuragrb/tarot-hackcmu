krowder app


Anurag Bhatt, Daniel Hasegan

Krowder

Existing features: https://github.com/dhasegan/tarot-hackcmu, http://tinyurl.com/tarotcmu

1. Basic models for a user, question, answer
2. Registration, login, logout
3. Users can add questions
4. Answer questions with numerical values only
5. Templates for all these
6. Algorithm for averages and scores
7. Uses bootstrap for css and bootstrap js libraries
8. Uses ajax at various points in question submission

Extending/features to add

1. More complete registration system
Self explanatory

2. Retroactively set the correct answer
We want users to know how they have done and challenge an answer that could be set incorrectly. The answer to a question can be retroactively set by the user who created that question or by a moderator. 

3. Real time histogram of the results
Users can see how they compare with their peers and friends. 

5. User profiles, friend/follower system
Self explanatory. We can decide what information to ask for after we decide on our target demographic.

6. Question categories, question types
We don't want to restrict users to just one type of question. They can ask questions with numerical answers, yes/no questions, polls, "would you rather" style questions, etc. Only some of these types would have a correct answer.

7. Improve the UI
Self explanatory

8. Upvote/downvote system
Ties in with answer explanations. Users can optionally justify their choices, and other users can vote on whether the explanation of the answer is constructive or not. 

9. Explanations for answers and questions
For questions: We would have an optional headline that users can use to describe their intent.

For answers: Description/justification of the answer.

10. User history of answers
To assess the "reliability" of users, similar to reddit karma

11. Question visibility filtering
Followers' questions, question searching, question categories, related categories, etc.

12. User groups
regular users, mods, admins, etc.

4. Predictive graphs based on past results
Not yet brainstormed, but the idea is to have graphs that predict how future trends for similar question categories would work

13. Trend graphs visible to the question asker.
Graphs to see how the answer has changed over time

For graphing, we plan to use rickshaw.js/dygraphs/flot, depending on which of these libraries best suit our data formats. 



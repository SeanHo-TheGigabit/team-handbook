# Backend Development Advice

## When there is new task arrive

Flow:

1. Task been assigned
2. Study Requirement
3. QnA
4. Proposal (UI how to change, API how to design)
5. Development

Remark:

- Step 2-4 must not be too long, minimize the flow
- If cannot see the requirement, then ask
- Usually Glendon task need not build from the scratch
- Chatgpt is good for the research or code draft starting, speed up develope and sorten the time

Personal feeling:

- Most important is the output, strive for the task done
- Whenever want to submit the task, ask yourself, what you want Glendon do to deploy your this thing? You are the ownership of your task, you take 100% responsibility of your task. Also included for the frontend data integrity as well, ask some question to frontend team and see how will the data flow toward user face.

## When new feature release

1. Beware on the data structure change

If there is the data structure change, we need to consider the following:

- the migration on the database plan
- the backward compatibility function or stuff

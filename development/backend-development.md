# Backend Development Advice

- [When there is new task arrive](#when-there-is-new-task-arrive)
- [Before start coding](#before-start-coding)
- [When new feature release](#when-new-feature-release)
- [When create a new endpoint](#when-create-a-new-endpoint)
- [Before commit and push](#before-commit-and-push)
- [Why so hard to ask](#why-so-hard-to-ask)
- [What is the cost of not ask](#what-is-the-cost-of-not-ask)
- [Why i have the courage to ask](#why-i-have-the-courage-to-ask)
- [How to ask](#how-to-ask)

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
- Whenever want to submit the task, ask yourself, what you want Glendon do to deploy your this thing? You are the ownership of your task, you take 100% responsibility of your task.
- Also included for the frontend data integrity as well, ask some question to frontend team and see how will the data flow toward user face.

## Before start coding

1. Leave a message to glendon before start

## When new feature release

1. Beware on the data structure change

If there is the data structure change, we need to consider the following:

- the migration on the database plan
- the backward compatibility function or stuff

## When create a new endpoint

- Always need to take care about the default value of the endpoint, expecially if we not gonna save a default value in the database.
- If it is a sensitive information, such as password, or API key, we need to take care about the security of the endpoint.
- Use uuid7 as the PK instead integer

## Before commit and push

- make sure no print() in the code

## Why so hard to ask

1. Feel i am incapable to ask, that if this question is too stupid to ask, or is the progress to slow to be asked.
2. Doesnt feel professional if I not go through like at least one round of trying.

## What is the cost of not ask

1. 

What if i ask

1. Either there i

## Why i have the courage to ask

1. Almost deadline, either continue fear or project undergo explossion
2. Glendon look not busy or doesnt seem to have mood
3. I feel i need to overcome this fear of been judge, potentially rejected

## How to ask

1. I feel the blockage is the goal look different. Glendon want something robust, not easy comeout error, then only come with the speed of progress. While my goal more focus on what is the task and how quick can i finish. (More like a exam kind of thinking)

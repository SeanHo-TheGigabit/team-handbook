# Backend Development Advice

- [When there is new task arrive](#when-there-is-new-task-arrive)
- [Before start coding](#before-start-coding)
- [When new feature release](#when-new-feature-release)
- [When create a new endpoint](#when-create-a-new-endpoint)
- [Before commit and push](#before-commit-and-push)

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

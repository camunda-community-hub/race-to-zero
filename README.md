# Race to Zero

A trivia game played in Camunda Platform Tasklist. 

The objective is to clear your inbox of tasks/trivia questions as fast as possible. 


## How to prepare questions

Before playing the game you need to prepare the questions you want to ask in the trivia game. 

The file [cards.json](./cards.json) contains examples for:
* Yes/No questions
* Number questions
* Multiple choice questions

Simply add your own questions and expected answers. The JSON snippet can then be passed in when starting a process instance.

## How to play
1. Deploy [./bpmn/race-to-zero.bpmn](./bpmn/race-to-zero.bpmn) process
2. Start an instance of this process and pass in the questions (see above)
3. Go to Tasklist


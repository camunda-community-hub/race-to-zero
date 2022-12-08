# Race to Zero
![Community Badge](https://img.shields.io/badge/Community%20Extension-An%20open%20source%20community%20maintained%20project-FF4700)
![Compatible with: Camunda Platform 8](https://img.shields.io/badge/Compatible%20with-Camunda%20Platform%208-0072Ce) 
[![](https://img.shields.io/badge/Lifecycle-Stable-brightgreen)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#stable-)

A trivia game played in Camunda Platform Tasklist. 

The objective is to clear your inbox of tasks/trivia questions as fast as possible. 


## How to prepare questions

Before playing the game we need to prepare the questions we want to ask in the trivia game. 

The file [cards.json](./cards.json) contains examples for:
* Yes/No questions
* Number questions
* Multiple choice questions

Simply add your own questions and expected answers. The JSON snippet can then be passed in when starting a process instance.

## How to play
1. Deploy [./bpmn/race-to-zero.bpmn](./bpmn/race-to-zero.bpmn) process
2. Start an instance of this process and pass in the questions (see above)
3. Go to **Tasklist**


## Contributing
* [Contributing Guide](./CONTRIBUTING.md)
* [Code of Conduct](./CODE_OF_CONDUCT.md)

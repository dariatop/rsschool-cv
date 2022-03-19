<img src="https://avatars.githubusercontent.com/u/94568393?v=4" alt="myphoto" width="15%"/>

# Daria Pavlova
#### *Junior Frontend Developer*

******

## Contacts
- **Location:** Georgia, Tbilisi

- **Phone:** (+995)551079788

- **E-mail:** dariatop1@gmail.com

- **GitHub:** dariatop


## About me
I'm e-learning developer. I develop interactive courses with Articulate Storyline software. 
I studied JS in Hexlet (Frontend) and successfully completed the 1st project - "Brain Games". 
My husband (an EPAM engineer) and I moved to Georgia after the war had started.
My current goal is to develop my front-end skills with a help of RS school so that I can get a job as a junior front-end developer by the end of the year.


## Skills
* JavaScript (Fundamentals,Functional Programming)
* HTML
* CSS
* Packet managers
* Linux OS/MacOS
* Shell scripting
* Webpack 
* Git
* VS Code
* Adobe suite
* Project management skills (Agile, Kanban)

## Code examples
```
import readlineSync from 'readline-sync';

const roundsCount = 3;

const engine = (gameDiscription, generateRound) => {
  const userName = readlineSync.question('Welcome to the Brain Games!\nMay I have your name? ');
  console.log(`Hello, ${userName}!`);
  console.log(gameDiscription);
  for (let i = 0; i < roundsCount; i += 1) {
    const [question, expected] = generateRound();
    console.log(`Question: ${question}`);
    const actual = readlineSync.question('Your answer: ');
    if (expected !== actual) {
      console.log(`'${actual}' is wrong answer ;(. Correct answer was '${expected}'.\nLet's try again, ${userName}!`);
      return;
    }
    console.log('Correct!');
  }
  console.log(`Congratulations, ${userName}!`);
};
export default engine;
```
## Education
* Togliatti Academy of Management:
    * Management (specialist)
* Hexlet school:
    * Frontend developer (30% progress)

## Experience
[Project "Brain Games"](https://github.com/dariatop/frontend-project-lvl1 "Click me")

*CLI app for brain training  - my first project in Hexlet School.*

## Languages
1. **English** - B2+ 
2. **French** - A1

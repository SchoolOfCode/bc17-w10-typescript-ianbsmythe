# The Basics of TypeScript

## The Foundations of TypeScript
The foundation of TypeScript is JavaScript - a language that makes web pages more interactive. Any modern website will utilise some amount of JavaScript. Furthermore, the more complex the site; the more complex the JavaScript. 

JavaScript, however, was not built fo building complex systems.

## The Beginnings of TypeScript

Developers started looking for a betetr way to write JavaScript.  

Around 2010, Microsoft noticed that a lot of their teams were using a community project called Script# (ScriptSharp) to build their JavaScript apps. This library allowed developers to write code in C#, and then turn it to JavaScript. C# had excellent features for building large applications - so it made the experience of building these apps more pleasant. In fact, many teams had found this was the only way they could build complex applications in large teams. Anders Hejlsberg, the creator of C#, was tasked to investigate this phenomenon...

People were so annoyed with JavaScript that they were willing to code in a completely different language in order to get the powerful *IDE (integrated development environment) features they were used to.

He create a new language that was closer to JavaScript. One that enabled all of the IDE features that JAvaScript was missing - TypeScript was born. It is now a staple of modern development. In many metrics, it is even more popular than JavaScript. 

*An IDE (Integrated Development Environment) is a software application that helps programmers write, test, and debug their code more easily. It combines tools like a code editor (where you write code), a compiler (which turns your code into something a computer can run), and a debugger (to find and fix errors). An IDE also often includes features like auto-completion, syntax highlighting, and project management to make coding more efficient. Examples of IDEs include Visual Studio, PyCharm, and Eclipse.*

## How TypeScript Works

- In typeScript, the code is primarily inside a `.ts` file;
- Inside your IDE, these files are monitored by TypeScript's 'language server'.  This server watches as you type, and powers IDE features like autocompletion and error checking, among many others.
- `.js` files can be executed directly by the browser or runtime; `.ts` files can't - they need an initial build process. 
- This is where TypeScript's `tsc` Command Line Interface (CLI) comes in.  It transforms your `.ts` files into `.js` files. 
- This enables you to take advantage of TypeScript's features while writing your code, but the output is still plain JavaScript. 
- **Benefits of this system:** Get in a feedback loop with TypeScript - Write code; the in-IDE server gives feedback; you adjust by the feedback; this all occurs before code goes into the browser.
- This loop is faster than JavaScript's so can help create higher-quality code faster. 

## What is Different About TypeScript? 

- **TYPES**
- Typescript was built tp allow amazing tooling for JavaScript.
- If you know the types of everything in your application, you can implement powerful IDE features like autocomplete, inline erros and automatic refactors.

## Tools for TypeScript Development




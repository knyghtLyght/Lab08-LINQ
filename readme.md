D![cf](http://i.imgur.com/7v5ASc8.png) Lab 8 : LINQ in Manhatten
=====================================

## To Submit this Assignment
- fork this repository
- write all of your code in a directory named `lab-#`; + `<your name>` **e.g.** `lab08-amanda`
- push to your repository
- submit a pull request to this repository
- submit a link to your PR in canvas


## Directions
Provided is a JSON file that contains a data set of location information for properties in Manhatten.
- Read in the file and answer the questions below
- Use LINQ queries and Lambda statements (when appropriate) to find the answers. 
- You must have a mix of LINQ queries and Lambda expressions when answering the questions

## Setup
- Add the data.json file to your solution root folder
- Explore the NuGet packages and install NewtonSoftJson
- Do some self research and find out how to read in JSON file (hint: JsonConvert.DeserializedOject is *part* of it)
- You will need to break up each section of the JSON file up into different classes, use your resources - ask the TA's if your stuck. (Maybe find a converter of some sort??)

## Questions
Each query builds off of the next. ..
1. Output all of the neighborhoods in this data list
2. Filter out all the neighborhoods that do not have any names
3. Remove the Duplicates
4. Rewrite the queries from above, and consolidate all into one single query.

## ReadMe
A README is a module consumer's first -- and maybe only -- look into your creation. The consumer wants a module to fulfill their need, so you must explain exactly what need your module fills, and how effectively it does so.
<br />
Your job is to

1. tell them what it is (with context)
2. show them what it looks like in action
3. show them how they use it
4. tell them any other relevant details
<br />

This is ***your*** job. It's up to the module creator to prove that their work is a shining gem in the sea of slipshod modules. Since so many developers' eyes will find their way to your README before anything else, quality here is your public-facing measure of your work.

<br /> <br /> Refer to the sample-README in the class repo for an example. 
- [Reference](https://github.com/noffle/art-of-readme)

## Rubric
- 7pts: Program meets all requirements described in Lab directions

	Points  | Reasoning | 
	 ------------ | :-----------: | 
	7       | Program runs as expected, no exceptions during execution |
	5       | Program runs/compiles, Program contains logic/process errors|
	4       | Program runs/compiles, but throws exceptions during execution |
	2       | Missing tests // tests are not passing // not enough valid tests |
	2       | Missing Readme Document // Readme Document does not meet standards |
	0       | Program does not compile/run. Build Errors. |
	0       | No Submission |

- 3pts: Code meets industry standards
	- These points are only awardable if you score at minimum a 5/7 on above criteria

	Points  | Reasoning | 
	 ------------ | :-----------: | 
	3       | Code meets Industry Standards // methods and variables namings are appropriate // Selective and iterative statements are used appropriately, Fundamentals are propertly executed // Clearly and cleanly commented |
	2       | syntax for naming conventions are not correct (camelCasing and PascalCasing are used appropriately) // slight errors in use of fundamentals // Missing some comments |
	1       | Inappropriate naming conventions, and/or inappropriate use of fundamentals // Code is not commented  |
	0       | No Submission or incomplete submission |



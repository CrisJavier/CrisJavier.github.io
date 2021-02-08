---
layout: essay
type: essay
title: Coding Standards Improve the Quality of Your Coding and Standards
# All dates must be YYYY-MM-DD format!
date: 2021-02-07
labels:
  - Coding Standards
  - Software Engineering
---

```ruby
/**
 * How many violations of the AirBnb Javascript Style guide can we pack into one file?
 * Created by Philip Johnson on 8/4/16.
 */

var foo = 3;
const car = "Toyota";
const obj = {
  car: car,
  'foo': 3,
  bar: 'this' + 'is' + this.car,
  baz: 'b\az'
};
const zumba = obj['car'];
const stuff = new Array();

function f(){};
function zob(param) {
  param = 2;
  let foob=4+param;
  if (param == 4) {
    return foob;
  }
}
[1, 2, 3].map(function (x) {
  const y = x + 1;
  return x * y;
});
class MyClass {
  constructor() {}
  getName() {
    return this.name;
  }
  getName() {
    return this.name;
  }
}
const TheTitle = 'The Title';
```

## Cleanup on Aisle 2!

Look at this piece of work. For an outsider looking in or if you were to take just a simple glance at the code you wouldn't see much of an issue with it. But look at it for longer than a second and you see the equivalent to having a sink full of dishes, a movie theatre's floor after the a screening of the next big Marvel Movie, or my room. Simply put, it's a mess. It's not consistent with its use of quotes ie: single quotes versus double quotes. It's got some code that's outright redundant such as having two functions with the exact same name and the exact same value returned. And right at the beginning of all this mess, there's a variable initialized using 'var' (???) and isn't even used anywhere else in the code. 

## What the Heck are Coding Standards?

If only there existed some sort of guideline for this code so atrocities like the above can be cleaned easier. Oh wait, they do exist! Introducing coding standards. Coding standards help the development of software programs that are less complex and thereby reduce the errors. Assuming the standards are met whenever someone finishes some work on their code, all subsequent code will be easier to follow, maintain, or even edit because theoritically anyone can understand it. None of the glaring issues possible without the coding standards will exist, bar some oversights from the initial coding standards. When implemented into your code, you may be able to see markers where the coding standard will determine needs to be fixed because it violates a standard. It could be anything from redundant functions, a variable never used, improper variable initialization, etc. 

## Can't Get Enough of Those Green Checkmarks

At the very least, that was what I experienced the first time I was met with coding standards. The above code was actually created intentionally to see how many violations of the 'AirBnB Javascript Style guide' they could pack into a single file. Turns out they were able to fit around 28. My task was to go through this piece of work using ESLint with IntelliJ and make sure I turn all of the red errors into a single green checkmark. The task was handled similarly to having to clean my room. Initially, the task seems unending and may take 'forever'. But once I get started I just keep going until the whole thing is clean, line by line. We never use a variable? Just get rid of it. Redundant function? In the trash. Inconsistent use of quotes? Just turn that double quote into a single quote. Line by line I worked through the code until in the top right of my IntelliJ UI, I see a '✅', filling me much deserved feeling of satisfaction. Like I had somehow made the world a better place by cleaning up the mess that was handed to me. I personally feel that even given the relatively small amount of time I've experienced coding with coding standards, my code has become miles more legible and much easier to understand.

## Are Coding Standards Perfect?

I believe coding standards should be implemented by any software engineer looking to improve their coding 'handwriting' or legibility because they help make your code clean consistently. However, I don't think they're perfect. Coding standards can be extremely subjective. People will eventually have different coding standards from yourself. I could easily imagine trouble starting because some people refuse to have to reallign their code to match what someone else judges to be the 'right way to code'. That possibly being the case, coding standards may not be 100% perfect but I still think they're better than nothing.
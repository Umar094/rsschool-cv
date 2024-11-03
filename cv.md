# Full Name - Umar Ulbiev

===

## Contact Information

**DISCORD** umar_68063

**Telegram** t.me/okifree

===

## Self-Introduction
Hello everyone, I want to tell about my jorney. The **main reasone** I started to learn programing is I wanted to find the thing that I like to do, I started when I was at school(3-4 years ago), It was not intense learning. I started to seriously learn front-end like 4 monts ago.

***What did I do to learn effectively?***
    +codewars
    +more practice then theory
    + makeup of websites (from **easy** to **hard**) then with **JS**
===

## Skills
* HTML
* CSS
* JavaScript
* REACT
* A little bit of TAILWIND
* SCSS
* A little bit of BEM

## Code Examples from CodeWars

===

***Description***

Time to win the lottery!

Given a lottery ticket (ticket), represented by an array of 2-value arrays, you must find out if you've won the jackpot.

Example ticket:

[ [ 'ABC', 65 ], [ 'HGR', 74 ], [ 'BYHT', 74 ] ]
To do this, you must first count the 'mini-wins' on your ticket. Each subarray has both a string and a number within it. If the character code of any of the characters in the string matches the number, you get a mini win. Note you can only have one mini win per sub array.

Once you have counted all of your mini wins, compare that number to the other input provided (win). If your total is more than or equal to (win), return 'Winner!'. Else return 'Loser!'.

===

**Solution**

```
function bingo(ticket, win){
    let  result = 0;

    ticket.forEach(element => {
        let string = element[0];
        let winCharCode = element[1];

        for(let i = 0; i < string.length; i++){
            if(string.charCodeAt(i) === winCharCode){
                result += 1
            }
        }
    });

    return result >= win ? 'Winner!' : 'Loser!';
}
```

===

## Projets

I have a few of projects that I like to show.

**Calculator**
    1. https://umar094.github.io/calculator-app-main/

**Responsive site**
    2. https://umar094.github.io/sideProject/

===


## My English

I think my english is between A1 and A2, I learned english watching videos, movies, reading, in english, not so far I started learning some words in Anki. 




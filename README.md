# 2-2-2022
// Started at 4:55 2-2-2022
// Coding challenge #2

const calcTip = function (bill) {
    return bill >= 50 && bill <= 300 ? bill * 0.15 : bill * 0.2
}
const bills = [125, 555, 44];
const tips = [calcTip(bills[0]), calcTip(bills[1]), calcTip(bills[2])];
const totals = [bills[0] + tips[0], bills[1] + tips[1], bills[2] + tips[2]];

console.log(bills, tips, totals); 


const jonasArray = [
    'Jonas',
    'Schmedtmann',
    2017 - 1991,
    'teacher',
    ['Micheal', 'Peter', 'Steven']
];

const jonas = {
    firstName: 'Jonas',
    lastName: 'Schmedtmann',
    age: 2037 - 1991,
    job: 'teacher',
    friends: ['Micheal', 'Peter', 'Steven']
};


const jonas = {
    firstName: 'Jonas',
    lastName: 'Schmedtmann',
    age: 2037 - 1991,
    job: 'teacher',
    friends: ['Micheal', 'Peter', 'Steven']
};
console.log(jonas);

console.log(jonas.lastName)
console.log(jonas['lastName']);

const nameKey = 'Name';
console.log(jonas['first' + nameKey]);
console.log(jonas['last' + nameKey]);

// console.log(jonas.'last' + nameKey);

const interestedIn = prompt(`What do you want to know about Jonas? Choose between firstName, lastName, age, job, and friends`);

if (jonas[interestedIn]) {
    console.log(jonas[interestedIn]);
} else {
    console.log(`Wrong request! Choose between firstName, lastName, age, job, and friends`)
}

jonas.location = 'Portugal';
jonas['twitter'] = '@jonasschmedtmann';
console.log(jonas);
*/
// Challenge
// "Jonas has 3 friends, and his best friend is called Micheal"

const jonas = {
    bestFriend: 'Micheal',
    friend1: 'Bobby',
    friend2 = 'Steve'
}
console.log(`Jonas has ${jonas[length]} friends, and his best friend is called ${jonas.bestFriend}.`)
// ended at 5:56 2-2-2022
// episode 43 @14:48

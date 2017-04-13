Javascript 4/30 Array Cardio

What I learned:

console.table(); will show results in table as opposed to console.log();

Array.prototype.map() will always return same amount

Array.prototype.sort() ternary statement can be used to shorten

const ordered = inventors.sort((firstPerson, secondPerson) => firstPerson.year > secondPerson.year ? 1 : -1);

console.table(ordered);
function greet(name) {
    return "Hello, " + name + "!";
}

console.log(greet("COGNIFY")); 


let score = 85;

if (score >= 90) {
    console.log("Grade: A");
} else if (score >= 80) {
    console.log("Grade: B");
} else {
    console.log("Grade: C");
}

for (let i = 0; i < 5; i++) {
    console.log(i); 
}

let i = 0;
while (i < 5) {
    console.log(i); 
    i++;
}
let numbers = [1, 2, 3, 4, 5];
numbers.forEach(function(number) {
    console.log(number); 
});


function findHighestMarks(marks) {
    let highest = marks[0]; 

    for (let i = 1; i < marks.length; i++) {
        if (marks[i] > highest) {
            highest = marks[i]; 
    }

    return highest; 

}

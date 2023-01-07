# Week-3-Repo
Week 3 repository for assignments
//#1a
var arrayOfAges=[3,9,23,64,2,8,28,93];
//created array
//to access an index, use [] with the number of index
console.log(arrayOfAges[7]-arrayOfAges[0]);
//printed sum of subtracting two values

//#1b
arrayOfAges.push(42);
//added a number to array
console.log(arrayOfAges[8]-arrayOfAges[0]);
//print sum of subtracting two values

//#1c
function findAverage(arrayOfAges){
    let average=0;
    for( i=0; i < arrayOfAges.length; i++){
        let currentNum=arrayOfAges[i];
        average+=currentNum;
     }
    average=average/arrayOfAges.length;
return average;      
}
console.log(findAverage([3,9,23,64,2,8,28,93,42]));
//created a function to find the average
//for loop used to iterate through the array
//all the array numbers equal to 272. Dividing it by 9 equals to the result 30.22



//#2a
 let arrayOfNames=['Sam','Tommy','Tim','Sally','Buck', 'Bob'];
//array of given names created

//#2b
let totalNameCount=0;
let nameCount=0;
let characters='';
for(let i=0;i<arrayOfNames.length; i++){
let name=arrayOfNames.length;
nameCount+=arrayOfNames[i].length;
console.log(nameCount);
console.log(nameCount/arrayOfNames.length);
}

//#2b
//creeated loop to concatenate all the names in array with spaces
let nameString="";
for(let i=0;i<arrayOfNames.length; i++){
    nameString+=arrayOfNames[i]+" ";
   // return arrayOfNames;
}
console.log(nameString);
//console.log(arrayOfNames+" ");

//#3-To access last element of an array simply do array[last element] 
let colorsArray=["blue","pink", "red","white"]
console.log(colorsArray[3]);

//#4-To access first element of an array simply do array[first element]
console.log(colorsArray[0]);


//#5
arrayOfNames=['Sam','Tommy','Tim','Sally','Buck', 'Bob'];
nameLengths=[3,5,3,5,4,3];

//#6
function findSum(nameLengths){
    let sum=0;
    for( i=0; i < nameLengths.length; i++){
        let currentSum=nameLengths[i];
        sum+=currentSum;
     }
    sum=sum/nameLengths.length;
return sum;      
}
console.log(findSum([3,5,3,5,4,3]));


//#7
let word="hello ";
let n=2;
function multiply(word,n){
    let repeated=word.repeat(n);
    console.log(repeated);
} multiply(word,n);

//#8
let firstName= "Red";
let lastName="Harrington";
function fullName(firstName, lastName){
    this.firstName;
    this.lastName;
}console.log(firstName + " "+ lastName);


//#9
let numeros=[4,11,32,81];
let sum= 128;
function total(numeros){
 if(sum<100){
    return false;
 }else if(100<sum){
    return true;
 }
}console.log(total(numeros,sum));


//#10
array1=[1,2,3,7,10,12,21];
function numbers(array1){
    let total=0;
    for( i=0; i < array1.length; i++){
        let currentTotal=array1[i];
        total+=currentTotal;
     }
    total=total/array1.length;
return total;      
}
console.log(numbers([1,2,3,7,10,12,21]));


//#11
//I created two arrays with two separate corresponding functions to find the average
randomNumberArray=[32,11,88];//131/3=43.66
secondNumbersArray=[44,25,1];//70/3=23.3

function meanOfNumbers(randomNumberArray){
    let aggregate =0;
for(let i=0; i<randomNumberArray.length; i++){
    let digit= randomNumberArray[i];
    aggregate+=digit;
}
    aggregate=aggregate/randomNumberArray.length;
    return aggregate;
}

console.log(meanOfNumbers([32,11,88]));

//second function created

function doubleTrouble(secondNumbersArray){
    let aggregate =0;
for(let i=0; i<secondNumbersArray.length; i++){
    let digit= secondNumbersArray[i];
    aggregate+=digit;
}
    aggregate=aggregate/secondNumbersArray.length;
    return aggregate;
}
console.log(doubleTrouble([44,25,1]));

//created a function to compare both functions

function comparison(meanOfNumbers,doubleTrouble){
if(secondNumbersArray<randomNumberArray){
    return true;
}else{
   return false;
   }
}console.log(doubleTrouble<meanOfNumbers);

//# 12
var drink=10.50; //created a variable to compare moneyInPocket with
var isHotOutside="true"; //boolean expression
var moneyInPocket=0; //set to 0, depending on user input

function willBuyDrink(isHotOutside,moneyInPocket){
    if(isHotOutside=== "true"){
        return true;
     while(drink<moneyInPocket){
            return true;
        }
    } 
}

//#13 Create a function to solve a problem.
//Problem: Do I enough money to go to the movies??

var ticketPrice= 15.00;
var movieSnacks= 20.00;
var cashAvailable= 45.00;

function movieMoney(){
    let totalPrice=ticketPrice+movieSnacks;
    if(totalPrice<= cashAvailable){
        console.log("Let's go to the movies!");
    }else{
        console.log("Bummer, not enough money for movies.");
    }
} movieMoney();

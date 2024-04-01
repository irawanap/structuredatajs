# structuredatajs

first learn about structure data


let restaurant = {
    name: "Bakso Mang Dicoding",
    city: "Bandung",
    "favorite drink": "Es Teh",
    "favorite food": "Bakso",
    isVegan: false
};

let name = restaurant.name;
let favoriteDrink = restaurant["favorite drink"];

console.log(name);
console.log(favoriteDrink);


let evenNumber = [];

for (let i = 1; i <= 100; i++) {
    if (i % 2 === 0) {
        evenNumber.push(i);
    }
}

console.log(evenNumber);


let currency = new Map([
  ["USD", 14000],
  ["JPY", 131],
  ["SGD", 11000],
  ["MYR", 3500],
 ]);

 const priceInJPY = 5000;

const priceInIDR = priceInJPY * currency.get("JPY");
console.log(priceInIDR);

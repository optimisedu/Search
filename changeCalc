//node index.js

const change = [
    {
        twoPound: 2,
        onePound: 1,
        fiftyPence: 0.50,
        twentyPence: 0.20,
        tenPence: 0.10,
        fivePence: 0.05
    }
]


const changeCalculator = (amount) => {
    let change = [];
    let remaining = amount;
    let twoPound = Math.floor(remaining / 2);
    remaining = remaining % 2;
    let onePound = Math.floor(remaining / 1);
    remaining = remaining % 1;
    let fiftyPence = Math.floor(remaining / 0.50);
    remaining = remaining % 0.50;
    let twentyPence = Math.floor(remaining / 0.20);
    remaining = remaining % 0.20;
    let tenPence = Math.floor(remaining / 0.10);
    remaining = remaining % 0.10;
    let fivePence = Math.floor(remaining / 0.05);
    remaining = remaining % 0.05;
    change.push({ twoPound, onePound, fiftyPence, twentyPence, tenPence, fivePence });
    console.log(change);
}

changeCalculator(41.25);

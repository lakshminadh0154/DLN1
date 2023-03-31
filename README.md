const numbers = [3, 5, 9, 10, 12, 15, 18, 20, 21];
const divisibleByThree = [];

for (let i = 0; i < numbers.length; i++) {
  if (numbers[i] % 3 === 0) {
    divisibleByThree.push(numbers[i]);
  }
}

console.log(`Numbers divisible by 3: ${divisibleByThree}`);

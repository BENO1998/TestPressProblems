# TestPressProblems

1.Reverse String:

function ReverseString(str) {
    return str.split('').reverse().join('')
}

console.log(ReverseString("codecode"))

2.Prime Or Not:

function test_prime(n)
{

  if (n===1)
  {
    return false;
  }
  else if(n === 2)
  {
    return true;
  }else
  {
    for(var x = 2; x < n; x++)
    {
      if(n % x === 0)
      {
        return false;
      }
    }
    return true;  
  }
}

console.log(test_prime(4));

3. Arranging Largest Value From given array:

const largest = (...nums) => nums.sort((a, b) => ('' + b + a) - ('' + a + b)).join('');

console.log(largest(54,546,548,60));

4. Print Reverse Of number:

  const reverseNumber = number => parseFloat(number.toString().split('').reverse().join('')) * Math.sign(number)

console.log(reverseNumber(988))

5. Minimum and Maximum Value:

function MinMax() {
    let Arr = [54, 546, 548, 60];
console.log("Minimum element =:" + Math.min(...Arr));
    console.log("Maximum Element =:" + Math.max(...Arr));
}
 
MinMax();

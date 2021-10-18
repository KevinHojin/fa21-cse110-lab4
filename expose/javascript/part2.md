Q1: 3, observe that prices.length is 3. Then at the point where the loop with i = 2, i will increment to 3, but it will stop at the condition check at next loop. So, i will be 3.
Q2: 150, after the for-loop is finished, last value that is assigned to discounted Price would be 300 * 0.5 which is 150.
Q3: 150, from the above, last value that is assigned to finalPrice would be Math.round(150*100) / 100 which is 150
Q4: The function will return array of [50, 100, 150]. Our input prices array was [100, 200, 300]. Then we go into the for-loop with discount rate 0.5. So each element will have finalPrice of half of its original price. Then each element is pushed to 'discounted' array. Therefore, the return value which is 'discounted' will have array of [50,100,150]
Q5: error. As 'let' will be held in its block, 'i' is not defined out of for-loop. Therefore, i cannot be printed.
Q6: error. Same syntax with Q5, 'discountPrice' is not defined out of for-loop, as 'let' is defined in its block.
Q7: 150. finalPrice is in the same block with 'console.log(finalPrice)', so 'finalPrice' can be accessed with its final assinged value, which is 150.
Q8: [ 50, 100, 150 ]. As same syntax with Q7, 'discounted' is in same block with return statement, it can be returned with pushed array of [50,100,150] (reference from Q4)
Q9: error. Same syntax with Q5. 'i' is not defined out of for-loop becuase 'let' will be held in its block. Therefore, console.log(i) cannot be printed.
Q10: 3. As input prices is [100,200,300], the length of prices array is 3. And length has not been reassigned, so it will print 3.
Q11: [ 50, 100, 150 ]. Inside of for-loop, it will run from i = 0 to i = 2. Also we have discount rate of 0.5, each element will be pushed at discount rate of 0.5. Observe that const discountedPrice is declared each loop, not being re-reassgined.
Q12
A: student.name
B: student["Grad Year"]
C: student.greeting()
D: student["Favorite Teacher"].name
E: student.courseLoad[0]
Q13
A: '32', as integers map to their exact string representation
B: 1, '3' is converted to number, so 3-2 = 1
C: 3, null becomes 0, so 3 + 0 = 3
D: '3null', 3 is concatenated with null as a string
E: 4, true is mapped to 1 so 1+3 = 4
F: 0, false maps to 0 and null also maps to 0, so 0 + 0 = 0
G: '3undefined', 3 is concatenated with undefined as a string
H: NaN, undefined maps to NaN and 3 maps to number, so 3-NaN = NaN
Q14
A: true, '2' becomes number 2
B: false, '2' is compared to '1' from '12', so '2'>'12'. Therefore false.
C: true, '2' becomes number 2
D: false, types are different
E: false, true maps to 1, but 1 and 2 are not equal
F: true, Boolean(2) is true, so they are same with same type
Q15: While == allows conversion to test equality, === does not allow conversion. So, to test equality using ===, they should have same type.
Q17: [ 2, 4, 6 ], so from modifyArray, we passed doSomething as an argument. Inside of modifyArray function, we perform 'newArr.push(callback(array[i]));'. Which means that 'newArr.push(doSomething(array[i]));'. Therefore, each element for input array will be doubled by doSomething function, which will result in returning [ 2, 4 ,6 ].
Q19:
1
4
3
2

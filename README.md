BLOCK18 WORKSHOP: Writing Test Specifications

------- UNIT TESTS -------
* FORMAT: { Expect [action] to be [some result] }
1. Multiplication Function
  - expect [multiply(3,4)] to be [a number]
  - expect [multiply(3,4)] to be [equal to 12]
  - expect [multiply('a',4)] to be [an error]
  - expect [multiply()] to be [a no input error]
  - expect [multiply(2,4,6)] to be [too many arguments passed error]
2. ConcatOdds Function
  - expect [concatOdds([1,2,3,4,5],[3,5,7,9]) to be [an array]
  - expect [concatOdds([1,2,3,4,5],[3,5,7,9]) to be [1,3,5,7,9]
  - expect [concatOdds(1, 4)] to be [not enough arguments passed error]
  - expect [concatOdds([a,2,3],[2,5,7])] to be [an incorrect argument error]
  - expect [concatOdds([1,3],[2,4,5],[3,6,8])] to be [too many arguments passed error]

------- FUNCTIONAL TESTS -------
1. Shopping Cart CHeckout
* FORMAT: { when a user [does something with some parameters], [some thing should happen] }
  - When a user [adds item to shopping cart], [item & price (object) gets added to array]
  - When a user [removes an item from cart], [item {object} gets removed from array]
  - When a user [checks shopping cart], [all items displayed w/ individual price & total price]
  - When a user [tries to ], []

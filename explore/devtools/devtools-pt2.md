1. The bug was that num1 and num2 are of type let so they have block scope and don't exist outside the block they're defined in.
2. I would fix it by changing the type of num1 and num2 to be var.
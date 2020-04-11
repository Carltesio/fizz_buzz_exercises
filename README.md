# fizz_buzz_exercises
Fizz-Buzz is a group word game for children to teach them about division. Players take turns counting up from one, replacing any number that is divisible by three with the word ‘fizz’, any number divisible by five with the word ‘buzz’, and any number divisible by both three and five to be replaced with ‘fizz buzz’.

The “Fizz-Buzz test” is an interview question designed to help filter out the 99.5% of programming job candidates who can’t seem to program their way out of a wet paper bag http://wiki.c2.com/?FizzBuzzTest

Our objective is to write a ruby program that simulates the Fizz Buzz game.

REQUIREMENT OF FIZZ-BUZZ

The objective is to write a program that takes a number or an array of numbers and returns “fizz”, “buzz”, “fizz buzz” or the number (greater than zero) given certain conditions are fulfilled.

CONDITIONS

Return:

• “fizz” if the number is divisible by 3

• “buzz” if the number is divisible by 5

• “fizz buzz” if the number is divisible by 15

• the same number if no other requirement is fulfilled



## Installation

Install the rspec Gem to run the tests with rspec:
in your terminal run:
```bash
 gem "rspec"
```
then run the bundle command:
```bash
 bundle
```


## Usage

Try out your program again in irb. Remember that you have to load or require the source file. 
Now any number should work. That’s why we wrote our tests - so that we could be confident it would work under any scenario.

In your IRB console run the following examples to see it make it work:

```bash
$ irb
2.2.0 :001 > load './lib/fizz_buzz.rb'
 => true 
2.2.0 :002 > fizz_buzz(23)
 => 23 
2.2.0 :003 > fizz_buzz(3)
 => "fizz" 
2.2.0 :004 > fizz_buzz(6)
 => "fizz" 
2.2.0 :005 > fizz_buzz(10)
 => "buzz" 
2.2.0 :006 > fizz_buzz(45)
 => "fizz buzz" 
2.2.0 :007 >
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)



**Pages:** | [1](https://github.com/Thor-x86/varl/blob/master/docs/1-Getting_Started.md) | [2](https://github.com/Thor-x86/varl/blob/master/docs/2-Data_Types.md) | [3](https://github.com/Thor-x86/varl/blob/master/docs/3-Array_and_Object.md) | 4 | [5](https://github.com/Thor-x86/varl/blob/master/docs/5-Contribution.md) |  
  
# DOs and DON'Ts  
  
## Empty key is not allowed

### Don't:

    "" = some value

### Don't:

    = some value

## Watch for duplicate keys!

NOTE: lowest will replace its upper clone

### Don't:

    upin = betul tak? *this line is useless
    upin = betul betul betul

### Do:

    upin = betul tak?
    ipin = betul betul betul

## Equals sign inside key

### Don't:

    ==cool-key== = some value

### Do:

    "==cool-key==" = some value

## String cannot be multi line

### Don't:

    address = "Jl. Keputih,
	    Surabaya, Jawa Timur"

### Do:

    address = "Jl. Keputih,\nSurabaya, Jawa Timur"

## Object cannot be cramped into single line

### Don't:

    flower = {name = Tulip, color = 0xff, tall = 100}

### Do:

    flower = {
	    name  = Tulip
	    color = 0xff
	    tall  = 100
	}

## Array can be both multi-line or single line

### Do:

    friends = [Taylor Otwell, Evan You, Jeff Delaney, Ryan Dahl, Florian]

### Do:

    friends = [Taylor Otwell, Evan You,
	    Jeff Delaney, Ryan Dahl, Florian]

## Keep object multi-line event though inside array

### Do:

    library = [{
        name   = Harry Potter
        author = J. K. Rowling
    }, {
	    name   = Steve Jobs
	    author = Walter Issacson
	    year   = 2011
	}]

## Keep brackets balanced

### Don't:

    flower = {
	    name  = Tulip
	    color = 0xff
	    tall  = 100

### Do:

    flower = {
	    name  = Tulip
	    color = 0xff
	    tall  = 100
	}
  
##
  
**Pages:** | [1](https://github.com/Thor-x86/varl/blob/master/docs/1-Getting_Started.md) | [2](https://github.com/Thor-x86/varl/blob/master/docs/2-Data_Types.md) | [3](https://github.com/Thor-x86/varl/blob/master/docs/3-Array_and_Object.md) | 4 | [5](https://github.com/Thor-x86/varl/blob/master/docs/5-Contribution.md) |  
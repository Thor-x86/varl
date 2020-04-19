
**Pages:** | [1](https://github.com/Thor-x86/varl/blob/master/docs/1-Getting_Started.md) | [2](https://github.com/Thor-x86/varl/blob/master/docs/2-Data_Types.md) | 3 | [4](https://github.com/Thor-x86/varl/blob/master/docs/4-Do_and_Dont.md) | [5](https://github.com/Thor-x86/varl/blob/master/docs/5-Contribution.md) |  

# Array and Object  

.varl is not limited by each line of variables, it can do even more. Let's go further!

## Array

Storing array into .varl is essentially the same as you ever did before

    my numbers = [77, 32, 26, 11, 21, 11]

Splitting array into the next line is completely legal

    my numbers = [77, 32,
	    26, 11, 21, 11]

## Object

Storing object much like putting another .varl inside curly bracket, into a variable.

    ghost = {
	    name     = Kuntilanak
	    opacity  = 0.5
	    position = behind you
	}

If you want to access the ghost's name with javascript, it will be like

    ghost.name
    // output: "Kuntilanak"

Need to note that inside object, you have to separate each variable with line break like usual varl. It's not JSON anyway...

## Nested Array and Object

It's clearly legal to put array in array, object in object, array in object, etc...

    CPU     = AARCH64 v10
    RAM     = 16e9
    storage = [{
	    name   = Internal Flash Drive
	    type   = NAND
	    vendor = Samsnug
	    size   = 128e9
    }, {
	    name   = Micro SD Card
	    type   = SDHC
	    fs     = exFAT
	    vendor = 假的
	    size   = 1e12
	}]

##
  
**Pages:** | [1](https://github.com/Thor-x86/varl/blob/master/docs/1-Getting_Started.md) | [2](https://github.com/Thor-x86/varl/blob/master/docs/2-Data_Types.md) | 3 | [4](https://github.com/Thor-x86/varl/blob/master/docs/4-Do_and_Dont.md) | [5](https://github.com/Thor-x86/varl/blob/master/docs/5-Contribution.md) |  
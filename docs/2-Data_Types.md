
**Pages:** | [1](https://github.com/Thor-x86/varl/blob/master/docs/1-Getting_Started.md) | 2 | [3](https://github.com/Thor-x86/varl/blob/master/docs/3-Array_and_Object.md) | [4](https://github.com/Thor-x86/varl/blob/master/docs/4-Do_and_Dont.md) | [5](https://github.com/Thor-x86/varl/blob/master/docs/5-Contribution.md) |  
  
# Data Types
  
.varl supports universally frequently used  data types:

- String
- Boolean
- Number (integer, float, scientific, octal, hex, and binary)
- Array and Object ([next page](https://github.com/Thor-x86/varl/blob/master/docs/3-Array_and_Object.md))

The cool thing is ability to recognize what data type supposed to be :)
What did I meant by that? Let's figure out, shall we :D   

## String

In .varl syntax, you don't need to put any quote marks if the value is absolutely string like below.

    book title = Man Eats Catnip, now he is a CatMan!

The variable's key is **book title** with value **Man Eats Catnip, now he is a CatMan!**. That's obvious right! but... what about below?

    phone number = 08787135622

The .varl decoder will recognize that as number. What if we need that to be string? Just put the quote marks to enforce value as string as below

    phone number = '08787135622'

Now the value is string. Beside of that, there is a feature that derives from popular languages like JavaScript, PHP, Python, etc. It's **double quote marks.** Here is the example

    test = "Lorem Ipsum\n\t\"Dolor\" Amet\nConsectus"

Job of double quote marks is similar to single quote marks but allows [escaped characters](https://www.w3schools.com/js/js_strings.asp#midcontentadcontainer) in it. So, the value of **test** variable is

    Lorem Ipsum
	    "Dolor" Amet
    Consectus

You need to know that .varl only uses universal frequently applied escape characters (for sake of simplicity) as listed below.

**\n** => New Line (a.k.a. Enter)
**\t** => Tab
**\\\\** => Backlash ( \\ )
**\\\'** => Single quote ( ' )
**\\\"** => Double quote ( " )

Keep in mind that .varl uses UTF-8 encoding which is supports variety of characters including emojis 🤓.

One more thing, did you now that the variable's key always string?

    "cool key" = "hot value! \n :)"

Guess what... you can put equals sign in it with quote marks :D

    "==cool-key==" = "hot value! \n :)"

## Boolean

Put boolean into .varl is very easy! Here's the example

    dev-mode = true

and another example

    dev-mode = false

## Null

Sometimes we need to keep a few variables empty, for example:

    this is empty = 

That's it, no value. Just put a key name and equal sign at the end. The .varl decoder will register **this is empty** variable as **null**.

## Number

We can put normal integer number like

    year = 2020

or... we can put decimal number like

    pi = 3.14

or even scientific number like

    G = 6.674e-11

Besides of those numbers, you can also put technical number such as:

    * Octal number:
    permission = 0o0755
    
    * Hex number:
    cyan = 0x00ffff
    
    * Binary:
    example = 0b00100110

  ##
  
**Pages:** | [1](https://github.com/Thor-x86/varl/blob/master/docs/1-Getting_Started.md) | 2 | [3](https://github.com/Thor-x86/varl/blob/master/docs/3-Array_and_Object.md) | [4](https://github.com/Thor-x86/varl/blob/master/docs/4-Do_and_Dont.md) | [5](https://github.com/Thor-x86/varl/blob/master/docs/5-Contribution.md) |  
# Pairing Project

## The Plan

This pairing lab does not have a designated place to switch drivers. Instead, every 30 minutes the pair's responsibilities should swap. The driver becomes the navigator, and vice versa.

To minimize extra cloning and forking, this project should be completed in only one person's Github account.

# Roman Numerals

### Skills: Modifying a Ruby class, Integers

## Description

The Romans were a clever bunch. They conquered most of Europe and ruled it for hundreds of years. They invented concrete and straight roads and even bikinis. One thing they never discovered though was the number zero. This made writing and dating extensive histories of their exploits slightly more challenging, but the system of numbers they came up with is still in use today. For example the BBC uses Roman numerals to date their programmes.

The Romans wrote numbers using letters - I, V, X, L, C, D, M. (Notice these letters have lots of straight lines and are hence easy to hack into stone tablets).

## Instructions

Write a method on the Integer class to convert from normal numbers to Roman Numerals: e.g.

```ruby
 1.to_roman # => "I"
10.to_roman # => "X"
 7.to_roman # => "VII"
```

There is no need to be able to convert numbers larger than about 3000. (The Romans themselves didn't tend to go any higher.)

[Wikipedia](http://en.wikipedia.org/wiki/Roman_numerals) says: Modern Roman numerals...are written by expressing each digit separately starting with the left most digit and skipping any digit with a value of zero.

To see this in practice, consider the example of 1990.

In Roman numerals 1990 is MCMXC:

* 1000 = M
* 900 = CM
* 90 = XC

2008 is written as MMVIII:

* 2000 = MM
* 8 = VIII

See also: [Nova Roma](http://www.novaroma.org/via_romana/numbers.html)

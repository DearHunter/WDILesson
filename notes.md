# Hashes
### Sample lesson for GA's WDI
###### Created by: [Matt Nodurfth](http://github.com/DearHunter)


# Hashes
  * Identify what a hash is and why you would use it instead of an array

# Activity
* Discuss with students:
	* What is a hash?
	* Why use a hash vs array?
* Demonstarte how to do the following using pry:
	* Create a hash
	* Access items in a hash (vs. an array)   



## Review
   1. What are some differences between symbols and strings?
   2. At what number does an array's index start and why are programmers silly like that?
   3. What are two ways to declare an array? 



## So ... What's wrong with arrays?
* Nothing!
* But... semantic indicies
* Not just numbers!



## Hashes!

> **A Hash is a dictionary-like collection of unique keys and their values.**

* Nicknames: associative arrays or dictionaries
* The last value should have no comma at the end
* Ordered by key insertion



## Hash Creation
#### Keyword or literal notation:
    foo = Hash.new
    foo[:key] = "value"

    bar = { :key   => "value",
            1      => :value1,
		    "key2" => 42
	      }
  	bar.store( :key, "new value" )



## But wait, there's more!
If the keys are always symbols:
    
    goo = { :one => 1, :two => 2 }
Is the same as

    goo = { one: 1, two: 2 }



## Default Values
    
    goo = Hash.new(10)
    goo.default = 10



## Retrevial
* Simply typing in the name to get the hash literal:
		puts foo[:key]
		
* To get the value from the known key:
    
    ```puts foo```
      
<!-- * Or looping though the hash to get the key and value:

    SOME CODE HERE -->



## And Remember
* Symbols are more effiecent than strings, so they make great key values



## Hands on Hashes
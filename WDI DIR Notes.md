### why are programmers silly and start couting at zero?
### hashes are like arrays except we can declare our key


# Hashes
  * Identify what a hash is and why you would use it instead of an array

# Activity
* Discuss with students:
	* What is a hash?
	* Why use a hash vs array?
* Demonstarte how to do the following using pry:
	* Create a hash
	* Access items in a hash (vs. an array)   

Intro questions
   What main diff between symbol and string?
   Why do we start array index at 0 (what number does array index start and why)?
   What are two ways to declare an array? 

So what if we don't want our index to be an integer?  Can you think of anything that uses an index based on integers?  What are some limitations to this technique?  RIGHT! So we can do that, and it's called a hash.  Hash's index can be any object, ie, like a string.  It's useful to think of hashes as dictionaries, because that's what they are.  They hold a key, a word, and a value, the definition.





Create a hash 

books = {}

books = Hash.new(0)  // creates new hash with 0 the default value for all keys

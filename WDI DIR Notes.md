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


1. Symbols are immuatable, strings aren't.  For 10 instances of a symbol it only takes one space in memeory, whereas strings take one space for each instance. Mutable items can be changed after assignment, while immutable can only be overwritten. 
2. offset from initial memorry location. so array[0] is zero offset from the first, ie the first one.  and arry[1] is 1 offset from the inital, ie 2nd item
		Proformance, 1 vs 0 offer no advantage yet perform slightly worse.  So the small proformace loss of 1 based justifies the use of 0 based. BC the machine would need to do -1 for each array computation.
3. foo = Array.new & foo1 = []  // Literal notation vs new keyword


review, question why arrays are inadequate, HASHES, hands on hash	2


What would I use a dictionary for?
Any time you have to take one value and "look up" another value. In fact you could call dictionaries "look up tables."
What would I use a list for?
A list is for any sequence of things that need to go in order, and you only need to look them up by a numeric index.







		<section>
			<section>
				<h2>Fragmented Views</h2>
				<p>Hit the next arrow...</p>
				<p class="fragment">... to step through ...</p>
				<ol>
					<li class="fragment"><code>any type</code></li>
					<li class="fragment"><em>of view</em></li>
					<li class="fragment"><strong>fragments</strong></li>
				</ol>

				<aside class="notes">
					This slide has fragments which are also stepped through in the notes window.
				</aside>
			</section>
			<section>
				<h2>Fragment Styles</h2>
				<p>There's a few styles of fragments, like:</p>
				<p class="fragment grow">grow</p>
				<p class="fragment shrink">shrink</p>
				<p class="fragment roll-in">roll-in</p>
				<p class="fragment fade-out">fade-out</p>
				<p class="fragment highlight-red">highlight-red</p>
				<p class="fragment highlight-green">highlight-green</p>
				<p class="fragment highlight-blue">highlight-blue</p>
			</section>
		</section>

## Coding Exercises No. 04
1. Go through the [ruby String documentation](https://ruby-doc.org/core-2.4.1/String.html) and look for a method or function that prepends or combine one string to another string. Using said method prepend the string "```Learning ```" to the string "```Ruby```".

2. Go through the [ruby String documentation](https://ruby-doc.org/core-2.4.1/String.html) and look for a method or function that remove characteres from a string. Using said method, it turns the string "```Learning Ruby```" into the string "```Lrnng Rby```".

3. There is a ruby String method that allows to justify a string, padding it with another string. Find said method and use it on the string "```Ruby```" together with "```<3```" so that you get the following string result:  

```ruby
"Ruby<3<3<3"
```

4. Create a ruby application called ```exercise_04.rb```. Fill it in with the following lines:

```ruby
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
# your code here... 
```

So that, when you run  your code, e.g., ```ruby exercise_04.rb```, you get the following output  


```ruby
5
```

5. Copy ```exercise_04.rb``` to ```exercise_05.rb```, then open this new file. Add another line before the line that you just added, so that, when you run your code you get the following output:

```ruby
99
```

6. Create a new ruby file called ```exercise_06.rb```, and fill in the following line:

```ruby
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
# your code here...
puts numbers.inspect
```

So that you get the following output:

```ruby
[2, 4, 6, 8, 10]
```

**Tip:** Consult the [ruby Array documentation](https://ruby-doc.org/core-2.4.1/Array.html) for the correct method or function to use.

7. Again, copy the finished ```exercise_06.rb``` to ```exercise_07.rb```.

Now change the code so that you get the following output:

```ruby
[10, 8, 6, 4, 2]
```

**Tip:** Consult the [ruby Array documentation](https://ruby-doc.org/core-2.4.1/Array.html) for the correct method or function to use.

**Note:** The method select that you used in the last exercise returns an array. On this array (the returned value) you can use another method by appending another dot ```.```, and the method that would produce the output ```[10, 8, 6, 4, 2]```.

**Note:** There is another method that reverses the order of the array. You can find it by googling for “ruby array reverse”.

8. Again, copy the finished ```exercise_07.rb```, then change your code so that you get the following output:

```ruby
[10, 8, 4, 2]
```

**Tip:** Consult the [ruby Array documentation](https://ruby-doc.org/core-2.4.1/Array.html) for the correct method or function to use.

**Bonus:** Find at least three different solutions for this last change.

9.  Create a new file called ```exercise_09.rb```, and fill the following lines:

```ruby
dictionary = { :one => "ichi", :two => "ni", :three => "san" }
# your code here...
puts dictionary[:two]	
```

So that it prints out

```
ni
```

 	





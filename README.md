# Practice functions, forEach, let, createElement, classList, innerHTML, append, template literals

This is [Skillcrush](https://skillcrush.com/) course practice.

# Instructions

Set the innerText of the total variable to a template literal that will display the number of songs in your epicMix, like “12 great songs!”. 
Hint: Don’t manually input the number because your array elements might change; use the length property instead.


Create a variable called mixInfo for a function expression with mix as a parameter.

In the function, loop through the mix using forEach(). Your forEach() callback function needs two parameters: song and index.

In your callback function, create a list element and assign it to a variable called li. Add the class called “song” to your list Item

Use innerHTML to add the index number and song name inside li :
`<span class="song-number">#${index + 1}</span> ${song}`;
.
Append the list item to mixList which is the unordered list element.

Back in the button’s click event listener, call your mixInfo() function and pass it the epicMix array as an argument.

Save and reload. You should see the number of songs at the top and a list of the songs below!

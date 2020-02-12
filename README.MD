2.
You can use keywords "closes" and "resolves" to auto-close issues as well as "fixes".

3.
You can close multiple issues with a single pr as long as you put
a comma and a space between each (fixes #number).

4.
// create an array called words

var words = ['DREAM', 'CAR', 'SNAKE']

// create a new array called capitalwords that has every element of words but lowercased

var capitalwords = words.map(function (word) {
    return word.toLowerCase()
})

// print the new array capitalwords

console.log(capitalwords)

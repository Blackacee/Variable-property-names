# Variable-property-names
 
var dictionary = {
 lettuce: 'a veggie',
 banana: 'a fruit',
 tomato: 'it depends on who you ask',
 apple: 'a fruit',
 Apple: 'Steve Jobs rocks!' // properties are case-sensitive
}
var word = prompt('What word would you like to look up today?')
var definition = dictionary[word]
alert(word + '\n\n' + definition)

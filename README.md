# Programming as Conversation 4: Array and Hash Quiz

???

# Programming as Conversation 4: Array and Hash Quiz

?: Collection types are called scalar data types.

( ) TRUE
(X) FALSE

?: Which syntax can be used to make a new, empty `Array`?

( ) `Array.new`
( ) `new_array`
( ) `new_array = []`
(X) Both A and C

?: Which syntax can be used to add items to an `Array`?

( ) ```new_array = "New String"``
( ) ```new_array << "New String"```
( ) ```new_array.push("New String")```
(X) Both B and C

?: Which method removes (and returns) the last element from an array?

( ) `.shift`
( ) `.unshift`
( ) `.last`
(X) None of the above

?: Which range operator excludes the last value from a sequence?

( ) `..`
( ) `.range`
(X) `...`
( ) `<=>`

?: Which syntax can be used to create a new `Hash`?

( ) 
```
new_hash = {
  :name => "Mario"
}
```
( ) ```Hash.new```
( ) ```new_hash = {}```
(X) All of the above.

?: What syntax can be used to return the value of the key `pearl`?

```
drumset_colors = {
  :tama => "burgundy",
  :pearl => "blue",
  :yamaha => "black",
  :ludwig => "white"
 }
```

( ) ```drumset_colors[1]```
(X) ```drumset_colors[:pearl]```
( ) ```drumset_colors["pearl"]```
( ) ```drumset_colors[pearl]```

?: What syntax can be used to return the value of `size` for `Yamaha`?

```
drumsets = { tama: {color: "burgundy", size: 7}, :pearl => {color: "blue", size: 5}, yamaha: {color: "black", size: 5}, ludwig: {color: "white", size: 5}}
```

(X) ```drumsets[:yamaha][:size]```
( ) ```drumsets[yamaha][size]```
( ) ```drumsets["yamaha"]["size"]```
( ) ```drumsets[:yamaha]```

?: What will `cars["toyota"]` evaluate to?

```
cars = { toyota: ["avalon","camry"], honda: ["civic", "accord"] }
```

( ) ["avalon","camry"]
( ) ["avalon"]
( ) ["camry"]
(X) None of the above.

?: What will the command `cars[:ford] = "focus"` do?

```
cars = { totoya: ["avalon","camry"], honda: ["civic", "accord"] }
 => {:totoya=>["avalon", "camry"], :honda=>["civic", "accord"]}`
```

( ) Overwrite the hash
( ) Throw an error
( ) Return `nil`
(X) Update the hash

?: What will the command `cars[:ford] = "taurus"` do?

```
{:totoya=>["avalon", "camry"], :honda=>["civic", "accord"], :ford=>"focus"}
```

(X) Overwrite the value of `cars[:ford]`
( ) Add an additional value to `cars[:ford]`
( ) Update the value of `cars[:ford]` to "focustaurus"
( ) Remove the key-value pair.

???

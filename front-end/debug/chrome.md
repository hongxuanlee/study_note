* convert Your Browser Into An Editor

```
document.body.contentEditable=true
```

* Monitor Events

```
monitorEvents($('selector'))
```

* Find the Time Of Execution of a Code Block

```
console.time('myTime'); //Starts the timer with label - myTime
console.timeEnd('mytime'); //Ends the timer with Label - myTime

//Output: myTime:123.00 ms
```

* Arrange the Values of a Variable into a Table

```
var myArray=[{a:1,b:2,c:3},{a:1,b:2,c:3,d:4},{k:11,f:22},{a:1,b:2,c:3}];
console.table(myArray)
```

* Inspect an Element in the DOM

   $0, $1, $2, etc. can help you grab the recently inspected elements

```
  inspect($(‘selector’))

```

* List the Properties of an Element

```
  dir($(‘selector’)) 
```

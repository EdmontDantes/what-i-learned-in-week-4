# what-i-learned-in-week-4
### list of syntax that I have learned over the course of the week or strengthened understanding of it:    

* str.split('') - splits string into an array   
* str.slice(numBeginingStr, numEndStr) - slices string from one num index to specific end num index
* array.slice(value)
* array.push(value)
* array.includes(value)
* array.pop(value)
* array.join(value)
* Math.floor() - returns a number to the small integer if float num (ie 3.9 = 3)  
* Math.ceil() - returns a number to the biggest integer if float num (ie 3.9 = 4)  
* Math.abs() - makes a number [int or float] only positive regadless whether it was positive or neagive  
* str.charAt() - returns one character at a number of the index in a string  
* str.indexOf(*'string_value'*) - return a first index of a character of that part in the string  
* str[someVariableOrNum] - shorthand for returns str.indexOf(someVariableOrNum)

### useful code snippets :
random range numbers
```console.log(Math.random() * (max - min) + min)```  

### DOM Manipulation  
Document Object Manipulation is a javascript ability to manipulate and change HTML and CSS frontend to look for user input and provide a dynamic content.

Here are some examples that were covered in classwork (Notice that all of these can be combined together to produce various results):  

* document.querySelector('_someTagOrClassOrIDorManyVariationsOfThat_')  
_somePlace_.appendChild(_ienode_)  - appends a tag to the parent tag  
* .style._someAtributeToStyle_  - CSS manipulation changes  
* document.createElement(_ienode_)  - create a tag or any element (could be a class or id)  
* _someElement_.lastElementChild  - appends to last Element Child  
* _someElement_.firstElementChild  - appends to first Element Child   
* _someImage_.src - used to source an image with url(either network or local)  
* _someElement_.innerText - appends inner text into a node  



## Loops:
Loops are functions that repeat an action until a condition is satisfied:

* while (*"some_condition_is_true_run_this_loop_until_its_satisfied"*) loops { _repeatable action_ }

* For(*i="some_num_or_var"; condition_toSatisfy; i++ or i--*) loops { _repeatable action_ }

Not a lot of explanation for the biggest part of the learning week but honestly it's simple description would suffice for a powerful tool.  
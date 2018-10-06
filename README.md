# rachelTemplate

**rachelTemplate is a easy but powerful javascript template engine. and users just need to use one function to build their page。**

*****
**
you can cody rachelTemplate.js and link it to your html file so that you can use the mini template engine.
**
[website](https://dongdaxiaodong.github.io/rachelTemplate/)
----
how to use?
1. the most important thing which need user to know is that there are three types of engine need to use double block,and they are {`for_()`}  {`if_()`}  {`!if_()`} 
2. {`keyName`}  keyName is the object's key .  and rachelTemplate can converse {`keyName`} to value.
3. {`keyName1.keyName2`}
4. {`if_keyName`},this block means that if valueObj[keyName] is not falsy!  the string which in "if" label will be used
5. {`!if_keyName`},this block means that if valueObj[keyName] is falsy! the string which in "!if" label will be used
6. {`for_keyName`},for block means that the string in for block will be used many times so that every value in your valueObj will be show

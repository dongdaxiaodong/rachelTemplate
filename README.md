# rachelTemplate
a javaScript template for web font end

rachelTemplate is a very very small javascript template engine. and it only have one function for user to use.

you can cody rachelTemplate.js and link it to your html file so that you can use the mini template engine.

how to use?
1. {`keyName`}  keyName is the object's key .  and rachelTemplate can converse {`keyName`} to value.


2.{`keyName1.keyName2`} if your json object is likes this 
```
{
name:{girl:rachel,boy:colin}
}
``` 

so, you can use this to fill your html


3.{`#keyName`} this is for loop . your json object should like this {city:[{food:banana,visit:2},{food:apple,visitL3}]}

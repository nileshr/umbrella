## .html()

Retrieve or set the html of the elements:


```js
// GET
.html();

// SET
.html(html);
```


### Parameters

*GET*
should pass no parameter so it retrieves the html.

*SET*
`html`: the new value that you want to set



### Return

*GET*
`string`: the html of the first node

*SET*
`u`: returns the same instance of Umbrella JS



### Examples

Get the main title:

```js
var title = u('h1').html();
```

Set the main title:

```js
u('h1').html('Hello world');
```


### Related

[.attr(html)](#attr)

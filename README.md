# jQuery Simple Counter



<br>


## .html

```html
<script type="text/javascript" src="http://code.jquery.com/jquery-2.1.0.min.js"></script>
<script type="text/javascript" src="jQuerySimpleCounter.js"></script>
```


```html
<div id="count-test"></div>
```


<br>


## .js


```js
$('#count-test').jQuerySimpleCounter({
  end:100,
  duration: 4000
});

```


<br>


## More options:

```js
start:  0, // inicial number
end:    100, // final number
easing: 'swing',
duration: 400,
complete: function(){console.log('Finished!')}
```

<br>

## Credits:
[Joss Crowcroft](https://github.com/josscrowcroft)

[Use jQuery.animate() to increment / decrement numeric text or an element’s value](http://www.josscrowcroft.com/2011/code/jquery-animate-increment-decrement-numeric-text-elements-value)

jQuery Simple Counter
===================

###Simple jQuery Animate Counter


```sh
<div id="count-test"></div>
```

```sh
<script type="text/javascript" src="http://code.jquery.com/jquery-2.1.0.min.js"></script>
<script type="text/javascript" src="jQuerySimpleCounter.js"></script>
```

```sh
$('#count-test').jQuerySimpleCounter({
		end:100,
		duration: 4000
});

```

###More options:

```sh
{
    start:  0, // inicial number
    end:    100, // final number
    easing: 'swing',
    duration: 400,
    complete: function(){
      console.log('Hello!');
    }

}
```
#####Author:
[Marcos César](http://github.com/marcoscesar)

#####Credits:
[Joss Crowcroft](https://github.com/josscrowcroft)
- [Use jQuery.animate() to increment / decrement numeric text or an element’s value](http://www.josscrowcroft.com/2011/code/jquery-animate-increment-decrement-numeric-text-elements-value)

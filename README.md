jQuerySimpleCounter
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
[marcoscesar]:http://github.com/marcoscesar


#####Credits:
[Joss Crowcroft]:http://www.josscrowcroft.com/2011/code/jquery-animate-increment-decrement-numeric-text-elements-value




> The problem: waiting for the two (or more) async http calls to finish
> Doing it with jQuery is pretty simple:
> jQuery has the [when function](http://api.jquery.com/jQuery.when/) and you can use it like this:
> `$.when(ajax1(),ajax2()).done(function(a1, a2){});`
> 
> Where ajax1 and ajax2 functions should return the deffered object:
> 
> `function ajax1(){
	   return $.ajax({
						url: "blabla",
						dataType: "json",
						data: ...});
	}`
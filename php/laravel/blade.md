# Blade - Laravel
> Blade is the PHP template engine for those familiar with Python and Django, blade is basically Django Templates in PHP/Laravel.

## Blade working

* >Blade allows us to use comments through {{-- Example Comment --}} and this will not appear in the code HTML

* >Through a Mechanism in the Controller, we can manipulate the data directly in the HTML Blade as if we were programming in PHP.
    Example:
   Assuming that I have a data that I sent in the Controller a variable called ("$name") in which this variable receives the value of ("João"). Through Blade we can call this variable by "{{}}" It would look like this: "<p>{{$name}}</p>"


* >Blade we can use its own variable "$loop => index" to display the index in a Foreach

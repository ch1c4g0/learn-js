
<p>You can have as many statements as you'd like separated with a semi colon.</p>

```
alert('Hello'); alert('World');
```

<p>Write statements on separate lines for readability.</p>

<p><h1>Semicolons / Line Breaks</h1></p>

<p>Line breaks are interpreseted as an implicit semicolon, this is not always true though.<br>
The following are both examples of semicolon / implicit semicolon usage.</p>

<p>False,</p>

```
alert(3 +
1
+ 2);
```

<p>True,</p>

```
alert('Hello')
alert('World')
```

<p>Our true value works because the alert function already exists within javascript, you are simply calling it with valid strings.<br>

The alerts will also pop up individually(2 separate alerts).<br>

alert() is blocking, meaning it pauses everything else in the page while its open, Once you click okay, the next call will be ran.</p>

***<p>Although semi-colons are optional, it is best practice to use them for code readbility.</p>***

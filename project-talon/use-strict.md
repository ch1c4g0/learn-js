
<p><h1>What is use-strict?</h1></p>

<p>Used to enforce a stricter parsing and error-handling on your JavaScript.<br>

It forces the JavaScript engine to transition out of standard "sloppy" mode to "strict" mode.</p>

<p><h2>Location,</h2></p>

<p>When located at the top of a script, the whole script works the modern way.</p>

```
"use strict";

// this code works the modern way
...
```

**<p>This can be put at the beggining of a function, doing so enables strict mode for that function only.</p>**

**<p><h3>Placement matters,</h3></p>**

```
alert("some code");
// "use strict" below is ignored--it must be at the top

"use strict";

// strict mode is not activated
```

**<p>Browsers/Consoles does NOT run in strict mode by default.</p>***

```
'use strict';
alert('this is a strict alert');
```

<p>Classes nad modules may contain use strict automatically, this means we may not have to include them in our code.</p>

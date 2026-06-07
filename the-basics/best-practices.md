

<p><h1>Validation,</h1></p>

<p>Avoid relying on client-side validation only, this is the main function of js and developers sometimes use it for validating forms and rely on it entirely.</p>

<p>Because users can manipulate/disable javascript client-side, performing validation server-side is essential.</p>


<p><h1>Libraries,</h1></p>

<p>Be cautious when using libraries with your code, bad actors often upload libraries that resemble legitimate ones.</p>


<p><h1>Hard-coded Secrets</h1></p>

<p>Never hardcode sensitive data like API keys, access tokens, or credentials into your JS code, as the user can easily check the source code and get the password.</p> 

```
// Bad Practice
const privateAPIKey = 'pk_TryHackMe-133</p>
```

<p><h1>Always obfuscate and minify</h1></p>

<p>Improves load time, makes it harder for attackers to understand logic, and reduces size.</p>

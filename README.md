# Configuring ESLint
## Let's Learn an ESLint Rule
Alright, so you know what's super trippy about JavaScript? It doesn't require semicolons at the end of statements. By default, it will make assumptions about where your statements end and add them in where it sees fit. This is called ASI, automatic semicolon insertion, and if you're not aware of it, it could seriously mess up your code.

So what can we do about this? Are we doomed? Don't worry, there's an ESLint Rule for that!

The semi rule gets rid of the ambiguity of optional semicolons. You can either make semicolons required (set to "always") or disallow the use of them altogether (set to "never"). That way, you won't need to worry about ASI messing with your code.

[Read more about the semi rule here!](https://eslint.org/docs/latest/rules/semi)
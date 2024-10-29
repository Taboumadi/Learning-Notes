### Definition:
A Switch is a statement that allows testing for equality against a list of values
![](https://i.imgur.com/oueXtpP.png)
# Syntax Components
![](https://i.imgur.com/hXxRSX4.png)
1. **switch (expression)**: The `switch` keyword is followed by an expression in parentheses. This expression is evaluated once and compared with the values of each `case`.
![](https://i.imgur.com/bQoBXAu.png)
3. **case value**: Each `case` keyword is followed by a value and a colon. If the expression matches this value, the code block associated with this `case` is executed.
![](https://i.imgur.com/L5IX7LO.png)
3. **break**: The `break` statement terminates the `switch` statement. If omitted, the program continues to execute the subsequent `case` blocks (this is called “fall-through”).
![](https://i.imgur.com/DEY636j.png)
5. **default**: The `default` keyword is optional and specifies the code to execute if none of the `case` values match the expression. It acts like the final `else` in an `if-else` chain.

# Mnemonic
A useful mnemonic I've found is that switches are like lawyers

A lawyer has cases, like evidence "exhibit a, b, c... etc." and between presenting each case, the court adjourns and takes a break.
![](https://i.imgur.com/lnUD0Fl.png)
![](https://i.imgur.com/of7DeVQ.png)


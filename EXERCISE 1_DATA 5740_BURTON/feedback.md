## Score: 19/20

### Part 1

Just some quick notes on the code.

* Good handling of the edge case where the item value == max.
* Using `print()` inside a function is fine for early stage debugging, but good to avoid that habit in the long run. Use the logging library instead.
* Most critically, your function doesn't return anything. Typically functions `return` something rather than print them at the end. **(-1)**

### Part 2

* In addition to your comments about using AI for coding, it'll be important to think about how the use of AI in this class isn't just about coding, but also about thinking through analytical approaches: Do I use a t-test or some ARIMA or some other approach to analyzing this problem? How do I setup the null hypothesis for this scenario, etc?

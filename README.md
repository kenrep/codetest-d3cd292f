## 10 Substrings

*Please read these instructions carefully.*

A 10-substring of a number is a substring of its digits that sum to 10. For example, the 10-substrings of the number 3523014 are:

**352**3014
3**523**014
3**5230**14
35**23014**

A number is called 10-substring-friendly if every one of its digits belongs to a 10-substring. For example, 3523014 is 10-substring-friendly, but 28546 is not.

Write a performant program that discovers all the 10-substring-friendly numbers between 0 and N, where N is an arbitrary input. Some hints:

- This problem has no data dependencies--so it's possible to parallelize the search.
- Solve the problem naively and optimize from there.
- Use Git as if this were a real project you were completing on a fully functioning Agile team. Make sure that if you create multiple feature/devleopment branches then you rebase when merging into master so your commit history is maintained.
- Try to use good, readable style.
- The timebox exists to encourage small, concise, and appropriately engineered solutions, but don't get too stressed on the deadline: it's not a hard stop. It's better to go over by 30 minutes and produce excellent, robust code than check in a partially working solution.

Examples:

```
N = "0"
[] // Empty Array

N = "91"
[91]

N = "ACD42"
[] // Empty array

N = 200
[19, 91, 109, 118, 127, 136, 145, 154, 163, 172, 181, 172, 190]
```

### If you finish the solution with lots of time left:

- Think of ways to make it faster. Implement performance improvements.
- Consider threading and parallelization.
- Did you write a quick and dirty solution? Now abstract it a bit more and make it elegant and reusable.
- Do you have enough test coverage? Write some load tests if you've run out of unit test targets.

### Rules of the game:

1. You can use any existing frameworks in the programming language of choice.
2. You may pick which user interface you want to use without penalty.
3. We expect unit tests in the appropriate framework of your choice. If you're using a more exotic programming language or feature set, please provide instructions on how to run your tests. We will be running them. Writing zero tests is a fairly huge penalty.

Hope you have fun, and please email all questions to: jduv@aimconsulting.com.
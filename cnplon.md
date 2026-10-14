# Profile: Christopher Plonski

- **NetID:** cnplon
- **Major:** Computer Science
- **Question that I chose from the memoization exercise:** Count ways to reach n'th stair
- **Link to the question article:** https://www.geeksforgeeks.org/dsa/count-ways-reach-nth-stair/
- **My solution:**

```

int countWays(int n) {

    // Base cases
    if (n == 0 || n == 1)
        return 1;

    return countWays(n - 1) + countWays(n - 2);
}

int main() {
    int n = 4;
    printf("%d", countWays(n));
    return 0;
}

```

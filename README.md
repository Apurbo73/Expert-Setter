### Expert Setter
This C++ code reads a number of test cases and, for each one, checks if a condition between two integers `X` and `Y` is satisfied.

### Let's break it down:

```cpp
#include <iostream>  
using namespace std;
```

* Includes the standard input/output library.
* Allows use of `cin` and `cout` without `std::` prefix.

---

```cpp
int main() {
    int T;
    cin >> T;
```

* Reads the number of test cases `T`.

---

```cpp
    while (T--) {
        int X, Y;
        cin >> X >> Y;
```

* Runs a loop `T` times.
* For each test case, it reads two integers: `X` and `Y`.

---

```cpp
        if (Y * 2 >= X) {
            cout << "YES" << endl;
        } else {
            cout << "NO" << endl;
        }
```

* The condition checks whether **twice the value of `Y` is greater than or equal to `X`**.

  * If true: prints `YES`
  * If false: prints `NO`

---

```cpp
    }

    return 0;
}
```

* Ends the loop and returns `0` to signal successful execution.

---

### Example:

Input:

```
3
4 2
5 1
6 3
```

Output:

```
YES
NO
YES
```

Explanation:

* 2×2 = 4 ≥ 4 → YES
* 1×2 = 2 < 5 → NO
* 3×2 = 6 ≥ 6 → YES


This C++ program processes multiple test cases where it reads two integers, `X` and `Y`, for each case and checks whether `Y * 2` is greater than or equal to `X`. If the condition is satisfied, it prints "YES"; otherwise, it prints "NO". The loop runs `T` times, where `T` is the number of test cases entered by the user.

In simpler terms, the code is determining whether doubling the value of `Y` is enough to meet or exceed `X`. It's useful in situations like checking if someone has at least half the resources required (e.g., time, money, strength) to complete a task. The result for each test case is printed immediately after the check.

Let me know if you'd like a [real-world use case](f) or [code comment version](f) of this.


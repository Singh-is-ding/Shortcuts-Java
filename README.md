# Java `printf` & `print` Shortcuts

This project provides two simple shortcut methods to replace writing `System.out.println` and `System.out.print` repeatedly in Java.

## 🚀 Purpose
- Use `printf(...)` when you want to **print with a newline** (just like `System.out.println`).
- Use `print(...)` when you want to **print without a newline** (just like `System.out.print`).

## 📜 Code
```java
package print;

public class p {
    // Shortcut for println
    public void printf(Object... params) {
        for (Object p : params) {
            System.out.println(p);
        }
    }

    // Shortcut for print
    public void print(Object... params) {
        for (Object p : params) {
            System.out.print(p);
        }
    }
}

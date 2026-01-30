# **MyStringLib – Simple C String Library**

## **Overview**

**String-Library** is a small C library that implements basic string functions from scratch. It helps you practice **modular programming**, **headers**, and **multi-file projects** in C.

---

## **Project Structure**

```
String-Library/
│
├─ include/
│   └─ my-string.h       ← Function declarations
│
├─ src/
│   ├─ hello.c       ← Function definitions
│
│
│

```

---

## **Functions**

| Function                | Description                               |
| ----------------------- | ----------------------------------------- |
| `my_strlen`             | Returns the length of a string            |
| `my_strcmp`             | Compares two strings                      |
| `my_strcpy`             | Copies a string                           |
| `my_strcat`             | Concatenates strings                      |
| More can be added later | Example: reverse string, duplicate string |

---

## **Example Usage**

```c
#include <stdio.h>
#include "my-string.h"

int main() {
    char str[] = "Hello";
    size_t len = my_strlen(str);
    printf("Length: %zu\n", len);

    char dest[50];
    my_strcpy(dest, str);
    printf("Copied: %s\n", dest);

    return 0;
}
```

## **Learning Goals**

1. Understand **header and source file separation**.
2. Learn **compiling and linking multiple `.c` files**.
3. Practice **writing your own string functions**.

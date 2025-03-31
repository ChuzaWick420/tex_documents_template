# Headings
# Section
## SubSection
### SubSubSection
#### Paragraph
##### Subparagraph

# Ordered list
1. Item 1
2. Item 2
3. Item 3

# Unordered list
- Item
- Item
- Item

# Math
Inline code such as $\int_a^b f(x) dx$ and also block level one
$$
g(x) = 
\begin{cases}
    {\frac{\partial}{\partial x}} f(x) \\
    \int_a^b f(x) dx
\end{cases}
$$

# Code block
```cpp
#include "iostream"
#include <stdio.h>

void foo(const char* target) {
    std::cout << target << std::endl;
}

enum Test1 {
    HI = -1,
    BYE
} test;

typedef struct {
    int* num_ptr = nullptr;
    char character = '\0';
} Test2;

int main () {
    int x = 420;
    float y = 6.9f;

    // random comment
    if(x > 100)
        return -1;

    switch(x) {
        
    }

    const char* str = "Hello World";

    printf("%d\n", x);
    printf("%2.1f\n", y);

    foo(str);

    return 0;
}
```

# Text formatting
- _italic_
- **Bold**

# Images
![Dragon](assets/dragon.png)

<!--## Tables-->
<!---->
<!--|Heading 1|Heading 2|-->
<!--|---|---|-->
<!--|value 1| value 2|-->

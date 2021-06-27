---
title: Introduction
weight: 10
menu:
  notes:
    name: Introduction
    identifier: notes-c-basics-intro
    parent: notes-c-basics
    weight: 10
---

<!-- A Sample Program -->
{{< note title="Hello World">}}
  
```c
#include <stdio.h>

void say_hello(void)
{
  char str[10] = "Hello";
  printf("%s World",str);
}

int main(void)
{
  say_hello();
  return 0;
}
```


{{< /note >}}



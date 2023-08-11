> 请用 C++ 写一个带注释的 Hello World 程序，并解释这段代码。回答需使用 Markdown，并确保中英文间有空格。请把这段话作为引用格式写在答案开头。

```cpp
#include<iostream> // 引入 iostream 头文件，使得程序可以使用输入输出流功能

int main() { // 主函数，C++ 程序的执行入口
    std::cout << "Hello, World!" << std::endl; // 输出 "Hello, World!" 到控制台并换行
    return 0; // 返回 0，表示程序正常结束
}
```

解释：

- `#include<iostream>`：这是一个预处理器命令，告诉编译器在编译前要包含 `iostream` 头文件。`iostream` 是 C++ 标准库中的一个文件，它定义了如 `cin` 和 `cout` 等用于流输入/输出的对象。

- `int main()`：这是 C++ 程序的主函数，也称为程序的入口点。当程序开始执行时，`main` 函数是首先被调用的。函数前的 `int` 表示此函数返回一个整数类型的值。

- `std::cout << "Hello, World!" << std::endl;`：这是用于输出的代码。其中 `std::cout` 是一个输出流对象，它可以与 `<<` 运算符配合使用，将字符串 "Hello, World!" 输出到控制台。`std::endl` 是流控制符，用于输出换行。

- `return 0;`：这是主函数的返回语句。`0` 通常表示程序正常结束，而非零值则可以表示各种错误。

总之，当这个程序被执行时，它会在控制台输出 "Hello, World!" 并换行。
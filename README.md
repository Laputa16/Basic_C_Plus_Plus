# Basic_C_Plus_Plus

## Mục lục

1. What is C++?
- C ++ là một ngôn ngữ đa nền tảng có thể được sử dụng để tạo ra các ứng dụng hiệu suất cao.
- C ++ được phát triển bởi Bjarne Stroustrup, như một phần mở rộng của ngôn ngữ C.
- C ++ cung cấp cho người lập trình khả năng kiểm soát cao đối với tài nguyên hệ thống và bộ nhớ.

Ngôn ngữ này đã được cập nhật 4 lần chính vào các năm 2011, 2014, 2017 và 2020 lên C ++ 11, C ++ 14, C ++ 17, C ++ 20.

2. Why Use C++?
- C ++ là một trong những ngôn ngữ lập trình phổ biến nhất thế giới.
- C ++ có thể được tìm thấy trong các hệ điều hành ngày nay, Giao diện người dùng đồ họa và các hệ thống nhúng.
- C ++ là một ngôn ngữ lập trình hướng đối tượng mang lại cấu trúc rõ ràng cho các chương trình và cho phép mã được sử dụng lại, giảm chi phí phát triển.
- C ++ có tính di động và có thể được sử dụng để phát triển các ứng dụng có thể thích ứng với nhiều nền tảng.
- C ++ rất thú vị và dễ học!

Vì C ++ gần giống với C # và Java nên lập trình viên dễ dàng chuyển sang C ++ hoặc ngược lại.

3. Difference between C and C++

C ++ được phát triển như một phần mở rộng của C và cả hai ngôn ngữ đều có cú pháp gần như giống nhau.
Sự khác biệt chính giữa C và C ++ là C ++ hỗ trợ các lớp và đối tượng, trong khi C thì không.

C++ is a statically typed,general purpose programming language. C++ was derived C, band is largely based on it.

Note: A programming language is said to used static typing when type checking is performed during compile-time as opposed to run time.

4. Standard Libraries
Standard C++ has three important components

- Core language
Provides all necessary building blocks, including variables, data types, literals, etc.
- Standard library
Offers a rich set of functions for manipulating files, string, etc.
- Standard template library
Offers methods for the manipulation of data structures, etc.

5. First program of C++

Write a program in C++ print a massage on output screen.
```
#include<iostream.h>
using namespace std;
int main()
{
    cout <<"Hello world";
    return();
}
```
6. Program Explanation

- Pound sign(#)
The pound sign(#) at the beginning of a line targets the compiler's pre-processor to include the <iostream.h> header.

  `#include<iostream.h>`

C++ offers verious headers, each of which contains information need for programs to work properly. This particular program calls for the header file <iostream.h>.

The <iostream.h> header define the standard stream objects that input and output data.

- using namespace std;

In our code, the line using namespace std; tells the compiler to use the std (standard) namespace. The std namespace includes features of the C++ standard library.

- main() function

Program execution begins with the main() function. The entry point of every C++ program is main() function.

- Curly brackets {}

Curly brackets {} indicate the beginning and end of a function, which can also be called the function's body. The information inside the brackets indicates what the function does when executed.

- cout<< "Hello world";

cout<< "Hello world"; results in the display of Hello world to output screen.

- cout : is used in combination with the insertion operator

- Insertion operator << : Write the insertion operator as << to insert the data comes after cout into the stream the comes before.

- Semicolon (;)

The semicolon (;) is used to terminate a statement.

- return 0;

The last instruction in the program is the return statement. The line return 0; terminate the main() function and causes it to return value 0 to the calling process.


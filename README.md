# C++ LinkedList Library

A simple and modular C++ LinkedList library designed for efficient insertion, deletion, search, and traversal operations. This library is implemented using templates to support various data types.

## Features
- **Dynamic Size Management**: Automatically adjusts the size as elements are added or removed.
- **Template Support**: Generic implementation for handling different data types.
- **Core Operations**:
  - Insert at head or tail
  - Delete by value
  - Search for an element
  - Print the linked list
  - Get the current size of the list

## Files
1. **`LinkedList.h`**: Header file containing the LinkedList class definition.
2. **`LinkedList.tpp`**: Implementation file for the LinkedList class.
3. **`main.cpp`**: Example usage of the LinkedList library.

## Usage
1. Clone the repository or copy the files into your project.
2. Include `LinkedList.h` in your main program.
3. Compile using a C++11 or later-compatible compiler.

### Example
```cpp
#include "LinkedList.h"

int main() {
    LinkedList<int> list;

    list.insertAtHead(10);
    list.insertAtTail(20);
    list.insertAtTail(30);
    list.printList();

    list.deleteByValue(20);
    list.printList();

    return 0;
}
```

```cpp-outlput
    // Output
    10 -> 20 -> 30 -> nullptr
    10 -> 30 -> nullptr
```

## Requirements
1.**`C++ Compiler`**: GCC, Clang, or any C++11 compatible compiler.
2:**`Environment`**: Works seamlessly on Replit or any IDE supporting C++.

## Future Extensions
- #### Add support for Binary Trees and other data structures.


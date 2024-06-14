# Theta Language Support for Visual Studio Code

## Overview

This Visual Studio Code extension provides syntax highlighting support for the Theta programming language. It enhances the editing experience by colorizing syntax elements such as keywords, variables, functions, comments, and more, making code easier to read and understand.

## Features

- **Syntax Highlighting**: Colorizes various syntax elements including keywords, variables, functions, and comments.
- **Multi-line Comment Support**: Highlights multi-line comments using `/- ... -/` delimiters.
- **Function Declaration and Call Highlighting**: Differentiates function declarations from function calls with appropriate highlighting.
- **Type Highlighting**: Recognizes and highlights types enclosed within `< >`, including nested types.

## Installation

To install the Theta Language Support extension:

1. Open Visual Studio Code.
2. Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
3. Search for "Theta Language Support".
4. Click **Install** to install the extension.
5. Once installed, the extension will provide syntax highlighting for `.th` and `.theta` files automatically.

## Usage

After installing the extension, it will automatically highlight Theta syntax in any `.th` file you open in Visual Studio Code. The syntax highlighting helps you quickly identify different elements of your code, improving readability and reducing errors.

### Supported Syntax Elements

- **Keywords**: `if`, `else`, `return`, etc.
- **Variables and Functions**: Highlighted differently based on context.
- **Types**: Recognizes and highlights types within `< >`, supporting nested types.
- **Operators**: Highlighted for clarity, including arithmetic and logical operators.
- **Comments**: Single-line `//` and multi-line `/- ... -/` comments are supported.

## Example

```theta
capsule MyCapsule
{
    // Define a function
    distance<String> = meow<List> -> {
        // Function body
        x<String>(arg1, arg2);
        y<List>(arg3);
    }
}

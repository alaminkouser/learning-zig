# Writing first zig program

Let's write our first zig program. We will write a simple program that prints `Hello, World!` to the console.

1. Create a new file named `main.zig` in an empty directory.
2. Open the file in your favorite editor.
3. Write the following code in the file:

    ```zig
    const std = @import("std");

    pub fn main() void {
        std.debug.print("Hello, World!\n", .{});
    }
    ```

4. Save the file.
5. Open a terminal in the same directory.
6. Run the following command:

```sh
zig run main.zig
```

You should see `Hello, World!` printed to the console.

## What is happening?

- `const std = @import("std");` imports the standard library.
  Zig has some standard libraries that you can use to write your programs. You can find the documentation for the standard library [here](https://ziglang.org/documentation/master/#Standard-Library).
- `pub fn main()` is the entry point of the program.
    The `main` function is the entry point of the program. The void after the `main()` function means that the function does not return anything. In this example program, we are not returning anything from the `main` function. And if you see a `!` before the `void`, it means that the function may not run successfully.
- `std.debug.print("Hello, World!\n", .{});` prints `Hello, World!` to the console.

That's it! You have written your first Zig program.

> [!NOTE]
> zig has std library which is imported using `const std = @import("std");`.
> `pub fn main() void` is the entry point of the program.
> `std.debug.print("Hello, World!\n", .{});` prints `Hello, World!` to the console.
> `zig run main.zig` runs the program.

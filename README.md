# zinput

A Zig command-line input library!

- [zinput](#zinput)
	- [Usage](#usage)

## Usage
```zig
const zinput = @import("zinput");

const my_string = zinput.askStringUnsized(allocator, "I need a string!");
defer allocator.free(my_string);
```

Check out the test in `main.zig` for an example!

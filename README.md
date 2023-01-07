# Zig URI Parser

A small URI parser that parses URIs after [RFC3986](https://tools.ietf.org/html/rfc3986).

> **NOTICE: THIS LIBRARY IS DEPRECATED!**  
> This library is now part of zig `std` library, available as `std.Uri` since [87b2234](https://github.com/ziglang/zig/commit/87b223428a8953b6af9bea61ff4cc905821c0557).
> 

## Usage Example

```zig
var link = try uri.parse("https://github.com/MasterQ32/zig-uri");
// link.scheme == "https"
// link.host   == "github.com"
// link.path   == "/MasterQ32/zig-uri"
```

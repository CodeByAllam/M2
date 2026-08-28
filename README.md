# WebKit CSSFontFace Exploit for PS4/PS5

### Vulnerability Scope

|               | CSSFontFace |
| :------------ | :---------- |
| PlayStation 4 | 6.00-13.52  |
| PlayStation 5 | 1.00-13.40  |

### Exploitable In

|               | CSSFontFace |
| :------------ | :---------- |
| PlayStation 4 | 6.00-11.02  |
| PlayStation 5 | 1.00-8.60   |

* PS5 is also exploitable if ASLR can be defeated, either through a heap-shaping trick or a separate leak bug, and the expected vtable pointer can be recovered before the native crash path.

## Supported by This Repository

|               | CSSFontFace |
| :------------ | :---------- |
| PlayStation 4 | 9.00        |
| PlayStation 5 | N/A         |

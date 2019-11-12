# Official Letter
The Repo contains latex files and the required packages to compile a custom left alligned official letter.

Compile the *letter.tex* file using LuaTeX or XeTeX. This is required as the main font of the document has been set as Times New Roman.

The following code may be used to compile the document in **Ubuntu** terminal

```
lualatex letter.tex && rm letter.aux && rm letter.log
OR
xetex letter.tex && rm letter.aux && rm letter.log
```
Suggestions and criticism are welcome :+1:

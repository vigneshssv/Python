# split
- split the string words
```bash
text = "Hello world"
result = text.split(" ") # split(",") split("-")
print(result) # res: ["Hello", "world"]
# split particular length only
text = "a-b-c-d"
res = text.split("-",2) # res: [a,b,c-d]
```
# stripe
- remove unwanted spaces, tabs, new lines
```bash
text = "Hello world  "
res = text.stripe() # res: Hello world, removed the spaces
text = "**hello**"
text.stripe("*") # remove the * symbol special character
text.stripe("hel") # remove the word
```
# f-string
- add variable value inside string
```bash
text = "vignesh"
print(f"hi i am {text}") # put a text inside string
```
# r-string
- convert the \\ into properly for string format
```bash
print(r"c\\windows\\vignesh\\") res: c\windows\vignesh
```

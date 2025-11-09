# emailnator
api for emailnator.com temp email site 
# Example
```nim
import asyncdispatch, emailnator, json
let email = waitFor get_emails()
echo email["email"].getStr()
```

# Launch (your script)
```
nim c -d:ssl -r  your_app.nim
```

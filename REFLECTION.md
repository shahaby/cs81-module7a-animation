# Reflection

**What part of the code was most confusing and why?**  
The most confusing part of the code was this line: `loader.textContent = frames[index % frames.length];`.
It took some time to realize that it makes the index wrap around when it goes beyond the length of the array.

**How does the animation help visualize asynchronous behavior?**  
The animation helps visualize asynchronous behavior by simulating and operation that is in progress. This can happen a lot especially in web applications that rely on APIs and fetching data.

**What did you change or improve, and what effect did it have?**  
I added another loop to change the background color every second. This improvement keeps the user from falling asleep while waiting.

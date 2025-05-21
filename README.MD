# Advanced Programming Module 10 - Timer
### Athazahra Nabila Ruby - 2306173113

> Understanding how it works
 
![Understanding](images/understand.png)
An async function runs in the background without blocking the execution of the main thread. This means that the main thread immediately continues to the next line of code without waiting for the async function to finish. Although the async function is called in sequence, it doesn't interrupt the main flow, which is why "hey hey" appears first before "Howdy" and "Done". When the spawner is dropped, it signals that the entire program has finished executing.

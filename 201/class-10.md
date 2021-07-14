# **Read: 10 - JS Debugging**
![](https://image.slidesharecdn.com/debugging-javascript-web-141030080414-conversion-gate02/95/debugging-javascript-1-638.jpg?cb=1415345877)
## Debugging is the process of finding errors. It involves a process of deduction. The console helps narrow down the area in which the error is located, so you can try to find the exact error. JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a description of the error. If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.

## **EXECUTION CONTEXTS :**
![](https://miro.medium.com/max/1052/1*2oAKZtsRSn_vWfJeHHWwYQ.png)
## The JavaScript interpreter uses the concept of execution contexts.

## **EXECUTION CONTEXT has three type :**

+ ## GLOBAL CONTEXT
+ ## FUNCTION CONTEXT
+ ## EVAL CONTEXT (NOT SHOWN)

## **DEALING WITH ERRORS :**
![](https://cdn.educba.com/academy/wp-content/uploads/2019/11/error-in-javascript.png)

## If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it. You will find that the developer tools available in every major modern browser will help you with this task. In this chapter, you will learn about the developer tools in Chrome and Firefox. (The tools in Chrome are identical to those in Opera.) IE and Safari also have their own tools (but there is not space to cover them all). You can handle errors gracefully using try, catch, throw, and f i na 1 ly statement s. Sometimes, an error may occur in the script for a reason beyond your control. For example, you might request data from a third party, and their server may not respond. In such cases, it is particularly important to write error-handling code. In the latter part of the chapter, you will learn how to gracefully check whether something will work, and offer an alternative option if it fails.



## **DEBUGGING TIPS :**
![](https://i.morioh.com/200721/48d32e3d.webp)
## Try those simple tips whenever you are debugging your scripts :

+ ## Use another browser
+ ## Add Numbers
+ ## Strip it Back
+ ## Explaining the Code
+ ## Search
+ ## Code playgrounds
+ ## validation tools
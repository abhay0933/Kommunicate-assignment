## UI ScreenShot
![ss](https://github.com/abhay0933/Kommunicate-assignment/assets/127731916/8c519b79-20c7-4444-9469-cb18522741a4)

## Hosted Link - https://abhay0933.github.io/Kommnicate/
Task 2 - Return the value of param
function getUrlParameterValue(url, parameter) {
var newurl=new URL(url);
val= newUrl.searchParams.get(parameter);
return val; }
getUrlParameterValue(https://www.kommunicate.io/poweredby?utm_source=https://www.kommunicate.io/ &u tm_medium=webplugin&utm_campaign=poweredby, "utm_campaign");

## Task 3 - Reverse a Number
let num = 12345;
let str= ""

while(num>0) { 
str+= num%10;
num = Math.floor(num / 10); }

console.log(parseInt(str));

## Task 4 - Describe Project
The CodePen clone project built with React and Firebase offers a familiar environment for developers to create, share, and collaborate on code snippets and projects. With Firebase
handling authentication and real-time database functionalities, users experience seamless access control and data synchronization. Leveraging React ensures a responsive and dynamic 
user interface, facilitating code editing and collaboration. In summary, the project provides a user-friendly platform for developers to showcase their work and collaborate effectively
within a modern coding environment.

Link - https://code-pen-clone-nine.vercel.app/home/auth

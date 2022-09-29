## [ _rsschool - cv_ ](https://github.com/RazumauMikita/rsschool-cv)
***
# **Mikita Razumau**


## **Contacts:**
***
* E-mail | anykey2solo@gmail.com

* Phone  | +375-29-836-47-58

* Discord | RazumauMikita#4836

***
## **About me:**
My name is Mikita. I am 29 years old.
***
## **Skills:**
* Git
* HTML/CSS
* Blender
* JavaScript
* Visual Studio Code

***
## **Code example:**
```
function formatDuration (seconds) {
 let arr = [];
 let x, x2, x3, x4, x5;
if (seconds == 0) {
    arr.push('now');
}


if (seconds >= 31536000) {

 
    if     (seconds == 31536000)  {
        arr.push('1 year');
        seconds = 0;
    } else {
    x = Math.floor(seconds / 31536000);
    let ost = seconds - (31536000 * x);
    x == 1 ? arr.push(x + ' year, ') : arr.push(x + ' years, ');
    seconds = ost;
    }
    
   

}  if (seconds >= 86400 && seconds < 31536000) {
      
        if (seconds == 86400) {
        arr.push('1 day');
        seconds = 0;
    } else {
    x2 = Math.floor(seconds / 86400);
    let ost2 = seconds - (86400 * x2);
    x2 == 1 ? arr.push(x2 + ' day, ') : arr.push(x2 + ' days, ');
   seconds = ost2;
    }

    
   
}  if (seconds >= 3600 && seconds < 86400) {

       
        if (seconds == 3600) {
        arr.push('1 hour');
      seconds = 0;
    } else {
    x3 = Math.floor(seconds / 3600);
    let ost3 = seconds - (3600 * x3);
    x3 == 1 ? arr.push(x3 + ' hour, ') : arr.push(x3 + ' hours, ');
   seconds = ost3;
    }

        

    
}  if (seconds >= 60 && seconds < 3600) {

   x4 = Math.floor(seconds / 60);
    let ost4 = seconds - (60 * x4);

        if (seconds == 60) {
        arr.push('1 minute');
       seconds = 0;
    } else {
    
    x4 == 1 ? arr.push(x4 + ' minute') : arr.push(x4 + ' minutes');
    seconds = ost4;

    }


    
}  if (seconds < 60 && seconds > 0) {
    x5 = seconds;
    x5 == 1 ? arr.push(x5 + ' second') : arr.push(x5 + ' seconds');

 }
 // Day and second
if (x2 > 0 && x3 == undefined && x4 == undefined && x5 > 0) {
    arr[arr.length - 2] = arr[arr.length - 2].substring(0, arr[arr.length - 2].length - 1);
}
// Hour and second || Hour and minute
if ((x3 > 0 && x4 == undefined && x5 > 0) || (x3 > 0 && x4 > 0 && x5 == undefined)) {
    arr[arr.length - 2] = arr[arr.length - 2].substring(0, arr[arr.length - 2].length - 1);
}




 if (arr.length > 1) {
    
    arr[arr.length - 2] = arr[arr.length - 2].replace(',','');
    
    arr.splice(-1,0,' and ');
}
 
    return arr.join('');
}  
```
***
## **Experience:**
I learn Java Script!
***
## **Education:**
Vitebsk State Technological University
***
## **English:**
Elementary (A2)
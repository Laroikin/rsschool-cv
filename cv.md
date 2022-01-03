## **Abdiganiev Saidbek**

### **My contacts**

* Email: [said24abdi04@gmail.com](said24abdi04@gmail.com)
* Telegram: [Laroikin](https://t.me/laroikin)
* Tashkent, Uzbekistan -> Seoul, South Korea

### **About me**

Hello! I am UX/UI Designer and Front-end Developer from Uzbekistan currently studying in one of the most prestigious universities of South Korea. I am already familiar with the basics of front-end development and I am working on further improving upon those skills and acquire new ones in the process.

## **My Skills**

* HTML5
* CSS3
* Javascript
* C++
* C
* Python
* LESS
* GULP
* Git&Github
* Figma
* Adobe Photoshop
* Adobe Illustrator
* Adobe Premiere Pro
* Adobe After Effects

## **Code example**

```
function isPangram(string){
  let b = string.split(" ").join("").toUpperCase();
  let a = [...new Set(b)];



  let c = a.filter(function (str){
    if(str == "," || str == "." || str == "1" || str == "2" || str == "3" || str == "4" || str == "5" || str == "6" || str == "7" || str == "8" || str == "9"  || str == "0"){
      return false;
    }
    else return true;
  })

  
  ans = (c.length == 26) ? true : false;

  return ans;
}
```
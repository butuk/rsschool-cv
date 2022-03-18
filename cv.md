
![photo](/photo.png)
# Vitali Yanusheuski

Email: bootook@gmail.com

Telegram: t.me/butuk

Skype: bootook

Discord: Vitali Yanusheuski (@butuk)

---
&nbsp;

15 years of experience in developing design concepts, web interfaces prototypes, websites and mobile applications designs. Worked both in agencies creating solutions for a number of clients and in product-oriented startups. Also have an experience in web design teaching and art-directing of small groups of designers. Interested in visualization of complex data and processes. My main goal now is to master a new profession of web developer.


## Employment 
Red Graphic interactive agency. Web designer. *2006—2012*

Borovoy design studio. Web designer. *2012—2013*

Startup Labs. UI/UX designer. *2013*

Digitalizm agency. Web designer. *2013—2015*

Adamantium. UI/UX designer. *2015—2017*

Freelancer. UI/UX and data visualization designer. *2017—2019*

iFuture. UI/UX and web designer. *2019—now*

IT Academy. Web design instructor. *2021*


## Education
BSU, faculty of economics. Bachelor's degree. *2002—2007*

Gorbunov bureau design school. *2014—2015*

## Additional education
Digital advertising concepts development course. *2012*

Data Lab data visualization courses. *2016*

Coursera Information visualization course. *2019*

Codecademy JS, D3.js, HTML and CSS courses. *2021*

Roller Scope School. *now*

## Skills
Graphic tools such as Figma, Sketch app, Adobe XD, Photoshop, Illustrator and Tableau. HTML, CSS, JS, D3.js, Git.

## Code example

>Task: Given a positive integer n written as abcd... (a, b, c, d... being digits) and a positive integer p. Need to find a positive integer k, if it exists, such that the sum of the digits of n taken to the successive powers of p is equal to k * n. In other words: is there an integer k such as: (a ^ p + b ^ (p+1) + c ^(p+2) + d ^ (p+3) + ...) = n * k? If it is the case we will return k, if not return -1.

```
function digPow(n, p){
  let nums = n.toString().split('');
    let sum = 0;
    for (let i = 0; i < nums.length; i++){
        sum += Math.pow(nums[i], p);
        p++;
    }
    if (sum%n) return -1;
    return sum/n;
};
```

## Latest project
https://butuk.github.io/rsschool-cv/cv

## Languages
English, advanced level, CEFR C1

Belarusian, native

Russian, if needed
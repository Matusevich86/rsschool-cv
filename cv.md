# Aliaksandr Matusevich
## My contact info:
1. Phone: +48571940719
2. Email: alex.matusevich23@gmail.com
3. My [Telegram:](https://t.me/AleksandrMatusevich)
## About Me
> I think one of my greatest strengths is hardworking. I also a have great communication skills, which allow me to become part of any team.
## Skils
*	**Programming Languages:** JavaScript, HTML5, CS3.
*	**Source Control:** Git.
*	**Tools:** Visual Studio Code, Brackets.
## Code Examples
```
    "use strict"
    var treeM = [ 5, 7, 
        [ 4, [2], 8, [1,3], 2 ], 
        [ 9, [] ], 
        1, 8
    ];

    function treeSum(x){
        var sum = 0;
        for(var i = 0; i < x.length; i++) {
            var v = x[i];
            if (typeof v == 'object') {
            sum += treeSum(v);
            }else{
                sum += v;
            }
            }; 
        return sum;  
    };
    treeSum(treeM);
```
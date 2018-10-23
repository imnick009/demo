# demo
javascript


let a=[30,40,50,60];
let b=[10,20,...a,70,80];
console.log(b);
function collect(...c)
{
    console.log(c);
}
collect(12,45,25,76);

let values=[10,20,30,40];
let double = (n) =>{
    return n*2;
}

let doubled=values.map(double);
console.log(doubled);

let scores=values.map((n)=>
{
    return n*2;
});
console.log(scores);


<!DOCTYPE html>
<html>
 <head>
  <meta charset="utf-8">
  <title>Demo</title>
 </head>
 <body>
   <div>Hello World!</div>
   <script type="text/javascript" src="class.js"></script>
    </body>
</html>
 

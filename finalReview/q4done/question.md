## Question A (50% credit): 

What does the following code do?  How can you reverse the order?

    var points = [40, 100, 1, 5, 25, 10];
    points.sort(function(roo,raa){return roo-raa});

## Question B (50% credit): 

What's wrong with my code below?  How would you fix it?  Would using `var pi =` help? Why or why not?

    http://jsbin.com/zugaginigu/edit?js,console
    




It will sort the array in ascending order. It can be reversed with points.reverse();


We need to move Pi up before it is called; var would not help.

(function myFn(radius){
    const pi = 3.1415926;
    var boundary = Math.pow(radius, 2) * pi
    if(boundary) console.log('boundary is ', boundary);
}(20)) 

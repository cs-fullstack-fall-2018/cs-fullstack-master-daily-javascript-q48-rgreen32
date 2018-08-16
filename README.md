# daily-javascript-q48

The following page is shown in the browser: 

```html
<!DOCTYPE html> 
<html> 
<head> 
      <title>Intro to JavaScript</title> 
          	<meta charset="utf-8" /> 
</head> 
<body> 
      <script> 
           var Shape = { 
                type: 'Square', 
                length: 10, 
                width: 10, 
                info: function() { 
                     console.log(`${this.type}: ${this.length}x${this.width}`); 
                } 
           }; 

           var shape1 = Object.create(Shape); 
           shape1.info(); 

           var shape2 = Object.create(Shape); 
           shape2.width = 5; 
           shape2.type = 'Rectangle'; 
           shape2.info(); 
      </script> 
</body> 
</html> 
```

What will be displayed in the console?
<hr>
Choose the correct answer

1) Square: 10x10

   Square: 10x10

2) Square: undefined

    Rectangle: undefined

3) Rectangle: 10x5

    Rectangle: 10x5

4) Square: 10x10

    Rectangle: 10x5

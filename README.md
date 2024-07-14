# 16.pseudo-class-and-pseudo--element
# program :
```
<!DOCTYPE html>
<html>
  <head>
    <title>advanced css</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>advanced CSS</h1>
    <div class="item">
    <p>It's basic html and css</p>
    </div>  
     <ul>
    <li>hello world1</li>
     <li>hello world2</li>
     <li>hello world3</li>
    </ul>  
   
  </body>
</html>
body{
  background-color: #f0f0f0;
  padding: 0;
  margin: 0;
}
p::before{
  content:"Read this:-";  
  color: #2343f3;
  padding: 0;
}
li:nth-child(3){
  background-color: #777;
}
h1{
  background-color: tomato;
  border-bottom: 2px solid red;
  text-align: center;
}
```
# output:
![WhatsApp Image 2024-07-14 at 22 56 18_9636dd87](https://github.com/user-attachments/assets/9016c9b6-6bec-4498-82d9-d333b40b528d)

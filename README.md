# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the Github repository and create a Django admin interface.

### Step 2:
Write HTML and CSS Code for designing book cover page and circulate them.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 500px;
            color: black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            background-image: url(/static/images/out.jpeg);
            background-size: cover;
        }
            

        .insight{
            color: darkslategrey;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(131, 96, 131);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: rgba(255, 251, 0, 0.752);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 300px;
            width: 90px;
            height: 70px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: white;">
            </div>
            <div class="booktitle">
                <h1>30 WAYS TO BECOME A SKILLED PROGRAMMER</h1></div>
            <div class="subtitle">
                C,C++,PYTHON,JAVA...
            </div>
            <div class="mypic">
                <img src="/static/images/index.jpeg" width="120" height="125" alt="">
            </div>
            <div class="id">
                <hr style="color: dimgray;">
            </div>
            <div class="author">
               <p><b>Subalakshmi V</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Eighteenth Edition</b>
            </div>
        </div>
    </body>
</html>
```

## Output:
![Output](./outs.png)

## HTML Validator:
![HTML Validator](./validator.png)

## Result:
The program for designing book cover page using HTML and CSS is executed successfully.

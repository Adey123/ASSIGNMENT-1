"# ASSIGNMENT-1" 
<html> 
<head>
    <meta charset="utf-">
    <meta name="descrption" content="Ghana-Tech Lab Assignment">
    <meta name="#author" content="ADEYLINE">
    <!--Responsivenss of my website-->
    <meta name= "viewport" content="width=device-width, initial-scale =1.0">
    <style>
        body{font-family:Arial, Helvetica, sans-serif;}
        * {box-sizing: border-box;}
        * {background-color: white
        }
    
    
        input[type=text], select,textarea{
            width: 100%;
            padding: 12px;
            border-radius: 4px;
            box-sizing: border-box;
            margin-top: 6px;
            background-color: black (128, 152, 180);
            font-size: 20px;

        }
        input[type=submit]{
            background-color: white;
            color: darkgray;
            padding: 12px 20px;
            border: none;
            cursor: pointer;
        }
                input[type=submit]:hover{
                    background-color: pink
                
                }
                .container{
                    border-radius: 5px;
                    background-color: white;
                    padding: 20px;
                }
                label {
                    margin: auto;
                 }
                 </style>
                 </head>
                 <body>
                     <h1> GHANA MUST WIN</h1>
                     <section>
                         <div class="container">
                             <form action="action_page.php">
                                 <label for="fname">First name</label>
                                 <input type="text" id="fname"name="firstname"placeholder="Your name.">
                                 <label class="label" for="lname">Last Name</label>
                                 <input type="text" id="lname" name="lastname" placeholder="Your last name.">
                                 <label for="country">Country</label>
                                 <select id="Country"name="Country">
                                     <options value="Ghana">Ghana</options>
                                     <option value="USA">USA</option>
                                    </select>
                                    <label for="subject">subject</label>
                                    <textarea id="subject"name="subject" placeholder="write something."styple="height: 400px;"></textarea>
                                    <input type="submit" value="submit">
                             </form>
                         </div>
                     </section>
                
             </body>
    </html>

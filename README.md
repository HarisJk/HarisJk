<!DOCTYPE html>
<html>
<style>
     input[type=text],select{
        width: 100%;
        padding: 12px 20px;
        display: inline-block;
        border: 1px solid #ccc;
        border-radius: 4px;
        box-sizing: border-box;
        color: hsl(0, 0%, 0%);
    }
     input[type=submit] {
        width: 100%;
        background:green;
        color: white;
        padding: 14px 20px;
        margin: 8px 0;
        border: none;
        cursor: pointer;
     }
     div{
        border-radius: 5px;
        background-color:bisque;
        padding: 20px;
     }
     h1{
        text-align: center;
        color:black;
     }

</style>
    <body style="background-color:powderblue;">
        <h1>EMPLOYEES LEAVE NOTIFICATION </h1>
    <div>
        <form action="/action_page.php">
            <label for="username">username:</label><br>
            <input type="text" id="username"name="Harish"><br>
            <label for="password">password:</label><br>
            <input type="text" id="password"name="347465"><br><br>
            <input type="submit" onclick="alert('S.Manikandan leave on monday 12/08/2024 to wednesday 14/08/2024')"" value="submit">
        </form>
    </div>   
</body>
</html

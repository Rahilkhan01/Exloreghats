# MyfirstCal
<!DOCTYPE html>
<html lang="en">
<head>
<style>
.container{
    text-align: center;
    margin: 25px;
}
table{
    margin: auto;
}
input{font-size: 34px;
      border: 5px solid black;
      border-radius: 21px
}
button{font-size: 23px;
        background-color: #978fa0;
        width: 103px;
        height: 58px;
        border-radius: 21px;
}
.calculator{
    background-color: rgb(193, 221, 245);
    border-radius: 53px;
    padding: 23px;
    display:inline-block;
}
</style>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
    <h1>Calculator</h1>
    
    <div class="calculator"> 
           <input type="text" name="screen" id="screen">
    <table>
        <tr>
            <td><button>(</button></td>
            <td><button>)</button></td>
            <td><button>c</button></td>
            <td><button>%</button></td>
        </tr>
        
        <tr>
            <td><button>(</button></td>
            <td><button>)</button></td>
            <td><button>c</button></td>
            <td><button>%</button></td>
        </tr>
        
        <tr>
            <td><button>7</button></td>
            <td><button>8</button></td>
            <td><button>9</button></td>
            <td><button>X</button></td>
        </tr>
        
        <tr>
            <td><button>4</button></td>
            <td><button>5</button></td>
            <td><button>6</button></td>
            <td><button>-</button></td>
        </tr>
        
        <tr>
            <td><button>0</button></td>
            <td><button>.</button></td>
            <td><button>/</button></td>
            <td><button>=</button></td>
        </tr>
        
        </table>
    </div>
    </div> 
</body>
<script src="index.js "></script>
</html>

### Hi there 👋

<!--
**tuliooarauj/tuliooarauj** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=], initial-scale=1.0">
    <title>Card</title>
    <style>
        *{
            padding: 0;
            margin: 0;

        }
        #container{
           width: 100vw;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        #card{
            
            width: 300px;
            height: 500px;
            background-color: purple;
            border-radius: 10px;
            border: 3px solid black;

            display: flex;
            align-items: center;
            flex-direction: column;
            justify-content: space-around;
        }

        h1{
            text-align: center;
            color: red;
        }
        img{
            width: 80%;
        }
        #link{
            display: flex;
        }
        a{
            text-decoration: none;
            text-align: center;
            color: black;

            border: 2px solid black;
           
            margin: 40px 30px;
            background-color: antiquewhite;

            border-radius: 10px;
            width: 80px;
            height: 30px;       


            display: flex;
            align-items: center;
            justify-content: center;
        }
        ul li{
            display: inline-block;
        }
    </style>
</head>
<body>
    <div id="container">
        <div id="card">
            <h1 >Salamence</h1>

            <img src="https://assets.pokemon.com/assets/cms2/img/pokedex/full/373.png" alt="Salamence">

            <div id="link">
                <a href="https://pokemondb.net/type/dragon"><p class="botao">Dragon</p></a>
                <a href="https://pokemondb.net/type/flying"><p class="botao">Flying</p></a>
            </div>
    
            <div id="icon">
                <ul>
                    <li>⭐</li>
                    <li>⭐</li>
                    <li>⭐</li>
                    <li>⭐</li>
                    <li>⭐</li>
                </ul>
            </div>
        </div>
        

       
    </div>
</body>
</html>

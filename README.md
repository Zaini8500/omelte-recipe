# omelte-recipe
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recipe-Page</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" type="image/png" href="images.jpg">
</head>
<body>
    <main>
        <div class="container">
            <div class="header-img">
                <img src="images.jpg" alt="omelette" class="omelette-img" width="100%" height="auto">
            </div>
            <header>
                <h1 class="main-heading">Simple Omelette Recipe</h1>
                <p class="sub-heading"> An easy and quick dish, perfect for any meal. This classic omelette combines beaten eggs cooked 
                    to perfection, optionally filled with your choice of cheese, vegetables, or meats.</p>
                    <div class="preparation">
                        <p class="prep-time">Preparation time</p>
                        <ul>
                            <li><b>Total:</b> Approximately 10 minutes</li>
                            <li><b>Preparation:</b> 5 minutes</li>
                            <li><b>Cooking:</b> 5 minutes</li>
                        </ul>
                    </div>
            </header>
            <section class="divider">
                <h2  class="sect-heading">Ingredients</h2>
                <ul>
                    <li>2-3 large eggs</li>
                    <li>Salt, to taste</li>
                    <li>Pepper, to taste</li>
                    <li>1 tablespoon of butter or oil</li>
                    <li>Optional fillings: cheese, diced vegetables, cooked meats, herbs</li>
                </ul>
                <div class="line"></div>
            </section class="divider">
            <section>
                <h2 class="sect-heading">Instructions</h2>
                <ol>
                    <li><b>Beat the eggs:</b> In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed. 
                        You can add a tablespoon of water or milk for a fluffier texture.</li>
                    <li><b>Heat the pan:</b> Place a non-stick frying pan over medium heat and add butter or oil.</li>
                    <li><b>Cook the omelette:</b> Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure 
                        the eggs evenly coat the surface.</li>
                    <li><b>Add fillings (optional):</b> When the eggs begin to set at the edges but are still slightly runny in the 
                        middle, sprinkle your chosen fillings over one half of the omelette.</li>
                    <li><b>Fold and serve:</b> As the omelette continues to cook, carefully lift one edge and fold it over the 
                        fillings. Let it cook for another minute, then slide it onto a plate.</li>
                    <li><b>Enjoy:</b> Serve hot, with additional salt and pepper if needed.</li>
                </ol>
                <div class="line"></div>
            </section>
            <section>
                <h2 class="sect-heading">Nutrition</h2>
                <caption>The table below shows nutritional values per serving without the additional fillings.</caption>
                <table>
                    <thead>
                        <tr>
                            <td class="table-data">calories</td>
                            <th class="table-head">277kcal</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td class="table-data">Carbs</td>
                            <th class="table-head">0g</th>
                        </tr>
                        <tr>
                            <td class="table-data">Protein</td>
                            <th class="table-head">20g</th>
                        </tr>
                        <tr>
                            <td>Fat</td>
                            <th>22g</th>
                        </tr>
                    </tbody>
                </table>
            </section>
        </div>
    </main>
</body>
</html>
h=
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: hsl(30, 54%, 90%);
}
main {
    width: 500px;
    background-color: hsl(0, 0%, 95%);
    padding: 2rem;
    margin: 3rem 0;
    border-radius: 1.5rem;
}
.omelette-img {
    border-radius: 0.6rem;
    margin-bottom: 0.5rem;
}
.main-heading {
    margin-bottom: 1.5rem;
}
.sub-heading {
    margin-bottom: 1.5rem;
    font-size: 12px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
.preparation {
    background-color: hsl(328, 63%, 95%);
    padding: 0.9rem 2.1rem;
    border-radius: 0.6rem;
}
.prep-time {
  position: relative;
  left: -14px;
  font-family:'Times New Roman', Times, serif;
  font-weight: bold;
  color: hsl(14, 45%, 36%);
  padding-bottom: 5px;
}  
  ul li {
    margin-left: 0.5rem;
    padding: 5px 1rem;
    font-size: 11px;
  }
  ul li::marker {
    content: "\2022";
    color: hsl(14, 45%, 36%);
    margin-right: 1.3rem;
  }
  ol li {
     padding: 5px 1rem;
     margin-left: 1rem;
     font-size: 11px;
  }
  ol li::marker {
    color: hsl(14, 45%, 36%);
    font-weight: bold;
  }
  .divider {
    margin: 1.2rem 0;
  }
  .sect-heading {
    color: hsl(14, 45%, 36%);
    margin-bottom: 0.6rem;
  }
  .line {
    margin: 1.5rem 0;
    opacity: 0.2;
    border: 1px solid;
  }
  table {
    width: 100%;
    padding-left: 1rem;
    padding-top: 1rem;
    border-collapse: separate;
  } 
th {
    color: hsl(14, 45%, 36%);
    text-align: left;
}
.table-head, .table-data {
    vertical-align: middle;
    padding: 10px;
    border-bottom: 1px solid rgb(10, 10, 10, 0.2);
    width: 1%;
    font-size: 12px;
}
th, td {
    vertical-align: middle;
    padding: 10px;
    width: 1%;
    font-size: 12px;
}
footer {
    margin-bottom: 10px;
    padding-bottom: 10px;
}
a {
    text-decoration: none;
    color: black;
}
a:hover {
    color: rgb(157, 157, 250);
    border-bottom: 1px solid;
}
@media only screen and (max-width: 500px){
    main {
        width: 432px;
        height: auto;
        margin: 0 auto 10px;
        padding: 0 0 30px;
        border-radius: 0;
    }
    body {
        width: 400px;
    }
    .container {
        border: none;
    }
    header {
        padding-left: 10px;
        padding-right: 15px;
    }
    section {
        padding-left: 10px;
        padding-right: 15px;
    }
    .omelette-img {
        border-radius: 0;
    }
}


  

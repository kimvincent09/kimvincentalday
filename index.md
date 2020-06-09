<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Black Market</title>
</head>
<style>
header{
    display: flex;
    justify-content: center;
    background-color: black;
    color: white;
    grid-row: 1/2;
}
footer{
    grid-row: 4/5;
    background-color: black;
    display: flex;
    color: white;
    justify-content: center;
    align-items: center;
}
nav{
    background-color: black;

    border-top: solid;
    border-color: white;
    grid-row: 2/3;
}
li{
    display: inline;
    margin: 0px 10px 0px 10px;
    padding:10px;
}
li:hover{
  background-color: gray;
}
a{
    text-decoration: none;
    color:white
}

.active{
    color: blue;
}
.container{
    display:grid;
    grid-template-rows: 100px 50px auto 100px;;
}
main{
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-template-columns: 3fr 1fr;
    align-content: center;
    grid-row:3/4;
}
#item{
    width: 100%;
grid-row: 2/3;
}
.a{
    grid-column: 1/2;
    grid-row: 2/3;
    display:grid;
    grid-template-rows: 1fr 1fr 1fr;
}
.b{
    grid-column: 2/3;
    grid-row: 2/3;
    display:grid;
    grid-template-rows: 1fr 1fr 1fr;
}
.c{
    grid-column: 3/4;
    grid-row: 2/3;
    display:grid;
    grid-template-rows: 1fr 1fr 1fr;
}

.intro{
    grid-column: 1/5;
    display: flex;
    justify-content: center;
    grid-row: 1/2;
}
.sticky{
    position: sticky;
    z-index: 1020px;
    top:0;
}
aside{
    grid-column: 2/3;
    display:grid;
    grid-template-rows: auto auto;
    border-left:solid;
    border-right:solid;
    border-color:black;
    position: sticky;
    top:25px;
    z-index: 100;
    height: 100vh
}
.products{
    display:grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 100px 30%;
    grid-column:1/2;
    grid-column-gap:25px;
    grid-row-gap:25px;
}
.ad{
    display: flex;
    justify-content: center;
    text-decoration: underline;
}
blockquote{
    text-align: justify;
}
#img{
    width: 100%;    


}
.caption{
    display: flex;
    justify-content: center;
    background-color: rgb(175, 175, 175);
    grid-row: 1/2;
}
button{
grid-row: 3/4;
background-color: black;
color:white;
cursor: pointer;
}
nav{
    filter: opacity(80%);
}





</style>
<body>
    <div class="container">
    <header>
        <h1>The Black Market</h1>
    </header>
    <nav class="sticky">
        <ul>
            <li><a href= "#" class="active">Home</a></li>
            <li><a href= "#">About</a></li>
            <li><a href= "#">Connect</a></li>
            <li><a href= "#">Products</a></li>
            <li><a href= "#">Hotline</a></li>
            <li><a href= "#">Account</a></li>
        </ul>
    </nav>

    <main>
        <div class="products">
        <div class="intro">
        <h1>Our Products</h1>
        </div>
      
        <div class="a">
            <h3 class="caption">VR Box</h3>
            <img src="13603287_1736843053238022_2269169925657281746_o.jpg" id="item">
            <button>Avail Now</button>
            </div>
            <div class="b">
                <h3 class="caption">VR Box</h3>
            <img src="13603287_1736843053238022_2269169925657281746_o.jpg" id="item">
            <button>Avail Now</button>
        </div>
        <div class="c">
            <h3 class="caption">VR Box</h3>
            <img src="13603287_1736843053238022_2269169925657281746_o.jpg" id="item">
            <button>Avail Now</button>
        </div>
   </div>
   <aside>
       <div class="ad"><h2>Advertisements</h2></div>
       <img src="13603287_1736843053238022_2269169925657281746_o.jpg" id="img">
       <blockquote>Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet odio veniam aliquam est voluptate! Quae, ratione cupiditate repellat officia obcaecati voluptas quisquam laboriosam debitis labore autem fugit consectetur, magnam adipisci.</blockquote>
   </aside>
    </main>
    <footer>
       <h5> Copyrights 2020. The Black Market</h5>
    </footer>
    </div>
</body>
</html>

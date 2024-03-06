*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
#heading{
    width: 100%;
     background-color: rgb(0, 217, 255);
    color: black;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 40px;
    padding: 15px 80px;
}
.logo{
    font-size: 30px;
    font-weight: bolder;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    color: black;
}
.logo span{
    font-size: 25px;
    font-weight: bolder;
    color: black;
}
.search{
    background-color: white;
    padding: 5px 5px 4px 8px;
    display: flex;
}


.inputfiled {
    width: 385px;
        outline: none;
    border: none;
    text-align: center;
    border-radius: 20px;
    font-size: 17px;
    text-transform: capitalize;
}
.navbar{
    display: flex;
    align-items: center;
    justify-content: center;

}
.navbar ul {
text-transform: none;
}
.navbar ul a li {
display: inline;
    list-style: none;
    color: black;
    margin: 20px;
    font-size: 20px;
}


.navbar .btn{
    background-color: white;
    padding: 8px;
    color: black;
}

.container{
    background-color: rgb(255, 255, 255);
    width: 100%;
    padding: 40px;
}
.container h3{
    text-align: center;
    font-size: 25px;
    font-weight: bolder;
    font-family: 'Times New Roman', Times, serif;
}

.container p{
padding: 20px 0px ;
    text-align: center;
    font-size: 16px;
   color: gray;
   letter-spacing: 3px;

}

.btn1{
    display: flex;
    gap: 20px;
    margin-top: 30px;
}

.btn1 li  {
    list-style: none;
    color: black;
}
.btn1 a{
    text-decoration: none;
}
.showing-btn{
    border: 1px solid gray;
    border-radius: 20px;
    padding: 10px 20px;

    background-color: white;
}
.showing-btn:hover{
    background-color: royalblue;
    border: 1px solid rgb(255, 255, 255);

}
.btn1 li:hover{
    color: white;
}
.search1{
    background-color: white;
    padding: 8px 5px 4px 8px;
    display: flex;
    border: 1px solid gray;
    border-radius: 20px;
    display: inline;
}


.inputfiled1 {
 margin: 35px 0px;
    width: 385px;
        outline: none;
    border: none;
    text-align: start;
    border-radius: 20px;
    font-size: 17px;
    text-transform: capitalize;
   
}

.main-card{
    display: flex;
    flex-wrap: wrap;
    padding: 15px 90px;
    gap: 50px;
}
.card{
    max-width: 240px;
   background-color: rgb(255, 255, 255);
   box-shadow: 5px 10px 10px rgba(0,0,0,0.6);
   

}
.card img{
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-top-left-radius: 5px;
   border-top-right-radius: 5px;
}
.card h1{
    font-size: 18px;
    margin-left: 5px;
    margin-top: 6px;
    margin-bottom: 6px;
}
.p-card{
    font-size: 16px;
    margin-left: 5px;
    margin-top: 6px;
    margin-bottom: 6px;
    color: gray;
}
.checked {
    margin-top: 5px;
    margin-bottom: 10px;
    color: orange;
  }

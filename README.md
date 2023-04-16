*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
    background-color: none;
}

/*--------------------*/
/*imagenes html,css y js*/
img{
    width: 120px;
}
#html{
    width: 170px;
    
/*--------------------*/

}

#img1{
    width: 200px; 
    height: 70px;
}
.titulo{
    background-color: rgba(167, 166, 166, 0.26);
}

#col{
    background-color: rgb(168, 29, 124);
}
/* Nosotros */



.body{
    font-family: sans-serif;
    text-align: center;
    color:black;
 
}
.header{
    width: 100%;
    height: auto;
    align-items: center;
    text-align: center;
    display: flex;
    justify-content: center;
    overflow: hidden;
    text-align: center;
    color:black;
    position: relative;
   


}

.video{
    
    position: absolute;
    display: flex; 
}
.absolute{
    width: 100%;
    height: 100%;
    padding-left: 500px;
    right:0px;
    padding-left: 400px;
    text-align: center;
    display: flex;
    justify-content: center;
}
  .absolute h1{
     width: 100%;
     height: auto;
    margin-bottom: 30px;
    font-size: 100px;
    font-weight: 500;
    z-index:100 ;
    font-family: Arial, Helvetica, sans-serif;

    display:flex;
   
}
.container, .box, .titulo, .content{
    width: 100%;  
    }

.container{
    max-width: 1150px;
    margin: auto;
    margin-top: 70px;
    text-align: center;
    color:black;
    line-height:1.7em;
    justify-content: center;
}

.content{
    display: grid;
    grid-template-columns: repeat(4,1fr);
    gap: 55px;
    
}
.box figure{
    width: 200px;
    height: 200px;
    border-radius: 50%;
    margin-bottom: 45px;
    display:flex;
    overflow: hidden;
    justify-content: center;
    text-align: center;
    margin-left: 70px;
}
.h1::after{
    display: block;
    width: 30px;
    height: 10px;
    content: "";
    margin: auto;

}
.box img{
    width: 100%;
    height: 100%;
    object-fit: cover; 
    border-radius: 50%; 
}

.name{
    color: black;
    
}
@media screen and(max-width:800px){
 h1{
    font-size: 50px;
 }   
}
@media screen and (max-width:500px){
    h1{
       font-size: 30px;
       margin-bottom:0;
    }   
   }
   h1::after{
    display: none;
   }

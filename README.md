## Hi Simo 👋
*{
  margin: 0;
  padding: 0;
}
body{
  background: black;
  color: #fff;
  font-family: serif;
  
}
h2{
  background :#fff;
  color:green;
  border: solid;
  border-width: 20px;
  border-color: red  #000A72 black green;
}
p{
  text-shadow: 1px 1px red;
  border: solid 1px #fff;
}
.gn{
  width:fit-content;
  
}
.crud{
  /*background-image:url("images/3.jpg") ;
  background-size: contain;
  background-repeat: no-repeat;
  */

  background: #040941;
  width: 96%;
  
  padding: 5px;
  border: solid 2px yellow;
  /*جعل المشروع في الوسط*/
  margin: auto;
 
}
.inputs,.output,.head{
  margin-bottom:30px ;
}
.head{
  text-align: center;
  text-transform: uppercase;
  margin: 10px 0;
}
input{
  background:  #D1E3BC;
  width: 43%;
  margin: 4px;
  padding: 2px;
  border-radius: 20px;
  
}
input:focus {
  background: lightblue;
  transform: scale(1.1);
}
.gender{
  width :fit-content;
}
#countries{
  margin-left: 30px;
}
#submit{
  background: #B2F167;
  width :100%;
  padding: 2px;
  font-weight:900 ;
  color: #070013;
  text-shadow:1px 1px 0px red ;
  border-radius: 30px;
  transition: 0.5s;
  
}
#submit:hover{
  letter-spacing: 1px;
}

#search{
  width :95%;
 
  
}
.btnsearch{
  display: flex;
  justify-content: space-between;
}
.btnsearch button{
  width :45%;
}
table{
  width :100%;
  margin: 10px 0;
  border: 2px double green;
  text-align: center;
}
table th{
  text-transform: uppercase;
  border: 2px double #EB34CB;
  text-shadow:1px 1px 0px red ;
  
}
table td{
  border: 2px double green;
}

#ct{
  overflow: scroll;
}
fieldset{
  display: flex;
  
}
#female{
  width:fit-content;
margin-left:30% ;
}
#male{
  width:fit-content;
margin-left:10% ;
}
#deleteAll{
  background: #93F37D;
  text-align: center;
  font-weight:600;
  color: red;
  text-shadow:1px 1px 0px #fff;
  border-radius: 5px;
  transition: 0.5s;
  margin: 20px 0;
}
#delete{
  background: #DD627E;
}
#update{
  background: #29E22C;
}
#update,#delete{
  border-radius: 10px;
  padding: 4px;
  color: #fff;
  font-weight: 600;
  text-shadow: 2px 2px #0C1FE7;
}

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="style.css" />
 <style>
body {
  width: 100%;

  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #181818;
}
.card {
  display: grid;
  grid-template-columns: 300px;
  grid-template-rows: 170px 190px 80px;
  grid-template-areas: "image" "text" "stats";
  border-radius: 100px;
  background: #181818;
  box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.9);
  font-family: sans-serif;
  text-align: center;
  color:white;
}
body:-webkit-scrollbar{
    display: none;
}
.image {
  grid-area: image;
}
.text {
  grid-area: text;
}
.stats {
  grid-area: stats;
}
.image {
  grid-area: image;
  background: url("https://i.pinimg.com/originals/67/48/e2/6748e2f29ea1cafaff9d9456d221bcdc.jpg");
  border-top-left-radius: 15px;
  border-top-right-radius: 30px;
  background-size: cover;
}
.text {
  grid-area: text;
  margin:20px;
}
.text .date {
  color:grey;
  font-size: 13px;
}
.text p {
  color: yellow;
  font-size: 15px;
  font-weight: 300;
}
.text h2 {
   color:green;
  margin:0px;
  font-size: 28px;
}
.text h3 { 
    font-size:28px;
       color:red;
}
.stats {
  grid-area: stats;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr;

  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 15px;
  background: #202020;
}

.stats .stat {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;

  color: white;
  padding: 0px;
}
.card:hover {
  transform: scale(1.15);
  box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.6);
}
.card {
  transition: 0.5s ease;
  cursor: pointer;
  margin: 20px 0px;
}</style>
  </head>
  <body>
    <div class="card">
      <div class="image"></div>
      <div class="text">
   
        <h2>New Year</h2>
        
          <p>New is the year!</p>
          <p>New are the hopes! </p>
          <p>New is the resolution! </p>
          <p>New are the spirits! </p>
          <p>New are wishes!</p>
          <p>New billion of project</p>
          <p>New billion of success</p>
          <p>New billion of dollars>
    <h3> from Mamadou Niaré</h3>
      </div>


    

  </body>
</html>

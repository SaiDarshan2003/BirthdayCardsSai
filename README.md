# BirthdayCardsSai
## Aim:
To create HTML page for Birthday of a friend.
## Code:
```

<!DOCTYPE html>
<html>
<style>
    body {
  width: 100vw;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background:url("1.jpg");
  overflow: hidden;
}
.card {
  display: grid;
  grid-template-columns: 300px;
  grid-template-rows: 210px 210px 80px;
  grid-template-areas: "image" "text" "stats";

  border-radius: 18px;
  background: white;
  box-shadow: 5px 5px 15px rgba(0,0,0,0.9);
  font-family: roboto;
  text-align: center;
  

  transition: 0.5s ease;
  cursor: pointer;
  margin:30px;
}
.card-image {
  grid-area: image;
  background: url("img1.jpg");
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
  background-size: cover;
}

.card-text {
  grid-area: text;
  margin: 25px;
}
.card-text .date {
  color: rgb(255, 7, 110);
  font-size:13px;
}
.card-text p {
  color: grey;
  font-size:15px;
  font-weight: 300;
}
.card-text h2 {
  margin-top:0px;
  font-size:28px;
}
.card-stats {
  grid-area: stats; 
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr;
  border-bottom-left-radius: 15px;
  border-bottom-right-radius: 15px;
  background: rgb(255, 7, 110);
}
.card-stats .stat {
  padding:10px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  color: white;
}
.card-stats .border {
  border-left: 1px solid rgb(172, 26, 87);
  border-right: 1px solid rgb(172, 26, 87);
}
.card-stats .value{
  font-size:22px;
  font-weight: 500;
}
.card-stats .value sup{
  font-size:12px;
}
.card-stats .type{
  font-size:11px;
  font-weight: 300;
  text-transform: uppercase;
}
.card:hover {
  transform: scale(1.15);
  box-shadow: 5px 5px 15px rgba(0,0,0,0.6);
}

/*card2*/
.card-image.card2 {
  background: url("img2.jpg");
  background-size: cover;
}
.card-text.card2 .date {
  color: rgb(255, 77, 7);
}
.card-stats.card2 .border {
  border-left: 1px solid rgb(185, 67, 20);
  border-right: 1px solid rgb(185, 67, 20);
}
.card-stats.card2 {
  background: rgb(255, 77, 7);
}
/*card3*/
.card-image.card3 {
  background: url("img3.jpg");
  background-size: cover;
}
.card-text.card3 .date {
  color: rgb(0, 189, 63);
}
.card-stats.card3 .border {
  border-left: 1px solid rgb(14, 122, 50);
  border-right: 1px solid rgb(14, 122, 50);
}
.card-stats.card3 {
  background: rgb(0, 189, 63);
}
</style>
  <head>
    <meta charset="UTF-8" /
  </head>
  <body>
    <div class="card" style="background-color: dimgray;">
      <div class="card-image"></div>
      <div class="card-text">
        <div style="color: aquamarine;"><h2><i>Many more happy returns of that day!!</i></h2></div>
<div style="color: chartreuse;"><i>I'm wishing you another year<br/>
    Of laughter, joy and fun,<br/>
    Surprises, love and happiness,<br/>
    And when your birthday's done,<br/>
    I hope you feel deep in your heart,<br/>
    As your birthdays come and go,<br/>
    How very much you mean to me,<br/>
    More than you can know.</i></div>
      </div>
      </div>
    </div>
    <div class="card"style="background-color: dimgray;">
      <div class="card-image card2"></div>
      <div class="card-text card2">
        <div style="color: aquamarine;"><h2><i>Happy Birthday My Loved One!!!</i></h2></div>
        <div style="color: chartreuse;"><i>You have no idea how much your friendship means to me. <br/>
            I may not say it often, but I love you and wish you nothing<br/>
             but happiness today and always. Happy birthday!<br/></i></div>
      </div>
      </div>
    </div>
    <div class="card"style="background-color: dimgray;">
        <div class="card-image card3"></div>
        <div class="card-text card3">
            <div style="color: aquamarine;"><i><h2>May God Bless You!!</h![1](https://user-images.githubusercontent.com/94692595/230767244-24375f36-9802-4c69-b9b1-2b90052ee2c8.jpg)
2></i></div>
          <div style="color: chartreuse;">May God be with you at each and every endevour that you<br/>
             embark on and shower you with nothing but grace and <br/>
             blessings.I will always be praying for your thrive in <br/>
             my prayers,:)!!<br/></div>
        </div>
        </div>
      </div>
  </body>
</html>

```
Output:
![1](https://user-images.githubusercontent.com/94692595/230767286-f08eabec-d7d0-4655-992f-b8e9030a61a1.png)

## Result:
A Birthsay card has been created using HTML.

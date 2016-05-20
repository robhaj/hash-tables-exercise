
## Top 10 Films By Domestic Box Office Gross

| Rank        | Title           | Domestic Box Office Gross (in millions)  |
| ------------- |-------------| -----|
|1|Star Wars Ep. VII: The Force Awakens|$9.36|
|2|Avatar|$7.6|
|3|Titanic|$6.58|
|4|Jurassic World|$6.52|
|5|The Avengers|$6.23|
|6|The Dark Knight|$5.33|
|7|Titanic |$6.58|
|8|Star Wars Ep. IV: A New Hope|$4.6|
|9|The Avengers: Age of Ultron|$4.59|
|10|The Dark Knight Rises|$4.48|


```js
var movies = [];
movies.push(["Star Wars Ep. VII: The Force Awakens", "$9.36"]);
movies.push(["Avatar", "$7.6"]);
movies.push(["Titanic", "$6.58"]);
movies.push(["Jurassic World", "$6.52"]);
movies.push(["The Avengers", "$6.23"]);
movies.push(["The Dark Knight", "$5.33"]);
movies.push(["Titanic", "$6.58"]);
movies.push(["Star Wars Ep. IV: A New Hope", "$4.6"]);
movies.push(["The Avengers: Age of Ultron", "$4.59"]);
movies.push(["The Dark Knight Rises", "$4.48"]);


var movie = "The Dark Knight";

for (var i = 0; i < movies.length; i++) {
  if (movies[i][0] == movie) {
    console.log(movie + ":" + myData[i][1]);
  }
}
```



```js
var movies = {};

movies["Star Wars Ep. VII: The Force Awakens"] = "$9.36";
movies["Star Wars Ep. VII: The Force Awakens"] = "$9.36";
movies["Avatar"] = "$7.6";
movies["Titanic"] = "$6.58";
movies["Jurassic World"] = "$6.52";
movies["The Avengers"] = "$6.23";
movies["The Dark Knight"] = "$5.33";
movies["Titanic"] = "$6.58";
movies["Star Wars Ep. IV: A New Hope"] = "$4.6";
movies["The Avengers: Age of Ultron"] = "$4.59";
movies["The Dark Knight Rises"] = "$4.48";
```

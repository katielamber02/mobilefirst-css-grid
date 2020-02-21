```
/* small tablet styles */
@media screen and (min-width: 620px) {
  .welcome-text {
    grid-column: 1/5;
  }
  .welcome-img {
    grid-column: 5/9;
  }
  .welcome-img img {
    width: 100%;
  }
  .projects {
    margin-top: 40px;
  }
  .projects a {
    grid-column: span 4;
    display: block;
    margin: 20px 0;
  }
  .projects a:last-child {
    grid-column: 3/7;
  }
  .projects a * {
    margin: 10px;
    max-width: 60%;
    margin: 10px 20%;
  }
  .projects h4 {
    text-align: center;
  }
  #skills {
    padding: 30px 100px;
  }
  footer {
    background-size: 20%;
  }
}
```

<img src="gitimages/10.png"  />

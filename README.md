```
.projects {
display: grid;
grid-template-columns: 1fr 1fr 1fr;
gap: 1px;
}
.projects a {
text-align: center;
background: #9893d8;
padding: 20px;
}

 <div className="projects grid">
          <a href="#">
            <img src="assets/project_1.png" alt="space race image" />
            <h4>Space Race Game</h4>
          </a>
          <a href="#">
            <img src="assets/project_2.png" alt="planet boy image" />
            <h4>Planet Boy API</h4>
          </a>
          <a href="#">
            <img src="assets/project_3.png" alt="captain cosmo image" />
            <h4>Captain Cosmo Blog</h4>
          </a>
 </div>
```
<img src="gitimages/1.png"  />
<img src="gitimages/2.png"  />

Image Size Changed:
```
.projects {
display: grid;
grid-template-columns: repeat(12, 1fr);
gap: 1px;
}
.projects a {
text-align: center;
background: #9893d8;
padding: 20px;
}

.projects img {
max-width: 100%;
}
```
<img src="gitimages/3.png"  />

Displaying On The Grid in Rows:
```
.projects {
display: grid;
grid-template-columns: repeat(12, 1fr);
gap: 1px;
}
.projects a {
text-align: center;
background: #9893d8;
padding: 20px;
}

.projects img {
max-width: 100%;
}
.projects a:nth-child(1) {
grid-column: 2/6;
grid-row: 1;
}
.projects a:nth-child(2) {
grid-column: 8/12;
grid-row: 1;
}
.projects a:nth-child(3) {
grid-column: 5/9;
grid-row: 2;
}
```
<img src="gitimages/4.png"  />

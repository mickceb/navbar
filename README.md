# Navbar Responsive
HTML :
```
<nav class="navbar">
    <div class="nav-elements" id="nav-elements">
        <h2><a href='#'>lorem ipsum</a></h2>
        <ul class="nav-links">
            <li><a href='#'>Item#1</a></li>
            <li><a href='#'>Item#2</a></li>
            <li><a href='#'>Item#3</a></li>
        </ul>
    </div>
</nav>
```

CSS :
```
nav {
  width: 100%;
  background: #6495ed;
  box-shadow: 0 0 3px #333;
  position: fixed;
}
.nav-elements {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 90%;
  margin: auto;
  height: 10vh;
}
.nav-elements a {
  color: #333;
  text-decoration: none;
}
.nav-elements a:visited {
  color: #333;
}
.nav-elements h2 {
  transition: all .3s ease-in-out;
}
.nav-links {
  display: flex;
  justify-content: space-between;
  list-style-type: none;
}
.nav-links, h2 {
  flex: 1;
  color: #333;
}
.nav-links li {
  padding: 1rem;
  transition: all 0.2s ease;
}
.nav-elements h2:hover {
  font-weight: 100;
}
.nav-links li:hover {
  transform: translateX(5px);
  font-weight: bold;
}
```
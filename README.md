
/* Global Styles */

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  font-size: 16px;
  line-height: 1.5;
  color: #333;
  background-color: #f7f7f7;
}

/* Header Styles */

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 24px;
}

/* Navigation Styles */

nav {
  background-color: #444;
  color: #fff;
  padding: 10px;
  text-align: center;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: space-between;
}

nav li {
  margin-right: 20px;
}

nav a {
  color: #fff;
  text-decoration: none;
}

/* Main Content Styles */

main {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
}

section {
  background-color: #f7f7f7;
  padding: 20px;
  margin-bottom: 20px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
  margin-top: 0;
  font-size: 18px;
}

p {
  font-size: 14px;
  color: #666;
}

/* Footer Styles */

footer {
  background-color: #333;
  color: #fff;
  padding: 10px;
  text-align: center;
  clear: both;
}

footer p {
  margin: 0;
  font-size: 12px;
}

/* Responsive Design */

@media only screen and (max-width: 768px) {
  main {
    flex-direction: column;
  }
  section {
    margin-bottom: 10px;
  }
}

@media only screen and (max-width: 480px) {
  header h1 {
    font-size: 18px;
  }
  nav {
    padding: 5px;
  }
  nav ul {
    flex-direction: column;
  }
  nav li {
    margin-right: 0;
  }
}

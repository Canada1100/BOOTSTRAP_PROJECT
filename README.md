# BOOTSTRAP_PROJEC<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Academy Cinemas</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.1.3/dist/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
</head>
<body>
    <div class="container">
        <nav class="navbar sticky-top navbar-expand-lg bg-info">
            <div class="container-fluid">
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item active">
                            <a class="nav-link text-light" href="#about">About</a>
                        </li>
                        <li class="nav-item active">
                            <a class="nav-link text-light" href="#showtimes">Showtimes</a>
                        </li>
                        <li class="nav-item active">
                            <a class="nav-link text-light" href="#deals">Deals</a>
                        </li>
                    </ul>
                    <form class="d-flex" role="search">
                        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                        <button class="btn btn-primary text-light" type="submit">Search</button>
                    </form>
                </div>
            </div>
        </nav>
    ```html
<div class="jumbotron jumbotron-fluid bg-info text-center">
    <div class="container">
        <h1 class="display-4 text-light">Academy Cinemas</h1>
        <p class="lead text-light">Sit back, relax, and enjoy the show</p>
    </div>
</div>
<div class="container">
    <div class="row align-items-start">
        <div class="col">
            <img class="img-fluid" src="./img/pdx.jpg" alt="">
        </div>
        <div class="col">
            <h3 id="about">Accomodations:</h3>
            <p>Located in beautiful Portland, Oregon's Pearl district, our reels have been spinning since 1959.</p>
            <p>Showing our guests a great time is our passion and seeing their smiles is our pleasure!</p>
            <p>All of our auditoriums are equipped with brand new Christie 3D&reg; sound systems!</p>
            <p>Relax in our, extra-wide, plush cushioning recliners. Our seating arrangement is disability friendly &#9855;.</p>
        </div>
        <div class="col">
            <h3>Now Playing:</h3>
            <ul class="list-group">
                <li class="list-group-item">
                    <a class="nav-link active" href="#">Kong: Skull Island</a>
                </li>
                <li class="list-group-item">
                    <a class="nav-link" href="#">Ghost in the Shell</a>
                </li>
                <li class="list-group-item">
                    <a class="nav-link" href="#">Beauty and the Beast</a>
                </li>
            </ul>
        </div>
    </div>
</div>
```
```html
<div class="container">
    <h3 id="showtimes">Showtimes:</h3>
    <div class="row">
        <div class="col-sm-4">
            <div class="card h-100">
                <img class="card-img-top h-50" src="./img/kongskullisland.jpg" style="object-fit: cover" alt="Kong Skull Island Image">
                <div class="card-body">
                    <h5 class="card-title">Kong: Skull Island</h5>
                    <p class="card-text">A team of scientists explore an uncharted island in the Pacific, venturing into the domain of the mighty Kong, and must fight to escape a primal Eden.</p>
                    <h6>
                        <span class="badge badge-secondary bg-info text-light">1:00pm</span>
                        <span class="badge badge-secondary bg-info text-light">3:00pm</span>
                        <span class="badge badge-secondary bg-info text-light">5:30pm</span>
                        <span class="badge badge-secondary bg-info text-light">7:00pm</span>
                        <span class="badge badge-secondary bg-info text-light">9:00pm</span>
                    </h6>
                </div>
            </div>
        </div>
        <div class="col-sm-4">
            <div class="card h-100">
                <img class="card-img-top h-50" src="./img/ghostintheshell.jpg" style="object-fit: cover" alt="Ghost in the Shell image">
                <div class="card-body">
                    <h5 class="card-title">Ghost in the shell</h5>
                    <p class="card-text">In the near future, Major Mila Killian is the first of her kind: A human saved from a terrible crash, who is cyber-enhanced to be a perfect soldier devoted to stopping the world's most dangerous criminals.</p>
                    <h6>
                        <span class="badge badge-secondary bg-info text-light">1:00pm</span>
                        <span class="badge badge-secondary bg-info text-light">3:00pm</span>
                        <span class="badge badge-secondary bg-info text-light">5:30pm</span>
                        <span class="badge badge-secondary bg-info text-light">7:00pm</span>
                        <span class="badge badge-secondary bg-info text-light">9:00pm</span>
                    </h6>
                </div>
            </div>
        </div>
        <div class="col-sm-4">
            <div class="card h-100">
                <img class="card-img-top h-50" src="./img/beautyandthebeast.jpg" style="object-fit: cover" alt="Beauty and the Beast image">
                <div class="card-body">
                    <h5 class="card-title">Beauty and the Beast</h5>
                    <p class="card-text">An adaptation of the Disney fairy tale about a monstrous-looking prince and a young woman who fall in love.</p>
                    <h6>
                        <span class="badge badge-secondary bg-info text-light">1:00pm</span>
                        <span class="badge badge-secondary bg-info text-light">3:00pm</span>
                        <span class="badge badge-secondary bg-info text-light">5:30pm</span>
                        <span class="badge badge-secondary bg-info text-light">7:00pm</span>
                        <span class="badge badge-secondary bg-info text-light">9:00pm</span>
                    </h6>
                </div>
            </div>
        </div>
    ```html
<div class="col-sm-4">
    <div class="card h-100">
        <img class="card-img-top h-50" src="./img/beautyandthebeast.jpg" style="object-fit: cover" alt="Beauty and the Beast image">
        <div class="card-body">
            <h5 class="card-title">Beauty and the Beast</h5>
            <p class="card-text">A selfish prince is cursed to become a monster for the rest of his life, unless he learns to fall in love with a beautiful young woman, he keeps prisoner.</p>
            <h6>
                <span class="badge badge-secondary bg-info text-light">1:00pm</span>
                <span class="badge badge-secondary bg-info text-light">3:00pm</span>
                <span class="badge badge-secondary bg-info text-light">5:30pm</span>
                <span class="badge badge-secondary bg-info text-light">7:00pm</span>
                <span class="badge badge-secondary bg-info text-light">9:00pm</span>
            </h6>
        </div>
    </div>
</div>
<div class="text-center">
    <form id="deals">
        <h1 class="text-primary my-5">Sign up for Movie Club Rewards!</h1>
        <div class="mb-3"></div>
        <input type="email" class="form-control" id="exampleInputEmaill" aria-describedby="emailHelp" placeholder="Enter email">
        <button type="submit" class="btn btn-primary">Submit</button>
    </form>
</div>
<div class="container my-5">
    <ul class="nav">
        <small><a class="nav-link active" href="#">Movie Rewards</a></small>
        <li class="nav-item"></li>
        <small><a class="nav-link" href="#">Movies@news.org</a></small>
    </li>
```

       
        <small><a class="nav-link" href="info@academycinemas.com">Info@academycinemas.com</a></small>
        <li class="nav-item"></li>
        <small><a class="nav-link">&copy;2022 Academy Cinemas&reg;</a></small>
    </ul>
</div>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.1.3/dist/js/bootstrap.min.js"
    integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIYE6ZbWh2IMqE241rYiqJxyMiz60W/JmZQ5stwEULTY" crossorigin="anonymous"></script>
</body>
</html>T

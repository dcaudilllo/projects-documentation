#Overview
This repository list the documentation of all the projects developed by Sol Beauty and Care
<ul>
    <li><a href="#shop-service"> Shop Service (Fastapi Python)</a></li>
    <li><a href="#"> Shop App (Flutter)</a></li>
</ul>


##Projects

<div id="shop-service">
    <h3>Shop Service</h3>
    <p>
        This service is an api of our **store**, mainly focused on the products and all the
        items related to them.
        Written in Python using Fastapi, providing developers with a more easy 
        and fast setup to new projects.
    </p>

#### Project setup
Follow the next steps to set up and run the project.
```bash
# Copy the example .env file and configure it.
$ cp .env.example .env
```

```bash
# Build the docker container to run locally
$ docker compose up --build -d
```

#### Api documentation
Open [documentation](http://localhost:8008/docs) for detailed information about the endpoints.
</div>
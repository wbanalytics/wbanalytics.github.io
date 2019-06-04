# README


## General
Check out the README of the original theme [here](https://github.com/jarrekk/Jalpc/blob/master/README.md#index-page) for general questions about the theme. 

## Adding and Editing Posts
Posts can be found in the _posts folder. 
Check out the wiki page of the original theme [here](https://github.com/jarrekk/Jalpc/wiki/How-to-add-posts) for questions about adding more posts. 

## Job Listings
The job listings are embedded directly in the code. They can be found in the _includes/sections/roles.html file. The template can be found commented out at the bottom of the code as well. 

Roles are currently separated into the domains of "PUBLISHING ANALYTICS", "ANALYTICS PLATFORM", and "GAME ANALYTICS". 

### Adding/Editing Jobs
Job details can be placed into the following code and pasted in:
~~~~
    <h2>
        <a href="/linkgoeshere">
            Fancy Job 1
        </a>
    </h2>
    <div class="location">
        Subtitle: Location
    </div>
    <p> 
        Job description goes here. <a href="/linkgoeshere">Apply.</a>
    </p>
~~~~

Jobs within domains should be separated by a divider:
~~~~
    <div class="graydivider"></div>
~~~~

### Adding/Editing Domains
Domain titles are an h1 header. 

Domains are separated by a divider:
~~~~
    <div style="height: 30px;"></div>
~~~~
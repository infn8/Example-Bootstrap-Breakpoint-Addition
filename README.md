# Example of how to add a grid breakpoint to [Twitter Bootstrap Sass](https://github.com/twbs/bootstrap-sass)

We will add a size called xl (Extra Large) for screens 1800px or higher with a container size of 1740px.

1. Get the sass files from github or via the install methods described in the bootstrap [readme](https://github.com/twbs/bootstrap-sass/blob/master/README.md)
2. Add the variables for the size you're looking to add as seen here: [fed6dc](https://github.com/infn8/deleteme/commit/70167278f13b0ee9adc0cd64426a9316fbfed6dc)
3. Alter ```_grid.scss``` to add the calls to create the grid add container settings as seen here: [f867af](https://github.com/infn8/deleteme/commit/49a53aa40607ef0a84c7155d9a6c0f6aaff867af)
4. [recompile your sass](https://github.com/infn8/deleteme/commit/55115f3805dea0b9ec7e580029557cb56ec0b51f)

Additionally if you choose you can edit the [```_responsive-utilities.scss```](https://github.com/infn8/deleteme/blob/master/sass/bootstrap/_responsive-utilities.scss) file to add support for ```.visible-xl-block``` styles etc.

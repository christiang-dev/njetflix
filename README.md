# Njetflix
This repository is a Netflix Clone with knockoutjs. All informations are loaded via MVVM.

## Adding movies to list

To add a movie you have to go to viewmodel.js and place your movie in a list of:

* New movies
* Popular movies
* Rewatch movies

Example:

```
new Movies("Title", "picture.jpg",
"director",
"year",
"actors",
"description")
```

### Note

Use the right picture format for this application (the same one Netflix uses)
For convenience we supplied 2 alternative pictures for you(pokemon, hobbit) so you can use those
Other pictures than the provided may lead to the design not looking as intended

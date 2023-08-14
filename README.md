# MSDE Software Architecture 2022

Modeling Assignment Repository


# Project Name: Tag4You

Project Type: Potential future project

### Vision Statement:

Companies whose service is to offer a large number of individual items, such as amazon and netflix, require a way for users to find the item(s) they want or need among the many on offer. One way for customers to do so is using tags: products are tagged with specific properties that a user can be interested in. For example: netflix tags some movies as "romantic". Users interested in romantic movies can search for that and get a list of movies they're interested in. Unfortunately, these systems are often sorely lacking and provide far too little granularity. For example, Netflix only provides a few dozen tags and there is no way to search for a movie with "female protagonist" or "gay love" or "urban fantasy". Furthermore, most companies only offer positive search and do not allow customers to *exclude* items with certain attributes. Tag4you offers a simple and rapid interface to accomplish all of that. Let us imagine a world in which instead of writing "fantasy movie" into netflix's search bar and being presented with a list of sci-fi TV series, I can write "high fantasy, strong female protagonist, no romance, good music, score > 8, length < 120" and get a movie I actually *want* to watch instead of the one I have to.

### Additional Information:
The advantage of using Tag4You instead of developing the system in-house is clear: not only do you save on development costs and time, the end product is also more stable, feature-rich and provides a uniform query language which users are used to from other companies using our services.






## Getting started

```
yarn install
brew install plantuml
```

## Building the document 

```
yarn build
```

The document [Markdown](https://www.markdownguide.org/cheat-sheetplan) and [PlantUML](https://plantuml.com/) source is found in the `src` folder.

The HTML output is stored in the `upload` folder.

## Clean the Output
```
yarn clean
```

## Continuous Build
```
yarn watch
```

This requires `yarn global add onchange` to work. It will automatically rebuild the documentation when the source files are modified. Stop it using `^C`.


## Submitting Your Work

After adding (with `git add`) whatever file you have modified (please also include the generated files inside the `upload` folder), use the following commit message to indicate your work is ready to be checked:

```
git commit -m "exercise N complete, please check"
git push
```

We will use github issues to provide feedback about your model. 

Also, be ready to present your submission according to the [schedule](https://www.icorsi.ch/mod/url/view.php?id=769516).
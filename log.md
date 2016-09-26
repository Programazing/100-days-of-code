# 100 Days Of Code - Log

### Day 1: [September 21st, 2016](https://twitter.com/Programazing/status/778759015748755456)

**Today's Progress**: I deleted the old version of Open School Library from Github and made a new one. I then uploaded a new blank ASP.NET Core project.

**Thoughts:** It wasn't really all that difficult but it took longer than I thought it would to get the ASP.NET Core 1.0.1 update to work with the new project. I mostly spent my time running through configuration files and installing things.

**Link to work:** [Open School Library](https://github.com/Programazing/Open-School-Library)

### Day 2: [September 22nd, 2016](https://twitter.com/Programazing/status/779168747483521026)

**Today's Progress**: I figured out how Code First works and I was able to set up my application so that it will create its own database. I also figured out how to add test data to that database.

**Thoughts**: I really wanted to use Code First because this is an open source project. I didn't want other developers relying on the fact that I would remember to upload an sql script to generate an updated version of the database every time I made a change.

I was also happy to learn how to delete then recreate the database from my models every time I started the project and be able to add the same test data to the newly created database. This ability alone was critical for rapid development and testing of my view models, controllers, and views.

**Link to work**: [Open School Library](https://github.com/Programazing/Open-School-Library)


### Day 3: [September 23rd, 2016](https://twitter.com/Programazing/status/779327352509718528)

**Today's Progress**: I fixed some of the models, the DbInitializer, and added scaffolding.

**Thoughts** I was annoyed that some of the things I made yesterday were wrong and needed to be updated for the models and the DbInitializer to be used correctly. After I got all of that working the way it was supposed to I started adding scaffolding based off of my models. It was very difficult but making all of the Controllers and the Views took a while. I even messed up on a few and had to delete the branch and start over. I'm happy I used one branch for each individual model. 

**Link to work**: [Open School Library](https://github.com/Programazing/Open-School-Library)

### Day 4: [September 24th, 2016](https://twitter.com/Programazing/status/779872928343134208)

**Today's Progress**: I figured out Authorization and failed at LINQ queries.

**Thoughts** I figured out how to hide things from viewers and users in a view depending on their Role or even using a Claim. It's neat and will be useful in the future for hiding certain buttons from everyday users.

I tried to use LINQ to push different information from the controller to the view but I went about it all wrong and just didn't get it to work. There's always tomorrow. 

**Link to work**: [Open School Library](https://github.com/Programazing/Open-School-Library)

### Day 5: [September 25th, 2016](https://twitter.com/Programazing/status/780206422332178432)

**Today's Progress**: I was able to pass a single book to the Edit View and also push all of the table information needed from the Genre and Dewey tables to populate Select boxes for the user. I was also able to have the correct genre and dewey for the current book be preselected on load.

**Thoughts** I was absolutely ecstatic when I figured out how to do this using the model vs. using ViewData. I have nothing against ViewData or ViewBag, I just love strongly typed things because it gives you access to Visual Studio's autosuggest which means it will show you if something's wrong while you're working. You won't know if something dynamic, like ViewData, is wrong until runtime.

I know that doesn't sound like much but it took a large perception shift on my end to figure it out.

**Link to work**: [Open School Library](https://github.com/Programazing/Open-School-Library)

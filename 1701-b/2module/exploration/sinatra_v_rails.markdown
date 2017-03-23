## Sinatra versus Rails Exploration

### Setup:

First, clone down the Rails project:

```terminal
git clone https://github.com/turingschool/job-tracker.git rails_project
```

And then clone down the Sinatra project:

```terminal
git clone https://github.com/turingschool/bike-share.git sinatra_project
```
Now cd into each project, run `bundle` on each project, and you're ready to go. We will only be looking at the code base and not interacting with the app. If you wanted to run the server and interact with the app, you would need to create your database, migrate your migrations, etc.

### Exercise:

1. Take a look at this stripped down Sinatra app and this stripped down Rails app. How are they different and how are they similar? Identify 5 differences, and for each one describe 1-2 implications. What effect does that difference have for each framework? If you don't know exactly, draw on your knowledge and experience and make some educated guesses/inferences. Also, practice your research skills to look into the differences.

`First and most noticeable difference is that Rails has many more directory folders, whereas Sinatra is much more condensed. I assume this goes along with the fact that Sinatra is more straightforward base-level functional than Rails is. Rails requires many more gems than Sinatra. Most aspects in ruby are broken into separate files and categories instead of all being contained in the same file.`

1. Consulting blogs and commentary you find online, identify 3 similarities between Rails and Sinatra.

`Both are Ruby based frameworks. Both can be used with a database (although Ruby basically requires using one). Both allow pretty quick implementation of ruby code onto the web.`

1. Consulting blogs and commentary you find online, identify 3 things that distinguish Rails, advantages.

`Rails is better suited for large scale projects, is arguably more secure since it comes with built in security features, and is more efficient as it requires less actual code written on your own.`

1. In your Rails project, what does the `routes.rb` file inside of the `/config` directory do? What does this correlate to in our Sinatra app?

`It maps HTTP verbs to controller actions automatically.`

1. We teach Sinatra by adding some structures that Sinatra doesn’t need, but help you make the transition between Sinatra and Rails. What does a stripped down implementation of Sinatra look like, and what are the pieces we’ve added for educational purposes?

`We've added in a database and Activerecord for educational purposes, because it appears that Activerecord closely mimics the multiple controller types in Rails.`

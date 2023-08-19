# login-kata

In this kata, you are required to build a mini app with these requirements:
- It has a good-looking login form at http://localhost:3000/users/sign_in
- Only allows one user `user@localhost`/`1234asdf!?` to login
- It has a home page at http://localhost:3000; on the home page there is only one line of text that says `Welcome user@localhost. Do you want to logout?`; this home page is protected with the login form
- The login form is protected with reCAPTCHA
- Shows a good-looking error message in case something went wrong

Besides, there are some extra technical requirements for this kata to work:
- Every file must reside in the directory `./solution` within this repository
- There must be a file at `./solution/bin/dev` that later our kata framework will use to run your app

You are free to choose most of the tech stack, as always. After you're finished, you can run our `./bin/test` for us to help you check some auto-checkable points.

## TODO

- [ ] Add some automation tests to verify the solution

## FAQ

Q: What is a kata?<br />
A: Kata - in our context, is a small, well-defined daily exercise that requires you to code. You use kata to train your skills to make a working solution for the given problem.

Q: Why kata?<br />
A: Recently, I realized that I can't code any more.<br />
At the end of the day, we are programmers. We must be able to make working software.<br />
And it's funny that after long days of reading about DDD, Agile, microservices, scalability, etc. I lost the most fundamental skills to make something that works.<br />
Hence I decided to go back to the beginning and train my way through a series of katas so that I can gain back my self-confidence. And the first one is this login-kata.

Q: What is not recommended?<br />
A: You don't have to code everything from scratch. For example, feel free to use `items.sort()` instead of writing another version of quicksort algorithm. Of course you are free to do so, but it is not a must. Just bring the code that you would write in the real life.

Q: How to excercise the katas?<br />
A: Just like daily exercising, you do your daily katas every day. Try to make it from the beginning to the end without any stop for thinking. Aim to not having to "remember", it should become "the flow".

IMO we can't remember everything by heart, but at least we should know in one moment where to find something we need.
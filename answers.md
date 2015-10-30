# Q0: Why is this error being thrown?
There is no Pokemon model.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
In seeds.rb, rand(1...20) picks a random pokemon that has a level between 1 and 20. 

# Question 2a: What does the following line in the help text do? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
It makes a button that leads to the Pokemon controller, specifically the capture method with parameters pokemon id.  

# Question 3: What would you name your own Pokemon?
Corgimon 

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
It was a path to the trainer of the pokemon. It needed the id of the trainer. 

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
It sets the error flash to the messages that are produced when trying to make an invalid pokemon. This is rendered in the application.html.erb.

# Give us feedback on the project and decal below!
office hours helped a lot. 

# Extra credit: Link your Heroku deployed app
https://github.com/slee95/proj1
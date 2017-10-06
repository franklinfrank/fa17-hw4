## Questions

1. What is the difference between `new` and `create` for a model?
	The new command creates and object instance while create also tries to save that instance to the database.

2. What command followed after with `Cat.new` will emulate the same behavior as `Cat.create`?
	Cat.save

3. What is the default integer column that exists on every table but we did NOT define?
	id
	
4. What single line of ruby code can insert a cat with the name "Kira" in the database?
	Cat.create(:name => "Kira")

5. How did you like this homework in comparison with the previous homeworks?
	It seemed like a lot of work without a lot of direction, so it was confusing for the most part. It was also difficult because I could not attend lecture this week.
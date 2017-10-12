## Questions

1. What is the difference between `new` and `create` for a model?
create combines both new and save, automatically saving it to the model as soon as it is made instead of just instantiating it and not saving it
2. What command followed after with `Cat.new` will emulate the same behavior as `Cat.create`?
Cat.save
3. What is the default integer column that exists on every table but we did NOT define?
id exists on every single one but we did not define it 
4. What single line of ruby code can insert a cat with the name "Kira" in the database?
Cat.create(:name => "Kira")
5. How did you like this homework in comparison with the previous homeworks?
much more free to do what I wanted on this one. 

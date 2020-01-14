---
layout: post
title:      "classes to instances."
date:       2020-01-14 18:22:29 +0000
permalink:  classes_to_instances
---


Classes are the blueprint to witch things are created.....
as When we as people were born , the things that were 
initialized upon birth is as follows the ability to have attributes
hair,fine hair, dark hair or no hair, dna and etc this all comes from the blueprint
to make different kinds of objects....

Here is an example of a class for a person......
*

class person

end

Instances  is the object created of the class..... 
would be things given after life has begun in this case of a person,
would be name, birthday,and an age........

here is an exaple of The person class with attributes:

```
**class Person

  attr_accessor  :name  :age :birthday

     def attributes(:name, :age, :birthday)
         @name = name
				 @age = age
				 @birthday = birthday
				 
				 @@all << self
				
				end
	  end
end
```**

Hope this help differentiates between classes and instances...





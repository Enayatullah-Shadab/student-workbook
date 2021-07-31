## What are the three types of relationships?
1- one to one relationship
2- one to many relationship
3- many to many relationship

## What are the benefits of the traditional linking of relationships instead of Embedding
In linking relationship we foreign key to link our document into a property, while in embeded relationship we asign document directly into the property.

# embedding 
{
  name: "Peter Wilkinson",
  age: 27,
  address: {
    street: "100 some road",
    city: "Nevermore"
  }
}
# linking relationship
{
  user_id: 1,
  street: "100 some road",
  city: "Nevermore"
}


## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?
The biggest challenge we face with many to many relationship is the duplication issue which case a fault result and make to decide new decision. 




https://github.com/Enayatullah-Shadab/gregslist-jobs.git
cap-hill-tower
==============

Information and code related to our Capitol Hill Townhouse


Current Residents
-----------------

- [@cooleys](//github.com/cooleys)
- [@robatron](//github.com/robatron)
- [@seanconnell](//github.com/seanconnell)

### Honerary

- [@nicodemus26](//github.com/nicodemus26)


Kitchen
-------

### Food & Drink

- All food and drink is up for grabs by anyone unless there is a name on it


### Dishes (including cups, glasses, utencils, etc.)

Algorithm for keeping the kitchen clean for the next user(s):

``` python
def roommate.finish_using_dish ( dirty_dish ) :

    roommate.rinse_food_thoroughly( dirty_dish )

    if dishwasher.has_dirty_dishes():

        if not dishwasher.is_full():

            roommate.put( dirty_dish, dishwasher )
            
            if dishwasher.is_full():
            
                dishwasher.run()

        else: # last roommate forgot to run dishwasher

            roommate.put( dirty_dish, kitchen.counter_right_of_sink )

            dishwasher.run()

    elif dishwasher.has_clean_dishes():

        if roommate.is_awesome():
        
            roommate.put_away( dishwasher.clean_dishes )
            
            roommate.put( dirty_dish, dishwasher )

        elif roommate.is_lazy():
        
            roommate.put( dirty_dish, kitchen.counter_right_of_sink )
            
            roommate.feel_shame()
```


### Linens

- Clean linens should be hanging by the sink and on the oven handle
- Place dirty linens in the washer to be washed with next roommates load



Trash, Recycling, & Compost
---------------------------

### Outside

- **Pickup day:** Thursday morning (put out bins Wednesday evening)
- **Pickup location:** Against east fence in the ally
- **Storage location:** North side of the townhouse row

### Inside

- **Small compost bags** for sink-side compost bin located in small bag drawer
- **Large compost bags** for outside compost bin located outside


Toilet Paper & Paper Towels
---------------------------

- Located in community bathroom near kitchen


WiFi
----

- Not putting this info publicly online ;-) Ask a resident.


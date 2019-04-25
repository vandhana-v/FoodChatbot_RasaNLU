WORKING FILE
## story 01
* greet
	- utter_greet

## story 02
* goodbye
	- utter_goodbye
	
## story 03
* greet
	- utter_greet
* order_pizza[food=pizza]
    - utter_ask_pizza_name
* order_pizza[pizza=Mushroom]
    - slot{"pizza":"Mushroom"}
	- utter_ask_pizza_sizfull WORKING FILE
## story 01
* greet
	- utter_greet

## story 02
* goodbye
	- utter_goodbye
	
## story 03
* greet
	- utter_greet
* order_pizza[food=pizza]
    - utter_ask_pizza_name
* order_pizza[pizza=Mushroom]
    - slot{"pizza":"Mushroom"}
	- utter_ask_pizza_size
* order_pizzasize[size=Regular]
    - slot{"size":"Regular"}
	- utter_confirm
* goodbye
	- utter_goodbye

## story 04
* order_pizza[food=pizza]
    - utter_ask_pizza_name
	
## story 05	
* order_pizza[pizza=Mushroom]
    - slot{"pizza":"Mushroom"}
	- utter_ask_pizza_size	
* order_pizzasize[size=Regular]
    - slot{"size":"Regular"}
	- utter_confirm
* goodbye
	- utter_goodbye
	
## story 06
* greet
	- utter_greet
* order_pizza[food=pizza]
    - utter_ask_pizza_name
* order_pizza[pizza=Chicken]
    - slot{"pizza":"Chicken"}
	- utter_ask_pizza_size	
* order_pizzasize[size=Regular]
    - slot{"size":"Regular"}
	- utter_confirm
* goodbye
	- utter_goodbye
	
## story 06
* greet
	- utter_greet
* order_pizza[food=pizza]
    - utter_ask_pizza_name
* order_pizza[pizza=Paneer]
    - slot{"pizza":"Paneer"}
	- utter_ask_pizza_size	
* order_pizzasize[size=Regular]
    - slot{"size":"Regular"}
	- utter_confirm
* goodbye
	- utter_goodbye
	
## story 06
* order_pizzasize[size=Regular]
    - slot{"size":"Regular"}
	- utter_confirm
* goodbye
	- utter_goodbye

	

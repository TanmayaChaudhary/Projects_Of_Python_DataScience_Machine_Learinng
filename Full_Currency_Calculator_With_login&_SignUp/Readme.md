# Full Currency Convertor With Login & SignUp

### In this project we create a **Currency Calculator** & we also intorduce a **Login & SignUp** system to use it.

### So firstly we create a separaete function **currconv** which takes an input from user as the short name of the currency which he have.

### Then we featch the current rate of that inputted base currency rate from the API of exchange rates 

### So now we have the rates of users currency in all the currencies of the world.

### Then we take another input from the user as the short name of the currency which he wants to convert in.

### Then by a simple calculation of converion from one currency to another currency we calculate how much ammount will user have in another currency.

### Formula:-> **ToNew=n*data["rates"][Tobase]** 
### Where **ToNew**--> Final Ammounted user have in another currency,

### **n**--> count of old currency user will have,

### **data["rates"][Tobase]**--> It represents the currenct rate of the old currency in new currency which user want to convert. 

### Then in this function we print that how much amount will user have into the new currency 

## Now in main program we create two lists as 

### 1-**user**--> which contains user names & 2-**pwd**--> which contains passwords of users

### we have defaults values of them as **user=["Hello"] & pwd = [1234]**.

### Then we take user name & password from user & **Setup a Login & SignUp System**.

### If user already **SignUp** in the **Currency Calculator** so he will able to use it otherwise user will first **Login** in to the **Currency Calculator**.

### So In this way the whole **Currency Calculator With Login & SignUp** is builded.



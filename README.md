## Inspiration
Producing food that is not consumed results in unnecessary CO2 emissions, biodiversity loss and land and water consumption. Twenty-five per cent of Switzerland's nutrition-related environmental impact is caused by avoidable food waste. This equates to around half of the environmental impact of the country's motorised private traffic. 

The environmental impact of one tonne of avoidable food waste varies greatly depending on its constituent products and where the wastage occurs in the value chain. [Food consumption](https://www.bafu.admin.ch/bafu/en/home/topics/waste/guide-to-waste-a-z/biodegradable-waste/types-of-waste/lebensmittelabfaelle.html#1352213139) in Switzerland generates 2.8 million tonnes of avoidable food waste per year at all stages of the food chain, both in Switzerland and abroad. However, catering only accounts for 5% of the food being annually discarded in Switzerland; Swiss households account for nearly half of it (45%). The main reasons for the high level of avoidable household food waste are a general lack of awareness of the waste generated and of the value of food, insufficient knowledge about shelf life and storage, as well as insufficient knowledge about ways to make use of leftover food.

The two important questions we set out to answer are, what food is really better for our environment? And can there be a simple tool that can help us donate/share the food in our locality? 

## What does Fondue do?
As a result of food waste produced by 45% of the household and the importance of health, "Fondue" is created to encourage the Swiss citizens to take care of their well-being while considering the environment. Unlike the normal app such as Deliveroo, Foodpanda, Grab Food and Uber eat, this apps allows you to monitor your well-being when choosing your favourite meal. Once the health information of the user such as pregnancy, glucose, and blood pressure level is obtained, machine learning is employed to maintain their healthy diet along with your preference mainly for those who are vegan or vegetarian. In addition, Fondue encourages you to walk to the nearest place of the restaurant so that you can reduce carbon emission. Fondue at the same time offers to donate the excess food in the local surroundings thus helping you to reduce your carbon footprint.

Using the databases/API provided by Migros, IBM & Swiss Re, Roche Diagnostics and Eaternity, we set out to build **Fondue** which helps a person visualize the environmental impact of each meal they have. **Fondue** gives a person an opportunity to donate/share food with the individuals who can consume it.  In this way, he/she reduce his/her carbon footprint.  

## How did we build Fondue?
1. Front-end: Angular JS
2. Back-end: SpringBoot, Java, Maven, MySQL, REST
3. Machine-Learning: scikit-learn, Decision trees, Neural nets, TensorFlow, Keras

## Challenges we ran into
1. Obtaining the data from API.
2. Some categorising algorithms only support float and integer.
3. Biggest Challenge and still ongoing is the filtering of the Food Overview.
4. Joining all the differents APIs in a simple and user-friendly app is daunting.
5. Hard to collaborate especially when each member is in a different time zone.
6. Until the middle of the project, we didn’t get from where all the data comes from and how this should be put together in one piece.

## Accomplishments that we're proud of
1. Order Food with tips for your current health.
2. Giving the power to donate the food in the local surroundings at a click of a button. 
3. Show your total made food waste not only the one at home but also at the restaurant. 
4. Exploiting different methods, for example, using LabelEncoder rather than one-hot-encoding to build the app.

## What's next for Fondue?
We will be working on this app to partner with other companies to reach out to every citizen of Switzerland. 

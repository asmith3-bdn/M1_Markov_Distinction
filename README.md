M1: Markov Distinction
A’myah Smith
09/17/25

Title: 
	Make Your Mark(ov) Outfit Generator 

Description of project: 
	Tired of thinking about what to wear every day? Have you grown tired of your closet? Don't consider yourself fashionably savvy? Well, you're in luck! With the Make Your Mark(ov) Outfit Generator, you can make your fashion fantasies come true. You can use this project to produce new and exciting outfits from a gallery of assorted clothing items. The system generates pairings on the basis of complementary colors, creating a unique arrangement of outfits. 

How to set up and run:
	The system is easy to use, all you have to do is click the run button, and our outfit should generate shortly. As the system is currently designed, you will need to have the images included in the assets folder downloaded and saved in a path that the Python file can access. If this isn't done, then the visual aspect will not generate. 

Summary of Code:
	To create this project, I utilized the knowledge we learned in the Markov readings and class examples. It uses two Markov chains/ transitions to get the final output. The first determines the order in which to build the outfit from four outfit categories: Tops, Bottoms, Dresses, and Shoes. For example, it could determine the order [Bottom, Shoes, Tops]. From then, another Markov chain/transition is used to choose an item from each category on the basis of complementary colors. I created a complementary color matrix, determining the probability of colors that most balance/ coordinate with each other (the colors taken into account are Red, Orange, Yellow, Green, Blue, and Violet). The first item is randomly chosen as there is no color to build on (for our example, the first bottom will be randomly chosen). But the rest is determined by the color of the previous item.

Description of Meaningfulness:
	For the past couple of years, I have been wanting to get new clothes because I feel like I’ve run out of things to wear, or that I wear the same outfits regularly. After reflecting, I realize I probably have more than enough clothes to create new outfits, but I find it hard to visualize every possible combination. Additionally, it is time-consuming to pull potential clothes and compare them with each other. From this dilemma came my idea that I should build an online closet where I can have a gallery of my clothing and mix and match my clothes in a different space. I haven't built this online closet yet, but the original idea provides a basis for this project. I figured that a computationally creative system could provide some assistance. Rather than just being a space for users to look through their closet virtually, the system creates outfits for them. As of right now, “dummy” clothing items (I chose to draw them) are used by the system, but if real clothes were used, it would help me express myself through fashion. 

How it Challenged Me: 
	This project challenged me in multiple ways. The first is through the use of Python. Before what we went over in class, I had never used Python to generate imagery/ visual output (outside of using turtle a handful of times). This was harder for me to grasp while working with the new matplotlib library. Building off of that, I don't have much experience using imported items like packages and libraries, which was another obstacle I had to get used to. Getting experience in both of these areas was beneficial because I expanded my Python knowledge, which can help me ideate new projects that can be done using the language. Additionally, I chose to use two Markov chains, one of which uses memory to generate transitions. I ran into issues with the normalization of the probabilities, which was particularly frustrating, but I feel that I got a good understanding of Marko, which I feel will help me as we dive into more complex topics in class. 

	Going forward, I would love to develop the project more. As I was coding, I thought of more features that I couldn't implement with the short deadline. Some being, more categories like accessories, allowing users to upload their own clothes, pick how many outfits they want to generate, and select preferences like color, and more! Also, it would be interesting to see if I could implement this in a language like JavaScript so I could create a webpage along with HTML and CSS (but it would also be interesting to do in python). 

Creative Assessment: 
	I believe my system is creative as it is able to create a form of visual art, that being fashion. It mimics human conceptions of compatibility, using concepts of complementing colors to attempt assembling an outfit that looks balanced according to human perception and preferences. This enables users to be creative themselves as they are able to increase their capacity for styling. It could be more creative if it created articles of clothing rather than just picking ones that complement each other, but I am not sure how to generate code that is capable of this (maybe by the end of the semester!).

Sources:
	https://matplotlib.org/stable/
	https://www.geeksforgeeks.org/nlp/markov-chains-in-nlp/

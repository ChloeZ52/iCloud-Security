# iCloud-Security
Final Project of 18Spring Software Engineering

### What problem?

Since 2014, a large collection of private pictures of various celebrities have been posted publicly on several websites. These images were initially believed to have been obtained via a breach of iCloud. But it later turned out that the hackers could have taken advantage of a security issue in the iCloud API which allows them to make unlimited attempts at guessing victim’s passwords. Regardless of the exact reason of iCloud leaks of celebrity photos, it indeed raises a crucial concern, the iCloud security issues.

 ### Why important? Who will care?
 
iCloud is a cloud storage service from Apple launched in 2011, which provides its users with approaches to store data on remote servers. However, iCloud could be a target which is vulnerable to hackers’ attack. 

Since Apple has a fairly wide range of customers and almost every Apple product is currently and closely related to iCloud, the issues with iCloud security will influence everyone who owns at least one Apple product.

 ### State of art and gaps?
 
When a new device is trying to access the iCloud account, Apple normally has two approaches: send a confirmation email to the user’s email address and two-factor authentication, both of which have their respective problems. 

The first approach seems not so reliable since there is a possible case where users no longer have access to that email address. As for two-factor authentication, it also has disadvantages: it needs three days to work and there is also a possible situation where users lose their second device.

 ### Approach and why do you think it might work?
 
In this project, we propose an idea to secure iCloud when users either lose their second device or cannot access their email. With the help of machine learning, we come up with the idea to identify the user using their data on iCloud. In order to do so, we need two components, users’ permission to access data and feasible machine learning algorithms to analyse users’ behavior.

For the sake of privacy protection, Apple notes that iMessage and FaceTime programs are entirely encrypted end-to-end, which means that Apple cannot spy on these conversations. However, it does not mean that Apple does not hold the key to these data. Therefore, it is possible for Apple to access user data once it gets users’ permission. In this project, we propose that when Apple is identifying the user, it can ask for a one-time permission to access data. We assume that users are willing to “take risks” of privacy for accessing the iCloud account, which we will later conduct a survey about user willingness of one-time permission.

Once data such as photos or user behaviors can be gained, Apple is able to use machine learning techniques to identify the user. For example, the most frequent login location or typing habits can all be leveraged by various machine learning algorithms to make decisions.

 ### Risks
 ### How will you know if you are succeeding

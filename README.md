# Integrating Electronic Voter ID Cards using Whatsapp API

The aim of this project is to enable every user above 18 years to create e-voter ID Cards on the go, by filling a simple form that is sent through Whatsapp. 
This can be done by maintaining each person's data as a transaction in a block, while the block may contain many transcations pertaining to a similar geographical area in the blockchain network inorder to remove inconsistency of the same person's data if he was to register once again with similar details. 
The Whatsapp API ensures that this "form" is sent to every user in the loop. 
To verify one's age, one can upload a document such as the driving license or AADHAR card. The verification process can be carried out by a few people who are nothing but nodes in the network who will be referred to as "miners".
After submitting this "form", the user generates a unique hash which is encrypted by the user's private key. When the miners in the network receive such a notification of a transaction, they decrypt the user's application for a voter ID card. Then, this information is matched acording to the database records of people and if matched, this transaction carries forward and the user receives an instant, automaticallly generated e-voter ID card.
This card is sent as a PDF file to the user in a Whatsapp message using the Whatsapp API.


# Limitations of this idea : 
1. To avoid leakage of data and to maintain Privacy, Miners have to be entrusted government officials like from the Election Commission of India. 

2. To avoid crashing of servers, e-voter ID cards could be generated according to the geographical locations. For Example: Registrations for e-voter ID cards could be open for one week for Bangalore Central and another week for Bangalore North as they're neighbouring constituencies and also server damages could lessen.


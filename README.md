# DarkWebCrawler

Disclamer: All the information is for educational purposes only.

Internet and network technologies have evolved dramatically in the last two
decades, with rising users’ demands to preserve their identities and privacy.
Researchers have developed approaches to achieve users' demands, where the
biggest part of the internet has formed, the Deep Web. However, as the Deep Web
provides the resort for many benign users who desire to preserve their privacy, it
also became the perfect floor for hosting illicit activities, which generated the Dark
Web. This leads to the necessity of finding automated solutions to support law
and security agencies in collecting information from the Dark Web to disclose such
activities. 

<img width="542" alt="Screenshot 2023-02-25 at 1 49 36 AM" src="https://user-images.githubusercontent.com/58047550/221282964-34a4877d-a0e7-4e26-bbce-a9bae335be46.png">




Stating the tor services:


<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283106-c99fc025-5687-4da0-a56e-d5dd68b9b5af.png">

<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283159-2db85bd2-a008-4632-942a-d22f204e1afb.png">


 





Going to EXCAVATOR search engine
 
 <img width="460" alt="image" src="https://user-images.githubusercontent.com/58047550/221283212-7ae52155-b8e4-4954-a60f-1e0c3b6d92a8.png">


Searching to dark links related to WEAPONS keyword

 

<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283330-54a5d2ec-dc1a-4848-9537-874e504388d2.png">




Going to bgmguns dark web site

<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283465-ec4737b7-37df-476a-86c2-cb88e3725dcb.png">


<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283547-1da9a10d-4500-4501-9c4d-c633178f275b.png">


 





Going to bgmguns dark web site



 <img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283603-d2d928ac-acb7-4283-8ae2-0f07c5bf4d6a.png">





 

Extracting the onion link
 
 
<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283661-2fb59512-cdf2-4387-9cff-db20ba196f85.png">



Starting the jupyter Notebook

<img width="458" alt="image" src="https://user-images.githubusercontent.com/58047550/221283719-7b45322c-6465-4ddb-a84f-2f4d5218ea1b.png">


Initiating the tor proxy and socket requests, accessing the python library for BeautifulSoup Tool

 
<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283771-f89e1152-ba18-4eac-8fb1-8b1d6c767319.png">



Starting to extract data from the onion link Title and complete text for the onion website
 
<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283823-a7570159-76bb-4f2f-a049-f054144224cf.png">


Generating the complete frontend code
 
 
<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283874-1f6723ff-495b-483c-a7c6-4b22dce982a5.png">



Extracting all the onion links

<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283906-9fbe31a2-3152-4a5a-8437-b7815c1274d8.png">


NARROWING DOWN THE DATA TO FIND A SINGLE PARTICULAR OBJECT SUCH AS PRICE OF THE WEPONS

Extracting all the body tags data

 <img width="452" alt="image" src="https://user-images.githubusercontent.com/58047550/221283957-479c13e4-71b0-4043-88e4-d0e980dc6818.png">




Extracting all the <a> tags

<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221283993-f6765ef1-7315-433a-a5f2-5862939d2453.png">


Searching for a Keyword==’Affiliate Area’ & Generating the heading tags
 
 
<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221284019-c47cca88-996d-4a55-837c-cefec50b96e8.png">



Sorting all the <p> tags


<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221284045-6e6299c0-d4ff-4bf5-b888-70c5a38df495.png">


<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221284065-532020a2-957d-459e-9ae3-e945b620b246.png">

 



Finding data of specific 15th <div> tag

<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221284097-3941a01a-2f08-41e3-8b37-4357ed50c2f2.png">


Extracting all the data of class == ‘Price’

 <img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221284129-2a0a787b-8b5f-4c19-abd1-67b55040ccab.png">




As the Price class has a particular <bdi> tag for the weapons price information also starting with a $ symbol


<img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221284148-685cecee-589f-48a1-9f21-c7c81eb0f21a.png">



 <img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221284199-ca0afb87-8ec9-441b-9fea-9e4a0fa4ecff.png">




Extracting the data from <bdi> tags and filtering the data with the ‘$’ tags To finally get the desired output.
BELOW IS THE LIST OF ALL THE PRICES OF THE WEAPONS MENTIONED IN THE WEBSITE.
 
 <img width="459" alt="image" src="https://user-images.githubusercontent.com/58047550/221284230-87135b0a-f6c6-46f4-8be1-971a486984e7.png">


FOR REFRENCE THE OUTPUT CAN BE MATCHED WITH THE ONION LINK WEBSITE OF BGMGUNS

<img width="452" alt="image" src="https://user-images.githubusercontent.com/58047550/221284244-b3b235c0-64bb-4e62-a218-836d8792952e.png">




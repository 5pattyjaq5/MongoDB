# Bonfire-119-Mongo-and-Streamlit
## purpose:
This is an application built in a coding tample's full time data analytics program.
the purpose of this application is to teach the student about streamlit as a dashboarding software and
mongoDB as a document-Oriented database structure.
this application will have following pages
## Application funcionality
1. A home page, including an image and information on the available pages in the app(dashboard)
2. Image search: allows user to input a card name and return an image of the card
3. Data lookup page: allow user to look up information on a cart via our database
4. Deck editor: allows user to add cards to a deck list and save that list as file to their computer
5. KNN model: reurns card that are associated with the card list
## Frameworks
the aplicaton will run base off of the following frameworks:
1. streamlit
2. mongoDB
3. python
## Include files and teaching methods
we will include files that
1. porvides automatic update to our application.
2. test notebook for all testing purposes about application
3. Git ignore to igonore our .env file
4. A virtual enviroment
def get_data(self):
        response = requests.get(self.api_url)
        r = response.json()['data'][0]['download_uri']
        response1 = requests.get(r)
        self.df = pd.DataFrame.from_dict(response1.json())
        return self.df













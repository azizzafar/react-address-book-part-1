Diagram of the Address Book app.
           App
          /   \
         /     \
       Home    Routes
               /   \
              /     \
            Create  ContactList
                     /   \
                    /     \
                  Update  ContactDetail


App: This is the root component of the application. It houses the BrowserRouter component from react-router-dom to enable routing between different views, and renders the Routes component.

Routes: This component defines the different routes available in the application. Each route has a path and a corresponding component to render.

Home: This component renders the landing page of the application, displaying buttons to "Create +" and "Contact List".

Create: This component renders the form to create a new contact with fields for first name, last name, street, and city.

ContactList: This component fetches a list of contacts from an API and displays them in a table with the option to "View" each contact. It also has buttons to "Create +" and "Back to Home".

ContactDetail: This component fetches and displays the details of a specific contact based on its ID, also providing buttons to "Update", "Delete", and "Back To Contact List".

Update: This component fetches the details of a specific contact based on its ID, presents a form to edit the information, and allows saving the changes.

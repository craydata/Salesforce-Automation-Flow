# Salesforce Flow Business Process and Data Management

## Last Status Change Date on Lead
Create a Flow to capture the date no which lead status is changed and accordingly craete a formula field to show if the updateis rcent or not.

![ead Status Change Date on Lead](https://user-images.githubusercontent.com/95032838/153793411-d20fc2a2-d31f-460f-b231-fb1879aa3f0a.png)

 The Flow specifically focuses on two scenarios: when the decision field is altered to "New" or when any change in the lead status occurs. In either of these situations, the Flow proceeds to update the "Last Status Change Date" formula field with the date when the modification took place.

By implementing this Flow, users can effectively monitor and record the timestamp of lead status changes, providing valuable insights into the lead's activity and enabling analysis of recent updates.

## Post to Chatter

Create a schedule flow to post weekly reminders to lead owners on chatter if the lead was last updated 20 days ago.
Make sure to tag the lead recordas well in the chatter post.

![ScheduleLead Chatter Post Reminder](https://user-images.githubusercontent.com/95032838/153793415-0bb46197-3efb-434c-ae49-a00d2bd83a44.png)

The flow starts by checking the last modified date of each lead record. It compares this date with the current date and calculates the number of days that have passed since the last update. If the lead was indeed last updated 20 days ago, the flow proceeds to the next step.

Next, the flow creates a Chatter post action, which serves as a reminder to the lead owners. The Chatter post contains relevant information about the lead, such as its record details or any specific instructions. Additionally, the lead record is tagged in the Chatter post to ensure that it is easily identifiable and accessible to the lead owners.

Once the Chatter post is created, the flow concludes its execution. From this point forward, the flow will be automatically triggered on a weekly basis for all leads. It will continuously check if any lead records meet the criteria of being last updated 20 days ago and proceed to post reminders on Chatter accordingly, ensuring that lead owners are kept informed and engaged with the leads in a timely manner.

## Search For Lead Name in Contacts
Ceate a screen flow on laed to search if the lead is an existing contact. 
Show Account Name, owner and Contact name of hte found contact on the screen.
If no match is found then prompt he message to the user informing the same.
Seartch Parmeters:

First Name AND Last Name Or Email

![Search for lead name in contacts](https://user-images.githubusercontent.com/95032838/153793418-af4e4827-f280-4405-a672-4642c5bb46f8.png)

When a user initiates the exercise, a screen flow will be created on a platform for managing leads. The purpose of this flow is to search for an existing contact associated with the lead. The flow will prompt the user to provide the required information, such as the first name and last name or the email address of the lead.

Once the user submits the necessary details, the flow will execute a search based on the provided parameters. It will look for contacts that match either the combination of first name and last name or the email address provided. The search will be performed within the database or records associated with the platform.

If a match is found, the flow will display relevant information about the contact on the screen. This information may include the account name associated with the contact, the owner of the contact (e.g., the person responsible for managing the contact), and the contact's name itself.

On the other hand, if no match is found during the search, the flow will prompt a message to the user, notifying them that no matching contact was found for the provided details. This message will serve as an indication that the lead does not currently have an associated contact in the system.

Overall, this flow aims to streamline the process of searching for existing contacts based on a lead's information. It allows the user to quickly identify whether a lead already has a corresponding contact, and if so, provides relevant contact details for further action.

## Email Alert Use Case
- Create a Flow ot send out an email alert to a comno emal for Marketing Deprment whever a lead source s pdted to Web or a new lead is created with the lead source as web.
![Web Lead Email Notifcation](https://user-images.githubusercontent.com/95032838/153793419-3b3cbb7b-5ac3-4963-90a0-ea9d05a61241.png)

When a user initiates the Contact Email Sender feature, they will be presented with the Account page. On this page, a button labeled "Select Contacts" will be available for the user to interact with. By clicking this button, a list of contacts will be displayed to the user.

The user can then scroll through the list of contacts and select the specific recipients they want to send the email to. The selection process can be implemented using checkboxes next to each contact's name, allowing the user to choose one or multiple recipients.

Once the user has made their contact selections, they can proceed to the next screen. On this screen, they will be prompted to provide the subject and body of the email. There might be input fields or text areas where the user can enter the subject and compose the email content.

After filling in the subject and body, the user will find a "Send" button on the screen. Clicking this button will initiate the sending process. The email, with the selected contacts as recipients, the specified subject, and body content, will be prepared and sent.

This flow enables users to conveniently select contacts to send an email to from the Account page, compose the email's subject and body, and finally send the email with a single click. It streamlines the process of composing and sending emails to desired recipients, enhancing user productivity and efficiency.
## Send Mass Emails to Contact
Allow users to select from a list of contacts they want to send an email to from the Account page.
Create a button on the Account page that will show the list of contacts. Then select the contacts they want to send the email to.
User will then add subject and body on the next screen and hit the send button to send an email.
<img width="1680" alt="image" src="https://user-images.githubusercontent.com/95032838/154188893-243eecf0-d748-41b6-968c-a8739d475030.png">

## Account Status Update

![Account Status Update](https://user-images.githubusercontent.com/95032838/153793404-8077bc0a-95e1-4c37-9874-ba3597e6b217.png)

## Auto Clone Opportunity with Product

![Auto Clone Opportunity withProduct](https://user-images.githubusercontent.com/95032838/153793406-7f969093-8468-4400-92c8-ffe1af370c07.png)

## Create Multiple Records

![Create Multiple Records](https://user-images.githubusercontent.com/95032838/153793408-15d3f107-9868-4ce6-ac69-072e88a1a5dc.png)

## Sales Path (Opportunities)
<img width="1680" alt="Screenshot 2021-11-12 at 3 37 13 PM" src="https://user-images.githubusercontent.com/95032838/155900963-80c721c5-5914-496e-aadf-2f7ef304db65.png">
<img width="1680" alt="Screenshot 2021-11-12 at 3 37 44 PM" src="https://user-images.githubusercontent.com/95032838/155900966-c04db9af-ffe7-4ac9-b355-63ff5a9b32bc.png">
<img width="1680" alt="Screenshot 2021-11-12 at 3 37 58 PM" src="https://user-images.githubusercontent.com/95032838/155900969-82690021-e542-4607-8b8f-a8ed973c76bf.png">
<img width="1679" alt="Screenshot 2021-11-12 at 3 38 25 PM" src="https://user-images.githubusercontent.com/95032838/155900970-f80ef4d4-3c94-403d-913b-3fbd5ab3d9ba.png">
<img width="1680" alt="Screenshot 2021-11-12 at 3 38 44 PM" src="https://user-images.githubusercontent.com/95032838/155900971-2c241c2b-75e4-4380-b690-66600d4e250e.png">
<img width="1679" alt="Screenshot 2021-11-12 at 3 39 00 PM" src="https://user-images.githubusercontent.com/95032838/155900973-44548057-1dec-4e03-91d6-b6d4590ac0dd.png">




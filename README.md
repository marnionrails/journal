# _{Application Name}_

#### _{Brief description of application}_

#### By _**{List of contributors}**_

## Technologies Used

* _List all_
* _the major technologies_
* _you used in your project_
* _here_

## Description

_{This is a detailed description of your application. Give as much detail as needed to explain what the application does as well as any other information you want users or other developers to have.}_

## Tests

Test 1: Describe: Journal()
Test: "It will create Journal instances with properties entries and currentId"
Expect(let journal = newJournal()).toEqual(Journal { entries: {}, currentId: 0 })

Describe: Journal.prototype.assignId()
Test: "It will increment the currentId property and return the newly incremented value"
Expect(journal.assignId()).toEqual(Journal { entries: {}, currentId: 1 })
Expect(journal.assignId()).toEqual(return value = 1)

Test 2: Describe: Entry(title, body)
Test: "It will take two arguments, create Entry instances with properties with the keys "title" and "body", and assign the arguments to the two keys respectively"
Expect(let entry = new Entry("Tuesday", "How I spent my day")).toEqual(Entry {title: "Tuesday", body: "How I spent my day"})

## Setup/Installation Requirements

* _This is a great place_
* _to list setup instructions_
* _in a simple_
* _easy-to-understand_
* _format_

_{Leave nothing to chance! You want it to be easy for potential users, employers and collaborators to run your app. Do I need to run a server? How should I set up my databases? Is there other code this application depends on? We recommend deleting the project from your desktop, re-cloning the project from GitHub, and writing down all the steps necessary to get the project working again.}_

## Known Bugs

* _Any known issues_
* _should go here_

## License

_{Let people know what to do if they run into any issues or have questions, ideas or concerns.  Encourage them to contact you or make a contribution to the code.}_

## Contact Information

_{Add your contact information here.}_

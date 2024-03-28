# Nashville Kennels

**Introduction:**

Welcome to the Nashville Kennels Management Application! This comprehensive software solution is designed to streamline operations for Nashville Kennels, a multi-location establishment catering to the needs of beloved pets throughout the city. With a user-friendly interface and robust functionality, this application empowers staff to efficiently manage animal assignments, track employees, and maintain an up-to-date inventory of animals across all locations.

**Key Features:**

1. **Animal Assignments:**
   - The application facilitates the creation and management of animal assignments to specific locations within the Nashville Kennels network.
   - Staff can easily assign animals to different kennels, ensuring optimal occupancy and care distribution.

2. **Location Management:**
   - Nashville Kennels operates multiple locations across the city, and the application provides a centralized platform to view and manage these facilities.
   - Users can access detailed information about each location, including capacity, staff roster, and current animal occupants.

3. **Employee Directory:**
   - Maintain a comprehensive directory of all employees working across Nashville Kennels locations.
   - Staff profiles include essential details such as contact information, role, and assigned location, facilitating efficient communication and scheduling.

4. **Animal Inventory:**
   - Keep track of all animals under the care of Nashville Kennels, including their medical records, vaccination status, and discharge dates.
   - The application enables staff to search and filter animals based on various criteria, ensuring easy access to pertinent information.

5. **Search Functionality:**
   - Users can quickly search for specific locations, animals, or employees within the application, enhancing productivity and responsiveness.
   - Advanced search filters allow for precise retrieval of information, optimizing workflow efficiency.

6. **Discharge Management:**
   - Streamline the process of removing animals from the database upon discharge from the kennel.
   - Staff can update discharge status and relevant details, ensuring accurate records and inventory management.

The Nashville Kennels Management Application is a valuable tool for optimizing operations and delivering top-notch care to furry companions across the city. With its intuitive interface and robust functionality, it empowers staff to efficiently manage animal assignments, track employees, and maintain a comprehensive inventory of animals across multiple locations.


## Setup

1. Run `npm install --location=global yarn`. If that doesn't work, try `npm install -g yarn`
1. Clone the repository and `cd` into the project directory.
1. Run `yarn install`.
1. Run `npm install typescript --save-dev`
1. Run `yarn start` to verify that the application compiles and starts in the browser.

### API

Each teammate will run their own API instead of using a shared one. In the `data` directory, you will see a `database.json.fixture` file that each teammate will use to [seed their database](https://en.wikipedia.org/wiki/Database_seeding).

Each teammate should create a **separate** directory in their workspace directory named `kennel-api`. Then create a `database.json` file in that directory. Copy pasta the example data into the new file. Then start json-server in that directory.

We repeat, **DO NOT CREATE A `database.json` FILE ANYWHERE IN THE APPLICATION REPOSITORY**.


# 🚀 SheyCars - Car Rental System 🚗

## 📖 Description

SheyCars is a full-stack Node.js application that enables users to book cars for rent. The system allows users to register, login, and view available cars. Users can also book cars and view their booking history. The application is built using React, Express, MongoDB, and Redux.

SheyCars is designed to provide a seamless user experience, with features such as car filtering, sorting, and pagination. The application also includes a Stripe payment gateway for secure transactions.

## ✨ Features

1. ✨ User Registration and Login: Users can register and login to the system using their email and password.
2. ✨ Car Listing: The system displays a list of available cars, with filtering and sorting options.
3. ✨ Booking System: Users can book cars for rent, with options to select the car, date, and time.
4. ✨ Payment Gateway: The system uses Stripe to process payments securely.
5. ✨ Booking History: Users can view their booking history, with options to cancel or update bookings.
6. ✨ Car Filtering: Users can filter cars by make, model, and location.
7. ✨ Car Sorting: Users can sort cars by price, rating, and availability.
8. ✨ Pagination: The system displays cars in a paginated format, with options to navigate through pages.
9. ✨ Error Handling: The system includes error handling for unexpected errors and exceptions.
10. ✨ Responsive Design: The application is designed to be responsive, with a user-friendly interface that adapts to different screen sizes and devices.

## 🧰 Tech Stack

| Technology | Description |
| --- | --- |
| Node.js | Server-side runtime environment |
| Express | Web framework for building web applications |
| React | Front-end framework for building user interfaces |
| MongoDB | NoSQL database for storing data |
| Redux | State management library for managing application state |
| Stripe | Payment gateway for processing transactions |
| Ant Design | UI library for building user interfaces |

## 📁 Project Structure

```
src/
app/
components/
DefaultLayout.js
Spinner.js
...
containers/
App.js
BookingCar.js
...
models/
carModel.js
bookingModel.js
...
pages/
Home.js
Login.js
Register.js
...
reducers/
alertsReducer.js
carsReducer.js
bookingsReducer.js
...
actions/
bookingActions.js
...
store.js
index.js
reportWebVitals.js
App.css
index.css
package.json
```

## ⚙️ How to Run

### Setup

1. Clone the repository: `git clone https://github.com/sheycars/sheycars.git`
2. Install dependencies: `npm install`
3. Create a MongoDB database: `mongod`
4. Create a Stripe account and obtain a test API key: `stripe`
5. Update the `config.js` file with your Stripe API key and MongoDB database URL

### Environment

1. Set environment variables:
	* `MONGODB_URI`: MongoDB database URL
	* `STRIPE_API_KEY`: Stripe API key
	* `NODE_ENV`: Environment (e.g. development, production)

### Build

1. Run the build script: `npm run build`

### Deploy

1. Deploy the application to a production environment (e.g. Heroku, AWS)

## 🧪 Testing Instructions

1. Run the test script: `npm run test`
2. Use a testing framework such as Jest or Mocha to write tests for the application
3. Use a testing library such as Enzyme or React Testing Library to test React components


SheyCars is developed by HariKrishna, a full-stack developer with a passion for building scalable and maintainable software applications.

## 📝 License

SheyCars is licensed under the MIT License.

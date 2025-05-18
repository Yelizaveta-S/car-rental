# RentalCar - Car Rental Frontend Application
This is a frontend web application for "RentalCar," a company specializing in car rentals. Built with React, Vite, and Redux, this application provides a seamless user experience for Browse, filtering, and renting vehicles using a dedicated backend API.

## Features
Homepage: Engaging banner with a call to action.

Catalog Page: Displays a comprehensive list of available vehicles with robust filtering options (brand, price, mileage) and the ability to favorite cars. Pagination (Load More) is implemented for efficient Browse.

Car Details Page: Detailed view of a selected car, including photos and a rental form.

State Management: Utilizes Redux for global state management, including vehicle lists, filters, and favorite cars.

Routing: Implemented with React Router for intuitive navigation (/, /catalog, /catalog/:id).

Backend Integration: Seamless communication with the car rental API via Axios for all data operations, including server-side filtering and pagination.

Persistence: Favorite cars list is preserved across page reloads.
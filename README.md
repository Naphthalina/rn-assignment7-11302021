NAPHTHALINA

##Design Choices
- Component-Based Structure: The application is split into a set of self-contained and reusable components, facilitating easy maintenance and scalability.
  All screens and key features are implemented as different components.
  
- Navigation: It uses React Navigation for navigation among the different screens.
  It creates stack and drawer navigators to implement smooth and user-friendly transitions within this program.

- Context API: This is used to manage global state, mainly for handling the shopping cart.
  The CartContext makes it easier to dispatch actions that would handle the tasks of adding items and removing them from the cart.

- React Native Elements: It taps into a number of elements and components from the React Native library, ensuring clean, consistent, and responsive design across all forms of devices.

##Data Storage and Management
- It uses @react-native-async-storage/async-storage for persistent data storage.
  In this way, this enables the app to locally store data in the device, hence safeguarding essential data such as cart items and user preference that surpass even after the closure of the app.

- The logic for storage is encapsulated within helper functions for ease of management or extension in the future.

##Screenshots

![home1](https://github.com/user-attachments/assets/f2cd5522-b5ec-4e90-9c0d-0224ae3314a7)
![home2](https://github.com/user-attachments/assets/c3e5e5e4-5d3c-4da5-a008-272d6635cbbe)
![home3](https://github.com/user-attachments/assets/db4e0f1d-c186-4f49-be87-d53167b47e6d)
![home4](https://github.com/user-attachments/assets/828ab9b8-76d3-4e05-ae5e-4f0dbb952cd7)
![home5](https://github.com/user-attachments/assets/11d40ebe-16c0-490d-b154-8e1fa17c565b)
![drawer](https://github.com/user-attachments/assets/fa18a3bd-f8e8-4d4a-94fa-19292fa8ef23)
![product-detail](https://github.com/user-attachments/assets/35f76857-0b37-4bf9-abe4-a1c68394b21a)
![checkout](https://github.com/user-attachments/assets/7177db87-e955-4ca6-ba69-ed0aa2944be3)










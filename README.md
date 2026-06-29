# CS-360---Module-8

The goal of this project was to develop a fully functional Android inventory management application. The application allows users to create an account, securely log in, add inventory items, update existing items, and delete items when they are no longer needed. A key feature of the application is the optional SMS notification system that alerts users when an inventory item's quantity falls below a specified threshold.

The app was designed to address the needs of users who want a simple and organized way to track inventory. By providing secure authentication, real-time inventory management, and automated low-stock notifications, the application helps users maintain accurate inventory records while reducing the likelihood of running out of important items.

The application included several important screens: a login screen, an account creation screen, an inventory dashboard, and screens for adding and updating inventory items. The inventory dashboard displayed items in an organized grid, allowing users to quickly view and manage their inventory.

The interface was designed with simplicity and usability in mind. Buttons were clearly labeled, forms were easy to complete, and navigation between screens was straightforward. Confirmation messages and immediate updates after adding, editing, or deleting inventory items provided users with confidence that their actions were successful. The clean layout and intuitive workflow contributed to a positive user experience.

I approached development by breaking the project into smaller, manageable components. I first designed the user interface and then implemented one feature at a time. This included developing the database functionality, user authentication, CRUD operations, SMS permissions, and inventory notifications.

Throughout development, I tested each feature individually before moving on to the next. This incremental approach made it easier to locate and correct errors before they affected other parts of the application. In future software projects, I plan to continue using modular development and incremental testing because they improve organization, simplify debugging, and produce more reliable applications.

I tested the application extensively using the Android Emulator. I verified that users could successfully create accounts, log in with valid credentials, add inventory items, edit existing items, delete items, and observe immediate updates within the inventory grid.

I also tested the SMS notification feature by lowering inventory quantities below the threshold to verify that notifications were triggered correctly when permission was granted and that the application continued functioning properly when SMS permissions were denied. Testing demonstrated that the application's core functionality operated correctly and helped identify minor issues before submission. This process is essential because it improves software reliability and ensures that users receive the expected experience.

One of the biggest challenges was integrating multiple components into a single application. User authentication, database management, CRUD operations, runtime permissions, and SMS messaging all had to work together without interfering with one another.

I overcame these challenges by implementing each feature independently and verifying its functionality before integrating it into the complete application. Breaking complex tasks into smaller objectives made development more manageable and reduced the likelihood of introducing new bugs while adding features.

I believe my strongest accomplishment was successfully integrating the SQLite database with the application's inventory management system. Users can add, edit, and delete inventory items while the interface updates immediately to reflect those changes.

I was also proud of implementing secure user authentication and the SMS notification system for low inventory levels. These features demonstrated my understanding of Android development concepts, including activities, layouts, database management, runtime permissions, event handling, and user-centered application design. Completing this project strengthened my confidence in developing functional mobile applications and provided a strong portfolio artifact that demonstrates both my technical and problem-solving abilities.


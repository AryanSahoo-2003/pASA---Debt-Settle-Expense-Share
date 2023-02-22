# pASA---Debt-Settle-Expense-Share

pASA is an expense sharing app built using Kotlin as the programming language and Firebase as the database. The app allows users to create groups, add members to the groups, and track expenses within each group. Users can also view their overall balance within the group, and see how much they owe or are owed by other members.

Some of my features include :-
1.User authentication:
As the first step, I implemented user authentication using Firebase Authentication. This allowed users to sign in to the app using their email address and password, ensuring that only authorized users could access the app and its features.

2.Group creation:
Next, I developed a feature that allows users to create groups and invite members to join. I used Firebase Realtime Database to store the group data, including the group name, members, and their corresponding balances. Users could create as many groups as they want and invite members by sending them an invitation link.

3.Transaction recording:
Once the group was created, I implemented a feature that enables users to record transactions by specifying the amount, description, and the members involved in the transaction. The transaction data was stored in Firebase Realtime Database as well. Users could easily keep track of their expenses within the group.

4.Balance calculations:
To calculate the overall balance within the group, I implemented balance calculations to track how much each user owes or is owed by other members within the group. This calculation was based on the transactions recorded and was displayed on the app's main screen. Users could see their net balance and easily settle their debts within the group.

5.Notifications:
To remind users of their outstanding debts or overdue payments, I implemented notifications using Firebase Cloud Messaging. This feature sent notifications to the users, helping them stay on top of their financial obligations.

6.User interface:
Finally, I developed a user-friendly interface using Kotlin for the app's front-end development. I used Firebase Realtime Database to store and retrieve data, making it efficient and secure. The interface was simple and intuitive, allowing users to navigate the app and use all its features seamlessly.

In summary, "pASA" is an expense sharing app that enables users to track their expenses and manage their finances within groups. The app is easy to use, and the data is stored securely in Firebase Realtime Database. With features such as user authentication, group creation, transaction recording, balance calculations, and notifications, "pASA" is a powerful tool for managing group expenses.

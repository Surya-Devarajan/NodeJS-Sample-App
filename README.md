## Bugs fixed

- [#20](https://github.com/health-home/WeCare-Web/issues/20): Web- Chrome - Patient listing is not showing complete list of special category patients
- [#23](https://github.com/health-home/WeCare-Web/issues/23): Web- Chrome - Typing text style is different in listing and individual chat
- [#24](https://github.com/health-home/WeCare-Web/issues/24): Web - Columns missing in patient list
- [#29](https://github.com/health-home/WeCare-Web/issues/29): Web - Chat - If the message length is more in size , in chat listing - time is shown in two lines
- [#32](https://github.com/health-home/WeCare-Web/issues/32): Web-Chat-Coach is able to send empty and blank messages

## Features added

### Login

- A coach can login to the app using his valid email and password.
- A coach can logout from the app.

**Note**

- Currently, only coach login is considered.
- Coach will be logging in with his predefined email and password.
- A red border against input fields will be shown if invalid input entries.
- Since coach is predefined, password reset screen (if logging in for the 1st time) is not shown at the moment.

### Chat

- At the moment, coach will get list of predefined patient(s).
- Coach will be able to chat with patient(s).
- Coach will be able to see the name of patient(s) in listing.
- Coach can see the online status of patient(s). A green indicator will be showing if online; white otherwise.
- Coach will be able to see the last message along with patient name.
- Coach will see an icon against the last message indicating whether the last message is audio or video or any attachment.
- Coach will be able to see unread messages count.
- Coach will be able to see last message arrived time along with last message.
- Coach will be able to see if a patient has read the message.
- Coach will be able to upload/attach audio, video and files.
- Coach can view and play audio, video and files.
- Coach can see a typing indicator if any of the patient(s) has started typing.
- Coach will be able to see the message history upon scrolling up.
- Coach will be able to sort patient list by recent message.
- Coach will be able to sort patient list by unread message.
- Coach will be able to mark all message as read.
- Coach will be able to see the messages grouped by date like today, yesterday, etc.
- Coach will be able to see the messages grouped by time.

**Note**

- A coach can upload media files having size of maximum 5MB.
- The maximum message length that a coach can sent is limited to 10000 characters.
- The age, gender and location are at the moment are hard-coded.
- The avatar and name shown in the top right corner is hard-coded.
- Audio recording is not part of the web chat.
- Video/Camera recording is not part of the web.

### Patient list

- A coach can see list of patients, which are special category.
- The list will contain: - Patient name - Patient ID - Gender - Age - Email ID - Phone number

**Note**

- Special category field will not be showing.
- If any data is against a patient is empty then '---' will be showing.

### Coach profile

- A coach can navigate to profile screen.

**Note**

- The functionality for saving the changes made in the profile is not implemented.

### Known issues

- Forgot password functionality is not implemented.
- File attachments are getting downloaded instead of displaying in the chat window itself.
- Once chat icon, against a patient, is clicked then (at the moment), the corresponding chat/channel window will not be active. Instead, the user will be redirect to cha window.

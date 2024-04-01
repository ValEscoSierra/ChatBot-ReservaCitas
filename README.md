## 🏥Chatbot for Appointment Booking and Confirmation - README

This TypeScript-based chatbot aims to streamline the process of booking and confirming appointments for an alternative medical clinic. The bot utilizes Google Calendar and OpenAI to automate the appointment booking process.

### 🔑Key Features

- **Appointment Booking**: Users can request appointments via the chatbot by specifying their availability and preferences.
- **Appointment Confirmation**: Once a booking is made, the bot can confirm the appointment and send reminders as needed.
- **Integration with Google Calendar**: Utilizes Google Calendar to manage and schedule appointments.
- **Integration with OpenAI**: Utilizes OpenAI to provide contextual and helpful responses to user inquiries.
- **Integration with make.com**: Utilizes make.com endpoints to connect POST and GET requests to URLs necessary for interacting with Google Calendar, Google Sheets, and the bot to provide accurate responses regarding appointment availability.

### 📕Requirements

- Node.js and npm installed on the system.
- Access to a Google account with permissions to use Google Calendar.
- OpenAI credentials for integration with its API.
- Access to Work.com endpoints for communication with Google Calendar and other bot functionalities.

### 📄Usage Instructions

1. Clone this repository to your local machine.
2. Install dependencies by running the following command:
```typescript
pnpm install
```
4. Configure the necessary credentials for Google Calendar, OpenAI, and Work.com. These credentials should be provided in specific configuration files. Refer to the documentation for details on setting up these credentials correctly.
5. Once the credentials are configured, you can run the chatbot in development mode using the following command:
```typescript
pnpm run dev
```
### 🗒Documentation and important links:

- **Plantillas de Make:** [Documentation Make](https://www.make.com/en)
- **Chatpdf:** [Documentation Chatpdf](https://www.chatpdf.com/)
- **API Chatpdf:** [Documentation API Chatpdf](https://www.chatpdf.com/docs/api/backend)
- **Google Sheets:** [Documentation](https://docs.google.com/spreadsheets/d/1jOZ5YKEV3xTFjzGXB3YDwE2A59fOCYlKC_5J9Dpvpps/edit#gid=0)
- **OpenAI:** [Documentation OpenIA API](https://openai.com/blog/openai-api)



### ⛑Contribution

If you'd like to contribute to this project, feel free to fork this repository and submit pull requests with your improvements. Make sure to follow the contribution guidelines set in the repository.

### 📝Additional Notes

This chatbot is under constant development and improvement. If you encounter any issues or have suggestions for enhancements, feel free to open an issue in the repository or get in touch with the development team.

Thank you for using our appointment booking and confirmation chatbot! We hope it proves to be highly useful.


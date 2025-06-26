# ConnectIt

ConnectIt is a user-friendly online meeting and collaboration platform designed to make virtual communication seamless and productive. It offers a suite of features to facilitate real-time interaction, note-taking, and collaborative work, all within an intuitive interface.

## Features

- **Instant Chat Rooms:** Create or join chat rooms for real-time messaging before, during, and after meetings.
- **Video Meetings:** Host or join secure video calls with multiple participants.
- **Collaborative Whiteboard:** Work together on a virtual whiteboard during meetings. The whiteboard can be downloaded for future reference.
- **Note-Taking:** Take and share notes during meetings, ensuring important points are captured and accessible.
- **Meeting Scheduler:** Schedule and manage meetings with reminders and easy joining options.
- **User Authentication:** Secure login and registration for all users.
- **Responsive Design:** Works smoothly on desktops, tablets, and mobile devices.

## Directory Structure

- `client/` - Frontend React application
  - `src/Components/Chat Room/` - Chat room UI and logic
  - `src/Components/Meet/` - Video meeting components
  - `src/Components/Editor/` - Collaborative whiteboard/editor
  - `src/Components/Notes/` - Note-taking features
  - `src/Components/Home/` - Landing and dashboard pages
  - ...and more modular components for navigation, options, and user management

- `server/` (if present) - Backend server for authentication, meeting management, and real-time communication

## Getting Started

1. **Clone the repository:**
   ```
   git clone <repo-url>
   cd connect-it
   ```

2. **Install dependencies:**
   ```
   cd client
   npm install
   ```

3. **Run the application:**
   ```
   npm start
   ```

4. **(Optional) Start the backend server:**
   ```
   cd ../server
   npm install
   npm start
   ```

## Technologies Used

- React.js (Frontend)
- Node.js & Express (Backend, if present)
- WebRTC (Video/Audio calls)
- Socket.io (Real-time chat and collaboration)
- CSS3 (Responsive design)

## Contributing

Contributions are welcome! Please open issues and submit pull requests for new features, bug fixes, or improvements.

## License

This project is licensed under the MIT License.

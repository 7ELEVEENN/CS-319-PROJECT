# Educational Keylogger Project

## ⚠️ Educational Purposes Only
This project was developed as part of an Information Assurance course to demonstrate security concepts and potential vulnerabilities. It is intended **strictly for educational purposes**. Using keyloggers or similar monitoring tools without explicit consent is illegal and unethical.

## Project Overview
This educational keylogger demonstrates various security concepts and monitoring capabilities in a Node.js environment. It was created to understand potential security vulnerabilities and the importance of implementing proper security measures in systems.

## Features
- 🎯 Keystroke monitoring and logging
- 📧 Email reporting capabilities
- 📸 Webcam capture functionality
- 🖥️ Active window tracking
- 💾 Local log file storage
- ⌨️ Special character and modifier key support
- 🔄 Inactivity timeout handling

## Technical Implementation
- Built with Node.js
- Uses various npm packages for functionality:
  - `node-global-key-listener` for keyboard monitoring
  - `nodemailer` for email capabilities
  - `node-webcam` for camera access
  - `active-win` for window tracking

## Setup and Installation
1. Clone the repository
   ```bash
   git clone [repository-url]
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Configure email settings
   - Update the email configuration in `index.js`:
     - Replace sender email
     - Update email credentials
     - Modify recipient email

4. Run the application
   ```bash
   node index.js
   ```

## Security Considerations
This project demonstrates several security concepts:
- Keystroke logging mechanisms
- System monitoring capabilities
- Data exfiltration methods
- Screen and camera access
- User activity tracking

## Educational Value
This project helps understand:
- Potential security vulnerabilities in systems
- Importance of user activity monitoring
- Data collection and transmission methods
- Implementation of security measures
- Ethical considerations in security tools

## Important Notice
This tool should only be used:
- In controlled, educational environments
- With explicit permission
- For learning security concepts
- On your own systems

## Dependencies
- Node.js
- npm packages:
  - active-win: ^8.1.1
  - nodemailer: ^6.9.7
  - node-global-key-listener: ^0.1.1
  - node-webcam: ^0.8.2

## Author
[Your Name]

## License
ISC

## Disclaimer
This project is for educational purposes only. The authors and contributors are not responsible for any misuse or damage caused by this program. Users must comply with all applicable laws and regulations regarding monitoring and surveillance tools.

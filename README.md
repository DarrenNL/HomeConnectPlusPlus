# HomeConnect Plus +

Demo of an interactive smart home web application that allows users to control various devices in their home through a web interface. The application features real-time device control, natural language processing for commands, an interactive home view, and enhanced security measures during authentication.

## Features
*   User Authentication: Secure login and registration with additional verification using NumberVerify, SIMSwap Verify, and Location Verify APIs.
*   Real-Time Device Control: Control over 10 smart home devices with real-time updates using Socket.IO.
*   Natural Language Processing: Use natural language commands to control devices via integration with OpenAI's API.
*   Interactive Home View: Aesthetic 3D home representation using JavaScript and CSS animations, reflecting device statuses.
*   Speech Recognition: Voice command input using the OpenAI API for hands-free device control and smart device automation.
*   Security Enhancements: Protection against SIM swap fraud, unauthorized access, and device compromise.

## Demo
![alt text](https://github.com/DarrenNL/HomeConnectPlusPlus/blob/main/static/assets/render_gif.gif?raw=true)

## Technologies Used in Full Scale Application
*   Backend:
    - Flask
    - Flask-SocketIO
    - SQLAlchemy
*   Frontend:
    - HTML5, CSS3, JavaScript
    - jQuery
    - Bootstrap
    - Three.js (for 3D rendering)
*   APIs:
    - OpenAI API
    - NumberVerify API
    - SIMSwap Verify API
    - Location Verify API
*   Database:
    - SQLite (can be replaced with PostgreSQL or MySQL)
## API References
OpenAI API
*   Purpose: Process natural language commands and convert them into structured actions.
*   Documentation: [OpenAI API Docs](https://beta.openai.com/docs/)

NumberVerify API
*   Purpose: Validate phone numbers during authentication.
*   Documentation: [NumberVerify API Docs](https://camaraproject.org/number-verification/)

SIMSwap Verify API
*   Purpose: Detect recent SIM swap activities to prevent fraud.
*   Documentation: [SIMSwap API Docs](https://camaraproject.org/sim-swap/)

Location Verify API
*   Purpose: Verify the user's location during authentication for enhanced security.
*   Documentation: [Location Verify API Docs](https://camaraproject.org/device-location/)

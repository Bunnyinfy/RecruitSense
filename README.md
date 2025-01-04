# RecruitSense

RecruitSense is an open-source platform designed to revolutionize the recruitment process through cutting-edge automation and intelligent technologies. It streamlines candidate assessments, enhances communication, and ensures security during recruitment rounds, making the hiring process efficient and transparent.

## Features

### Comprehensive Recruitment Rounds
- **Aptitude, Technical, and HR Rounds**:  
  - Use pre-existing question sets.  
  - Manually input custom questions.  
  - Generate AI-based aptitude/technical questions using prompts.  

### Seamless Data Management
- Automatic extraction of candidate data from Excel files for easy management.

### Real-Time Dashboards
- Live updates on candidates' progress during assessments.

### Effortless Communication
- Integrated email functionality for streamlined correspondence with candidates.

### Assessment Authorization
- **Real-Time Face Detection**:  
  - Monitor unauthorized participants during assessments.  
  - Capture proof images of any violations.  

- **Candidate Restrictions**:  
  - Prevent copy-pasting code.  
  - Restrict switching tabs or opening other apps during assessments.

## Tech Stack
- **Frontend**: React.js  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Additional Technologies**:  
  - Face Detection Integration  
  - Gemini API Integration  

## Installation and Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/recruit-sense.git
   cd recruit-sense
   ```

2. **Install Dependencies**
   - Navigate to the client and server directories and install dependencies:
     ```bash
     cd client
     npm install
     cd ../server
     npm install
     ```

3. **Set Up Environment Variables**
   - Create a `.env` file in the `server` directory and configure the following:
     ```
     MONGO_URI=your-mongodb-connection-string
     PORT=your-server-port
     GEMINI_API_KEY=your-gemini-api-key
     ```

4. **Run the Application**
   - Start the server:
     ```bash
     npm start
     ```
   - Start the client:
     ```bash
     cd ../client
     npm start
     ```

5. **Access the Application**
   - Open your browser and navigate to `http://localhost:3000`.

## Contributing
Recruit Sense is an open-source project, and contributions are welcome. If you want to contribute:
1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes and push them to your branch.
4. Submit a pull request.


---

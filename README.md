# nodeJs-file-system


### Step 1: Run npm init
### Step 2: Enter Package Name
### Step 3: Enter Entry File
### Step 4: npm install express nodemon body-parser
### Step 5: Create "index.js" inside a Root folder
### Step 6: Inside index.js enter below:

const express = require('express')
const HTTP_SERVER = express();
HTTP_SERVER.listen(5000, "localhost", () => {
    console.log("Server started")
})
http://localhost:5000/
HTTP_SERVER.get('/', (req, res) => {
    return res.status(200).json({
        message: "My first ever API"
    })
})


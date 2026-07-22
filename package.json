const express = require('express');
const app = express();
const port = process.env.PORT || 3000;

app.get('/', (req, res) => {
  res.send('<h1>Backlog Bouncer Steam Auth</h1><p>This is the authentication endpoint for the mobile app.</p>');
});

app.get('/success', (req, res) => {
  res.send(`
    <div style="text-align: center; margin-top: 50px; font-family: sans-serif;">
      <h1 style="color: #66C0F4;">Login Successful!</h1>
      <p>You can now close this window and return to the app.</p>
    </div>
  `);
});

app.listen(port, () => {
  console.log(`Server running on port ${port}`);
});
import React, { useState } from 'react';
import './App.css'; // You can add some basic styling here

function App() {
  const [message, setMessage] = useState('');
  const [response, setResponse] = useState('');
  const [loading, setLoading] = useState(false); // Add loading state

  const sendMessage = async () => {
    if (message.trim() === '') {
      alert("Please enter a message.");
      return;
    }

    setLoading(true); // Start loading

    try {
      const res = await fetch('YOUR_BACKEND_URL/chat', { // Replace with your Render backend URL
        method: 'POST',
        headers: {
          'Content-Type': 'application/json',
        },
        body: JSON.stringify({ text: message }),
      });

      if (!res.ok) {
        throw new Error(`HTTP error! Status: ${res.status}`);
      }

      const data = await res.json();
      setResponse(data.response);
    } catch (error) {
      console.error('Error sending message:', error);
      setResponse('An error occurred: ' + error.message);
    } finally {
      setLoading(false); // Stop loading
      setMessage(''); // Clear the input field
    }
  };

  return (
    <div className="App">
      <h1>Dr. Ojijo Intelligence System</h1>
      <div className="chat-container">
        <div className="input-area">
          <input
            type="text"
            value={message}
            onChange={(e) => setMessage(e.target.value)}
            placeholder="Type your message..."
          />
          <button onClick={sendMessage} disabled={loading}>
            {loading ? 'Sending...' : 'Send'}
          </button>
        </div>
        <div className="response-area">
          <p>Response: {response}</p>
        </div>
      </div>
    </div>
  );
}

export default App;

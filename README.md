
# Header Parser Microservice

This is a simple microservice built for the [FreeCodeCamp Back End Development and APIs certification](https://www.freecodecamp.org/learn/back-end-development-and-apis/).

## 📌 Project Objective

Build a microservice that returns information about the client's device, language, and software using HTTP request headers.

## 🚀 How It Works

When a client sends a GET request to `/api/whoami`, the server responds with a JSON object containing:

- `ipaddress`: The client's IP address
- `language`: The client's preferred language
- `software`: Information about the client's operating system and browser

### Example Response:

```
{
  "ipaddress": "127.0.0.1",
  "language": "en-US,en;q=0.9",
  "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64)..."
}
```

## 📁 File Structure

```
.
├── index.js           # Main Express server
├── package.json        # Project metadata and dependencies
├── views/
│   └── index.html      # Landing page
└── public/             # Static files
```

## 🛠️ Tech Stack

- Node.js
- Express.js
- JavaScript

## 📚 Learnings

- Working with HTTP headers in Express
- Extracting and sending client data in JSON format
- Basic server setup and routing

---

Created with 💻 by [kurogamidesuu](https://github.com/kurogamidesuu)

---
title: "My Journey in Creating an Axios Tutorial: From Setup to Final Video 🎥"
description: "Explore my experience in creating a tutorial for Axios, from setting up a React project to demonstrating simple and complex use cases, and the lessons I learned along the way."
pubDate: "Sept 16 2024"
heroImage: "/images/axios.png"
---

Hey folks! 👋 I'm Shane Jeremich, a web development student, and today I want to share my experience creating a tutorial on **Axios**. A few months ago, I made this tutorial for a previous class, where I explained how to install Axios, provided examples of how to use it, and shared why it’s become an essential tool in my toolkit for making HTTP requests in JavaScript. Originally, I uploaded the video to Microsoft Stream, but now I’ve decided to write an article about my experience creating my first-ever tutorial. I reuploaded the video to YouTube and am using this post to reflect on the whole process. This article isn’t just about Axios—it’s about my journey of learning how to teach it. Let’s dive in!

## Watch the Tutorial 🎥

Here’s the video tutorial I created on YouTube:

<div class="video-container">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/SjtyDFBrGCQ?si=EVlQchcwk-PaUCqX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<style>
.video-container {
  position: relative;
  padding-bottom: 56.25%;
  height: 0;
  overflow: hidden;
  max-width: 100%;
  background: #000;
}

.video-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
}
</style>

<br>
<br>

## How I created my Axios Tutorial 🎬

When I set out to create this tutorial, I wanted to keep things straightforward while demonstrating both simple and more complex uses of Axios. Here's a breakdown of the steps I took to record the video:

### Set Up the Project:

I started by creating a new React project using Vite with the following command:

```bash
npm create vite@latest axios-tutorial -- --template react
```

<br>

After the project was set up, I installed Axios:

```bash
npm install axios
```

<br>
<br>

### Basic Example with Random User API:

Once the project was up and running, I imported Axios:

```javascript
import axios from "axios";
```

<br>
Then, I used a simple useEffect hook to make a GET request to the Randomuser.me API to fetch a random user picture. This provided a basic example of how to use Axios for HTTP requests:

<br>
<br>

![Code Example #1](/blog/images/code.png)

After showing the basic example, I demonstrated a more complex use case from a previous project of mine where I had integrated Axios for full CRUD operations. This example highlighted how Axios can be used to handle a variety of requests, such as GET, POST, PUT, and DELETE, for more dynamic data management.

With the project setup complete, I utilized my MacBook’s recording capabilities to capture the tutorial. I meticulously walked through each example and then edited the footage to create a polished final video, which was eventually uploaded to YouTube. This process allowed me to share my insights and provide a comprehensive look at Axios in action.

## So what is Axios? 📡

**Axios** is a **promise-based HTTP client** for JavaScript that can be used in both the browser and Node.js. It simplifies the process of making HTTP requests and handling responses, making it easier to interact with APIs and fetch data from servers.

Here’s what sets Axios apart:

- **Promise-Based**: Axios uses promises, which makes it easier to work with asynchronous operations and handle responses.
- **Browser and Node.js**: Axios can be used in both browser environments and Node.js, making it versatile for different types of projects.
- **Interceptors**: Axios allows you to intercept requests and responses, enabling you to modify them before they are handled.
- **Automatic JSON Transformation**: Axios automatically transforms JSON data, making it easier to work with APIs that return JSON responses.

Axios's simplicity and versatility make it an excellent choice for projects that require making HTTP requests, whether you're fetching data from an API or submitting data to a server.

## What Can You Do with Axios? 🌐

Axios is extremely versatile and can be used for a wide range of applications. Here are a few things you can do with it:

- **Fetch Data from APIs**: Axios makes it easy to fetch data from APIs and handle the responses.
- **Submit Data to Servers**: You can use Axios to send data to servers, whether it's for form submissions or other types of data.
- **Handle Errors Gracefully**: Axios provides built-in error handling, making it easier to manage errors and display appropriate messages to users.
- **Interceptors for Custom Logic**: Axios interceptors allow you to add custom logic to requests and responses, such as adding authentication tokens or logging.

In short, Axios is ideal for projects that require making HTTP requests and handling responses in a clean and efficient manner.

## How to Install Axios 🛠️

Installing Axios is straightforward. You can install it using npm or yarn if you're working with Node.js, or you can include it directly in your HTML file if you're working in the browser.

### Using npm

To install Axios using npm, run the following command:

```bash
npm install axios
```

<br>
<br>

### Using yarn

To install Axios using yarn, run the following command:

```bash
yarn add axios
```

<br>
<br>

### Using a CDN

If you prefer to include Axios directly in your HTML file, you can use a CDN:

```html
<script src="https://cdn.jsdelivr.net/npm/axios/dist/axios.min.js"></script>
```

<br>
<br>

## Examples of Using Axios 📚

Here are some examples of how to use Axios to make HTTP requests:

### Fetching Data from an API

```javascript
import axios from "axios";

axios
  .get("https://api.example.com/data")
  .then(response => {
    console.log(response.data);
  })
  .catch(error => {
    console.error("Error fetching data:", error);
  });
```

<br>
<br>

### Submitting Data to a Server

```javascript
import axios from "axios";

const data = {
  name: "Shane Jeremich",
  email: "shane@example.com",
  age: 25,
};

axios
  .post("https://api.example.com/submit", data)
  .then(response => {
    console.log("Data submitted successfully:", response.data);
  })
  .catch(error => {
    console.error("Error submitting data:", error);
  });
```

<br>
<br>

## Reflecting on My Tutorial Experience 📝

Creating a tutorial on Axios was a rewarding experience, but if I had to do it all over again, there are a few things I would do differently:

- **Plan the Video Layout Better**: I would spend more time planning the structure of the video to ensure a smooth flow of information. This would help in delivering the content more effectively.
- **Add Better Visuals**: Incorporating more visuals, such as diagrams and code snippets, would make the tutorial more engaging and easier to follow.
- **Have a Written Script**: Writing a script beforehand would help in reducing nervous filler words and ensure that I cover all the important points without missing anything.
- **Edit the Video Better**: I would focus on editing the video to remove any unnecessary parts and improve the overall quality. This would make the tutorial more polished and professional.

<br>
<br>

## Final Thoughts 🧑‍💻

Axios is a powerful tool for making HTTP requests in JavaScript, and creating a tutorial on it was a great learning experience. Whether you're fetching data from an API or submitting data to a server, Axios simplifies the process and makes it more efficient.

As someone who was already familiar with Axios, this experience has been less about learning the tool itself and more about improving my ability to articulate technical concepts. Working on projects like this and creating tutorial videos has pushed me to develop my technical speaking skills—learning how to explain my code, experiences, and thought process more clearly. I know that fluency in technical vocabulary is something I need to work on, and producing content like this is exactly the kind of practice that helps me grow. Moving forward, I want to continue creating more tutorials and projects to refine these skills.

Thanks for reading! Stay tuned for more posts as I continue my journey into web development. 💻🚀

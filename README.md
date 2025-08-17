<h1 align="center">🚀 TaskHub</h1>

<p align="center">
  <strong>Modern Kanban Project Management Tool</strong><br>
  Built with <code>React</code>, <code>TypeScript</code>, <code>Node.js</code>, <code>Tailwind CSS</code>, and <code>Clerk</code> for authentication
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-18.2.0-blue?logo=react" />
  <img src="https://img.shields.io/badge/TypeScript-5.2.0-blue?logo=typescript" />
  <img src="https://img.shields.io/badge/Node.js-20.x-green?logo=node.js" />
  <img src="https://img.shields.io/badge/Clerk-Auth-lightgrey?logo=clerk" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" />
</p>

---

<h2>📝 Overview</h2>

<p>
TaskHub is a sleek, Kanban-style project management tool designed for teams and individuals. With drag-and-drop task handling, real-time collaboration, and customizable workflows, TaskHub helps you stay organized and productive.
</p>

<ul>
  <li>Visualize tasks with clarity</li>
  <li>Track progress and milestones</li>
  <li>Collaborate in real-time</li>
  <li>Automate notifications</li>
  <li>Maintain transparency with activity logs</li>
  <li>Secure authentication powered by Clerk</li>
</ul>

---

<h2>🛠️ Tech Stack</h2>

<table>
  <tr>
    <th>Frontend</th>
    <th>Backend</th>
    <th>Tooling & DevOps</th>
  </tr>
  <tr>
    <td>React 18</td>
    <td>Node.js 20</td>
    <td>Vite</td>
  </tr>
  <tr>
    <td>TypeScript</td>
    <td>Express.js</td>
    <td>ESLint + Prettier</td>
  </tr>
  <tr>
    <td>Zustand</td>
    <td>Clerk Auth</td>
    <td>Husky + GitHub</td>
  </tr>
</table>

---

<h2>📚 Table of Contents</h2>

<ul>
  <li><a href="#features">Features</a></li>
  <li><a href="#installation">Installation</a></li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#environment-setup">Environment Setup</a></li>
  <li><a href="#clerk-setup">Clerk Setup</a></li>
  <li><a href="#contributing">Contributing</a></li>
  <li><a href="#license">License</a></li>
</ul>

---

<h2 id="features">✨ Features</h2>

<details>
  <summary><strong>Click to expand feature list</strong></summary>
  <ul>
    <li>🧩 Kanban Board with drag-and-drop</li>
    <li>🔄 Customizable workflows</li>
    <li>👥 Real-time collaboration</li>
    <li>🔔 Automated notifications</li>
    <li>📈 Activity tracking</li>
    <li>🎯 Milestone monitoring</li>
    <li>🔐 Authentication via Clerk</li>
  </ul>
</details>

---

<h2 id="installation">⚙️ Installation</h2>

<pre>
git clone https://github.com/SatChittAnand/TaskHub.git
cd TaskHub
npm install
npm run dev
</pre>

<p><em>Requires Node.js ≥ 20 and npm ≥ 9</em></p>

---

<h2 id="usage">🚀 Usage</h2>

<ol>
  <li>Sign in using Clerk authentication</li>
  <li>Create tasks and assign team members</li>
  <li>Drag & drop tasks across columns</li>
  <li>Customize workflows to match your process</li>
  <li>Collaborate and comment in real-time</li>
  <li>Receive smart notifications</li>
  <li>Track activity logs for transparency</li>
</ol>

---

<h2 id="environment-setup">🌐 Environment Setup</h2>

<p>Create a <code>.env</code> file in the root directory:</p>

<pre>
VITE_API_URL=http://localhost:5000/api
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
</pre>

<p><strong>Note:</strong> Never commit your <code>.env</code> file.</p>

---

<h2 id="clerk-setup">🔐 Clerk Setup</h2>

<ol>
  <li>Go to <a href="https://clerk.dev" target="_blank">Clerk.dev</a> and create an account</li>
  <li>Create a new Clerk application</li>
  <li>Copy your <strong>Publishable Key</strong> and <strong>Secret Key</strong></li>
  <li>Paste them into your <code>.env</code> file</li>
  <li>Wrap your app with <code>&lt;ClerkProvider&gt;</code> and use <code>SignedIn</code>, <code>SignedOut</code> components</li>
</ol>

<p>For more details, check out the <a href="https://clerk.dev/docs" target="_blank">Clerk Documentation</a>.</p>

---

<h2 id="contributing">🤝 Contributing</h2>

<details>
  <summary><strong>Click to view contribution steps</strong></summary>

  <ol>
    <li>Fork the repository</li>
    <li>Clone your fork</li>
    <pre>git clone https://github.com/your-username/TaskHub.git</pre>
    <li>Create a feature branch</li>
    <pre>git checkout -b feature/your-feature-name</pre>
    <li>Make your changes</li>
    <li>Commit with a descriptive message</li>
    <pre>git commit -m "Add: your feature description"</pre>
    <li>Push to your fork</li>
    <pre>git push origin feature/your-feature-name</pre>
    <li>Open a pull request</li>
  </ol>

  <p>Please follow our coding standards and include relevant tests.</p>
</details>

---

<h2 id="license">📄 License</h2>

<p>This project is licensed under the <a href="LICENSE">MIT License</a>.</p>

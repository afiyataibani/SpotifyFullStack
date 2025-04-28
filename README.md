![Screenshot 2025-04-28 195827](https://github.com/user-attachments/assets/852990a4-dbc8-45be-a40f-d05ef18672b2)
![Screenshot 2025-04-28 195802](https://github.com/user-attachments/assets/20cece99-85e8-45c7-9a7b-ca6b3bb710e0)
![Screenshot 2025-04-28 195732](https://github.com/user-attachments/assets/033ff169-2cbe-4333-88ba-1b4f26f781be)
![Screenshot 2025-04-28 195703](https://github.com/user-attachments/assets/4b77a1c9-d33a-48c7-8715-fbfa6891947e)
![Screenshot 2025-04-28 195638](https://github.com/user-attachments/assets/57b91ccd-7705-4673-b8b9-b87867d67967)
![Screenshot 2025-04-28 195617](https://github.com/user-attachments/assets/7aa1b57e-f1c7-42c9-9298-1d5fb94c5ed1)
![Screenshot 2025-04-28 195527](https://github.com/user-attachments/assets/7f211825-3cef-4863-b151-daa12306b35e)
<body style="font-family: Arial, sans-serif; line-height: 1.6; padding: 20px;">

  <h1>🎵 Spotify Full Stack Project</h1>

  <p>A complete <strong>Spotify Clone</strong> built using the <strong>MERN Stack</strong> with dynamic albums and songs, cloud storage for media files, and a fully functional admin panel to manage songs and albums.</p>

  <hr>

  <h2>🚀 Live Links</h2>
  <ul>
    <li><a href="https://spotifyfullstack-frontend.onrender.com" target="_blank">Spotify Frontend (Clone)</a></li>
    <li><a href="https://spotifyfullstack-backend.onrender.com" target="_blank">Spotify Backend</a></li>
    <li><a href="https://spotifyfullstack-admin.onrender.com" target="_blank">Spotify Admin Panel</a></li>
  </ul>

  <hr>

  <h2>📂 Project Structure</h2>
  <ul>
    <li><strong>spotify-clone</strong> — Frontend client where users can listen to music, browse albums, play/pause songs, and use next/previous buttons along with a working seek bar.</li>
    <li><strong>spotify-backend</strong> — Backend server using Node.js, Express.js, and MongoDB for storing and managing songs, albums, and user interactions. Integrates <strong>Cloudinary</strong> for media file storage and <strong>Axios</strong> for API calls.</li>
    <li><strong>spotify-admin</strong> — Admin panel where new songs and albums can be added dynamically to the database, which are then fetched in real-time by the Spotify Clone frontend.</li>
  </ul>

  <hr>

  <h2>🛠️ Technologies Used</h2>
  <ul>
    <li><strong>Frontend (spotify-clone)</strong>: React.js, HTML5, CSS3, JavaScript, Axios</li>
    <li><strong>Backend (spotify-backend)</strong>: Node.js, Express.js, MongoDB, Mongoose, Cloudinary, CORS</li>
    <li><strong>Admin Panel (spotify-admin)</strong>: React.js, Form Handling, Axios, Cloudinary Integration</li>
  </ul>

  <hr>

  <h2>🎯 Features</h2>
  <ul>
    <li>🎶 Play, Pause, Next, and Previous functionality for songs.</li>
    <li>⏩ Working Seek Bar to navigate within a song.</li>
    <li>📀 Dynamic Albums - Albums are added via Admin Panel and fetched automatically.</li>
    <li>🎵 Dynamic Songs - Songs are associated with albums and played dynamically.</li>
    <li>📡 Full integration with Cloudinary for audio and image storage.</li>
    <li>🛡️ Secure REST APIs for managing songs and albums.</li>
    <li>⚡ Fast Axios-based API calls between frontend, backend, and admin panel.</li>
    <li>🗄️ MongoDB database to store song and album information.</li>
  </ul>

  <hr>

  <h2>📝 How It Works</h2>
  <ol>
    <li>The <strong>Admin Panel</strong> allows admins to add new songs and albums with song names, artists, and media uploads.</li>
    <li>The data is sent to the <strong>Backend Server</strong> using Axios and stored in <strong>MongoDB</strong>.</li>
    <li>The <strong>Spotify Clone (Frontend)</strong> fetches this data from the backend server and displays dynamic albums and songs.</li>
    <li>Users can <strong>play</strong> songs, <strong>pause</strong>, jump to <strong>next</strong> or <strong>previous</strong> songs, and even use the <strong>seek bar</strong> to navigate within the song.</li>
  </ol>

  <hr>

  <h2>📢 Important Notes</h2>
  <ul>
    <li>This project is deployed using <strong>Render.com</strong> for both frontend and backend.</li>
    <li>Cloudinary is used to store and fetch all audio and image files efficiently.</li>
    <li>All three modules (Frontend, Backend, Admin Panel) are interconnected and rely on a single database instance.</li>
    <li>Admin Panel access should be limited to authenticated users in production (currently open for project demonstration purposes).</li>
  </ul>

  <hr>

  <h2>🤝 Contributing</h2>
  <p>Feel free to fork this project, raise issues, and create pull requests if you want to contribute!</p>

  <hr>

  <h2>📧 Contact</h2>
  <p>If you have any queries or suggestions regarding this project, feel free to connect!</p>

</body>

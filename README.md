# Vicky Posts - Social Media Application

A modern, full-stack social media application built with Node.js, Express.js, and EJS. This project implements complete CRUD operations with a beautiful glass-morphism UI design.

## 🚀 Features

- **Create Posts**: Users can create new posts with username and content
- **View Posts**: Display all posts in a beautiful card layout
- **Edit Posts**: Update existing post content
- **Delete Posts**: Remove posts with confirmation
- **Responsive Design**: Modern glass-morphism UI with gradient backgrounds
- **RESTful API**: Proper HTTP methods (GET, POST, PATCH, DELETE)
- **Unique IDs**: UUID implementation for post identification

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Templating**: EJS (Embedded JavaScript)
- **Styling**: CSS3 with gradients, glass-morphism effects
- **Middleware**: method-override for PATCH/DELETE support
- **Utilities**: UUID for unique post IDs

## 📁 Project Structure

```
Vicky-Posts/
│
├── 📄 index.js              # Main server file with Express routes
├── 📄 package.json          # Project dependencies and scripts
├── 📄 package-lock.json     # Dependency lock file
├── 📄 README.md             # Project documentation
├── 📄 .gitignore            # Git ignore rules
│
├── 📁 public/               # Static assets
│   └── 📄 style.css         # Modern CSS with glass-morphism design
│
└── 📁 views/                # EJS templates
    ├── 📄 index.ejs         # Home page - displays all posts
    ├── 📄 new.ejs           # Create new post form
    ├── 📄 edit.ejs          # Edit existing post form
    └── 📄 show.ejs          # Individual post details page
```

## 🎨 UI Features

- **Glass-morphism Design**: Semi-transparent cards with backdrop blur
- **Gradient Backgrounds**: Purple-blue gradient theme
- **Smooth Animations**: Hover effects and transitions
- **Color-coded Actions**: 
  - Purple/Blue for primary actions (View, Edit)
  - Red/Orange for destructive actions (Delete)
- **Responsive Layout**: Works on all device sizes
- **Modern Typography**: Clean, readable fonts

## 🚀 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/ItsVikasA/Vicky-Posts.git
   cd Vicky-Posts
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the server**
   ```bash
   npm start
   # or
   node index.js
   ```

4. **Open your browser**
   ```
   http://localhost:8080
   ```

## 📦 Dependencies

```json
{
  "express": "^5.1.0",
  "ejs": "^3.1.10",
  "uuid": "^10.0.0",
  "method-override": "^3.0.0"
}
```

## 🛣️ API Routes

| Method | Route | Description |
|--------|-------|-------------|
| GET | `/` | Home page - displays all posts |
| GET | `/posts` | Display all posts |
| GET | `/posts/new` | Show create post form |
| POST | `/posts` | Create a new post |
| GET | `/posts/:id` | Show individual post details |
| GET | `/posts/:id/edit` | Show edit post form |
| PATCH | `/posts/:id` | Update existing post |
| DELETE | `/posts/:id` | Delete a post |

## 🎯 Key Learning Outcomes

- **RESTful API Design**: Implemented proper HTTP methods and routes
- **Server-side Rendering**: Used EJS templating for dynamic content
- **Express.js Middleware**: Utilized method-override, static files, and body parsing
- **Modern CSS**: Created glass-morphism effects and responsive design
- **CRUD Operations**: Complete Create, Read, Update, Delete functionality
- **Git Version Control**: Professional repository management

## 🚀 Future Enhancements

- [ ] User authentication and authorization
- [ ] MongoDB database integration
- [ ] Image upload functionality
- [ ] Real-time updates with Socket.IO
- [ ] Like and comment system
- [ ] User profiles
- [ ] Search and filter functionality

## 📸 Screenshots

### Home Page
Beautiful card layout with all posts displayed with glass-morphism effects.

### Create Post
Clean form interface for creating new posts.

### Edit Post
Simple editing interface with pre-filled content.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Developer

**Vikas**
- GitHub: [@ItsVikasA](https://github.com/ItsVikasA)
- LinkedIn: [Connect with me](https://linkedin.com/in/yourprofile)

## 🙏 Acknowledgments

- Thanks to Apna College for the MERN Stack learning journey
- Inspiration from modern social media platforms
- Glass-morphism design trends

---

⭐ **If you found this project helpful, please give it a star!** ⭐

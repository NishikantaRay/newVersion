<div align="center">

```
                ██████╗ ███████╗███╗   ██╗██████╗ ███████╗██████╗ ███████╗██████╗ 
                ██╔══██╗██╔════╝████╗  ██║██╔══██╗██╔════╝██╔══██╗██╔════╝██╔══██╗
                ██████╔╝█████╗  ██╔██╗ ██║██║  ██║█████╗  ██████╔╝█████╗  ██████╔╝
                ██╔══██╗██╔══╝  ██║╚██╗██║██║  ██║██╔══╝  ██╔══██╗██╔══╝  ██╔══██╗
                ██║  ██║███████╗██║ ╚████║██████╔╝███████╗██║  ██║███████╗██║  ██║
                ╚═╝  ╚═╝╚══════╝╚═╝  ╚═══╝╚═════╝ ╚══════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝
```

### 🌟 _"Render your story, configure your future"_ 🌟

[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://github.com/NishikantaRay/renderer)
[![Vanilla JS](https://img.shields.io/badge/Vanilla-JS-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TOML Config](https://img.shields.io/badge/Config-TOML-blue.svg)](https://toml.io/)
[![Zero Build](https://img.shields.io/badge/Build-Zero-green.svg)](https://github.com/NishikantaRay/renderer)
[![v2.0 Ready](https://img.shields.io/badge/Version-2.0-brightgreen.svg)](https://github.com/NishikantaRay/renderer)
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://renderer.nishikanta.in/)
[![Documentation](https://img.shields.io/badge/Docs-Available-blue.svg)](https://renderer.nishikanta.in/docs)

**✨ A powerful, configuration-driven portfolio system that transforms your story into a stunning web presence**

*Built with vanilla HTML, CSS, and JavaScript • Powered by TOML configuration • Designed for developers, designers, and dreamers*

**🌐 [Live Demo](https://renderer.nishikanta.in/) | 📚 [Documentation](https://renderer.nishikanta.in/docs) | 🔧 [GitHub Repository](https://github.com/NishikantaRay/renderer)**

</div>

---

## ✨ Features

### **🎯 Version 2.0 Highlights**
- 🔧 **TOML-First Architecture** - Robust TOML parsing with smart fallbacks
- 🏢 **@Mention System** - Professional company mentions with enhanced styling
- 🔗 **Enhanced URL Support** - Repository, demo, and documentation links
- 🎓 **Education System** - Dedicated education section with institution links
- ⚡ **Performance Optimized** - Console cleanup and production-ready features
- 🛠️ **Debugging Tools** - Advanced debugging and development utilities

### **Core Features**
- 🔧 **Fully Configurable** - Configure every aspect through TOML files
- 📄 **Multipage Support** - Home, About, Projects, Blog, Resume, and Contact pages
- 📝 **Markdown Content** - All content stored in markdown files for easy editing
- 🌙 **Dark/Light Theme** - Automatic theme detection with manual toggle
- 📱 **Responsive Design** - Works perfectly on mobile and desktop
- ⚡ **Fast Loading** - No frameworks, just clean vanilla code
- 🔍 **SEO Friendly** - Proper meta tags and semantic HTML

### **Advanced Configuration**
- 🎛️ **Enable/Disable Any Feature** - Granular control over every component
- 📊 **Analytics Dashboard** - Optional project analytics and charts
- 🎨 **UI Customization** - Control animations, layouts, and interactions
- ♿ **Accessibility Controls** - Configure accessibility features
- 🚀 **Performance Options** - Lazy loading, caching, and optimizations
- 🔧 **Debug Mode** - Built-in debugging and development tools

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/NishikantaRay/renderer.git

# Navigate to the project
cd renderer

# Serve locally (Python 3)
python -m http.server 8000
# or with Node.js
npx serve .

# Open your browser
open http://localhost:8000
```

**💡 Pro Tip:** Visit the live documentation at [renderer.nishikanta.in/docs](https://renderer.nishikanta.in/docs) for comprehensive setup guides and configuration examples!

## � Documentation

🌐 **[Complete Documentation](https://renderer.nishikanta.in/docs)** - Interactive documentation hub with:

- **Configuration Guides** - Step-by-step TOML configuration examples
- **Feature Tutorials** - How to implement each portfolio feature
- **Code Examples** - Copy-paste ready code snippets
- **Live Demos** - Interactive previews of all components
- **Best Practices** - Tips for optimal portfolio performance
- **Troubleshooting** - Common issues and solutions

**Quick Documentation Links:**
- 🏠 [Home Configuration](https://renderer.nishikanta.in/docs#home-config)
- 🚀 [Projects Setup](https://renderer.nishikanta.in/docs#projects-config)
- 📝 [Blog System](https://renderer.nishikanta.in/docs#blog-config)
- 📄 [Resume Builder](https://renderer.nishikanta.in/docs#resume-config)
- 🔗 [Social Links](https://renderer.nishikanta.in/docs#social-config)

## �📁 Project Structure

```
minimal-portfolio/
├── 📄 HTML Pages
│   ├── index.html          # Home page with hero section
│   ├── about.html          # About page
│   ├── projects.html       # Projects showcase with analytics
│   ├── blog.html          # Blog with dynamic content loading
│   ├── resume.html        # Interactive resume
│   ├── contact.html       # Contact information
│   └── docs.html          # Interactive documentation hub
│
├── ⚙️ Configuration (TOML)
│   ├── home.toml          # Home page: hero, clients, products, dashboard
│   ├── projects.toml      # Projects: features, analytics, sections
│   ├── blog.toml          # Blog: posts, pagination, settings
│   ├── resume.toml        # Resume: sections, skills, experience
│   └── social.toml        # Social links and display settings
│
├── 📝 Content (Markdown)
│   ├── about.md           # About page content
│   ├── projects.md        # Projects content
│   ├── blog.md           # Blog posts and content
│   ├── contact.md         # Contact page content
│   └── [blog-posts].md   # Individual blog posts
│
├── 📚 Documentation
│   ├── docs/
│   │   ├── README.md      # Main documentation
│   │   ├── HOME_CONFIG.md # Home configuration guide
│   │   ├── PROJECTS_CONFIG.md # Projects setup
│   │   ├── BLOG_CONFIG.md # Blog system guide
│   │   ├── RESUME_CONFIG.md # Resume builder
│   │   └── SOCIAL_CONFIG.md # Social links setup
│
├── 🎨 Styling
│   ├── css/
│   │   ├── home.css       # Home page styles
│   │   ├── projects.css   # Projects page styles
│   │   ├── blog.css       # Blog styles
│   │   ├── resume.css     # Resume styles
│   │   └── [page].css     # Other page styles
│
├── 🔧 JavaScript
│   ├── js/
│   │   ├── home.js               # Home page functionality
│   │   ├── projects.js           # Projects page logic
│   │   ├── blog-system.js        # Blog system
│   │   ├── resume.js            # Resume interactions
│   │   ├── [page]-config-toml.js # Configuration loaders
│   │   └── [feature]-config.js   # Feature configurations
│
├── 🖼️ Assets
│   └── images/            # Images and media files
│
├── 📚 Documentation
│   ├── docs/
│   │   ├── HOME_CONFIG.md        # Home page configuration guide
│   │   ├── PROJECTS_CONFIG.md    # Projects configuration guide
│   │   ├── BLOG_CONFIG.md        # Blog configuration guide
│   │   ├── RESUME_CONFIG.md      # Resume configuration guide
│   │   ├── SOCIAL_CONFIG.md      # Social links configuration
│   │   └── DASHBOARD-CONFIG.md   # Dashboard configuration
│
└── 📦 Package Files
    ├── package.json       # Development dependencies
    └── README.md         # This file
```

## ⚙️ Configuration Guide

### **🏠 Home Page Configuration (`config/home.toml`)**

Control every aspect of your home page:

```toml
# Hero section
[hero]
name = "Nishikanta Ray"
title = "Full-Stack Developer & Designer"
intro = [
    "Your introduction paragraph...",
    "Additional details..."
]

[hero.actions]
primary_text = "Hire Me"
primary_link = "resume.html"
secondary_text = "Let's Talk"
secondary_link = "#contact"

# Enable/disable sections
[sections]
enabled_sections = ["freelance-clients", "latest-products", "dashboard"]

# Freelance clients section
[freelance_clients]
enabled = true
title = "Trusted by Clients"
subtitle = "Companies I've worked with"

# Add clients
[[freelance_clients.clients]]
name = "TechStart Inc."
logo = "🚀"  # Emoji or image path
status = "completed"
period = "Oct-Dec 2024"
project = "E-commerce Platform"

# Latest products
[latest_products]
enabled = true
title = "Latest Products"

# Dashboard with analytics
[dashboard]
enabled = false  # Set to true to enable
title = "Dashboard & Analytics"

[dashboard.sections]
charts = false           # Project charts
recent_activity = false  # Activity feed
skills_progress = false  # Skills progress bars
statistics = false       # Stats grid
```

**📖 Full Guide:** [docs/HOME_CONFIG.md](docs/HOME_CONFIG.md)

### **🚀 Projects Page Configuration (`config/projects.toml`)**

Complete control over your projects showcase:

```toml
# Main page settings
[page]
title = "Projects"
subtitle = "A showcase of my recent work"

# Content loading
[content]
enable_markdown_content = true
enable_fallback_content = true
show_intro = true

# Featured projects
[featured_projects]
enabled = true
show_tech_stack = true      # Technology badges
show_features_list = true   # Key features
show_project_links = true   # Demo/GitHub links
enable_hover_effects = true # Animations

# Analytics dashboard
[analytics]
enabled = false  # Disable analytics section
title = "Project Analytics & Activity"

[analytics.charts]
enabled = true
weekly_activity = true      # Activity charts
project_distribution = true # Distribution charts

[analytics.timeline]
enabled = true
max_events = 10            # Timeline events

# Project statistics
[project_stats]
enabled = true
animate_numbers = true      # Animated counters

# Open source section
[opensource]
enabled = true
show_github_stats = true    # GitHub statistics
show_star_counts = true     # Repository stars

# Performance settings
[performance]
lazy_load_images = true     # Lazy loading
preload_critical_content = true

# Accessibility
[accessibility]
high_contrast_mode = false  # High contrast theme
focus_indicators = true     # Enhanced focus
keyboard_navigation = true  # Keyboard support
```

**📖 Full Guide:** [docs/PROJECTS_CONFIG.md](docs/PROJECTS_CONFIG.md)

### **📝 Blog Configuration (`config/blog.toml`)**

Configure your blog system with v2.0 enhancements:

```toml
# Blog metadata
[blog]
title = "Personal Blog"
description = "Thoughts on web development and technology"
author = "Nishikanta Ray"
author_profile = "https://github.com/NishikantaRay"
base_url = ""

# Pagination
[pagination]
posts_per_page = 6
enabled = true

# Feature settings
[settings]
enable_comments = true
enable_social_sharing = true
enable_search = true
enable_categories = true
enable_tags = true
enable_related_posts = true
default_image = "https://dummyimage.com/600x400/0066cc/ffffff&text=Blog+Post"

# Blog posts with enhanced features
[[posts]]
id = "typescript-modern-web"
title = "Building Modern Web Applications with TypeScript"
description = "TypeScript best practices and implementation strategies"
date = "2024-10-12"
tags = ["TypeScript", "Web Development", "JavaScript"]
category = "Development"
content_file = "typescript-modern-web.md"
author = "Nishikanta Ray"
read_time = "8 min read"
featured = true
status = "published"
image = "https://dummyimage.com/600x400/0066cc/ffffff&text=TypeScript+Web"
repo_url = "https://github.com/NishikantaRay/typescript-examples"
demo_url = "https://typescript-demo.yoursite.dev"
license = "MIT"
contributors = ["Nishikanta Ray", "Community Contributors"]
features = [
    "Type safety for large codebases",
    "Seamless integration with modern frameworks", 
    "Improved developer productivity",
    "Better tooling and editor support"
]
related_posts = ["minimal-design", "open-source-journey"]
```

**📖 Full Guide:** [docs/BLOG_CONFIG.md](docs/BLOG_CONFIG.md)

### **📄 Resume Configuration (`config/resume.toml`)**

Create an interactive resume with v2.0 features:

```toml
# Personal information
[personal]
name = "Nishikanta Ray"
title = "Full-Stack Developer"
email = "your@email.com"
phone = "+1234567890"
location = "Your City, Country"
profile_image = "path/to/image.jpg"
summary = "Passionate developer with expertise in modern web technologies"

# Experience with @company mentions
[[experience]]
title = "Senior Full-Stack Developer"
company = "@TechCompany"  # Use @mention for enhanced styling
location = "City, Country"
start_date = "2022-01"
end_date = "Present"
description = "Led development of scalable web applications using React and Node.js"
technologies = ["React", "Node.js", "TypeScript", "AWS"]

# Education with institution links
[[education]]
degree = "Bachelor of Computer Science"
institution = "University Name"
institution_url = "https://university.edu"  # Enhanced with clickable links
location = "City, Country"
start_date = "2018-09"
end_date = "2022-05"
gpa = "3.8/4.0"
relevant_coursework = ["Data Structures", "Algorithms", "Web Development"]

# Skills with proficiency levels
[[skills]]
category = "Frontend"
technologies = ["React", "TypeScript", "Vue.js", "CSS3", "HTML5"]
proficiency = "Expert"
years_experience = 5

# Settings
[settings]
show_gpa = true
show_location = true
enable_share_button = true
show_technologies = true
enable_company_links = true     # v2.0: Enhanced company linking
enable_institution_links = true # v2.0: Clickable institution links
```

**📖 Full Guide:** [docs/RESUME_CONFIG.md](docs/RESUME_CONFIG.md)

### **🔗 Social Links Configuration (`config/social.toml`)**

Manage your social media presence:

```toml
# Display settings
[display]
show_text = false        # Icons only vs text + icons
show_tooltips = true     # Hover tooltips

# Social links
[[links]]
id = "github"
name = "GitHub"
url = "https://github.com/NishikantaRay"
icon = "fab fa-github"
enabled = true

[[links]]
id = "linkedin"
name = "LinkedIn"
url = "https://linkedin.com/in/NishikantaRay"
icon = "fab fa-linkedin"
enabled = true
```

**📖 Full Guide:** [docs/SOCIAL_CONFIG.md](docs/SOCIAL_CONFIG.md)

## 🎨 Customization Examples

### **v2.0 Professional Setup (Recommended)**
```toml
# Enhanced blog with all v2.0 features
[blog.settings]
enable_comments = true
enable_social_sharing = true
enable_search = true
enable_categories = true
enable_tags = true
enable_related_posts = true

# Resume with @mentions and institution links
[resume.settings]
enable_company_links = true
enable_institution_links = true
show_technologies = true

# Performance optimizations
[performance]
lazy_load_images = true
preload_critical_content = true
console_cleanup = true  # v2.0: Production console cleanup
```

### **Minimal Setup (Performance Focused)**
```toml
# Disable heavy features
[analytics]
enabled = false

[ui]
animations = false

[performance]
lazy_load_images = true
preload_critical_content = true
console_cleanup = true

[interactive]
project_filtering = false
search_functionality = false
```

### **Analytics-Heavy Setup**
```toml
[analytics]
enabled = true

[analytics.charts]
enabled = true
weekly_activity = true
project_distribution = true

[dashboard]
enabled = true

[dashboard.sections]
charts = true
statistics = true
recent_activity = true
```

### **Accessibility-First Setup**
```toml
[accessibility]
high_contrast_mode = true
focus_indicators = true
keyboard_navigation = true

[ui]
animations = false  # Reduce motion
smooth_scrolling = false

[performance]
preload_critical_content = true
```

## 🛠️ Development

### **Local Development**
```bash
# Install dependencies (optional)
npm install

# Start development server
npm run dev
# or
python3 -m http.server 8000
# or
npx serve .
```

### **Enable Debug Mode**
```toml
[development]
debug_mode = true           # Show debug information
performance_metrics = true # Performance timing
error_logging = true       # Log errors
console_cleanup = false    # v2.0: Disable for debugging
```

### **v2.0 Production Optimization**
```toml
[production]
console_cleanup = true      # Clean console output
error_handling = "silent"   # Silent error handling
cache_busting = true       # Cache busting for configs
performance_monitoring = true
```

### **Adding New Features**
1. **Add configuration option** in appropriate TOML file
2. **Update JavaScript** to respect the configuration
3. **Add CSS rules** for styling
4. **Document** in the corresponding guide

## 📖 Content Management

### **Adding Blog Posts**
1. Create markdown file in `content/`
2. Add post configuration to `config/blog.toml`:
```toml
[[posts]]
id = "my-new-post"
title = "My New Blog Post"
description = "Post description"
date = "2024-10-16"
content_file = "my-new-post.md"
tags = ["web", "development"]
```

### **Updating Projects**
1. Edit `content/projects.md` for markdown content
2. Or configure in `config/projects.toml` for dynamic content

### **Managing Resume**
Update `config/resume.toml` with your experience, skills, and achievements.

## 🚀 Deployment

### **Zero-Config Deployment**
Deploy to any static hosting service:

- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your GitHub repository  
- **GitHub Pages**: Enable in repository settings
- **Cloudflare Pages**: Connect repository
- **Any static host**: Upload files

### **Environment-Specific Configuration**
Create different configuration files for different environments:
```bash
config/
├── home.toml          # Production
├── home.dev.toml      # Development
└── home.staging.toml  # Staging
```

## 🔧 Troubleshooting

### **TOML Configuration Issues (v2.0 Improvements)**
1. **TOML Not Loading**: Check browser console for parsing errors
2. **Custom TOML Parser**: v2.0 includes built-in TOML parser fallback
3. **Cache Issues**: Files now include cache-busting parameters
4. **Multi-line Arrays**: v2.0 supports complex multi-line TOML structures

### **Configuration Not Loading**
1. Check browser console for TOML parsing errors
2. Verify TOML syntax using an online validator
3. Ensure configuration files exist in `config/` directory
4. Try hard refresh (Ctrl+Shift+R) to clear cache

### **Features Not Hiding**
1. Enable debug mode: `debug_mode = true`
2. Check browser console for configuration status
3. Clear browser cache and reload
4. Verify TOML file structure matches documentation

### **Content Not Displaying**
1. Verify markdown files exist in `content/` directory
2. Check file paths in configuration
3. Enable fallback content: `enable_fallback_content = true`
4. Check network tab for failed file requests

### **Blog System Issues**
1. **TOML Changes Not Reflected**: Clear browser cache
2. **Posts Not Loading**: Check content file paths in blog.toml
3. **Images Not Displaying**: Verify image URLs in post configuration
4. **Features Not Working**: Check settings section in blog.toml

## 🤝 Contributing

1. **Fork** the repository
2. **Create** a feature branch
3. **Add** configuration options for new features
4. **Update** documentation
5. **Submit** a pull request

## 🌐 Links

- **🔗 Live Demo:** [renderer.nishikanta.in](https://renderer.nishikanta.in/)
- **📚 Documentation:** [renderer.nishikanta.in/docs](https://renderer.nishikanta.in/docs)
- **💻 GitHub Repository:** [github.com/NishikantaRay/renderer](https://github.com/NishikantaRay/renderer)
- **🚀 Clone Command:** `git clone https://github.com/NishikantaRay/renderer.git`

## 📄 License

MIT License - Feel free to use and modify for your own portfolio!

---

**✨ Built with ❤️ by [Nishikanta Ray](https://github.com/NishikantaRay) • Made for developers who value simplicity and power**

*Start building your story today at [renderer.nishikanta.in](https://renderer.nishikanta.in/)* 🌟

## 🎯 Why This Portfolio?

### **v2.0 Advantages**
- ✅ **Enhanced TOML Support** - Robust parsing with smart fallbacks
- ✅ **Professional Styling** - @Company mentions and institutional links
- ✅ **Production Ready** - Console cleanup and performance optimizations
- ✅ **Better UX** - Enhanced URL support and improved navigation
- ✅ **Developer Friendly** - Advanced debugging and development tools

### **Core Advantages**
- ✅ **No Build Process** - Works immediately
- ✅ **No Framework Dependencies** - Pure vanilla code
- ✅ **Complete Customization** - Configure without coding
- ✅ **Fast Performance** - Minimal overhead
- ✅ **SEO Optimized** - Static HTML with proper meta tags
- ✅ **Accessible** - Built-in accessibility features
- ✅ **Mobile First** - Responsive design
- ✅ **Dark/Light Theme** - Automatic and manual switching

### **Perfect For**
- 👨‍💻 **Developers** who want a professional portfolio
- 🎨 **Designers** who need a clean showcase
- 📚 **Students** building their first portfolio
- 💼 **Professionals** who want easy content management
- 🚀 **Anyone** who values performance and simplicity
- 🏢 **Companies** looking for professional team pages

---

**🌟 Star this repository if you find it helpful!**

For detailed configuration guides, see the `docs/` directory.

Need help? Open an issue or check the troubleshooting section above.

## 📊 Changelog

### **Version 2.0 (Latest)**
- 🔧 **TOML-First Architecture**: Robust TOML parsing with custom fallback parser
- 🏢 **@Mention System**: Professional company mentions with enhanced styling  
- 🔗 **Enhanced URL Support**: Repository, demo, and documentation links
- 🎓 **Education System**: Dedicated education section with institution links
- ⚡ **Performance Optimized**: Console cleanup and production-ready features
- 🛠️ **Advanced Debugging**: Comprehensive debugging and development tools
- 🎨 **Professional Styling**: Enhanced CSS for company mentions and links
- 🔄 **Smart Caching**: Cache-busting for configuration files
- 📝 **Blog Enhancements**: Improved blog system with better TOML support

### **Previous Versions**
- v1.x: Initial release with basic TOML configuration
- v0.x: Beta versions with experimental features

---

**✨ Built with ❤️ by [Nishikanta Ray](https://github.com/NishikantaRay) • Made for developers who value simplicity and power**

*Start building your story today at [renderer.nishikanta.in](https://renderer.nishikanta.in/)* 🌟

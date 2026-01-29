# .dot

A beautiful Blazor WebAssembly website with an inspiring story about digital creativity.

## Summary

Creates a complete Blazor WebAssembly application deployable to GitHub Pages with:
- **Story Page** — "The Digital Garden", a beautiful narrative about a developer's journey
- **Interactive Counter** — Classic Blazor component demonstrating WebAssembly functionality  
- **Weather Display** — Sample data visualization with Bootstrap styling
- **GitHub Actions** — Automated CI/CD pipeline for seamless deployment
- **Pre-commit Hooks** — Code quality enforcement with trailing whitespace and file formatting

Supports local development with `dotnet run` and automatic GitHub Pages deployment on push.
Built with .NET 10, Bootstrap 5, and modern web standards.

## Features

- ✨ **Beautiful Story Page** with elegant typography and centered layout
- 🎯 **Interactive Components** demonstrating Blazor's capabilities
- 📱 **Responsive Design** with Bootstrap CSS framework
- 🚀 **GitHub Pages Ready** with automated deployment workflow
- 🔧 **Pre-commit Quality** ensuring clean, consistent code
- 🎨 **Professional Styling** with dark navbar and modern aesthetics

## Quick Start

```bash
# Clone and run locally
git clone https://github.com/bniladridas/.dot.git
cd .dot
dotnet run

# Visit http://localhost:5000
```

## Deployment

Automatically deploys to GitHub Pages on every push to `main`:
- **Live Site**: https://bniladridas.github.io/.dot/
- **Build Status**: GitHub Actions workflow handles compilation and deployment
- **Base Path**: Configured for GitHub Pages subdirectory hosting

## Project Structure

```
.dot/
├── Pages/
│   ├── Home.razor          # Welcome page
│   ├── Counter.razor       # Interactive counter
│   ├── Weather.razor       # Sample data display
│   └── Story.razor         # Beautiful story page
├── Layout/
│   ├── MainLayout.razor    # App shell
│   └── NavMenu.razor       # Navigation component
├── .github/workflows/
│   └── deploy.yml          # GitHub Actions deployment
└── .pre-commit-config.yaml # Code quality hooks
```

## Tech Stack

- **Frontend**: Blazor WebAssembly (.NET 10)
- **Styling**: Bootstrap 5 + Custom CSS
- **Deployment**: GitHub Pages + GitHub Actions
- **Quality**: Pre-commit hooks (v6.0.0)
- **Icons**: Bootstrap Icons

🤖 *Generated with Kiro CLI*

---

**Note**: A minimal Blazor WebAssembly application showcasing the power of C# in the browser, featuring an inspiring story about digital creativity and modern web development practices.

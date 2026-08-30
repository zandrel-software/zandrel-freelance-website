# Zandrel Freelance Website

<p align="center">
  <img
    src="Zandrel.Web/wwwroot/images/zandrel-social-preview.png"
    alt="Zandrel — Soluciones de software para tus ideas y proyectos"
    width="100%"
  />
</p>

<p align="center">
  Freelance software development website built with <strong>.NET 10</strong> and <strong>Blazor WebAssembly</strong>.
</p>

<p align="center">
  <a href="https://zandrel.com/">
    View Live Website
  </a>
</p>

---

## About Zandrel

Zandrel is a freelance software development website focused on turning ideas, needs and project requirements into practical software solutions.

The site presents services for people, professionals and projects that need software developed around a specific objective, with direct communication, clearly defined scope and solutions adapted to each project.

Current service areas include:

- Professional websites
- Custom software systems
- Process automation
- Applications and tools
- APIs and integrations
- Databases and dashboards
- Custom software projects

The public website is written in Spanish and is designed to keep the service proposition clear, concise and easy to understand without unnecessary technical complexity.

## Website Goals

The website is designed to communicate Zandrel's freelance software development services through a direct and professional experience.

Its main goals are to:

- Explain available software development services clearly
- Present a simple project-based working process
- Keep communication direct and personal
- Show that solutions are adapted to the real scope and needs of each project
- Present software development in accessible, non-technical language
- Provide a single, low-friction contact channel through WhatsApp
- Maintain a modern and professional visual identity
- Work consistently across desktop, laptop, tablet and mobile devices

## Tech Stack

| Area | Technology |
| --- | --- |
| Framework | .NET 10 |
| Frontend | Blazor WebAssembly |
| Language | C# |
| UI | Razor Components |
| Styling | Custom CSS |
| Hosting | GitHub Pages |
| CI/CD | GitHub Actions |
| Production Domain | zandrel.com |

The project intentionally avoids unnecessary dependencies and infrastructure.

It does not currently require:

- JavaScript frameworks
- CSS frameworks
- npm packages
- Authentication
- Backend APIs
- Server-side infrastructure
- Databases

The website is deployed as a standalone static Blazor WebAssembly application.

## Architecture

The solution contains a single Blazor WebAssembly project:

```text
zandrel-freelance-website/
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── Zandrel.Web/
│   ├── Components/
│   │   ├── Layout/
│   │   │   ├── SiteHeader.razor
│   │   │   ├── SiteHeader.razor.css
│   │   │   ├── SiteFooter.razor
│   │   │   └── SiteFooter.razor.css
│   │   │
│   │   └── Sections/
│   │       ├── HeroSection.razor
│   │       ├── HeroSection.razor.css
│   │       ├── ServicesSection.razor
│   │       ├── ServicesSection.razor.css
│   │       ├── ProcessSection.razor
│   │       ├── ProcessSection.razor.css
│   │       ├── AboutSection.razor
│   │       ├── AboutSection.razor.css
│   │       ├── ContactSection.razor
│   │       └── ContactSection.razor.css
│   │
│   ├── Layout/
│   │   ├── MainLayout.razor
│   │   └── MainLayout.razor.css
│   │
│   ├── Pages/
│   │   └── Home.razor
│   │
│   ├── wwwroot/
│   │   ├── css/
│   │   │   └── app.css
│   │   │
│   │   ├── images/
│   │   │   ├── brand/
│   │   │   └── zandrel-social-preview.png
│   │   │
│   │   ├── index.html
│   │   ├── robots.txt
│   │   └── sitemap.xml
│   │
│   ├── App.razor
│   ├── Program.cs
│   ├── _Imports.razor
│   └── Zandrel.Web.csproj
│
├── README.md
└── Zandrel.slnx
```

## Landing Page Structure

The current landing page follows this structure:

```text
Header
└── Hero
    └── Services
        └── Process
            └── About
                └── Contact
                    └── Footer
```

The experience is intentionally compact and focused on helping visitors understand:

1. What can be developed
2. How the project process works
3. What Zandrel is
4. How to start a conversation

## Services

The website currently presents five main service categories.

### Websites

Modern and responsive websites for ideas, services, projects, businesses and professional presence.

### Custom Systems

Software tools built around specific workflows, information management needs and operational requirements.

### Automation

Solutions focused on reducing repetitive work, connecting processes and improving efficiency.

### Applications and Tools

Applications, APIs, databases, integrations, dashboards and other software components developed according to project requirements.

### Custom Projects

Software projects that do not fit into a predefined category and require a tailored technical approach.

## Working Process

The site communicates a simple four-step process:

```text
1. Tell us what you need
2. Define the project
3. Develop the solution
4. Deliver the result
```

Each project is handled independently, with defined scope, direct communication and a solution adapted to its requirements.

Corrective fixes related to the originally agreed functionality can be handled after delivery, while new features, scope changes, redesigns, infrastructure and external services are considered separately.

## Contact

The website intentionally uses WhatsApp as its primary contact channel.

This avoids unnecessary forms and keeps the interaction direct.

Current project contact URL:

```text
https://wa.me/527751272647
```

The website uses a predefined message to provide context when a visitor starts a conversation from the site.

## Design System

The visual identity uses a warm, restrained palette designed to feel professional, approachable and distinct from a traditional corporate software website.

### Core Colors

| Token | Value |
| --- | --- |
| Cocoa | `#2F2A28` |
| Cacao | `#3B2A23` |
| Terracotta | `#E26A4A` |
| Coral | `#F59B7E` |
| Sand | `#F4E2C4` |
| Cream | `#FFF7ED` |
| Taupe | `#A99589` |
| Beige | `#EDE4D6` |

### Semantic Colors

| Usage | Value |
| --- | --- |
| Background | `#FFFAF4` |
| Alternate Background | `#FFF7ED` |
| Surface | `#FFFFFF` |
| Soft Surface | `#FFF3E9` |
| Primary Text | `#2F2A28` |
| Secondary Text | `#655851` |
| Muted Text | `#7B6C64` |
| Accent | `#E26A4A` |
| Strong Accent | `#B94732` |

The visual direction is intended to feel:

- Professional
- Direct
- Warm
- Modern
- Minimal
- Approachable
- Clear rather than visually overloaded

## Responsive Design

The website is designed for:

- Desktop monitors
- Laptops
- Tablets
- Mobile devices
- Small mobile viewports

Responsive behavior is implemented with custom CSS.

The layout includes:

- Responsive containers
- Adaptive section spacing
- Responsive typography
- Desktop and mobile navigation states
- Touch-friendly CTAs
- Simplified visual decoration on smaller screens
- Mobile-specific card layouts
- Reduced-motion support

## Accessibility

The project includes foundational accessibility considerations such as:

- Semantic headings and sections
- ARIA labels where appropriate
- Accessible navigation controls
- Keyboard-visible focus states
- Decorative content hidden from assistive technologies
- Reduced-motion support
- Appropriate image alternatives
- Semantic buttons and links

## Local Development

### Requirements

Install the .NET 10 SDK.

Verify the installation:

```powershell
dotnet --version
```

The installed version should be compatible with:

```text
10.0.x
```

### Clone the Repository

```powershell
git clone https://github.com/zandrel-software/zandrel-freelance-website.git
```

Navigate to the repository:

```powershell
cd zandrel-freelance-website
```

### Restore Dependencies

```powershell
dotnet restore ./Zandrel.Web/Zandrel.Web.csproj
```

### Run the Application

```powershell
dotnet run --project ./Zandrel.Web/Zandrel.Web.csproj
```

Alternatively, open:

```text
Zandrel.slnx
```

in Visual Studio and run `Zandrel.Web`.

## Production Build

Create a Release build with:

```powershell
dotnet publish ./Zandrel.Web/Zandrel.Web.csproj --configuration Release
```

The published output is a static Blazor WebAssembly application and does not require an ASP.NET Core backend.

## Deployment

The website is deployed automatically to GitHub Pages through GitHub Actions.

Production URL:

```text
https://zandrel.com/
```

GitHub Pages deployment:

```text
https://zandrel-software.github.io/zandrel-freelance-website/
```

The custom domain is configured through GitHub Pages and `zandrel.com` is the canonical public production URL.

The deployment workflow is located at:

```text
.github/workflows/deploy.yml
```

Every push to:

```text
main
```

triggers the deployment pipeline.

The workflow can also be executed manually through `workflow_dispatch`.

The deployment process:

1. Checks out the repository
2. Configures .NET 10
3. Reads the active GitHub Pages configuration
4. Restores dependencies
5. Publishes the Blazor WebAssembly application
6. Configures the correct production base path
7. Updates public deployment URLs when required
8. Creates the static hosting files
9. Uploads the GitHub Pages artifact
10. Deploys the site

## Dynamic Base Path Handling

The source application keeps:

```html
<base href="/" />
```

The deployment workflow reads GitHub Pages configuration through `actions/configure-pages`.

This allows the same source project to support both:

```text
https://zandrel-software.github.io/zandrel-freelance-website/
```

and:

```text
https://zandrel.com/
```

When deployed through the repository-specific GitHub Pages URL, the published artifact uses:

```html
<base href="/zandrel-freelance-website/" />
```

When deployed through the custom production domain, it uses:

```html
<base href="/" />
```

This prevents hardcoded deployment paths and keeps local development independent from hosting configuration.

## SEO and Social Sharing

The website includes:

- Page title
- Meta description
- Search engine indexing directives
- Canonical URL
- Open Graph metadata
- X / Twitter Card metadata
- Social sharing preview image
- `robots.txt`
- XML sitemap

The canonical production domain is:

```text
https://zandrel.com/
```

Public SEO and social-sharing references use this domain in the source project, including:

- Canonical URL
- `og:url`
- `og:image`
- `og:image:secure_url`
- `twitter:image`
- `robots.txt`
- `sitemap.xml`

The deployment workflow adapts these URLs automatically when the website is served through a repository-specific GitHub Pages path.

The social preview asset is located at:

```text
Zandrel.Web/wwwroot/images/zandrel-social-preview.png
```

## Custom Domain

The production domain is:

```text
https://zandrel.com/
```

The `www` hostname redirects correctly to the canonical apex domain:

```text
https://www.zandrel.com/
```

GitHub Pages remains the hosting platform while `zandrel.com` acts as the public production URL.

HTTPS is enforced through GitHub Pages.

## Blazor Static Assets

The project targets .NET 10 and uses fingerprinted static assets.

The Blazor startup script uses the .NET 10 fingerprint placeholder:

```html
<script src="_framework/blazor.webassembly#[.{fingerprint}].js"></script>
```

This allows the published application to reference the generated fingerprinted WebAssembly startup asset correctly.

## Brand Assets

Brand assets are stored in:

```text
Zandrel.Web/wwwroot/images/brand/
```

Current variants include:

```text
zandrel-logo-horizontal-transparent.png
zandrel-logo-horizontal-white.png
zandrel-logo-horizontal-black.png
zandrel-mark-transparent.png
zandrel-mark-white.png
zandrel-mark-black.png
```

The social preview image is stored separately at:

```text
Zandrel.Web/wwwroot/images/zandrel-social-preview.png
```

## Development Conventions

The project follows these conventions:

- Technical naming is written in English
- Public website content is written in Spanish
- C# nullable reference types are enabled
- Implicit usings are enabled
- Components use scoped CSS
- Shared design tokens are centralized in `app.css`
- Deployment paths are configured dynamically
- Public URLs use the canonical production domain in source
- Unnecessary dependencies are avoided
- Changes should remain focused and minimal
- Git history follows Conventional Commits

Examples:

```text
feat: add new website section
fix: align section navigation with sticky header
refactor: refine hero visual annotations
chore: update brand assets
ci: update github pages deployment
docs: add project documentation
```

## Repository

Organization:

```text
zandrel-software
```

Repository:

```text
zandrel-freelance-website
```

Production website:

```text
https://zandrel.com/
```

GitHub Pages project:

```text
https://zandrel-software.github.io/zandrel-freelance-website/
```

---

<p align="center">
  <strong>Zandrel</strong><br />
  Software a medida para ideas y proyectos.
</p>

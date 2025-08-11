# Professional Portfolio

A modern and responsive portfolio template to showcase your personal information, skills, and projects.

## Folder Structure

```
portfolio/
├── index.html       # Main portfolio page
├── styles.css       # CSS file for customizing the interface
├── images/          # Image folder (if needed)
└── README.md        # This instruction file
```

## How to Customize

### 1. Personal Information

In the `index.html` file, find the sections marked with `[ ]` and replace them with your information:

- `[Your Name]` - Your full name
- `[Job Title]` - Example: "Full-stack Developer", "Software Engineer"
- `[City, Country]` - Your current location
- `[Brief description about yourself, your passions, and career goals]` - A short introduction about yourself

### 2. Contact Information

Update the following with your contact details:
- `[your.email@example.com]` - Your email address
- `[+1234567890]` - Your phone number

### 3. Skills

In the "Skills" section, you can:
- Add new skills by adding `<span>Skill Name</span>` tags
- Remove unnecessary skills
- Modify existing skill names

### 4. Work Experience

In the "Work Experience" section:
- Each `.job` block represents a job position
- You can add multiple `.job` blocks if you have more experience
- Fill in the fields:
  - `[Job Position]`
  - `[Company Name]`
  - `[Employment Period]`
  - `[Job description and achievements]`

### 5. Education

In the "Education" section:
- Each `.degree` block represents a degree
- Add information to the fields:
  - `[Degree]`
  - `[University Name]`
  - `[Study Period]`

### 6. Featured Projects

In the "Featured Projects" section:
- Each `.project` block represents a project
- You can add more projects by adding `.project` blocks
- Fill in the fields:
  - `[Project Name]`
  - `[Brief project description]`
  - `[Link to project or GitHub]`

### 7. Connect With Me

In the "Connect With Me" section:
- Update links to your social media profiles
- You can add or remove social platforms

## Interface Customization

The `styles.css` file contains all the interface styling. You can:

1. **Change the main color**:
   - Find lines containing `#2563eb` (current blue color) and replace with your preferred color code

2. **Change profile picture**:
   - Replace the image file or update the `src` attribute of the `<img class="avatar">` tag

3. **Customize fonts**:
   - In the `body` section, change the `font-family` property value

4. **Change gradient effects**:
   - In the `.profile-header` section, modify the `background: linear-gradient(...)` value

## Responsive Design

The portfolio is designed to be responsive and automatically adapts to different screen sizes.

## License

MIT License
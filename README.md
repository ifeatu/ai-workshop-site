# Cognitive Sovereignty in the AI Age Workshop

A complete GitHub Pages site for a full-day AI workshop designed for Church of the Latter Rain Youth, focusing on building critical thinking skills for students, professionals, and life.

## Workshop Overview

This workshop teaches participants how to maintain cognitive sovereignty while leveraging AI as a tool rather than a crutch. Through five structured hours, participants learn to:

- Understand what makes human thinking irreplaceable
- Use AI strategically for growth, not dependency
- Develop critical evaluation skills for the information age
- Build AI-resistant human capabilities
- Create personal frameworks for AI use

## Site Structure

- **Homepage** (`index.md`) - Workshop overview and schedule
- **Hour 1** (`hour1.md`) - The AI Mirror: Foundation building
- **Hour 2** (`hour2.md`) - Smart Collaboration: Practical skills
- **Hour 3** (`hour3.md`) - Information vs Understanding: Critical thinking
- **Hour 4** (`hour4.md`) - Future-Proofing Your Capabilities: Strategic development
- **Hour 5** (`hour5.md`) - Your Personal AI Strategy: Integration
- **Resources** (`resources.md`) - Tools, templates, and continued learning

## Deployment Instructions

### Quick Start with GitHub Pages

1. Fork or download this repository
2. Go to your repository settings
3. Navigate to "Pages" in the left sidebar
4. Select "Deploy from a branch" as the source
5. Choose `main` branch and `/ (root)` folder
6. Click "Save"

Your site will be available at: `https://[username].github.io/[repository-name]`

### Local Development

To run the site locally:

```bash
# Install Jekyll (requires Ruby)
gem install bundler jekyll

# Navigate to site directory
cd ai-workshop-site

# Install dependencies
bundle install

# Serve the site locally
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`

## Customization

### Site Configuration

Edit `_config.yml` to customize:
- Site title and description
- Author information
- Navigation structure
- Theme settings

### Styling

The site uses a custom layout in `_layouts/default.html` with embedded CSS. Key style variables are defined in the `:root` CSS selector for easy customization:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    /* ... more variables */
}
```

### Content Adaptation

All workshop content is in Markdown files and can be easily adapted for different audiences:

- **For Students**: Focus on academic integrity and learning
- **For Professionals**: Emphasize competitive advantage and leadership
- **For Community Groups**: Highlight cultural preservation and collective wisdom

## Workshop Facilitation

### Materials Needed

- Computer/tablet access for participants
- Projector or screen for group activities
- Handout materials (available in Resources section)
- Flip chart paper and markers for group work

### Time Requirements

- **Total Time**: 5 hours
- **Suggested Schedule**: 
  - Hour 1: 60 minutes
  - Hour 2: 60 minutes
  - Break: 15 minutes
  - Hour 3: 60 minutes
  - Hour 4: 60 minutes
  - Hour 5: 60 minutes

### Group Size

- Optimal: 8-15 participants
- Maximum: 25 participants (with additional facilitators)
- Minimum: 3 participants for group dynamics

## Learning Outcomes

By the end of this workshop, participants will be able to:

1. Distinguish between AI assistance and AI dependence
2. Evaluate AI outputs using critical thinking frameworks
3. Articulate their unique value proposition in an AI world
4. Use AI strategically while maintaining intellectual ownership
5. Create and implement a personal AI-use strategy

## Contributing

To contribute improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

### Content Guidelines

- Keep language accessible and practical
- Include interactive exercises
- Provide real-world examples
- Maintain focus on empowerment, not fear
- Test activities with diverse groups

## License

This work is licensed under Creative Commons Attribution-ShareAlike 4.0 International License. You are free to:

- Share: copy and redistribute the material
- Adapt: remix, transform, and build upon the material

Under the following terms:
- Attribution: provide appropriate credit
- ShareAlike: distribute under the same license

## Support

For questions about workshop facilitation or technical issues:

- Review the Resources page for facilitation guides
- Check the Issues section for common problems
- Share success stories and adaptations

---

*Building critical thinking skills for the AI age, one workshop at a time.*
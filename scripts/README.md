# Scripts Directory

## 🚗 Automotive Website Redesign Script

### Usage

Run the script to generate a comprehensive Cursor AI prompt for redesigning automotive websites:

```bash
npm run generate-automotive-redesign
```

### What it does

1. **Scans Available Images**: Automatically detects all images in `public/images/` directory with file sizes
2. **Collects Business Information**: Prompts for name, address, phone, email, specialties, hours
3. **Gathers Reference Links**: Google Business, Yelp, Facebook, and other business profiles
4. **Brand & Design Details**: Colors, personality, target audience
5. **Customer Reviews**: Option to use template reviews or paste actual ones
6. **Generates Comprehensive Cursor AI Prompt**: Creates detailed instructions for complete website redesign

### Output

The script generates `cursor-automotive-redesign-prompt.md` containing:

- Complete business context and branding guidelines
- Page-by-page redesign checklist (Home, Services, Reviews, Contact, Careers, Blog)
- LocalConfig.ts update requirements
- Visual consistency and functionality verification
- SEO and local business optimization
- Mobile and emergency service considerations

### Key Features

- **Extremely Detailed Analysis**: Covers every page and section
- **LocalConfig.ts Focused**: Only uses values accessible in configuration
- **Automotive Industry Specific**: Tailored for tire shops, auto repair, mobile mechanics
- **Customer Review Integration**: Uses actual business personality and tone
- **Professional Standards**: Ensures trustworthy, service-focused presentation

---

## 🔧 Fix Hardcoded Images Script

### Usage

Run the script to generate a Cursor AI prompt for fixing hardcoded image references:

```bash
npm run fix-images
```

### What it does

1. **Scans Available Images**: Automatically detects all images in `public/images/` directory
2. **Collects Business Context**: Prompts for company name, website type, location
3. **Gathers Reference Links**: Allows you to add relevant business links
4. **Creates Image Usage Guidelines**: Asks for preferences on how images should be used
5. **Generates Cursor AI Prompt**: Creates a comprehensive markdown file with detailed instructions

### Output

The script generates `cursor-fix-images-prompt.md` containing:

- Complete business context
- List of available images
- Step-by-step implementation instructions
- Success criteria and checklist
- Technical requirements for fixing hardcoded images

### Benefits

- **Zero 404 Errors**: Eliminates missing image references
- **Configuration-Driven**: Images controlled by config files, not hardcoded CSS
- **Automatic Fallbacks**: Graceful handling when images aren't configured
- **Professional Results**: Ensures clean, maintainable code

### Example Use Case

Perfect for fixing websites that have hardcoded image paths in CSS files that cause 404 errors, especially when converting template sites to custom business websites.

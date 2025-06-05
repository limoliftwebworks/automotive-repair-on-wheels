# Davis Tree Service - Employee Setup

## 🔗 Essential Links

- **Config Editor**: http://localhost:3000/config-editor?section=infoBar
- **Local Config File**: `src/config/localConfig.ts`
- **Live Site**: http://localhost:3000
- **Color Hex Finder**: https://www.color-hex.com/color-palette/1294
- **Backup Delete Script**: node scripts/fix-config-types.js
- **Automation Copy Script**: ./setup-new-project.sh
- **NPM Script**: npm run generate-cursor-prompt

## 📋 Setup Instructions

1. **Install Dependencies**

   ```bash
   npm install
   ```

2. **Start Development Server**

   ```bash
   npm run dev
   ```

3. **Open Browser**
   - Navigate to: http://localhost:3000

## 🎨 Editing Site Content

**Use the Config Editor**: http://localhost:3000/config-editor

- Make changes in any section
- Press `Ctrl+S` to save
- Or click "Save Changes" button
- Page stays on your current section after saving

## 🤝 Team Collaboration

**Push Your Changes**:

```bash
 push in github desktop
```

**Get Partner's Changes**:

```bash
git pull origin julien
```

**First Time Setup**:

```bash
./collaborate.sh setup
```

## 🛠️ File Structure

- `src/config/localConfig.ts` - Main site configuration
- `src/app/config-editor/` - Visual config editor
- `collaborate.sh` - Team collaboration script

## ⚠️ Important Notes

- Always use `Ctrl+S` in config editor (no auto-save)
- Run `./collaborate.sh pull` before starting work
- Run `./collaborate.sh push` when finished
- Config editor URL: http://localhost:3000/config-editor

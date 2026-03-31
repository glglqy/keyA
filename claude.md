# Claude Configuration for KeyA Project

## Git Configuration

### Remote Repository
- **Primary Remote**: `https://github.com/cajbkaad/keyA.git`
- **Default Branch**: `master`

### Commit Guidelines
- Always verify remote is set to `https://github.com/cajbkaad/keyA.git` before pushing
- Use descriptive commit messages that explain the purpose of changes
- Include the relevant file paths in commit messages when appropriate

### Push Instructions
1. Ensure all changes are staged (`git add .`)
2. Commit with a clear message (`git commit -m "Description of changes"`)
3. Push to the primary remote: `git push origin master`
4. If using `-u` flag for first push: `git push -u origin master`

## Project-Specific Rules

### Code Style
- Maintain black and white theme (#111111 background, #ffffff text)
- Use responsive design patterns
- Keep image and text layouts non-overlapping

### File Organization
- HTML: `index.html`
- CSS: `style.css`
- Images: Reference from `logo/` directory within the project
- Documentation: Keep in root directory

### Deployment Notes
- All pushes should go to the specified GitHub repository
- Verify that images are correctly referenced after pushes
- Test responsive behavior across device sizes
# Lab Assignment - XML & JSON

**Student:** Deng Yifan  
**Student ID:** 25014690

---

## Part 1: XML Lab - Book Catalogue

### Files
- `book.xml` - Book catalogue XML document
- `index.html` - HTML page displaying the XML data

### XML Structure
Each book has:
- `id` attribute (e.g., id="1")
- `title` child element
- `author` child element  
- `price` child element

### Validation
XML has been validated and is well-formed.

---

## Part 2: JSON Lab - User Profiles

### Files
- `userProfiles.json` - User profiles JSON document
- `users.html` - HTML page displaying the JSON data

### JSON Structure
Each user profile contains:
- `firstName`, `lastName`, `email`, `dateOfBirth`
- `address`: `street`, `city`, `state`, `zipCode`
- `preferences`: `theme`, `language`, `notifications`, `subscription`

### Extended Features
- Added `address` field to each user profile
- Added `subscription` field in preferences (newsletter subscription)
- Contains 3 user profiles with unique details

### Validation
JSON has been validated and is well-formed.

---

## GitHub Pages Deployment

To publish on GitHub Pages:
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings → Pages → Select branch as `main`
4. Your site will be available at: `https://<username>.github.io/<repo-name>/`

- Book Catalogue: `https://<username>.github.io/<repo-name>/index.html`
- User Profiles: `https://<username>.github.io/<repo-name>/users.html`

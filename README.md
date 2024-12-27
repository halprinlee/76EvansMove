# 76 Evans Move

Web based checklists for Kevin & Emily Move.

## Features

- ✓ Interactive checklist with categories
- ✓ Automatic progress tracking
- ✓ Local storage for progress persistence
- ✓ Email export functionality
- ✓ Responsive design
- ✓ No external dependencies

## Code Structure

```plaintext
index.html                 # Single file application containing all code
├── CSS                    # Styles section in <head>
│   ├── Variables         # CSS custom properties
│   ├── Base styles       # General styling
│   ├── Components        # Specific component styles
│   └── Media queries     # Responsive design rules
│
├── HTML                  # Main content structure
│   ├── Container        # Main wrapper
│   ├── Card             # Content card
│   └── Checklist        # Dynamic checklist items
│
└── JavaScript           # Script section
    ├── Data            # Categories and items
    ├── State           # Checked items tracking
    ├── UI Updates      # DOM manipulation
    └── Export          # Save/Email functions
```

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/halprinlee/76EvansMove.git
```

2. Open `index.html` in a web browser or deploy to GitHub Pages:
   - Go to repository Settings
   - Navigate to Pages section
   - Select main branch
   - Save to enable GitHub Pages

## Code Overview

### HTML Structure
```html
<!DOCTYPE html>
<html>
<head>
    <!-- Fonts and Styles -->
</head>
<body>
    <div class="container">
        <div class="card">
            <!-- Dynamic content -->
        </div>
    </div>
</body>
</html>
```

### CSS Components
```css
:root {
    --primary-color: #4F46E5;
    /* Other variables */
}

/* Component examples */
.card {
    background: var(--card-background);
    border-radius: 1rem;
    /* Other styles */
}
```

### JavaScript Functions
```javascript
// Data structure
const categories = {
    'Government & Official': [
        'Ontario Driver\'s License/Photo ID',
        // Other items
    ],
    // Other categories
};

// Core functions
function createChecklist() {
    // Renders checklist items
}

function updateTotalProgress() {
    // Calculates and updates progress
}

function emailProgress() {
    // Handles email export
}
```

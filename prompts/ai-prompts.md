# AI Prompts for Notion App Features

Below are a few example prompts I would give to Copilot or Cursor to help generate code for key parts of the Notion app. Each one is based on a real feature and includes the tech I’d use and what data it should work with.

---

### 1. Page Editor (Text Blocks)

**Tech Stack:** Flutter + Firebase  
**Data Model:** Each block is stored with fields like `id`, `type`, `content`, and `order`.

**Prompt:**  
“Create a screen in Flutter that displays a vertical list of text blocks. Each one should be editable. When the user presses Enter, a new block appears below. Blocks should be saved to Firestore using the page ID as the parent document.”

---

### 2. Sidebar Navigation

**Tech Stack:** React Native + Supabase  
**Data Model:** Pages have `id`, `title`, `parent_id`, and `workspace_id`.

**Prompt:**  
“Build a collapsible sidebar that shows a nested list of pages. Each item can be expanded to show subpages. When a page is clicked, navigate to that page’s content. The list should come from Supabase and follow the parent-child structure.”

---

### 3. Sharing a Page

**Tech Stack:** Flutter + Firebase  
**Data Model:** Each page document includes a `sharedWith` array that holds user IDs and access levels.

**Prompt:**  
“Add a feature to let users share a page by typing someone’s email. Look that email up in Firebase Auth or Firestore. If it exists, add their user ID to the page’s `sharedWith` list along with either ‘view’ or ‘edit’ permission.”

---

### 4. Login with Magic Link (Bonus)

**Tech Stack:** React Native + Supabase

**Prompt:**  
“Make a simple login screen where users type in their email and press a button. Use Supabase to send a passwordless login link to their email address.”


# Django_Blog_Platform

## Working Flow

### 1. User Registration / Login
- User visits the website.
- Can Register / Login using:
  - Email & Password
  - Secure Django Authentication System

| Action | Result |
|:-----------------------------|:----------------------------------------------|
| User enters valid credentials | Redirect to Homepage |
| User enters invalid details | Show error message (Incorrect password, Required fields missing) |

---

### 2. Homepage Opens
- User will see a clean, responsive blog homepage.
- Homepage contains multiple dynamic sections and layouts:

| Section | Description |
|:----------------------|:-------------------------------------------------------------|
| **Latest Posts** | Shows latest blog posts with title, image & short description |
| **Categories** | Filter posts by category or tag |
| **Featured Posts** | Highlighted or trending recommended posts |
| **Search** | Search blogs by title, keywords, or tags |
| **Quick Actions** | Create Post, View Profile, Logout options |

---

### 3. User Creates a Blog Post
- User clicks **Create Post**.
- User fills the blog form:

| Field | Description |
|:-------------|:-------------------------------------------|
| Title | Blog post title |
| Content | Main rich-text content |
| Image | Upload featured image |
| Tags | Add relevant tags |

- Validations:
  - Title is required  
  - Content is required  
  - Minimum length validation  
  - Image format/type check  

---

### 4. Blog Post View
- When user opens a specific blog:
  - Title  
  - Author  
  - Published Date  
  - Featured Image  
  - Full Blog Content  
  - Tags  

- Additional Features:
  - Related posts  
  - Estimated reading time  
  - Share button  

---

### 5. Comments Section
- Users can:
  - Add comments  
  - Edit their comments  
  - Delete their comments  
  - View all comments under a post  

| Action | Result |
|:----------------------|:--------------------------------------------|
| User adds a comment | Comment displayed below the post |
| User leaves empty comment | Validation message shown |

---

### 6. User Profile
- User can:
  - View their authored posts  
  - Edit posts  
  - Delete posts  
  - Update profile details  

---

### 7. Admin Dashboard
- Admin manages the full blog system.

| Admin Feature | Description |
|:----------------------|:------------------------------------------------|
| **Manage Posts** | Approve, edit, or delete any blog |
| **Manage Users** | Add, edit, or remove users |
| **Manage Comments** | Remove or control user comments |
| **Manage Categories** | Add, delete, or modify tags & categories |

---

### 8. End

---

## Development Status

### Dynamic Features

| Section | Description | Status |
|:---------------------|:-----------------------------------------------|:---------:|
| **User Authentication** | Login, Signup, Logout, Validation | ✔ Completed |
| **Homepage Layout** | Latest posts, featured posts, search bar | ✔ Completed |
| **Create/Edit Post** | User blog creation with validation | ✔ Completed |
| **Post Detail Page** | Full blog view with tags & related posts | ✔ Completed |
| **Comments System** | Add, edit, delete comments | ✔ Completed |
| **Categories & Tags** | Sorting & filtering blogs | 🔄 In Progress |
| **User Profile** | Manage posts & account | 🔄 In Progress |
| **Admin Dashboard** | Manage users, posts, comments | 🔄 In Progress |
| **AI Assistant (Optional)** | Auto-generate tags or summaries | ❌ Not Started |

---

## Frontend Development Files
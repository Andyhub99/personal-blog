# personal-blog
### Working Flow

1. User Registration / Login
   - User visits the website.
   - Can Register / Login via:
     • Email & Password  
     • Secured authentication system  
   - If login successful → redirected to Homepage  
   - If login fails → Show validation messages (wrong password, fields required, etc.)

2. Homepage Opens
   • User will see a clean and responsive homepage  
   • Homepage contains different options, sections, layouts:

   Section  
   Description  
   Latest Posts  
   Shows latest blog posts with image, title, short description  
   Categories / Tags  
   Filter blogs by tags or categories  
   Featured Posts  
   Highlighted blogs selected by admin  
   Search  
   Search blog posts by title or keywords  
   Quick Actions  
   Create Post, View Profile, Logout

3. User Creates a Blog Post
   • User can click:
     
     Option  
     Action  
     Create Post  
     Opens form to write a new blog  
     Edit Post  
     Update old post  
     Delete Post  
     Remove existing post  

   • Form Validations:
     - Title required  
     - Content required  
     - Image upload validation  
     - Minimum content length check  

4. Blog Post View
   • Full blog details open:
     - Title  
     - Author  
     - Date  
     - Image  
     - Full content  
     - Tags  

   • Also shows:
     - Related posts  
     - Reading time  
     - Share options  

5. Comments Section
   • Users can:
     - Add comments  
     - Edit or delete their own comments  
     - View all comments under blog  
   • Validations: no empty comments

6. User Profile
   • User can see:
     - Their posts  
     - Drafts  
     - Update profile  
     - Edit/Delete posts  

7. Admin Panel
   • Admin receives all posts  
   • Admin can:
     - Approve / Decline posts  
     - Manage users  
     - Manage comments  
     - Manage tags & categories  

8. End

### Development Status

Dynamic Features  
Section  
Description  
Status  

User Authentication  
Login, Signup, logout, validation  
Completed  

Homepage Layout  
Latest posts, featured posts, search bar  
Completed  

Create / Edit Posts  
Form validations, image upload  
Completed  

View Post  
Full page view with comments  
Completed  

Comments System  
Add, edit, delete comment  
Completed  

Categories & Tags  
Sorting & filtering blogs  
In Progress  

User Profile  
Manage posts & profile  
In Progress  

Admin Dashboard  
Post approval, management  
In Progress  

AI Assistant  
Suggest tags or summaries  
Not Started

### Frontend Development
templates/  
home.html  
login.html  
register.html  
post_create.html  
post_detail.html  
profile.html  
base.html  

static/  
css/style.css  
js/script.js  
images/
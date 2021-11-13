# **Sprint 1: Basic Auth & Profiles**

## **A user should be able to:**

1. Navigate to "/" and see a basic splash page with:
- The name of the website.
- Links to "Log In" and "Sign Up".
1. Sign up for an account.
2. Log in to their account if they already have one.
3. Be redirected to their public profile page after logging in.
4. On their public profile page, see their name, the current city they have set in their profile, and their join date.
5. See the site-wide header on every page with:
- A link to "Log Out" if they're logged in.
- Links to "Log In" and "Sign Up" if they're logged out.
1. Update their profile by making changes to their name and/or current city.
2. See the titles of all the posts they've contributed (start with pre-seeded data).
3. Click on the title of one of their posts and be redirected to a "show" page for that post.
4. View post "show" pages with title, author, and content.

<aside>
💲 **Bonuses**

</aside>

**A user should be able to:**

1. See a "default" profile photo on their profile page before adding their own photo.
2. Update their profile photo (consider using Paperclip or Uploadcare).
3. See their profile photo next to their posts.
4. Receive a welcome email after creating an account.

---

# **Sprint 2: CRUD**

## **A user should be able to:**

1. View the "San Francisco" page (at "/cities/1") including:
- The site-wide header.
- The name of the city.
- An iconic photo of the city.
1. View a list of posts on the San Francisco page:
- Sorted by newest first.
- With the post titles linked to the individual post "show" pages.
1. Use an "Add New Post" button on the San Francisco city page to pull up the new post form.
2. Create a new post for San Francisco.
3. Click "Edit" on ANY individual post, and be redirected to the edit form.
4. Click "delete" on ANY individual post, then:
- See a pop-up that says: "Are you sure you want to delete #{title}?"
- If the user confirms, delete the post.

<aside>
💲 **Bonuses**

</aside>

### **A user should be able to:**

1. Visit city pages via pretty urls, like "/cities/san-francisco".
2. Visit user profile pages via pretty urls, like "/users/james".
3. On a city's page:
- See post content truncated to 1000 characters max, with a link to view more.
- See a relative published date, e.g. "2 days ago".
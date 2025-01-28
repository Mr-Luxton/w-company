# Auth0 Authentication Integration

This project demonstrates how to integrate Auth0 for user authentication in a simple static website hosted on GitHub Pages.

## Steps to Set Up:

1. **Sign up for Auth0**: [Auth0](https://auth0.com/).
2. **Create a new application** in Auth0 (Regular Web Application).
3. **Configure your application**:
   - Set **Allowed Callback URLs** to your GitHub Pages URL (e.g., `https://your-username.github.io`).
   - Set **Allowed Logout URLs** and **Allowed Web Origins** to your GitHub Pages URL as well.
4. **Replace placeholders** in `index.html`:
   - Replace `'YOUR_AUTH0_DOMAIN'` with your Auth0 domain (e.g., `dev-abc123.auth0.com`).
   - Replace `'YOUR_AUTH0_CLIENT_ID'` with your Auth0 Client ID.
5. **Deploy on GitHub Pages**:
   - Commit your changes to the repository.
   - Go to **Settings** in your GitHub repository and set up GitHub Pages under the **GitHub Pages** section.
6. **Test**: After deployment, open the website and test the login/logout functionality.

## Features:

- Auth0 login.
- Simple user greeting after login.
- Logout functionality.

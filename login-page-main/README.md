# Modern Login & Sign Up Page

A beautiful, modern login and sign up system built with HTML, CSS, and JavaScript. This project features a smooth UI, dark/light mode, password strength meter, social login buttons, and more.

## Features

- Responsive, modern design with animated gradient backgrounds
- Sign Up and Sign In forms with:
	- Full Name, Phone Number, Email, Password, Re-enter Password fields
	- Show/Hide password toggle
	- Password strength meter (Weak/Medium/Strong with colors)
	- Input validation (email format, phone = 10 digits, password match)
- Dark/Light mode toggle button (top right corner)
- Social login buttons (Google, GitHub; demo only)
- Custom animated cursor
- Option to change the background image by uploading your own

## File Structure

```
login-page-main/
	README.md
	login page/
		index.html         # Main login/sign up page
		signup.html        # Standalone sign up page (optional)
		style.css          # Styles for all pages
		script.js          # Main JavaScript logic
		background-changer.js # Script for background image upload/adjust
		background-uploader.html # Standalone background uploader demo
```

## Getting Started

1. **Clone or Download** this repository.
2. Open `login-page-main/login page/index.html` in your browser.
3. Use the Sign Up form to create a new account (data is stored in your browser's localStorage).
4. Use the Sign In form to log in.
5. Try toggling dark/light mode, uploading a custom background, and using the social login buttons (demo only).

## Screenshots

![Sign Up Form Screenshot](screenshot-signup.png)
![Dark Mode Screenshot](screenshot-darkmode.png)

## Customization

- **Change Background:** Use the button in the top right to upload and adjust a custom background image.
- **Dark/Light Mode:** Click the moon/sun icon in the top right to toggle modes.
- **Social Logins:** The Google and GitHub buttons are for demo purposes. You can integrate real OAuth flows as needed.

## Credits

- UI inspired by modern web design trends
- Icons from [SVGRepo](https://www.svgrepo.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)

## License

This project is open source and free to use for learning and personal projects.

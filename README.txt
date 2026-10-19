DEEPA'S PORTFOLIO

HOW TO OPEN:
1. Extract this ZIP file.
2. Open the extracted folder.
3. Double-click index.html.
4. The portfolio opens directly in your web browser. No terminal or server is needed.

FILES:
- index.html : webpage content
- style.css  : webpage design

BEFORE SUBMITTING:
- Replace "Add your college name" with your actual college name.
- Replace the contact placeholders with your real links/details.
- The circle with the letter D is a profile placeholder. If you want to use a photo,
  put your image in this folder as profile.jpg, then replace:
      <div class="avatar" aria-label="Profile photo placeholder">D</div>
  with:
      <img class="profile-photo" src="profile.jpg" alt="Deepa's profile photo">
  and add this CSS:
      .profile-photo {
        width: 120px;
        height: 120px;
        object-fit: cover;
        border-radius: 50%;
        margin-bottom: 14px;
      }

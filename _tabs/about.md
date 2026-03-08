---
# the default layout is 'page'
icon: fas fa-info-circle
order: 1
---

<div class="profile-photo-container">
  <img src="assets/images/yosemite.jpeg" alt="Profile photo" class="profile-photo" />
</div>

A technical writer and editor with a PhD in English and practical experience creating, editing, and structuring developer and end-user documentation. Specializes in transforming complex technical information into clear, concise, and user-focused content. Applies UX writing and content design principles to ensure documentation is intuitive, well-organized, and accessible to both technical and non-technical audiences.

<style>
.profile-photo-container {
  width: 300px;
  height: 300px;
  margin: 0 auto 30px;
  border-radius: 50%;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  flex-shrink: 0;
  -webkit-mask-image: radial-gradient(circle, black 99%, transparent 100%);
  mask-image: radial-gradient(circle, black 99%, transparent 100%);
}

.profile-photo {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
  border-radius: 50%;
  -webkit-transform: translateZ(0);
  transform: translateZ(0);
  backface-visibility: hidden;
  -webkit-backface-visibility: hidden;
}

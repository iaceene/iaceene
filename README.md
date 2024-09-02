<!-- Container for GIFs -->
<div align="center" style="display: flex; justify-content: center; gap: 10px; flex-wrap: wrap;">
    <!-- Portrait GIFs -->
    <img src="https://media.giphy.com/media/scZPhLqaVOM1qG4lT9/giphy.gif" width="169" height="380" alt="GIF" class="gif-portrait">
    <!-- Landscape GIF -->
    <img src="https://media.giphy.com/media/MDJ9IbxxvDUQM/giphy.gif" width="380" height="169" alt="GIF" class="gif-landscape">
    <!-- Portrait GIFs -->
    <img src="https://media.giphy.com/media/gEKz4VLX7fQlsl8SFE/giphy.gif" width="169" height="380" alt="GIF" class="gif-portrait">
</div>

<!-- Container for Social Media Icons -->
<div align="center" style="display: flex; justify-content: center; gap: 20px; margin-top: 10px;">
    <a href="https://www.instagram.com/yassine.ajagrou" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram" width="50" height="50">
    </a>
    <a href="https://www.facebook.com/yassine.ajagrou.0" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b8/2021_Facebook_icon.svg/512px-2021_Facebook_icon.svg.png?20220821121039" alt="Facebook" width="50" height="50">
    </a>
</div>

<!-- Responsive Styling for Smaller Screens -->
<style>
    .gif-portrait {
        display: inline-block;
    }

    .gif-landscape {
        display: inline-block;
    }

    @media (max-width: 768px) {
        .gif-portrait {
            display: none;
        }
        
        .gif-landscape {
            display: inline-block;
        }
    }
</style>

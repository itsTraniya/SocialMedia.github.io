cd /path/to/your/repo  # Navigate to your repository folder
mkdir images           # Create an 'images' folder (or any folder name you prefer)
mv /path/to/downloaded/image.png ./images/  # Move your image into the 'images' folder
git add images/*
git commit -m "Add images to repository"
git push origin main  # If you're working with the 'main' branch, otherwise replace 'main' with your branch name


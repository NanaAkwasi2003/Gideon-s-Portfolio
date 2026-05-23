To complete the file uploads (Resume.pdf and icon.jpeg), please run the following commands in your terminal:

From your Desktop directory, run:
```bash
# Copy Resume.pdf to repo
cp Resume.pdf c:\Users\oppon\OneDrive\Desktop\portfolio-website\cv.pdf

# Copy icon.jpeg to repo
cp icon.jpeg c:\Users\oppon\OneDrive\Desktop\portfolio-website\logo-icon.png

# Then commit and push
cd c:\Users\oppon\OneDrive\Desktop\portfolio-website
git add cv.pdf logo-icon.png
git commit -m "Add Resume PDF and logo icon"
git push origin main
```

Alternatively, you can manually copy these files to your local repo and commit them.
# Formula 1 Data Science Project

A comprehensive analysis of Formula 1 racing data using the FastF1 API, exploring lap times, tire strategies, driver performance, and race dynamics across the 2024 season.

## 🚀 Deploy to Vercel

### Method 1: Deploy via Vercel CLI (Recommended)

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. **Navigate to the project directory**:
   ```bash
   cd f1-project-website
   ```

3. **Login to Vercel**:
   ```bash
   vercel login
   ```

4. **Deploy**:
   ```bash
   vercel
   ```
   
   Follow the prompts:
   - Set up and deploy? **Y**
   - Which scope? Select your account
   - Link to existing project? **N**
   - What's your project's name? **f1-data-science** (or your preferred name)
   - In which directory is your code located? **.**
   - Want to override the settings? **N**

5. **Production deployment**:
   ```bash
   vercel --prod
   ```

### Method 2: Deploy via Vercel Website

1. **Create a GitHub repository**:
   - Go to [GitHub](https://github.com) and create a new repository
   - Upload all files from the `f1-project-website` folder

2. **Connect to Vercel**:
   - Go to [Vercel](https://vercel.com)
   - Click "Add New Project"
   - Import your GitHub repository
   - Click "Deploy"

3. **Your site will be live** at: `https://your-project-name.vercel.app`

### Method 3: Deploy via Drag & Drop

1. Go to [Vercel](https://vercel.com)
2. Click "Add New Project"
3. Drag and drop the entire `f1-project-website` folder
4. Click "Deploy"

## 📁 Project Structure

```
f1-project-website/
├── index.html          # Main website file
├── vercel.json         # Vercel configuration
└── README.md           # This file
```

## 🔧 Local Development

Simply open `index.html` in your web browser to view the site locally.

## 📊 Adding Your Visualizations

Replace the placeholder text in the visualization sections with your actual images:

```html
<!-- Change this: -->
<div class="viz-placeholder">[Add your visualization here]</div>

<!-- To this: -->
<img src="path/to/your/image.png" alt="Visualization description">
```

You can:
1. Upload images to the same directory
2. Use a CDN or image hosting service
3. Use relative paths like `./images/viz1.png`

## 🌐 After Deployment

Your website will be accessible at:
- **Vercel URL**: `https://your-project-name.vercel.app`
- You can add a custom domain in Vercel settings

## 📝 Next Steps

1. Add your visualization images
2. Update the conclusions section after completing your analysis
3. Consider adding:
   - A favicon
   - Open Graph meta tags for social sharing
   - Google Analytics (if needed)

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- FastF1 API for data collection

## 📄 License

This project is for educational purposes.

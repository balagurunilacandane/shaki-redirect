# Shaki App - Deep Link Redirect

This is a GitHub Pages site that redirects users to the Shaki mobile app using deep links.

## How it works

1. User clicks a link like: `https://yourusername.github.io/shaki-redirect/?productId=123`
2. The page automatically redirects to: `shaki://product/123`
3. If the app is installed, it opens the product details
4. If the app is not installed, user can download it from Play Store

## Usage

Replace `yourusername` and `shaki-redirect` with your actual GitHub username and repository name.

### Test URLs:
- Product 1: `https://yourusername.github.io/shaki-redirect/?productId=1`
- Product 2: `https://yourusername.github.io/shaki-redirect/?productId=2`
- Product 123: `https://yourusername.github.io/shaki-redirect/?productId=123`

## Setup

1. Create a new GitHub repository named `shaki-redirect`
2. Upload these files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

Your site will be available at: `https://yourusername.github.io/shaki-redirect/` 
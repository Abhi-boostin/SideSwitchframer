# Sideswitch Framer Template

A modern AI agency website template built with Framer.

## Netlify Deployment

This project is configured for easy deployment on Netlify:

1. **Connect your repository** to Netlify
2. **Build settings**:
   - Build command: `echo 'No build step required'`
   - Publish directory: `.` (root directory)
3. **Deploy** - Netlify will automatically deploy your site

### Manual Deployment

You can also deploy manually by dragging and dropping the project folder to Netlify's deploy interface.

### Configuration Files

- `netlify.toml` - Netlify configuration for build settings and redirects
- `public/_redirects` - Fallback redirects for SPA routing

The site will be available at your Netlify subdomain (e.g., `your-site-name.netlify.app`).

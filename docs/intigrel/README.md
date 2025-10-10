# Intigrel CMS Documentation

## Table of Contents
1. [Getting Started](#getting-started)
2. [Dashboard Overview](#dashboard-overview)
3. [Content Management](#content-management)
4. [Services Management](#services-management)
5. [Layout Management](#layout-management)
6. [Settings](#settings)
7. [Best Practices](#best-practices)
8. [Troubleshooting](#troubleshooting)

---

## Getting Started

### Accessing the CMS

1. Navigate to: **https://intigrel.in/admin**
2. Log in with your admin credentials
3. You'll be taken to the main dashboard

### Navigation Structure

The CMS is organized into four main groups:

- **Manage Content** - Solutions, Tech Stack, and Careers
- **Services Management** - Service Sectors and Services
- **Manage Layouts** - Page Sections (Advanced)
- **Settings** - Locations and other configurations

---

## Dashboard Overview

### Key Features

- **Quick Navigation** - Use the sidebar to access different sections
- **Badge Counters** - Each menu item shows the total count of records
- **Search** - Use the search bar in tables to find specific items
- **Filters** - Filter content by status, type, or other criteria
- **Bulk Actions** - Select multiple items to perform actions at once

---

## Content Management

### Solutions (Blog/Case Studies)

Solutions are displayed on your website's insights/solutions pages.

#### Creating a Solution

1. Go to **Manage Content → Solutions**
2. Click **Create** button
3. Fill in the required fields:

   **Basic Information:**
   - **Title** - The main heading (auto-generates slug)
   - **Slug** - URL-friendly version (e.g., "our-solution" becomes `/solutions/our-solution`)
   - **Excerpt** - Short summary (3-4 lines)
   - **Featured Image** - Must be 1440 × 810 pixels (16:9 ratio)
     - Upload high-quality images
     - The editor will help you crop to the correct size
   - **Content** - Full article using the rich text editor

   **Additional Information:**
   - **Services** - Link related services to this solution

   **About Sidebar (Optional):**
   This section appears in the sidebar of the solution detail page and provides context about the company/client.

   - **Company Description** - Brief description about the company or client (3-4 lines)
   - **Industry** - The industry sector (e.g., "Technology", "Healthcare", "Finance")
   - **Location** - Geographic location (e.g., "London, United Kingdom")
   - **Company Size** - Employee count range (e.g., "11-50 employees", "100+ employees")
   - **Website URL** - Company website link (e.g., "https://example.com")

   *Note: All sidebar fields are optional. If left empty, the sidebar section won't be displayed.*

   **Publishing Settings:**
   - **Published** - Toggle to make visible on website
   - **Featured** - Toggle to highlight this solution

4. Click **Create** to save

#### Managing Solutions

- **Search** - Find solutions by title
- **Filter** - View only published or draft solutions
- **Reorder** - Drag and drop to change the display order
- **Edit** - Click on any solution to modify
- **Delete** - Remove unwanted solutions

---

### Tech Stack

Display technology logos and links on your website.

#### Adding Tech Stack Items

1. Go to **Manage Content → Tech Stack**
2. Click **Create**
3. Fill in the fields:
   - **Name** - Technology name (e.g., "React", "Laravel")
   - **Link** - Optional URL to the technology's website
   - **Logo** - Upload the technology logo
     - SVG format preferred for scalability
     - Alternatively, use transparent PNG
     - Recommended size: 200 × 200 pixels minimum
   - **Active** - Toggle to show/hide on website

4. Click **Create** to save

#### Reordering Tech Stack

- Drag and drop items in the list to change display order
- The order you set here is how they appear on your website

---

### Careers (Job Listings)

Manage job openings and career opportunities.

#### Creating a Job Listing

1. Go to **Manage Content → Careers**
2. Click **Create**
3. Complete the form:

   **Basic Information:**
   - **Title** - Job title (e.g., "Senior Software Engineer")
   - **Department** - Team or department name
   - **Slug** - Auto-generated URL (editable)
   - **Job ID** - Internal reference number
   - **Location** - Select from dropdown (manage locations in Settings)

   **Job Details:**
   - **Description** - Full job description with responsibilities
   - **Employment Type** - Full-time, Part-time, Contract, etc.
   - **Work Mode** - Remote, Hybrid, or On-site
   - **Header Image** - Optional banner image (800 × 450 pixels, 16:9 aspect ratio)

   **Display Settings:**
   - **Active** - Toggle to publish/unpublish the job listing

4. Click **Create** to save

#### Viewing Applications

- The **Applicants** column shows total applications received
- Click **Edit** on a job to view applicant details

---

## Services Management

### Service Sectors

Service Sectors are top-level categories for your services (e.g., "Emerging Technologies", "Infra and Operations", "Data and Applications").

#### Creating a Service Sector

1. Go to **Services Management → Service Sectors**
2. Click **Create**
3. Fill in the fields:
   - **Title** - Sector name
   - **Slug** - Auto-generated URL
   - **Subtitle** - Rich text description
   - **Services** - Select which services belong to this sector
   - **Active** - Toggle to show/hide

4. Click **Create** to save

#### Reordering Sectors

- Drag and drop to change the order displayed on your website

---

### Services

Detailed service pages with comprehensive information about specific offerings (e.g., "Artificial Intelligence", "Blockchain", "DevOps", "Data Analytics", "SaaS Applications").

#### Creating a Service

1. Go to **Services Management → Services**
2. Click **Create**
3. Complete the comprehensive form:

   **Media:**
   - **Featured Image** - Main service image (800 × 800 pixels, square format)

   **Basic Information:**
   - **Title** - Service name
   - **Slug** - Auto-generated URL
   - **Service Sector** - Select parent sector
   - **Description** - Service overview
   - **Service Icon** - Choose from 200+ icons
     - Use the search feature to find icons quickly
     - Icons are displayed throughout the website

   **Services Page Header:**
   - **Page Title** - H1 heading for service page
   - **Page Description** - Rich text content below title

   **Sub Services Grid:**
   - Click **Add Sub Service** to add multiple service offerings
   - Each sub-service includes:
     - Title
     - Description
     - Icon (searchable dropdown)
   - Expand/collapse items for easier management

   **Display Settings:**
   - **Active** - Toggle to publish/unpublish

4. Click **Create** to save

#### Icon Selection Tips

- Use descriptive search terms (e.g., "cloud", "security", "data")
- Icons are displayed as visual elements on your website
- Choose icons that represent the service clearly

---

## Layout Management

### Sections (Advanced)

**Important:** This is an advanced feature available only to super administrators. Sections control the layout and content of various website pages.

⚠️ **Caution:** Editing sections can affect multiple pages. Only modify if you understand the impact.

#### What Are Sections?

Sections are reusable content blocks used across different pages:
- Hero banners
- About sections
- Testimonials
- Gallery grids
- CTA (Call to Action) blocks
- Footer content

#### Editing a Section

1. Go to **Manage Layouts → Sections**
2. **Filter by page** to find the right section
3. Click **Edit** on the section you want to modify

Each section has unique fields based on its type:

##### Common Section Types

**Hero Sections:**
- Main homepage banner
- Background images with responsive sizes
- CTA buttons and text

**About Sections:**
- Company description
- Statistics (numbers with labels)
- Team photos

**Gallery Sections:**
- Multiple images in grid layout
- Upload images with proper dimensions

**Testimonial Sections:**
- Customer quotes
- Name and designation
- Minimum 2 testimonials required

**CTA Sections:**
- Call-to-action content
- Button text and links
- Feature lists with icons

**Footer Section:**
- Social media handles
- Platform selection
- URLs for each platform

#### Image Requirements by Section

Different sections require specific image dimensions:

| Section Type | Dimensions | Aspect Ratio |
|--------------|------------|--------------|
| Hero | 665 × 512 | ~1.3:1 |
| Team | 1920 × 960 | 2:1 |
| Gallery | 1080 × 720 | 16:9 |
| About Hero Images | Various | See helper text |

**Always check the helper text below each image field for exact dimensions.**

#### Section Display Settings

- **Active Toggle** - Show/hide section on the website
- Turning off a section removes it from the page

---

## Settings

### Locations

Manage geographic locations for job listings.

#### Adding a Location

1. Go to **Settings → Locations**
2. Click **Create**
3. Enter the location name (e.g., "New York", "Remote", "Dubai")
4. Click **Create**

Locations are then available when creating Career listings.

---

## Best Practices

### Images

1. **Always use the correct dimensions** specified in helper text
2. **Automatic optimization** - The CMS automatically compresses and converts images to WebP format
   - Exception: Hero images marked with "Manual Compression Required" are preserved at high quality for landing sections
   - For these special images, optimize before uploading using tools like TinyPNG or Squoosh
3. **Image quality**
   - Most images are auto-optimized, no manual compression needed
   - Hero/landing images: Manually compress while maintaining quality
   - Target file size: under 500KB per image for manual uploads
4. **Use descriptive file names** (e.g., "team-meeting-2024.jpg" not "IMG_1234.jpg")

### Content Writing

1. **Keep titles concise** - Under 60 characters for SEO
2. **Write clear excerpts** - Summarize the main points in 2-3 sentences
3. **Use rich text formatting** sparingly - Bold for emphasis only
4. **Break up long content** - Use headings and bullet points
5. **Proofread before publishing** - Always review in draft mode first

### Slugs and URLs

1. **Let slugs auto-generate** from titles
2. **Keep slugs lowercase** with hyphens (not underscores)
3. **Don't change slugs after publishing** - This breaks existing links
4. **Make slugs descriptive** - "cloud-computing-services" not "service-1"

### Publishing Workflow

1. **Create content as draft** (Published toggle OFF)
2. **Preview on staging** if available
3. **Toggle Published ON** when ready
4. **Monitor for issues** after publishing
5. **Update regularly** to keep content fresh

### Reordering Content

- Use drag-and-drop to reorder items
- The CMS uses a "sort" field to maintain order
- Changes are immediate on the website
- Most important items should be at the top

---

## Troubleshooting

### Common Issues

#### "Slug already exists" Error

**Problem:** You're trying to use a URL that's already in use.

**Solution:**
- Modify the slug to make it unique
- Add a number or descriptor (e.g., "service-2024")

#### Image Upload Fails

**Problem:** Image file is too large or wrong format.

**Solution:**
- Check file size (max 15MB)
- Use JPEG, PNG, or WebP formats
- Compress large images before uploading

#### Changes Not Appearing on Website

**Problem:** Edits aren't showing on the live site.

**Solution:**
1. Check if item is marked as "Active" or "Published"
2. Clear browser cache (Ctrl+F5 or Cmd+Shift+R)
3. Wait 1-2 minutes for cache to refresh
4. Contact developer if issue persists

#### Can't Delete an Item

**Problem:** Delete button is disabled or missing.

**Solution:**
- Some items are protected and can't be deleted
- Check if item is being used elsewhere (e.g., Service linked to Service Sector)
- Remove dependencies first, then delete

#### Rich Text Editor Not Working

**Problem:** Can't format text or insert links.

**Solution:**
- Try a different browser (Chrome recommended)
- Clear browser cache
- Ensure JavaScript is enabled
- Contact support if issue continues

---

## Tips for Success

### Organization

- **Use consistent naming** across all content
- **Tag content appropriately** with services, sectors, etc.
- **Archive old content** instead of deleting (mark as inactive)
- **Keep a content calendar** for regular updates

### Performance

- **Don't upload massive images** - Compress first
- **Limit the number of items** on homepage features
- **Use featured toggles** to highlight important content
- **Regular content audits** - Remove outdated information

### Security

- **Use strong passwords** for admin accounts
- **Don't share login credentials**
- **Log out when finished**
- **Only give access to trusted team members**

---

## Need Help?

If you encounter issues not covered in this documentation:

1. **Check the helper text** below form fields for guidance
2. **Try the built-in search** in tables
3. **Review this documentation** for similar scenarios
4. **Contact support** - For technical support or any issues, email: **hello@vivekraj.dev**

---

## Quick Reference

### Image Sizes Cheat Sheet

| Content Type | Recommended Size |
|--------------|------------------|
| Solution Featured Image | 1440 × 810 |
| Tech Stack Logo | SVG preferred, or 200 × 200 PNG |
| Career Header | 800 × 450 (16:9) |
| Service Featured Image | 800 × 800 (square) |
| Hero Image | 665 × 512 |

### Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Save | Ctrl+S (Cmd+S on Mac) |
| Search | Ctrl+K (Cmd+K on Mac) |
| Close Modal | Esc |

---

**Last Updated:** October 2025
**CMS Version:** Filament v3

For the latest updates and features, consult with your developer.

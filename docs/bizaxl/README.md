# Bizaxl CMS Documentation

## Table of Contents
1. [Getting Started](#getting-started)
2. [Dashboard Overview](#dashboard-overview)
3. [Industries Management](#industries-management)
4. [Best Practices](#best-practices)
5. [Troubleshooting](#troubleshooting)

---

## Getting Started

### Accessing the CMS

1. Navigate to: **https://bizaxl.com/admin**
2. Log in with your admin credentials
3. You'll be taken to the main dashboard

### Navigation Structure

The CMS is organized into logical groups:

- **Industry & Segments** - Manage industries and their segments
- **Content Management** - Other content sections
- **Settings** - System configurations

---

## Dashboard Overview

### Key Features

- **Quick Navigation** - Use the sidebar to access different sections
- **Badge Counters** - Each menu item shows the total count of records
- **Search** - Use the search bar in tables to find specific items
- **Drag & Drop Reordering** - Change the display order of items
- **Bulk Actions** - Select multiple items to perform actions at once
- **Activity Tracking** - View history of changes made to records

---

## Industries Management

Industries are the main service sectors your company specializes in (e.g., "Energy & Utilities", "Logistics & Transportation", "Healthcare"). Each industry has its own dedicated page with comprehensive information about how Bizaxl serves that sector.

### Understanding the Industry Structure

Each industry consists of:
- **Basic Information** - Title, slug, description, and icon
- **Detail Page Hero Section** - Content shown at the top of the industry page
- **Benefits** - Up to 3 key benefits for clients in this industry
- **Solution Sections** - Up to 4 alternating content blocks showcasing specific solutions
- **Segments** - Sub-categories within the industry (managed separately)

---

### Creating an Industry

1. Go to **Industry & Segments → Industries**
2. Click **Create** button
3. Fill in the comprehensive form (detailed below)
4. Click **Create** to save

---

### Form Sections Explained

#### Section 1: Basic Information

**Title** (Required)
- The main industry name (e.g., "Energy & Utilities")
- Minimum 10 characters, maximum 60 characters
- Auto-generates the slug when you type
- Best Practice: Keep it clear and descriptive

**Slug** (Required)
- URL-friendly version of the title
- Auto-generated from title (e.g., "energy-utilities")
- Must be unique across all industries
- Used in URLs: `/industries/your-slug`
- ⚠️ Don't change after publishing - breaks existing links

**Subtitle** (Required)
- Brief description of the industry (50-255 characters)
- Used for SEO purposes and on the industries listing page
- Appears in the accordion on `/industries` page
- Best Practice: Summarize the value Bizaxl brings to this industry

**Industry Icon** (Required)
- Visual representation of the industry
- Select from 200+ Lucide icons using the visual picker
- Search functionality available (e.g., search "energy", "truck", "health")
- Icon displays throughout the website
- Best Practice: Choose an icon that clearly represents the industry

---

#### Section 2: Detail Page Hero Section Content

This section controls what visitors see when they click into a specific industry page.

**Page Title** (Required)
- Main heading on the industry detail page
- 20-60 characters
- Should be compelling and action-oriented
- Example: "Power Your Energy & Utilities Operations"

**Page Description** (Required)
- Rich text content below the page title
- Minimum 100 characters
- Explains how Bizaxl helps companies in this industry
- Can include multiple paragraphs
- Best Practice: Focus on value proposition and outcomes

**Featured Image** (Optional)
- Featured app screenshot for the industry page hero
- Recommended resolution: 1200 × 675 pixels (16:9 aspect ratio)
- The CMS editor helps you crop to the correct size
- Leave empty if you don't have a good visual
- Maximum file size: 15MB
- Best Practice: Use high-quality screenshots showing your solution in action

---

#### Section 3: Benefits

Define up to 3 key benefits for clients in this industry.

**Adding Benefits:**
1. Click **Add Benefit** (maximum 3)
2. For each benefit:
   - **Benefit** - Brief statement (15-60 characters)
   - Examples: "Industry-specific solutions", "Proven track record", "Expert support team"
3. Benefits appear as checkmarks (✔️) on the industry page header
4. Section is collapsible for easier editing

**Best Practices:**
- Focus on tangible, specific benefits
- Use action-oriented language
- Keep them concise and scannable
- Highlight what sets Bizaxl apart for this industry

---

#### Section 4: Alternating Solution Sections

These are the main content blocks on the industry page, showcasing specific problems and solutions. They alternate between left-image/right-text and right-image/left-text layouts.

**Maximum:** 4 solution sections per industry

**For Each Solution Section:**

1. **Image** (Required)
   - Screenshot of your solution in action
   - Resolution: 1200 × 675 pixels (16:9 aspect ratio)
   - Automatically optimized to WebP format
   - Best Practice: Use creative screenshots - overlapped multiple screenshots in different aspect ratios with subtle shadows

2. **Badge Text** (Required)
   - Category label shown above the title
   - 5-20 characters
   - Examples: "Automation", "Analytics & Reports", "Integration"

3. **Title** (Required)
   - Main heading for this solution
   - 15-60 characters
   - Should describe the key feature or benefit
   - Example: "Automatic payment reminders"

4. **Subtitle** (Required)
   - Supporting headline
   - 15-60 characters
   - Provides additional context
   - Example: "No more endless follow-ups"

5. **Description** (Required)
   - Detailed explanation of the solution
   - 80-255 characters
   - Explains how it works and the benefits
   - Be specific about features and outcomes

6. **Button Label** (Optional)
   - Text for the CTA button
   - 5-25 characters
   - Example: "Learn More", "Get Started", "Book Demo"

7. **Button Link** (Optional)
   - URL where the button should link
   - Can be internal (/contact) or external (https://example.com)

**Managing Solution Sections:**
- Click the section header to expand/collapse
- Sections display the title in the header for easy identification
- Drag to reorder sections
- Delete unwanted sections using the trash icon

---

#### Section 5: Button Settings

Override the default call-to-action button that appears throughout the industry page.

**Button Label** (Optional)
- Custom text for the main CTA button
- 5-255 characters
- Leave empty to use default

**Button Link** (Optional)
- Custom URL for the button
- Must be a valid URL format

**When to Edit:**
- Only modify if you want to change the default behavior
- Most industries can use the default settings
- This section is collapsed by default

---

### Managing Industries

#### Viewing the Industries List

The industries table shows:
- **Title** - Industry name (searchable, sortable)
- **Segments** - Count of segments in this industry (badge)
- **Slug** - URL identifier (searchable, can be hidden)
- **Status** - Active/Inactive toggle
- **Created At** - Creation date (hidden by default)
- **Updated At** - Last modified date (hidden by default)

#### Table Actions

**Search:**
- Use the search box to find industries by title or slug
- Search is instant and filters as you type

**Reordering:**
- Drag and drop rows to change the display order
- The order you set determines how industries appear on the website
- Changes are immediate

**Toggle Status:**
- Click the Status toggle to activate/deactivate an industry
- Inactive industries don't appear on the public website
- Status shows green (active) or gray (inactive)
- Note: Content managers and editors cannot toggle status for industries they don't have permission to edit

**Action Menu (three dots):**
- **Edit** - Modify the industry details
- **Activities** - View change history for this industry
  - See who made changes and when
  - Track all modifications over time

**Bulk Actions:**
- Select multiple industries using checkboxes
- Click **Bulk Actions** dropdown
- Available action: **Delete** selected industries
- ⚠️ Use with caution - deletion is permanent

---

### Industry Segments

Each industry can have multiple segments (sub-categories). Segments are managed within the industry editing interface.

#### Managing Segments

1. **Edit an industry** from the industries list
2. Click the **Segments** tab at the top of the page
3. You'll see the segments relation manager

**Segment Fields:**
- **Name** - Segment name (e.g., "Oil & Gas", "Renewable Energy")
- **Slug** - Auto-generated URL identifier
- **Description** - Brief description of the segment
- **Icon** - Visual icon for the segment
- **Status** - Active/Inactive toggle

**Segment Actions:**
- **Create** - Add new segments to the industry
- **Edit** - Modify existing segments
- **Delete** - Remove segments
- **Reorder** - Drag and drop to change order
- **Toggle Status** - Activate/deactivate segments

---

### Activity Tracking

Every change made to an industry is tracked and logged.

#### Viewing Activity History

1. From the industries list, click the **three dots** menu
2. Select **Activities**
3. View the complete change history

**Activity Log Shows:**
- Date and time of changes
- User who made the changes
- What was changed (field names and values)
- Before and after states

**Use Cases:**
- Audit trail for compliance
- Track who changed what and when
- Revert unwanted changes by seeing original values
- Accountability for content updates

---

## Best Practices

### Content Writing

**Titles & Headlines:**
- Keep industry titles clear and professional
- Use title case (capitalize main words)
- Be specific - "Energy & Utilities" not just "Energy"
- Match industry terminology your audience uses

**Descriptions:**
- Write for your target audience in that industry
- Focus on outcomes and benefits, not just features
- Use concrete examples when possible
- Keep sentences short and scannable
- Proofread for grammar and spelling

**Solution Sections:**
- Tell a story - problem, solution, outcome
- Use active voice
- Be specific with metrics when available
- Include real use cases or scenarios

### Images

**General Guidelines:**
1. **Always use the correct dimensions** specified in helper text
2. **Image quality:**
   - High-quality, professional screenshots
   - Clear, crisp, not pixelated
   - Target file size: under 500KB per image
3. **Automatic optimization** - The CMS automatically compresses and converts images to WebP format
4. **Use descriptive file names** (e.g., "energy-dashboard-2024.jpg" not "IMG_1234.jpg")

**Screenshot Best Practices:**
- Show your actual product/solution in action
- Remove any sensitive customer data
- Use annotated screenshots to highlight key features
- Consider using multiple overlapping screenshots for visual interest
- Ensure text in screenshots is readable
- Use consistent screenshot styling across industries

### Icons

**Choosing the Right Icon:**
- Use the search feature in the icon picker
- Search terms: industry keywords (e.g., "energy", "health", "money")
- Icons should be immediately recognizable
- Maintain consistency across similar industries
- Test how icons look on both light and dark backgrounds

### Slugs and URLs

1. **Let slugs auto-generate** from titles
2. **Keep slugs lowercase** with hyphens (not underscores)
3. **Don't change slugs after publishing** - This breaks:
   - Existing links from other websites
   - Bookmarks users have saved
   - Search engine rankings
4. **Make slugs descriptive** - "energy-utilities" not "industry-1"
5. **Keep slugs short** - Remove unnecessary words like "the", "and", "or"

### Publishing Workflow

**Recommended Process:**

1. **Create content as inactive** (Status toggle OFF)
2. **Fill in all required fields** completely
3. **Add images** with proper dimensions
4. **Preview on staging** (if available)
5. **Review for accuracy** - check spelling, links, and data
6. **Toggle Status ON** when ready to publish
7. **Monitor the live page** after publishing
8. **Update regularly** to keep content fresh and relevant

### Reordering Content

- **Strategic ordering matters** - Put most important industries first
- The CMS uses a "sort" field to maintain order
- Changes are immediate on the website
- Consider your target audience when ordering
- Group related industries together if possible

### Segments Organization

- Create segments that truly represent distinct categories
- Don't over-segment - aim for 3-8 segments per industry
- Use clear, industry-standard terminology
- Keep segment descriptions concise
- Order segments from most to least common

---

## Troubleshooting

### Common Issues

#### "Slug already exists" Error

**Problem:** You're trying to use a URL that's already in use by another industry.

**Solution:**
- Modify the slug to make it unique
- Add a descriptor (e.g., "energy-utilities-asia")
- Check the industries list to see which slug is conflicting
- Consider if you're accidentally creating a duplicate industry

---

#### Image Upload Fails

**Problem:** Image file is too large or wrong format.

**Solution:**
1. Check file size (max 15MB)
2. Use JPEG, PNG, WebP, or GIF formats
3. Compress large images before uploading:
   - Use TinyPNG (https://tinypng.com)
   - Use Squoosh (https://squoosh.app)
   - Use your OS's built-in image compression
4. Ensure image meets minimum dimensions specified
5. Check your internet connection if upload stalls

---

#### Changes Not Appearing on Website

**Problem:** Edits aren't showing on the live site.

**Solution:**
1. **Check Status Toggle** - Is the industry marked as "Active"?
2. **Clear Browser Cache:**
   - Windows/Linux: Ctrl+F5
   - Mac: Cmd+Shift+R
   - Or use incognito/private browsing mode
3. **Wait for cache refresh** - Can take 1-2 minutes
4. **Check if you saved** - Look for success notification
5. **Verify you're viewing the correct page** - Check the URL
6. Contact your developer if issue persists

---

#### Can't Delete an Industry

**Problem:** Delete button is disabled or deletion fails.

**Solution:**
- Check if industry has active segments - remove segments first
- Some industries may be protected if they're linked to other content
- Verify you have the required permissions for deletion
- Use the Status toggle to deactivate instead of deleting
- Contact your administrator if you need deletion permissions

---

#### Icon Picker Not Loading

**Problem:** Icons don't display in the picker.

**Solution:**
- Refresh the page
- Try a different browser (Chrome recommended)
- Clear browser cache
- Check your internet connection
- Ensure JavaScript is enabled in your browser
- Contact support if issue continues

---

#### Rich Text Editor Not Working

**Problem:** Can't format text in description fields.

**Solution:**
- Try a different browser (Chrome recommended)
- Clear browser cache and cookies
- Disable browser extensions temporarily
- Ensure JavaScript is enabled
- Check if you're using an up-to-date browser version
- Contact support if issue continues

---

#### "Too few arguments" or Permission Errors

**Problem:** Error when trying to toggle status or edit.

**Solution:**
- You may not have permission for this action
- Contact your administrator to verify your role permissions
- Log out and log back in
- Check if you're assigned the correct role:
  - **Super Admin** - Full access to everything
  - **Content Manager** - Can create, edit, delete
  - **Editor** - Can view and edit only
  - **Viewer** - Can only view, no editing

---

### Getting Support

If you encounter issues not covered in this documentation:

1. **Check the helper text** below form fields for specific guidance
2. **Try the built-in search** in tables to find content
3. **Review this documentation** for similar scenarios
4. **Clear cache and retry** - Solves 80% of display issues
5. **Contact support:**
   - Email: support@bizaxl.com
   - Include:
     - What you were trying to do
     - What happened instead
     - Screenshots if possible
     - Your role/permissions level

---

## Tips for Success

### Organization

- **Use consistent naming conventions** across all industries
- **Keep a content calendar** for regular updates
- **Archive old content** instead of deleting (mark as inactive)
- **Document your decisions** - Note why certain content is ordered specific ways
- **Regular content audits** - Review and update industries quarterly

### Content Quality

- **Write for humans first**, search engines second
- **Use industry-specific language** your audience understands
- **Be concise but complete** - Quality over quantity
- **Include real examples** and case studies when possible
- **Keep tone consistent** across all industries

### Performance

- **Compress images** before uploading when possible
- **Don't upload unnecessarily large images**
- **Limit solution sections to what's essential** (remember: max 4)
- **Use the Status toggle** to hide work-in-progress content
- **Test on mobile devices** after major changes

### Security

- **Use strong passwords** for admin accounts
- **Enable two-factor authentication** if available
- **Don't share login credentials** with anyone
- **Log out when finished** editing
- **Only give access to trusted team members**
- **Review activity logs** periodically for unauthorized changes

### Collaboration

- **Communicate with team members** before making major changes
- **Use the Activity Log** to see what colleagues have changed
- **Assign clear ownership** of different industries to team members
- **Establish approval workflows** for publishing
- **Document your content strategy** and share with editors

---

## Quick Reference

### Character Limits Cheat Sheet

| Field | Minimum | Maximum | Notes |
|-------|---------|---------|-------|
| Industry Title | 10 | 60 | Auto-generates slug |
| Slug | - | 255 | Must be unique |
| Subtitle | 50 | 255 | For SEO & listings |
| Page Title | 20 | 60 | Industry detail page |
| Page Description | 100 | - | Rich text field |
| Benefit | 15 | 60 | 3 max per industry |
| Solution Badge | 5 | 20 | Category label |
| Solution Title | 15 | 60 | Feature heading |
| Solution Subtitle | 15 | 60 | Supporting text |
| Solution Description | 80 | 255 | Feature details |
| Button Label | 5 | 25 | CTA text |

### Image Sizes Reference

| Content Type | Recommended Size | Aspect Ratio |
|--------------|------------------|--------------|
| Featured Image | 1200 × 675 | 16:9 |
| Solution Section Image | 1200 × 675 | 16:9 |
| Icons | SVG (vector) | - |

### Keyboard Shortcuts

| Action | Windows/Linux | Mac |
|--------|---------------|-----|
| Save Form | Ctrl+S | Cmd+S |
| Hard Refresh | Ctrl+F5 | Cmd+Shift+R |
| Search in Table | Ctrl+F | Cmd+F |

---

## Glossary

**Industry** - A top-level service sector that Bizaxl serves (e.g., "Energy & Utilities")

**Segment** - A sub-category within an industry (e.g., "Oil & Gas" under Energy)

**Slug** - The URL-friendly version of a title used in web addresses

**Hero Section** - The prominent area at the top of a page with key information

**Solution Section** - A content block showcasing a specific problem and solution

**Status Toggle** - The switch that makes content active (visible) or inactive (hidden)

**Rich Text Editor** - Text input field that allows formatting (bold, italics, links, etc.)

**Activity Log** - Historical record of all changes made to a record

**Badge** - A small colored label showing counts or status

**Icon Picker** - Visual interface for selecting icons from a library

**Bulk Actions** - Actions performed on multiple selected items at once

**Relation Manager** - Interface for managing related records (e.g., segments within an industry)

---

**Last Updated:** October 17, 2025
**CMS Version:** Bizaxl V1

For technical support or feature requests, contact your development team or email hello@vivekraj.dev.

---

**© 2025 Bizaxl. All rights reserved.**

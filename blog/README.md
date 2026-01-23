# Blog System Documentation

The blog uses a JSON-driven approach where all post metadata lives in `posts.json` and JavaScript handles filtering and pagination dynamically.

## File Structure

```
blog/
├── posts.json          # All post metadata
├── README.md           # This documentation
└── [post-slug].html    # Individual post pages (using blog-post-template.html)
```

## How It Works

1. `blog.html` loads `posts.json` on page load
2. JavaScript renders filter buttons from the `categories` array
3. Posts are sorted by date (newest first) and displayed in a grid
4. Filtering happens instantly across ALL posts (not just current page)
5. Pagination updates dynamically based on filtered results

## posts.json Structure

```json
{
  "posts": [
    {
      "slug": "post-url-slug",
      "title": "Post Title",
      "date": "YYYY-MM-DD",
      "category": "category-id",
      "categoryLabel": "Category Display Name",
      "excerpt": "Brief description for the card (optional but recommended)",
      "image": "images/filename.jpg",
      "imageAlt": "Image description"
    }
  ],
  "categories": [
    { "id": "category-id", "label": "Category Display Name" }
  ],
  "config": {
    "postsPerPage": 9
  }
}
```

## Adding a New Post

### Quick Method (using /blog-post skill)
Run `/blog-post` and follow the prompts. The skill will:
1. Add the post entry to posts.json
2. Create the post HTML file from the template
3. Add the category if it's new

### Manual Method

1. **Add entry to posts.json:**
   ```json
   {
     "slug": "my-new-post",
     "title": "My New Post Title",
     "date": "2026-01-21",
     "category": "hormones",
     "categoryLabel": "Hormones",
     "excerpt": "What readers will learn from this post.",
     "image": "images/my-post-image.jpg",
     "imageAlt": "Description of image"
   }
   ```

2. **Create the post page:**
   - Copy `blog-post-template.html` to `blog/my-new-post.html`
   - Update the title, date, category, image, and content
   - The slug in the URL must match the `slug` in posts.json

3. **Add category if new:**
   If using a new category, add it to the `categories` array:
   ```json
   { "id": "new-category", "label": "New Category" }
   ```

## Adding a New Category

1. Add to the `categories` array in posts.json:
   ```json
   { "id": "category-slug", "label": "Display Name" }
   ```

2. The filter button will appear automatically on next page load

## Configuration

In `posts.json` under `config`:
- `postsPerPage`: Number of posts per page (default: 9)

## Notes

- Posts are automatically sorted by date (newest first)
- The slug must be URL-safe (lowercase, hyphens instead of spaces)
- Images should be placed in the main `images/` folder
- Post pages live in the `blog/` folder as individual HTML files
- When filtering by category, pagination resets to page 1

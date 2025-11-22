# xbook-public-data

Public data repository for xbook project, accessible via jsDelivr CDN.

## Files

- `styles.css` - Sample CSS file with basic styling for web projects

## How to Access Files via jsDelivr

jsDelivr is a free CDN that allows you to serve files directly from GitHub repositories. You can access the files in this repository using the following URL formats:

### Using the Latest Version

To always get the latest version of a file from the default branch:

```html
<!-- For CSS files -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/manishonc/xbook-public-data/styles.css">
```

Or in JavaScript/other contexts:
```
https://cdn.jsdelivr.net/gh/manishonc/xbook-public-data/styles.css
```

### Using a Specific Branch

To access files from a specific branch:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/manishonc/xbook-public-data@branch-name/styles.css">
```

### Using a Specific Version/Tag

To access files from a specific release tag or commit:

```html
<!-- Using a tag -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/manishonc/xbook-public-data@1.0.0/styles.css">

<!-- Using a commit hash (first 7 characters) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/manishonc/xbook-public-data@abc1234/styles.css">
```

## Benefits of Using jsDelivr

- **Fast and Reliable**: Global CDN with multiple points of presence
- **Free**: No cost for open-source projects
- **Automatic Minification**: Add `.min` before the extension (e.g., `styles.min.css`)
- **Version Control**: Pin to specific versions to prevent breaking changes

## Example Usage

Here's a complete HTML example using the CSS file from this repository:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>xbook Sample Page</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/manishonc/xbook-public-data/styles.css">
</head>
<body>
    <header>
        <h1>Welcome to xbook</h1>
    </header>
    <main class="container">
        <div class="card">
            <h2>Sample Content</h2>
            <p>This page uses CSS from xbook-public-data via jsDelivr CDN.</p>
            <a href="#" class="btn">Learn More</a>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 xbook Project</p>
    </footer>
</body>
</html>
```

## More Information

For more details about jsDelivr and its features, visit [jsDelivr Documentation](https://www.jsdelivr.com/).
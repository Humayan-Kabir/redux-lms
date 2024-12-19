# JSON Server API

A simple REST API server for video learning management system.

## Quick Start

```bash
npm install
npm start    # Starts server on http://localhost:9000
```

## Available Endpoints

```bash
# Videos
GET    /videos        # Get all videos
GET    /videos/:id    # Get single video
POST   /videos        # Create new video
PATCH  /videos/:id    # Update video
DELETE /videos/:id    # Delete video

# Tags
GET    /tags         # Get all tags
```

## Useful Links
- [JSON Server Documentation](https://github.com/typicode/json-server)
- [JSONView Chrome Extension](https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc)
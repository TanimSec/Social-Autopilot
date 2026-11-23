# Social Autopilot NodeJS SDK

This is the NodeJS SDK for [Social Autopilot](https://postiz.com).

You can start by installing the package:

```bash
npm install @postiz/node
```

## Usage
```typescript
import Social Autopilot from '@postiz/node';
const postiz = new Social Autopilot('your api key', 'your self-hosted instance (optional)');
```

The available methods are:
- `post(posts: CreatePostDto)` - Schedule a post to Social Autopilot
- `postList(filters: GetPostsDto)` - Get a list of posts
- `upload(file: Buffer, extension: string)` - Upload a file to Social Autopilot
- `integrations()` - Get a list of connected channels
- `deletePost(id: string)` - Delete a post by ID

Alternatively you can use the SDK with curl, check the [Social Autopilot API documentation](https://docs.postiz.com/public-api) for more information.
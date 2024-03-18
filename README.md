## Requirements

- `Web Browser` - Can be used as an emulator to build applications. Example [Chrome, Firefox, Safari & Opera].
- `Internet` - Because many use CDN and to make it easier to find solutions to all problems.

#### Example Syntax

```javascript
const socialSharingUtils = require("social-sharing-utilities");

const url = "https://example.com";
const text = "Check out this link";

const facebookShareUrl = socialSharingUtils.shareOnFacebook(url);
console.log("Share on Facebook:", facebookShareUrl);

const twitterShareUrl = socialSharingUtils.shareOnTwitter(url, text);
console.log("Share on Twitter:", twitterShareUrl);
```

#### Explanation

- `shareOnFacebook(url)`: Generates a URL for sharing the specified URL on Facebook.
- `shareOnTwitter(url, text)`: Generates a URL for sharing the specified URL and text on Twitter.

#### Return Value

- The functions return a string representing the URL for sharing the content on the respective social media platform.

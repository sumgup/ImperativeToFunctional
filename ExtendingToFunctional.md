**<u>TODO</u>**:

Three Sequential Operations:

1. Download
2. Create Document
3. Upload

**<u>Requirements</u>**:

1. Validate if URL is valid
2. All these operations are sequential, If any of the Operation fail it will log (using logger configured using DI) where fault occurred.
3. Log message on success.
4. Ability to sign the pdf -  Configuration
5. Return drive url.
6. Convert to pdf or doc - Configuration

**<u>Future Requirement:</u>**

1. Make this code parallel
2. Supply multiple URLS
3. Make it a serverless function﻿, so that everyone can download file
# Issues and Fixes

## Issue: AccessDenied when opening CloudFront URL
**Cause:** S3 bucket policy did not allow CloudFront access  
**Fix:** Updated bucket policy using CloudFront OAC and distribution ARN

## Issue: Blank page on first load
**Cause:** Default root object not set  
**Fix:** Set `index.html` as default root object in CloudFront

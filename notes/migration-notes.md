# Migration Notes – ADF-danay Cloud Migration

## Migration Type
Rehost (Lift-and-Shift) for static web content.

## Reasoning
- Static content does not require compute (EC2)
- S3 provides low-cost, durable storage
- CloudFront adds HTTPS, security, and global performance

## Key Decisions
- Used private S3 bucket instead of public hosting
- Chose CloudFront with Origin Access Control (OAC)
- Enforced HTTPS via CloudFront

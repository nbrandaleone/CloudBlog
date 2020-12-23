# CloudBlog

This is a static blog, generated by Hugo.
I use it to document my learnings and experience
with various Cloud Providers, specifically AWS and GCP.

I also include personal posts from time to time.

# Create post
hugo new posts/my-first-post.md

## Build site (with drafts)
hugo -D

## Sync blog to Google Storage bucket
gsutil rsync -R ~/gcp/CloudBlog/public/ gs://nicks-playground.net/

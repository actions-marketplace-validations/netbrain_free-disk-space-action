# Free Disk Space GitHub Action

This GitHub Action is designed to free up disk space on GitHub runners by performing a series of cleanup operations. It removes certain directories, purges specific packages, and cleans up Docker images.

## Usage

To use this action in your GitHub workflow, add the following step:

```yaml
steps:
  - name: Clear Disk Space
    uses: netbrain/free-disk-space-action@v0.0.1
```

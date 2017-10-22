# tokarchuk-blog

## Summary

This is a template for a craft cms. In addition there is docker compose envirement.

## Installation

1. Download Craft.zip from https://craftcms.com
2. Unzip Craft.zip to working directory
3. Next you have to restore modified files which has been replaced by unzipping:
   ```
    # git reset --hard
   ```
4. To run containers you have to execute the command:  
   ```
    # docker-compose up
   ```

## Testing
The site will be awailable on http://localhost/ but it still should be configured. The admin page is located in http://localhost/admin.
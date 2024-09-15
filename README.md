# shirtsbyshanecom
Website for shirtsbyshane.com

## TODO:
- Visual Studio Online
  - [ ] personalize dotfiles
- Site
  - [ ] update footer to include commmit and timestamp

## Maintenance:
https://learn.microsoft.com/en-us/azure/storage/blobs/storage-blobs-static-site-github-actions?tabs=userlevel#generate-deployment-credentials
```
az ad sp create-for-rbac --name "myML" --role contributor \
                            --scopes /subscriptions/<subscription-id>/resourceGroups/<group-name> \
                            --json-auth
```

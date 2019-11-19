# Search-for-Git-repos-locally
script to search for local git repos 

`Get-ChildItem . -Attributes Directory+Hidden -ErrorAction SilentlyContinue -Filter ".git" -Recurse | Out-File -FilePath C:\Dev\GitRepoList.txt`

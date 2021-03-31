### vlogin to ghcr
https://docs.github.com/en/packages/guides/pushing-and-pulling-docker-images

- add your personal access token (PAT) `export CR_PAT=YOUR_TOKEN`
- login `echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin`

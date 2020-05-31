# pms-docker
Plex Media Server in a container

## Environment variables:
**Time zone:** set *TZ* in .env/config
**Plex Claim Token:** set *PLEX_CLAIM* in .env/plex_claim
**Media directory:** *MEDIA* can be set in .env/config. It's located by default in the *./media* folder, a symbolic link to the actual location can be used
**User and group id** Initially set to 32400 in .env/config
#ddev-generated
FROM diffywebsite2/screenshot-worker:0.0.1
# I don't know why, but `npm install` tries to use this folder,
# even when using npm_config_cache=/mnt/ddev-global-cache/npm
# This should be in the parent Dockerfile
RUN mkdir /.cache && chmod ugo+w /.cache

docker-vim-be-good
------------------

Allows users to play http://github.com/KhulnaSoft/init.lua without
installing or building anything.

`stable` image build steps:

- `docker build --no-cache -t khulnasoft/vim-be-good:stable stable`
- `docker push khulnasoft/vim-be-good:stable`

`latest` image build steps (uses `stable` as a base):

- `docker build --no-cache -t khulnasoft/vim-be-good:latest latest`
- `docker push khulnasoft/vim-be-good:latest`

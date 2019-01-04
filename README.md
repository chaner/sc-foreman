
# Setup

```
bundle install
```

Create a file named `.env` with:
```
DEV_ROOT_PATH=~/dev/code
RAILS_ENV=development
RACK_ENV=development
```
where the path points to where all your sc project folders live.

# Usage

```
foreman start -f Procfile.dev
```

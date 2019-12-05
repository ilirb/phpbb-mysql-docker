# [WIP] Full stack phpBB on Docker

## Quick guide

1. Clone this repo
2. Download your version of phpbb from https://www.phpbb.com/downloads/
3. Extract it to `phpbb/` folder
4. Change passwords in `.env` file
5. Run `docker-compose up --build` or `docker-compose up -d --build` if you want it to run on background
6. Open `http://localhost` and proceed with phpBB installation
7. Delete `install/` folder in `phpbb`

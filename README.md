# roblox-group-funds-tracker

I run a few Roblox groups and got tired of checking the web UI for pending payouts. This polls the group API and drops results into a local SQLite db so I can query trends later.

## install

pip install -r requirements.txt

## usage

The db file gets created in the working directory. Use sqlite3 to query it directly.

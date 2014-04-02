### Direwolf Docs

# Dev process

You'll need some AWS creds with push access to the `skylight-docs` bucket on the `tilde` account.
Put these in `~/.fog`.

```
skylight-docs:
  :aws_access_key_id: ID
  :aws_secret_access_key: KEY
```

Run `bundle`, then `bundle exec middleman`.
Change the files in `src/` and visit http://0.0.0.0:4567/

To deploy, run `bundle exec rake deploy`

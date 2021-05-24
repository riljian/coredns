## Setup

```sh
# it would load DNS RRs from /etc/hosts
docker-compose up -d
```

## Problems

### `hosts` not reloaded after `/etc/hosts` in the docker host changed

inode changed caused the problem [issue](https://github.com/moby/moby/issues/15793#issuecomment-161162118)

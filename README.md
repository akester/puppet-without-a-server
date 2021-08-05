# Puppet Without a Server

This is a demo / template / jumping off point for a topic I cover in my blog.
The idea is to run Puppet without a centralized puppet server for quick
provisions or small environments that don't warrant the full-fledged puppet
environment.

Details on what these files do, how to modify them, and the end goal are all
detailed on [this blog post](https://aikester.com/2021/puppet-without-a-puppet-server/)

## Running Things

Use this snippet (as root):

```bash
curl -s https://raw.githubusercontent.com/akester/puppet-without-a-server/master/init.sh | bash
```

# nosqli-flintcms

Blind noSQL injection case study lab based on CVE-2018-3783 (privilege escalation on flintcms 1.1.9).

The vulnerability was originally discovered by Benoit Côté-Jodoin. You can read original report on [HackerOne](https://hackerone.com/reports/386807).

## Prerequisites

```
docker-compose
```

## Lab Setup

1. The environment variables are in `docker-compose.yml` you can change database's credential here.
2. Run `docker-compose up`, wait until the containers are built and running properly.
3. Go to `localhost:4000` you should see a welcome page. Then visit `localhost:4000/admin/install`, enter fake email username and password.
4. Let's hack!

Don't forget to run `docker-compose down` once finished hacking.

## How it works?

Coming soon.
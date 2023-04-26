# Docker Project

Project for the **Dockerfiles** and **Docker Compose** sections

## Initial configuration

- Create account at the https://unsplash.com jclapointe1950@gmail.com jclap/jclap1950
- At the https://unsplash.com/oauth/applications create new **demo** application with title **"Images Gallery"**.
  Demo applications are limited to 50 requests per hour
- In the newly created application find section **"Keys"** and copy **Access Key**
- In the **api** folder create file **.env.local** and add there following line:

Access Key=7XXzPdCMJtXYSVDJgSwUyNFdps_FLCe4T-kPFXhbS8M
Secret key=tls5l_qDagbopLl4BwsZIOeebxyTYECYUVE0AHX2bUU

```
UNSPLASH_KEY=<Paste copied Access Key here>
```

**EXAMPLE** with fake code(don't try to use it in your app):

```
UNSPLASH_KEY=2MJvApIkV13hfg2LmQlneILfHoJ2ttlzSdPKefGOyKM
```

- Save modified **.env.local** file

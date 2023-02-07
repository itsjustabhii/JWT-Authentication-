The ACCESS_TOKEN and REFRESH_TOKEN are generated using the command

- node require('crypto').randomBytes(64).toString('hex')

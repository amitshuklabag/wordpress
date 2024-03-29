# WORDPRESS + MySQL + PhpMyAdmin docker compose demo CI/CD pipeline

<a href="https://dash.elest.io/deploy?source=cicd&social=dockerCompose&url=https://github.com/elestio-examples/wordpress"><img src="deploy-on-elestio.png" alt="Deploy on Elest.io" width="180px" /></a>

Example application and CI/CD pipeline showing how to deploy a WORDPRESS + MySQL + PhpMyAdmin docker compose to elestio.

<img src="wordpress.png" style='width: 100%;'/>
<br/>
<br/>

# Once deployed ...

You can can open Wordpress admin panel here:

    https://[CI_CD_DOMAIN]/wp-admin
    Login: [ADMIN_EMAIL] (set in env var)
    password: [ADMIN_PASSWORD] (set in env var)

You can connect to your DB through PHPMyAdmin:

    https://[CI_CD_DOMAIN]:24580/
    Login: root (set in reverse proxy configuration)
    Password: [ADMIN_PASSWORD] (set in reverse proxy configuration)

# Redis

You can activate redis by going to the plugins section => installed plugins.
Click on settings below Redis Object Cache, then click on the Enable Object Cache button

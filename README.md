<div align="center">
  <a href="https://koyeb.com">
    <img src="https://www.koyeb.com/static/images/icons/koyeb.svg" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">Koyeb Serverless Platform</h3>
  <p align="center">
    Deploy a Redis application on Koyeb
    <br />
    <a href="https://koyeb.com">Learn more about Koyeb</a>
    ·
    <a href="https://koyeb.com/docs">Explore the documentation</a>
    ·
    <a href="https://koyeb.com/tutorials">Discover our tutorials</a>
  </p>
</div>


## About Koyeb and the Redis example application

Koyeb is a developer-friendly serverless platform to deploy apps globally. No-ops, servers, or infrastructure management.
This repository contains a Redis application you can deploy on the Koyeb serverless platform for testing.

This example application is designed to show how a Redis application can be deployed on Koyeb.

This Redis setup is a perfect way to have an internal cache for your other Koyeb services. This service does *not* offer persistency for data stored to Redis.

## Getting Started

Follow the steps below to deploy and run the Redis application on your Koyeb account.

Once the Redis application becomes healthy, you can reach it from any other Koyeb service using its internal domain, on the default redis port 6379: <SERVICE>.<APP>.koyeb

### Requirements

You need a Koyeb account to successfully deploy and run this application. If you don't already have an account, you can sign-up for free [here](https://app.koyeb.com/auth/signup).

### Deploy using the Koyeb button

The fastest way to deploy the Redis application is to click the **Deploy to Koyeb** button below.

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=docker&image=redis&ports=6379;tcp&name=redis-on-koyeb)

Clicking on this button brings you to the Koyeb App creation page with everything pre-set to launch this application.

## Contributing

If you have any questions, ideas or suggestions regarding this application sample, feel free to open an [issue](//github.com/koyeb/example-redis/issues) or fork this repository and open a [pull request](//github.com/koyeb/example-redis/pulls).

## Contact

[Koyeb](https://www.koyeb.com) - [@gokoyeb](https://twitter.com/gokoyeb) - [Slack](http://slack.koyeb.com/)

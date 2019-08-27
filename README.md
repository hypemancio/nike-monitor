## Nike Monitor - IN DEVELOPMENT

Hello, this is my nike monitor / script. It's still currently in development, so please give me some time. Also, I have plans of rewriting my supreme monitor which would support all regions, and have more sneaker scripts related + non sneaker related web apps that can be beneficial for almost anything.

### Installation

Nike Monitor requires the following...

- [Node.js (LTS Version)](http://nodejs.org/)
- [YarnPKG](https://yarnpkg.com/lang/en/docs/install/#windows-stable)

Quick start:

```bash

# Install dependencies
yarn install

# Run application
yarn run start

# Add stuff in your config.json
{
  "webhooks": [
    {
      "region": "us",
      "webhook_url": ""
    },
    {
      "region": "uk",
      "webhook_url": ""
    }
  ],
  "discord": {
        "username": "Nike Monitor",
        "avatar": "",
        "footertext": "",
        "footericon": ""
  },
  "pollMS": 2000
}

```

Features:

```bash

# Support all regions ✅
# Custom discord webhook embeds ✅
# Multithreaded like task system ✅
# Proxy support ✅
# Unique proxy task request ✅

```

## Faq

- Each task monitors each region, and rotatings proxies per request.
- Custom discord webhook embeds are supported, simply edit the config.json file.
- Required working proxies, either datacenter or residential proxies will work.
  - Ideally you would want to test what proxies & delay settings fits for you.
- If you want to put each monitor in its own discord channel, simply follow the format above.

## Need help?

Feel free to send to open an issue, and I'll do my best to resolve your issue.

## Bugs?

Feel free to make an issue about any particular errors or bugs such as internal functionality bugs.

## DISCLAIMER

Please do not abuse this script, any abused from this script will result in banned by Nike. This is meant for only to be used for educational purpose.

## App Info

### Author

Eric Zhang

### Version

1.0.0

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

# smartlink-parsers

This is an open repository of all Notifi Smart Link parsers hosted for this chain. Pushing your project source here is optional, but recommended if you'd like to offer more transparency of what your smart link is actually doing.

Anyone can offer suggestions or fixes by submitting a pull request. Notifi will pick up the latest changes once approved and ensure deployment to the appropriate link.

To start, please see our docs for [Creating a Smart Link](https://docs.notifi.network/docs/create-smart-links)

When you'd like to add your source to this repository, please send a pull request with a folder structure as below:

```
repository-root
└───YOUR_DAPP_NAME_USED_ON_ADMIN_PORTAL -- Obtained from Admin Portal
    ├───smartlinkid0 -- Id obtained from Smart Link details page on Admin Portal. Source in this folder from parser development workflow
    ├   └───package.json
    ├        ...
    ├───...
    └───smartlinkidn
```
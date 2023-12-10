To generate a new local package:
- Update version number in package.json
- Run the following in saleor-sdk.git:
$ npm run build --legacy-peer-deps
$ npm pack --pack-destination ../frontend.git

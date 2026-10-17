# node-nestpay-mk

A Node.js client for the NestPay (EST) payment gateway, published on npm as [`node-nestpay-mk`](https://www.npmjs.com/package/node-nestpay-mk).

Fork of [eraycetinay/node-nestpay](https://github.com/eraycetinay/node-nestpay), adapted for North Macedonian banks:

- MKD as the default currency and English as the default language
- the `3D_PAY_HOSTING` store type, with `Auth` in the hash string as the current gateway expects
- `express` as a peer dependency

```bash
npm install node-nestpay-mk
```

Usage follows the original project; see `examples/`. The credentials in the examples are the gateway's public test values.

MIT, original copyright kept.

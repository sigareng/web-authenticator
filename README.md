# web-authenticator

[![Build Workflow](https://github.com/sigareng/web-authenticator/actions/workflows/webpack.yml/badge.svg)](https://github.com/sigareng/web-authenticator/actions)

A *Google Authenticator* like offline webapp.

## ☂️ No External Services are used, local JavaScript execution only ☂️

Hosted at github pages: https://sigareng.github.io/web-authenticator/

Or host it on your onw GitHub account 
* Just fork this repo and this web app is available at:
  
  [https://\<USERNAME>.github.io/web-authenticator/](https://USERNAME.github.io/web-authenticator/)


### Features
* generate TOTP codes
* show remaining valid seconds for totp code
* generate QR-code with OTPAuth URL
  * click on QR-code to copy OTPAuth URL
* parse OTPAuth URLs in the `secret` input field
  * e.g. `otpauth://totp/john.doe?secret=N2SJSUOXCKQM5MAX7N7J3NBUQ4WTL66G&issuer=example.org`
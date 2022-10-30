# Changelog

## Unreleased

- Minimal supported version Node.js 14 LTS

## 0.3.0-beta.3 - 2022-10-09

- Updated Roboto font (version 3.005)
- Fixed calculating auto page height
- Fixed TrueType Collection loading from URL
- Fixed refetching fonts from URL

## 0.3.0-beta.2 - 2022-04-01

- Attachments embedding
- Support passing headers to request for loading font files and images via URL adresses

## 0.3.0-beta.1 - 2022-01-01

- Port code base to ES6+
- Unify interface for node and browser **(breaking change)**
- All methods return promise instead of using callback **(breaking change)**
- Change including virtual font storage in client-side **(breaking change)**
- Change parameters of `pageBreakBefore` function **(breaking change)**
- Support for loading font files and images via URL adresses (https:// or http:// protocol) in Node.js (client and server side now)

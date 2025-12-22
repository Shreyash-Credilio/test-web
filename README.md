# test-web

A test page for validating URL schemes and payment intents.

## Overview

This repository contains a test page that demonstrates various URL schemes including:

- **Payment Intent Links (UPI)**: Links that trigger UPI payment applications
- **Standard Schemes**: HTTP, HTTPS, file, chrome, data, javascript, about, copy
- **Non-Standard Schemes**: mailto, tel, sms, ftp, whatsapp, slack, custom protocols, etc.

## Usage

The test page is available at GitHub Pages. Click on different links to test how they behave on various platforms and browsers.

### Testing URL Schemes

The page includes:
1. **UPI Payment Links** - Test payment intent triggers on mobile devices
2. **Standard Protocol Links** - Test browser handling of common schemes
3. **Custom Protocol Links** - Test application-specific protocol handlers

## Local Development

To test locally:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Purpose

This page is designed to test and validate:
- How different browsers handle various URL schemes
- Payment intent triggering (especially UPI on mobile)
- Custom protocol handler behavior
- Deep linking to applications
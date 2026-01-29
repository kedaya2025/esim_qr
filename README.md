# eSIM QR Code Generator

A minimalist, dark-themed eSIM QR code generator with batch processing capabilities.

## Features

- **Batch Processing**: Paste multiple activation codes at once (one per line)
- **Auto Format Fix**: Automatically adds `LPA:1$` prefix if missing
- **Carrier Detection**: Automatically identifies carrier from activation code
- **Dark Theme**: Professional black, white, and gray color scheme
- **Responsive Design**: Works on desktop and mobile devices

## Usage

1. Paste your eSIM activation codes in the textarea (one per line)
2. Click "Generate QR Codes"
3. Scan the generated QR codes with your device

### Supported Formats

- Standard: `LPA:1$smdp.example.com$ACTIVATION_CODE`
- Auto-fix: `smdp.example.com$ACTIVATION_CODE` (will be auto-corrected)

## Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/esim-qrcode-generator)

Or manually:

```bash
vercel
```

## Tech Stack

- Pure HTML/CSS/JavaScript
- QRCode.js library
- No framework required
- Zero build step

## License

MIT

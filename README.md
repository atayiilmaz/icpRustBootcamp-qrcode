# qrcode

Welcome to the qrcode project and to the internet computer development community. This project was developed in ICP Rust Bootcamp.

## Running the project locally

If you want to test your project locally, you can use the following commands:

```bash
# Starts the replica, running in the background
dfx start --clean

# Deploys your canisters to the replica and generates your candid interface
dfx deploy
```

## Some Update Notes
- Added fields for specifying foreground and background colors, and error correction level.\
- Modified generate function to accept an error correction level parameter, defaulting to the value provided in options or the library's default.
- Moved QR code generation logic into a separate function to improve modularity and maintainability.
- Updated generate_qr_code function to return a Result type, allowing better error handling.
- Utilized Rust's Option pattern for cleaner and safer code.

# icpRustBootcamp-qrcode

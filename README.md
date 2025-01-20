# Template Simple Browser Extension with Deno

## Development Setup

1. Install [Deno](https://deno.land/).

1. Clone the repository or Click _"Use this template"_.

   ![Use this template button image](https://github.com/user-attachments/assets/2b600469-0840-4a9e-95a7-1a295eab72f3)

   or

   ```sh
   git clone https://github.com/Hashory/template-simple-browser-extension-with-deno.git
   ```

1. Cache the type files required for development.

   ```sh
   deno cache deno.json
   ```

1. Generate the extension files in the `/dist` directory.

   `bundle.ts` will be executed. Some permissions may be required.

   ```sh
   deno task bundle
   ```

1. Format the code.

   ```sh
   deno fmt
   ```

## License

[CC0-1.0 license](LICENSE)

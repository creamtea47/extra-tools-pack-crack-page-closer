# Extra Tools Pack Crack Page Closer

A minimal userscript that immediately attempts to close this exact page:

`https://www.extratoolspack.com/crack.php`

## Install

Install the script from Greasy Fork, or import [`outputs/ThankYouForTheForcedAd.user.js`](outputs/ThankYouForTheForcedAd.user.js) into Tampermonkey or Violentmonkey.

## What it does

- Runs only on the exact URL above.
- Calls `window.close()` at `document-start`.
- Does not send requests, store settings, display a UI, or access page content.

## Browser limitation

Browsers may refuse to close a tab that was not opened by JavaScript. When that happens, the script still runs immediately, but the browser keeps the tab open.

## License

[MIT](LICENSE)

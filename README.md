# NativeScript Vue with Vite Demo

Play around with NativeScript Vue and Vite.

*Prerelease features coming to NativeScript v9.*

```
npm install
```

## Develop with HMR

This will start Vite dev server and open a socket to the NativeScript app to develop with HMR for quick edits.

```
npm run dev:ios

// Or...

npm run dev:android
```

## Develop with Live Reload

```
ns debug ios --no-hmr

// Or...

ns debug android --no-hmr
```

### Notes

This project is configured via [nativescript.config.ts](nativescript.config.ts) to use Vite.

Explore the [vite.config.ts](vite.config.ts) where you can customize per your own needs.
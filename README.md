# X-ray Simulator Support Docs

This is the Mintlify documentation site for X-ray Simulator support.

## Local Development

Requirements:

- Node.js 20.17.0 or newer.
- npm. On Windows PowerShell, use `npm.cmd` if the `npm` PowerShell shim is blocked by execution policy.

Install the local Mintlify CLI dependency:

```powershell
npm.cmd install
```

Start the local docs preview:

```powershell
npm.cmd run dev
```

Mintlify serves the site at `http://localhost:3000`. To start without opening a browser automatically:

```powershell
npm.cmd run dev:no-open
```

Before publishing docs changes, run:

```powershell
npm.cmd run validate
```

Optional checks:

```powershell
npm.cmd run broken-links
npm.cmd run a11y
```

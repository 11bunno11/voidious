<div align="center">
    <img src="https://raw.githubusercontent.com/UseInterstellar/Interstellar/main/.github/branding/in.png">
    <p>Outerstellar but fixed, super cool; should be updated regualarly<p>
    <p>its forked, what'd you expect, a Plasma  TV?</p>
</div>


> [!IMPORTANT]
> If you fork this project, do whatever you want!

## Features
- Clean, Easy to use UI
- Password Protection (Optional)
- Built-in Tab Syste
- Fast Speeds

## Deployment

> [!IMPORTANT]
> This can be deployed to Vercel! Yippie!!

### Password Protection

1. Go to the `config.js` file and set `challenge` to **true**. Then, set the environment variable as follows:
2. For PNPM: Run either `config=true pnpm start` or `$env:config=true; pnpm start`, depending on your server.
3. For NPM: Run either `config=true npm start` or `$env:config=true; npm start` if you prefer NPM.

### Server Deployment

Run this in the vercel deployment page
if u dont know, i dont know so you try all by urself

```
pnpm i && pnpm start
```

### Updating

```bash
why update? dont f with it if it works (i f'ed up so im doing this all over again)
```




#### What happened to Replit Deployment?

As of January 1st, 2024, Replit is [no longer free](https://blog.replit.com/hosting-changes). Try GitHub Codespaces instead.(or vercel!)

### GitHub Codespaces

> [!NOTE]
> If you're setting the port below 1023, then you must run `sudo PORT=1023`

1. Create a GitHub account if you haven't already.
2. Click "Code" (green button) and then "Create Codespace on main."
3. In the terminal at the bottom, paste `pnpm i && pnpm start`.
4. Respond to the application popup by clicking "Make public."
> [!IMPORTANT]
> Make sure you click the "Make public." button, or the proxy won't function properly.
5. Access the deployed website from the ports tab.
6. For subsequent uses in the same codespace, just run `pnpm start`

### Solution for if there is no popup.

1. Run `pnpm i`, and before `pnpm start`, prepend `PORT=8080`, replacing 8080 with another port. For example, `PORT=6969 pnpm start`.
2. If this does not work then you can prepend `$env:PORT=8080;`, replacing 8080 with another port. For example, `$env:PORT=6969; pnpm start`
3. Go to the ports tab, Click Forward A Port, And type the port number.
4. Right-click Visibility and set Port Visibility to Public.


## Report Issues

If you encounter problems, open an issue on GitHub, and we'll address it promptly.
 

# Credits
me

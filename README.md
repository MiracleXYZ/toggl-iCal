# Toggl iCal

## Usage

### Deployment

```shell
npm i -g vercel
vercel
```

### Subscription

1. Open Calendar
2. `File` -> `New Calendar Subscription...`
3. Paste `https://<your-vercel-domain>/?token=<your_toggl_token_here>`

🎉 Now you can view the last six month's Toggl entries.

## Dev

1. `npm i -g vercel`
2. `vercel dev`
3. Open Calendar
4. `File` -> `New Calendar Subscription...`
5. Paste `http://localhost:3000/?token=<your_toggl_token_here>`

### Debugging

http://localhost:3000/index.json?token=your_toggl_token_here

---

Made by [KATTCORP](http://kattcorp.com).

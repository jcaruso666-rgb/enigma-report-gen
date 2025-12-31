# Deploy to Vercel

## Quick Deploy (3 clicks)

1. Go to https://vercel.com/new
2. Import your GitHub repo: `jcaruso666-rgb/enigma-report-gen`
3. Click "Deploy"

That's it! Vercel will automatically detect it's a static HTML site and deploy it.

## Manual Deploy via CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
cd enigma-report-gen
vercel

# Follow the prompts, then your app will be live!
```

## Why It Should Work Now

✅ Added `vercel.json` configuration  
✅ Single HTML file (no build needed)  
✅ Pure static site  
✅ No dependencies  

## Troubleshooting

**Issue:** 404 error  
**Fix:** Make sure `index.html` is in the root directory (it is!)

**Issue:** Blank page  
**Fix:** Check browser console for errors. The app works 100% client-side.

**Issue:** Build fails  
**Fix:** This is a static HTML site - there's nothing to build! Just serve the files.

## Live URL

After deploying, Vercel will give you a URL like:
`https://enigma-report-gen.vercel.app`

Share that and anyone can use it instantly!


# $PTARD Deployment Guide (Non-Developer Friendly)

## What’s Inside
- Smart Contract Code (ptard_contract.rs)
- Merkle Proofs (proofs.json)
- Frontend Site (React + Static HTML fallback)
- Simple index.html for preview

## What You’ll Do
1. Deploy contract (we’ll walk you through that separately)
2. Upload frontend to Vercel, Netlify, or Cloudflare Pages (free)

## Hosting the Website
Go to https://vercel.com and connect your GitHub (or upload manually).
1. Click “New Project” and upload the frontend folder
2. Use default settings – your site will be live instantly

## Claim Functionality
The Merkle proofs in proofs.json are used to validate wallets during claim.
You'll need a helper (we’ll provide script) to pass those into the contract.


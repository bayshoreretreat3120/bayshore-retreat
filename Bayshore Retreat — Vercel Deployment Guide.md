# Bayshore Retreat — Vercel Deployment Guide

**For: Amanda (Property Owner)**  
**From: Sir Jay**  
**Platform: Vercel (Free Hosting)**

---

## Overview

This guide walks you through deploying the Bayshore Retreat website to Vercel, a free hosting platform. You'll have full control over the site and can update it anytime.

**Timeline:** 20-30 minutes to set up and deploy.

---

## What You're Getting

- **Your complete website** (all code, photos, reviews, everything)
- **Free hosting** on Vercel
- **Custom domain support** (visitbayshoreretreat.com)
- **Full ownership** — you control everything
- **Easy updates** — push changes anytime

---

## Prerequisites

You'll need:
1. A **GitHub account** (free) — for storing your code
2. A **Vercel account** (free) — for hosting
3. Access to your **Cheapname domain** account (to update DNS)

---

## Step 1: Create a GitHub Account (If You Don't Have One)

1. Go to **github.com**
2. Click **"Sign up"**
3. Enter your email, create a password
4. Verify your email
5. Done!

---

## Step 2: Create a Vercel Account

1. Go to **vercel.com**
2. Click **"Sign up"**
3. Choose **"Continue with GitHub"** (easiest option)
4. Authorize Vercel to access your GitHub
5. Done!

---

## Step 3: Upload Your Project Code to GitHub

1. Log into **GitHub**
2. Click the **"+"** icon (top-right) → **"New repository"**
3. **Repository name:** `bayshore-retreat`
4. **Description:** "Bayshore Retreat vacation rental website"
5. Choose **"Public"** (so Vercel can access it)
6. Click **"Create repository"**
7. GitHub will show you instructions — follow them to upload the code

**Or, if you're not comfortable with GitHub:**
- I can help you upload the code via a simpler method
- Just let me know

---

## Step 4: Deploy to Vercel

1. Log into **Vercel**
2. Click **"Add New..."** → **"Project"**
3. Click **"Import Git Repository"**
4. Select your **`bayshore-retreat`** repository from GitHub
5. Click **"Import"**
6. Vercel will show deployment settings — just click **"Deploy"**
7. Wait 2-3 minutes for deployment to complete
8. You'll get a temporary Vercel URL (like `bayshore-retreat-abc123.vercel.app`)

---

## Step 5: Connect Your Custom Domain

1. In Vercel, go to your project → **Settings → Domains**
2. Click **"Add Domain"**
3. Enter: `visitbayshoreretreat.com`
4. Vercel will show you **DNS records** to add
5. Log into your **Cheapname** account
6. Go to **DNS Settings** for `visitbayshoreretreat.com`
7. Add the DNS records Vercel provided
8. Wait 24-48 hours for the domain to connect
9. Your site will be live at `visitbayshoreretreat.com`

---

## Step 6: Manage Your Site

**To update content:**
1. Edit files in your GitHub repository
2. Push the changes
3. Vercel automatically redeploys (takes 1-2 minutes)

**To add new reviews:**
- Edit the Home.tsx file in the `client/src/pages/` folder
- Add new review text
- Push to GitHub
- Site updates automatically

**To change photos:**
- The photos are hosted on a CDN (cloud storage)
- To change them, you'll need to upload new photos and update the URLs
- Or hire a developer to help

---

## Support & Help

**Vercel Help:**
- Visit **vercel.com/docs** for documentation
- Email support available

**GitHub Help:**
- Visit **github.com/support** for documentation

**Your Domain (Cheapname):**
- Log into your Cheapname account to manage DNS

---

## Important Notes

1. **Vercel is free** — no ongoing costs for hosting
2. **Your domain** (`visitbayshoreretreat.com`) costs ~$10-15/year at Cheapname
3. **You own everything** — all code, content, domain
4. **Backups** — GitHub stores all your code, so you always have a backup
5. **Updates** — You can update the site anytime by editing files and pushing to GitHub

---

## Troubleshooting

**Domain not connecting?**
- Wait 24-48 hours for DNS to propagate
- Check that you added the correct DNS records in Cheapname
- Contact Vercel support if it's been 48+ hours

**Site looks broken after update?**
- Check the Vercel deployment logs
- Rollback to the previous version if needed
- Contact a developer for help

**Need to make changes?**
- Edit files in GitHub
- Push changes
- Vercel redeploys automatically

---

## Next Steps

1. Create GitHub account (if needed)
2. Create Vercel account
3. Upload code to GitHub
4. Deploy to Vercel
5. Connect your domain
6. You're live!

---

**Questions?** Reach out to a developer or Vercel support.

**You've got this!** 🚀

---

**Last Updated:** July 2026  
**Site:** Bayshore Retreat — 3120 Mercer Rd, Bradenton, FL

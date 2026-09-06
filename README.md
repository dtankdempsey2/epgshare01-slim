# 🧰 Custom EPGShare01 Builder: Slim Down Your EPGs, Speed Up Your App!

Build a **personalized, lightweight EPG** using only the channels from your M3U playlist — optimized for performance and speed.

---

## ⚙️ What It Does

- ✅ Accepts your M3U playlist URL  
- 🔍 Extracts all `tvg-id` values  
- 🧹 Filters the giant [EPGShare01](https://epgshare01.online/) dataset to **only your channels**  
- 📦 Returns a compact, gzipped `epg.xml.gz` file

---

## 🤔 Why Use This?

**The Problem:**  
The full EPGShare01 file is **175+ MB**, bloated with 100,000+ programs — it slows down most IPTV apps.

**The Fix:**  
This script gives you a **5–20 MB** EPG tailored to *just* your playlist — making your app load faster and work better across devices.

**Benefits:**
- ⚡ Lightning-fast EPG loading  
- 💾 Saves storage space  
- 🚀 Faster app performance  
- 📱 Perfect for mobile and low-powered devices  

---

## 🚀 Usage

After deploying your own instance, use this URL format:

> https://your-project.vercel.app/api/epg?playlist=YOUR_PLAYLIST_URL

🔐 **Note:** Be sure to **URL-encode** your playlist link.

**Example:**

> https://your-project.vercel.app/api/epg?playlist=https%3A%2F%2Fraw.githubusercontent.com%2Fyourusername%2Frepo%2Fmain%2Fplaylist.m3u8

The result will be a gzipped EPG file ready to plug into your IPTV player:  
➡️ `epg.xml.gz`

---

## 🧪 Test Without Deploying

Want to try it first? Use this public instance:

> https://epgshare01-slim.vercel.app/api/epg?playlist=

> ⚠️ **Important Privacy Notice:**  
> This tool does **NOT** log or collect URLs or credentials.  
> **However**, you should **never share** playlists that contain **usernames, passwords, or private tokens** with third-party services.  
> For security and privacy, it’s always best to self-host by deploying your own instance.

---

## ⚡ One-Click Deploy to Vercel

Spin up your own secure instance in seconds:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/dtankdempsey2/epgshare01-slim&project-name=epgshare01-to-json&repository-name=epgshare01-slim)

Your endpoint will be:  

> https://your-project.vercel.app/api/epg

---

## 📅 Auto-Updated Daily

This builder uses the latest EPG data from **[EPGShare01](https://epgshare01.online/)**, refreshed twice daily.

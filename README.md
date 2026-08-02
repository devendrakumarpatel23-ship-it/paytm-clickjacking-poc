# 🎉 Paytm Clickjacking POC

## 📋 About
This is a Proof of Concept (POC) for a Clickjacking vulnerability found on Paytm's OAuth page.

## 🔍 Vulnerability Details
- **URL:** `https://accounts.paytm.com/oauth-js-sdk/index.html`
- **Issue:** Missing X-Frame-Options header
- **Impact:** Account takeover, wallet theft

## 🎯 How It Works
1. Paytm OAuth page loads in an iframe
2. A fake "Claim Prize" button is placed on top
3. User clicks the fake button
4. Actually clicks on Paytm's "Authorize" button
5. Attacker gains access to user's account

## 📸 Screenshots
[Add your screenshots here]

## 🛡️ Recommended Fix

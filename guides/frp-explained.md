# FRP: what it is, and what a repair shop should check before removing it

_Maintained by Backlight Pro. Site: https://www.backlightpro.com_

Every few days a customer walks in with a phone that was factory reset and now sits on a screen asking for "the Google account that was previously synced to this device". That screen is FRP.

## What FRP actually is

Factory Reset Protection is a Google feature that shipped with Android 5.1 in 2015. When a Google account and a screen lock are set on a device, a reset the phone does not consider trusted leaves the account tied to it. After the reset, setup asks for that account's password before the phone can be used at all. The point is simple: a stolen phone that gets wiped should still be worthless.

A reset done from Settings after unlocking the phone is trusted and does not trigger it. One done from recovery, or a remote erase, does.

Two details catch people out. If the account password was changed shortly before the reset, Google puts a 72 hour hold on signing in, so even the real owner has to wait. And on most Samsung phones the device also remembers the Samsung account, so it can ask for either one.

## Why shops see it every day

Second hand devices sold without signing out. Phones bought abroad. A customer who changed their Google password last week. A relative's phone whose owner has died or moved away. A company phone whose IT admin left. None of these people are thieves, and all of them are stuck.

## What a professional shop does first

Before any tool is opened, ask for proof:

- the receipt or invoice matching the device IMEI,
- the customer's ID,
- a short written statement that the device is theirs and that they accept the work.

Log the model, IMEI, date and who authorised the job. It takes two minutes and it protects the shop as much as the customer. Removing protection from a device you cannot prove ownership of is handling stolen property in most countries, whatever tool did the work.

Tell the customer this too: if they can still reach the Google account, they can remove the device from it in any browser in a few minutes and the phone unlocks for free. That is always the first answer.

## When the server route makes sense

When the account is genuinely gone, the phone can often be restored through a service that runs on model and IMEI. Results depend on the model, the security patch and the region, so the exact model is checked before anything is promised. Samsung, Honor, Xiaomi and MDM or Knox devices each behave differently, and an MDM or Knox device is not an FRP job at all: it needs the management console that enrolled it.

## What we do

At Backlight Pro we run FRP services for Samsung, Honor and Xiaomi, plus MDM and temp root work, from the site. Send the model and IMEI on WhatsApp and you get an answer on whether it is doable before you pay anything.

https://www.backlightpro.com

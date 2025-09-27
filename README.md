ChatRoom Project - Scaffold
===========================

This package contains a starter scaffold for:
- Flutter mobile app (basic screens: login, register with referral, home, profile)
- Node.js + Express backend (user model, payments, referral handling)
- Telegram bot (for manual payment submissions)
- React admin panel (list users, payments)

IMPORTANT:
- This is a scaffold for development and testing. You must configure environment variables,
  add actual SMS provider, Telegram bot token, MongoDB URI, and secure payment flow.
- Do NOT store real card numbers inside source files. Use environment variables.

Folders:
- mobile_flutter/        -> Flutter app (Dart)
- backend_node/          -> Node.js backend (Express + Mongoose)
- telegram_bot/          -> Telegram bot (Python)
- admin_react/           -> React admin panel

See each folder's README for how to run locally.

# [grammY](https://grammy.dev) on [Supabase Edge Functions](https://supabase.com/edge-functions)

Try it out: https://t.me/supabase_example_bot

![demo](./demo.gif)

## Deploy

1. Run `supabase functions deploy --no-verify-jwt telegram-bot`
2. Get your Telegram token from https://t.me/BotFather
3. Run `supabase secrets set TELEGRAM_BOT_TOKEN=your_token FUNCTION_SECRET=random_secret`
4. Set your bot's webhook url to `https://<PROJECT_NAME>.functions.supabase.co/telegram-bot` (Replacing `<...>` with respective values). In order to do that, run this url (in your browser, for example): `https://api.telegram.org/bot<TELEGRAM_BOT_TOKEN>/setWebhook?url=https://<PROJECT_NAME>.functions.supabase.co/telegram-bot?secret=<FUNCTION_SECRET>`
5. That's it, go ahead and chat with your bot 🤖💬

## More Supabase Edge Function Examples

Supabase Edge Functions can be used for a bunch of things, have a look at [some other examples](https://github.com/supabase/supabase/tree/master/examples/edge-functions).

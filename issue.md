# HCI Status — ALL FIXED ✅

## Login
**Status:** ✅ Working
- **Username:** admin
- **Password:** PLEASELOGIN123
- API login: ✅
- Browser login: ✅
- WebSocket (Apache port 82): ✅ 101 Switching Protocols

## Usage & Cost
**Status:** ✅ Working
- API `/api/usage/7` returns all data
- 12 sessions, 23.8M total tokens, **$4.11 estimated cost**
- **Fix:** Added DeepSeek V4 Flash & Pro pricing from OpenRouter API to `CUSTOM_PRICING`
- UI: click "Apply" on USAGE page to load data

## Open Items (optional)
- Cost is estimated — accurate rows added for deepseek/deepseek-v4-flash and deepseek/deepseek-v4-pro
- External WS on port 80 not tested (but local Apache port 82 works)
- WebSocket indicator not visible on Usage page (appears in Chat tab instead)

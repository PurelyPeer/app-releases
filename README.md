# PurelyPeer Application Release Public History


# 0.8.2

### ✨ Improvements
- `Create Mode`: added media posting during quest creation
- `Create Mode`: added text moderation on quest name and memo
- `Explore Mode`: removed comment creation for unfunded quests
- `Notifications`: opens app when clicked and redirects to corresponding page
- `Notifications`: add push notifications when someone liked your comment(s)
- `Notifications`: add push notifications when someone commented on your quest(s)
- `Comments`: enhanced UI/UX
- `App`: optimized bundle size

### 🔧 Bug Fixes
- `Create Mode`: fixed bug on memo editing becoming null
- `Notifications`: fixed bug on multicast notifications for flagging cashdrops and unblocking users

# 0.8.1

### 🚀 Features
- `Create Mode`: users can now add media
- `Explore Mode`: users can now add comments
- `Quests`: added text (name, memo, media, comments) and image (media) moderation using OpenAI
- `Transactions`: added `OP_RETURN` tags to PurelyPeer transactions for better tracking

### ✨ Improvements
- `Texts`: simplified date formatting
- `Theme`: updated air theme buttons

### 🔧 Bug Fixes
- `Quest Details`: corrected cashdrops remaining count when quest is not yet active
- `Quest Details`: fixed blank URLs showing as unsafe


# 0.8.0
### 🚀 Features
- `CashTokens`: added CashTokens support for wallets (send, receive, gallery, etc.)

### ✨ Improvements
- `Collect Mode`: added background OTP verification
- `Collect Mode`: added exploit analysis to prevent fake or automated collections
- `Notifications`: clicking notifications now redirect to their corresponding page
- `Transactions`: redesigned display of transaction history and handling of transactions
- `Onboarding`: enabled wallet importing during the onboarding process for a smoother setup experience

### 🔧 Bug Fixes
- `Create Mode`: fixed quest URL validation
- `Notifications`: fixed multicast push notifications not working

# TapBudget

A simple budget tracker. Switch a bill on when you pay it and the date is filled in for you.
Everything is saved on your own device. Nothing is sent anywhere.

The first time someone opens it, they see an **example budget** with made-up names and amounts, with some bills already ticked off.
They can play with it, open the menu and choose **Edit items** to make it their own, or tap **start with a blank budget**.
If someone already has budgets saved, the example is added to their list once. **Menu → Add an example budget** brings it back if it has been deleted.

## Finding your way around

- **Header (top):** the app icon on the left opens the menu, which slides out from the left edge. You can also swipe in from the left edge of the screen. Next to the icon is a greeting, with the open budget's name underneath. Tap the name to switch budgets. The round **+** button on the right adds an item.
- **Month bar:** stays pinned at the top while you scroll. The arrows move between months and **Today** jumps back to this month. Next to it is the health light. Green means all clear. Amber means a bill is due within 3 days, everyday spending is over budget, or your balance dips under your low balance line. Red means a bill is overdue or your balance would go below zero. On narrow phones the light shows without its word.
- **Tab bar (bottom):** a floating dark bar with five tabs. The open tab turns white and shows its name. A red badge on Bills counts overdue bills.
  - **Overview:** one fixed screen with no scrolling. Four cards (Bills, Money in, Spending and Cash flow) sit in a stack. They are wide, using most of the window, and they grow with it. Swipe left or right, tap a card peeking out at the side, or tap the chips above the stack. **See bills**, **See money in** and **See spending** open the matching tab, and the Cash flow card's button opens the starting balance sheet. Underneath, the month summary, loans and cards, and the example-budget note sit side by side. Swipe sideways to see them all. On a short screen these get shorter first, so the cards keep their room.

  **Cash flow** is a waterfall of the month. It starts at your starting balance, steps up with each paycheck and down with each bill in date order, and ends at the projected balance on the last day. Everyday spending budgets are not in it. Paid items use what you actually paid, and unpaid ones use the planned amount. Below your **low balance line** the chart is shaded red, any step that ends there is outlined, and a flag marks the lowest point. Tap **Starting balance** on the card to set what is in your account on the 1st, move it with the quick −$500, −$100, +$100 and +$500 buttons, and set the low balance line (it starts at $500). The preview shows the lowest point and the ending balance before you save. With **Carry over each month** on, every later month starts from the month before's ending balance, so you only set it once. A month before your first starting balance shows "Set starting balance". Each budget keeps its own.
  - **Bills:** a summary card at the top (bills paid and money received, each with a bar in your colors), then your income and bills, with a search box and filters: **All, Unpaid, Paid, Overdue**. The dark round button in the search box switches to the weekly schedule, one card per week, opening on this week. Swipe through the weeks, and tap **Show list** to go back. This tab scrolls.
  - **Spending:** what you have spent against each everyday budget, with filters: **All, Over budget, Within budget**.
  - **Insights:** expected income, planned spending and net for the month, where the money goes, a six-month chart and a debt balance prediction.
  - **Settings:** automatic bills, loans and credit cards, and shortcuts to wallpaper and colors, budgets, sharing and backup.
  - The app remembers the tab, view and filters you were using, and which gauge card was in front.
- **Bill details:** the round arrow at the end of each bill opens its own screen. It shows the amount and due date in a colored header, the switch, and the paid date and amount once it is paid. The pencil button edits the item. **Coming up** is a row of cards for the other bills still to pay this month. Swipe through them, switch one on, or tap its dark arrow to open it. Go back with the back button, Escape, or a swipe in from the left edge.
- **Menu (slide-out):**
  - **Budgets:** switch budgets, manage them, or open the example.
  - **Tools:** Add item, Edit items, Share this budget, Import a budget.
  - **Backup:** save a budget to a file, or restore one from a file.
  - **Appearance:** Auto (follows the phone), Light or Dark, and **Wallpaper and colors…**.
  - **About:** the About page, privacy policy and support.
- **Sheets:** Add item, Share, Import and Manage budgets open as a panel that slides up from the bottom. Close it with the X, by tapping outside it, or with Escape.
- **Messages:** short confirmations such as "Link copied" appear above the tab bar and fade away.

## Wallpaper and colors

Open **Menu → Wallpaper and colors…** (it is in Settings too). Everything here works in light and dark mode and is saved on that device.

**Each budget keeps its own wallpaper, colors and look (Flat or Glass).** The sheet says which budget you are changing. Switch budgets and the app switches to that budget's look. A new budget starts with the look that was showing when you made it. Light, Dark or Auto is one setting for the whole app.

- **Wallpaper:** tap **Choose a picture** to put one of your own photos behind the app. **Change picture** swaps it and **Remove** takes it away.
  - **Dim** fades the picture toward the page color (light or dark). **Blur** softens it.
  - Big photos are shrunk to 2,200 pixels on the longest side before they are saved, so they load quickly.
  - Text never sits on the picture itself. Headings, the greeting and notes get a near-solid plate behind them, so they stay readable on any photo.
  - The picture stays on that device. It is not in share links or backup files. Neither are a budget's colors or look, so an imported budget starts with the look that is showing.
  - Two budgets can use the same picture without storing it twice. A picture no budget uses any more is deleted, including when its budget is deleted.
- **The look:** white cards, charcoal buttons and soft shadows. **Flat** keeps the month bar, tab bar, menu and sheets solid. **Glass** makes them see-through and blurred. With a wallpaper, Glass is a little more solid so text stays readable. With Increase Contrast turned on, Glass stays solid.
- **Ready-made sets:** Cyan & Yellow (the default), Ocean, Forest, Sunset, Berry and Graphite.
- **Your own colors:** three pickers.
  - **Card color:** the Bills card, the bill headers, and the Bills heading and bar on the Bills tab.
  - **Bar and chart color:** the Spending card, progress bars, charts, and the markers beside the Spending, Insights and loan headings.
  - **Highlight color:** the Money in card, the Money in heading and bar on the Bills tab, and this week in the schedule.
- **Readable by default:** the gauge cards and bill headers sit on a dark base, so their white text stays readable whatever you pick. Elsewhere the text color on each of your colors is chosen automatically (white or dark). If a color can't hold readable text, a note says so. In dark mode, very dark colors are lightened automatically so they still show.
- **Reset** returns to Cyan & Yellow.

**Where your colors show.** Every screen uses all three: a small colored marker sits beside each section heading, the Overview gauges and the Bills summary card use them, bars and charts use the bar color, and each bill's arrow button takes a soft tint of its section's color. Each budget keeps its own set, so switching budgets switches all of it.

Green, orange and red keep their meaning (paid, due soon, overdue) whichever colors you pick.

## Put it online with GitHub Pages (free)

1. On github.com, create a new repository (for example `budget-tracker`). Make it **Public**.
2. Upload everything in this package: the six files (`index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`) and the `about` folder. Drag the folder in too, so it keeps its pictures.
3. Open **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then **Save**.
4. After a minute or two the page shows your address, `https://YOUR-USERNAME.github.io/budget-tracker/`.

## The About page

`about/` is a one-page site that explains the app and points people to it. It lives at `https://YOUR-USERNAME.github.io/YOUR-REPO/about/`. Share that link when you want to explain the app. Its buttons open the app itself.

It is plain HTML with no scripts, trackers or outside fonts. `about/preview.png` is the card that shows when the link is pasted into a message or post.

**Set your web address (needed once).** The page tells social sites where it lives, using the address `https://geiger12.github.io/BudgetTracker17/about/`. Replace it with your own in four lines near the top of `about/index.html`:

1. On GitHub, open `about/index.html` and click the pencil (Edit).
2. Press Ctrl+H (Cmd+Option+F on a Mac) to find and replace.
3. Find `geiger12.github.io/BudgetTracker17` and replace it with `YOUR-USERNAME.github.io/YOUR-REPO`, then replace all.
4. Commit the change.

Social sites keep the first preview they see, so test before you post: Facebook's Sharing Debugger, LinkedIn's Post Inspector, or paste the link into a draft.

## Install it on an iPhone

1. Open the address in **Safari**.
2. Tap **Share**, then **Add to Home Screen**.
3. Open it from the new icon.

## Sharing a budget

- **To share:** Menu → **Share this budget**, then **Share setup** (items, amounts, loans and cards only) or **Share with paid history** (which also carries your starting balance and low balance line). Backup files include them too. Send the link by message, Notes or AirDrop.
- **To receive:** copy the link, open TapBudget from the home screen, then Menu → **Import a budget**. It reads the copied link and asks you to confirm.
  If the link isn't picked up automatically, paste it into the box and tap **Import**.

On iPhone, tapping a link opens Safari, which keeps its own storage separate from the home-screen app. So copy the link rather than tapping it.
The data is inside the link and is never sent to GitHub. Anyone who has the link can read the budget, so delete the message afterwards.

## Importing from a spreadsheet

`TapBudget-import-template.xlsx` is a fill-in workbook for typing a whole budget at once. Fill in the **Items** sheet (and **Loans and cards**, if you like), wait for **Export** to say *Ready*, then copy cell **B12**. In the app, open **Menu → Import a budget**, paste, and tap **Import**. The budget is added as a new one.

Rows that are missing something turn red and say what they need. The paste box also copes with the extra quote marks Excel can add when it copies text. A filled-in copy holds personal finance details, so keep it private and out of the repository. The workbook is not part of the app files, so it does not go online with them.

## Several budgets

Tap the budget name under the greeting, or use the menu. **Menu → Manage budgets** creates, renames and deletes budgets. Each is separate.

## Notes

- Data lives in the browser on that device and is not encrypted. The budgets and settings are in localStorage. Each budget's look is in localStorage too. The wallpaper pictures are in IndexedDB, so they never take room from your budgets. A different phone or browser starts with the example until you Import.
- Updating the app: re-upload the files that changed. Each time `index.html` changes, also change the cache name at the top of `sw.js` (for example `tapbudget-v23` to `tapbudget-v24`) so phones drop the old copy. If a change doesn't appear, close and reopen the app.

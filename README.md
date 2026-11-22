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
  - **Overview:** one fixed screen with no scrolling. Four cards (Bills, Money in, Spending and Cash flow) sit in a stack. They are wide, using most of the window, and they grow with it. Swipe left or right, tap a card peeking out at the side, or tap the chips above the stack. All four chips share one row (the name on top, the number underneath), so none is ever hidden off the edge. **See bills**, **See money in** and **See spending** open the matching tab, and the Cash flow card's button opens the starting balance sheet. Underneath, the month summary, loans and cards, and the example-budget note sit side by side. Swipe sideways to see them all. On a short screen these get shorter first, so the cards keep their room.

  **Cash flow** is a waterfall of the month. It starts at your starting balance, steps up with each paycheck and down with each bill in date order, and ends at the projected balance on the last day. Everyday spending is in it too, as one orange step a week (see **Cash flow explorer** below). Paid items use what you actually paid, and unpaid ones use the planned amount. Below your **low balance line** the chart is shaded red, any step that ends there is outlined, and a flag marks the lowest point. Tap the **Start** pill on the card to set what is in your account on the 1st, move it with the quick −$500, −$100, +$100 and +$500 buttons, and set the low balance line (it starts at $500). The preview shows the lowest point and the ending balance before you save. With **Carry over each month** on, every later month starts from the month before's ending balance, so you only set it once. A month before your first starting balance shows "Set starting balance". Each budget keeps its own.
  - **Bills:** a summary card at the top (bills paid and money received, each with a bar in your colors), then your income and bills, with a search box and filters: **All, Unpaid, Paid, Overdue**. The dark round button in the search box switches to the weekly schedule, one card per week, opening on this week. Swipe through the weeks, and tap **Show list** to go back. This tab scrolls.
  - **Spending:** what you have spent against each everyday budget, with filters: **All, Over budget, Within budget**.
  - **Insights:** expected income, planned spending and net for the month, the **Cash flow explorer** (see below), where the money goes, a six-month chart and a debt balance prediction.
  - **Settings:** automatic bills, loans and credit cards that follow your bills, and shortcuts to wallpaper and colors, budgets, sharing and backup.
  - The app remembers the tab, view and filters you were using, and which gauge card was in front.
- **Bill details:** the round arrow at the end of each bill opens its own screen. It shows the amount and due date in a colored header, the switch, and the paid date and amount once it is paid. The pencil button edits the item. **Coming up** is a row of cards for the other bills still to pay this month. Swipe through them, switch one on, or tap its dark arrow to open it. Go back with the back button, Escape, or a swipe in from the left edge.
- **Menu (slide-out):**
  - **Budgets:** switch budgets, manage them, or open the example.
  - **Tools:** Add item, Edit items, Share this budget, Import a budget.
  - **Backup:** save a budget to a file, or restore one from a file.
  - **Appearance:** Auto (follows the phone), Light or Dark, **Easy mode (big print)**, and **Wallpaper and colors…**.
  - **About:** the About page, privacy policy and support.
- **Sheets:** Add item, Share, Import and Manage budgets open as a panel that slides up from the bottom. Close it with the X, by tapping outside it, or with Escape.
- **Messages:** short confirmations such as "Link copied" appear above the tab bar and fade away.

## Cash flow explorer and my chequing balance

**Tap the Cash flow card** on the Overview, or its **Explore the cash flow** button, and the app opens the **Cash flow** section at the top of Insights. (The **Start** pill on the card still opens the starting balance sheet.)

- **A chart you can move and zoom.** It follows your balance through every bill and paycheck, from the first month you have a balance for to a year ahead. Drag to move through time. Pinch with two fingers, or use **+** and **−**, to zoom. The arrow buttons step back and forward, **Today** comes back to now, and the chips show 1 month, 3 months, 6 months or a year. On a computer, hold Ctrl and scroll to zoom, and use the arrow keys, **+** and **−** with the chart selected. Zoomed out, you see the trend line and the low-balance zone. Zoomed in, each bill and paycheck becomes a bar, with its amount. Tap a bar to read what it was and the balance after it.
- **Everyday spending is in the chart too.** Groceries, gas and every other everyday spending item become one orange step a week (the 7th, 14th, 21st and 28th), so the chart shows your whole month and not only the bills. Add, change or remove an item and the Overview waterfall and this chart move right away. Weeks that have already passed count what you planned, or what you have spent so far if that is more. What is left is spread evenly over the weeks ahead. Other months use the plan, and earlier months use what you tracked. Turn **Include everyday spending** off, in the Starting balance sheet or under this chart, to chart bills and money in only. The low-balance warnings, the health light and Easy mode's account message follow the same setting.
- **Three numbers on top.** The plan for today, your balance (the last one you typed) and the lowest the balance gets from today on.
- **My chequing balance.** Type what your bank app shows, and the day it is for (today by default). It appears on the chart as a marker, and a line says whether you are **ahead of or behind plan** (the same message shows on the Overview card, where the waterfall gets a white **Now** bar). Each entry is kept in **Recent balances**, so the markers become a record of how real life compares with the plan. **Remove** deletes one. You can also type it in the **Starting balance** sheet, in **Chequing balance right now**.
- **Update the forecast from it** (on by default). From the day you typed, the chart starts again from your real balance. Later months carry on from there, the low-balance warnings and the health light use it, and a dashed line shows the old plan so you can see the gap. Turn it off to keep the plan as it was, with the markers only.
- **You do not need a starting balance.** If you only type your chequing balance, the app works out what the month started at, and everything else follows.
- Balance entries are included in a backup and in **Share with paid history**. **Share setup** leaves them out. The app keeps the latest 90.

## Loans and cards that follow your bills

You no longer have to type a payment. Link each loan or card to the bills you already tick, and its balance moves by itself.

- **Set it up once** in **Settings → Loans and cards → Edit** (or when you add one). Pick **which bill pays it**. The app suggests the bill whose name matches. For a credit card, also pick which bills are **charged to the card**, using the "Paid with" names on your bills. An optional **interest rate** on a loan splits each payment into interest and principal, so the balance matches your statement more closely.
- **Then just tick bills.** Tick *Car loan payment* and the loan drops by the amount you paid. Tick a bill that was paid with the card and the card goes up. Tick the card's payment bill and it comes down. Untick any of them and the balance goes back. A short line under each linked bill shows the change (for example *Car loan: $11,250 → $10,865*) and says what will happen before you tick it. A short message says the new balance when you tick.
- **Automatic bills work too.** When an automatic payment is marked paid on its due day, the loan or card follows, with no taps at all.
- **Nothing is counted twice.** When you link a loan or card, or save a new balance, the bills already paid are treated as inside that balance. Only ticks after that move it. If you delete a linked bill, the balance stays where it was.
- **Check in about once a month.** **Settings → Check in with your statements** (or the *Check in* link on the Overview when it has been a while) lists each loan and card with what the app thinks. Tap **Looks right** if it matches your bank, or **It is different** and type the real number. It says how far off it was and why that usually happens, such as interest.
- **If you would rather type it,** choose **None, I will update it myself**. Those loans and cards work as before, with **Record a payment** or **Update balance**.
- The Overview card, the debt chart on Insights and the example budget all use these live balances. In Easy mode, a bill that is linked says so in plain words, and **I paid it** moves the loan too.
- A **Share with paid history** link and a backup file carry the links and the bookkeeping. **Share setup** keeps the links but leaves the bookkeeping out, so the person who receives it starts fresh.

## Version number

The app shows its version, for example **TapBudget version 32**, so you can tell which copy a phone is running. It is at the very bottom of the **Settings** page (below the privacy line), pinned at the bottom of the **menu** (hidden when the menu is collapsed to icons), and at the bottom of **More** in Easy mode. It is the same number as the cache name in `sw.js` (`tapbudget-v32`).

## Easy mode

For anyone who wants a calmer, larger app. Turn it on from **Menu → Easy mode (big print)** or **Settings → Easy mode (big print)**. The app then opens in Easy mode every time, until someone chooses **More → Use the full app**. The choice and the print size are saved on that device only.

Easy mode shows the same budget, with the same data, in a much simpler way. It has no waterfall, tables, swipe-in menu or search, and only four big buttons along the bottom:

- **Home:** the next bill (or the oldest late one) with a big **I paid it** button, the bills left to pay and money still to come in plain numbers, and a plain-words message about the account: *You should be fine*, *Watch your balance* or *You may run short*. It uses the starting balance you set.
- **Overview:** the month at a glance, with nothing to edit. A banner says in plain words whether *Everything looks good*, a bill is *due soon* or *late*, or the balance needs watching. Under it are big cards with thick progress bars: **Bills** (for example *4 of 7 paid*), **Money in**, **Everyday spending** (when you have spending budgets) and **Your account**, which has a simple bar for the lowest point against your warning line plus where the month starts, bottoms out and ends. **Coming up** lists the next few bills and paydays. A **This month / Next month** switch sits at the top. Bars always come with the numbers in words, so color is never the only clue.
- **Bills:** this month's bills and money coming in, each with one big button (**I paid it**, **I got paid**, or **Undo**), with a switch between **This month** and **Next month**. Late bills have a red border and the word *Late*. Bills set to pay by themselves say so and have no button.
- **More:** **Large** or **Extra large** print, the account balance, switching between budgets, **Save a backup copy**, and **Use the full app**.

**Add a bill** takes three things: what it is called, how much, and which day of the month it is due, plus a choice between a bill and money coming in. **Change or remove** on any item opens the same form. Removing always asks first.

In Easy mode you can change only bills and money in. The Overview also shows everyday spending, read only. Loans and cards, the charts and the look settings stay in the full app, and are not changed by Easy mode. Text and buttons are at least 22px (27px on Extra large), buttons are at least 64px tall, the main buttons (like **I paid it**) are a light tint of your colors with dark text and a clear outline, so they stand out without being heavy, and every word of text meets the 4.5:1 contrast target in light and dark, at both sizes. Wallpaper and Glass are not used in Easy mode, so text always sits on a plain background.

## Wallpaper and colors

Open **Menu → Wallpaper and colors…** (it is in Settings too). Everything here works in light and dark mode and is saved on that device.

**Each budget keeps its own wallpaper, colors, look (Flat or Glass) and switch style.** The sheet says which budget you are changing. Switch budgets and the app switches to that budget's look. A new budget starts with the look that was showing when you made it. Light, Dark or Auto is one setting for the whole app.

- **Wallpaper:** tap **Choose a picture** to put one of your own photos behind the app. **Change picture** swaps it and **Remove** takes it away.
  - **Dim** fades the picture toward the page color (light or dark). **Blur** softens it.
  - Big photos are shrunk to 2,200 pixels on the longest side before they are saved, so they load quickly.
  - Text never sits on the picture itself. Headings, the greeting and notes get a near-solid plate behind them, so they stay readable on any photo.
  - The picture stays on that device. It is not in share links or backup files. Neither are a budget's colors or look, so an imported budget starts with the look that is showing.
  - Two budgets can use the same picture without storing it twice. A picture no budget uses any more is deleted, including when its budget is deleted.
- **Switches:** pick how every on and off switch looks, with a live preview of each style. **Classic** is the standard switch. **Check and X** is green with a check when on and red with an X when off. **Glow** is a glass track with a glowing green light when on and a dim, blurred red one when off. **Sun and ring** is a bright sun when on and a ring when off. **Soft ring** is a solid dot when on and a ring when off, in your bar color. Every style tells on from off by more than color: the knob side, a symbol, a ring against a solid shape, or a sharp light against a blurred one. The track, the knob and the symbols are at least 3:1 against the background in light and dark (the Classic switch is unchanged). The choice is saved with the budget's colors and wallpaper, and applies to the paid switch on each bill, the Settings switches and the ones in the sheets. The lock on automatic bills stays as it is. There is a **Try it** switch in the sheet.
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
- Updating the app: re-upload the files that changed. Each time `index.html` changes, also change the cache name at the top of `sw.js` (for example `tapbudget-v32` to `tapbudget-v33`) so phones drop the old copy, and change `APP_VERSION` near the top of the script in `index.html` to the same number (`"33"`). That number is what the app shows as its version (see below). If a change doesn't appear, close and reopen the app.

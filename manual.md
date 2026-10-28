---
title: "Experiment platform: user manual"
subtitle: "For participants and researchers"
date: "October 2026 (updated 28 October)"
---

# 1. About this manual

The platform runs online experiments and surveys in a web browser. Researchers build and run their studies on it;
participants take part from a computer, a tablet or a phone.

This manual has two parts:

- **Part A, for participants** (section 2): logging in, the home page, taking part in a study.
- **Part B, for researchers** (sections 3 to 14): the admin pages, the app editor (settings, payoffs, bots, pages), the
  previewer, bricks, the shared library, running a study, paying participants and getting the data, and the settings of
  the platform for its main admin.

In this manual, `YOUR-SITE` stands for the address of the platform where your research team runs it (for example
`https://studies.example.org`). Names of buttons and tabs are written in **bold**, as they appear on screen.

# Part A. Participants

# 2. Taking part in studies

Each app (each experiment) shows its own pages and instructions. This part explains what is common to all of them:
the home page, logging in, and what happens before and after a study.

## 2.1 The home page

The home page is `YOUR-SITE/home.php`, titled **Research studies**. It is the same page for participants and
researchers: a switch at the top chooses **Participant** or **Researcher**. Participants stay on **Participant**.

You can also reach a study directly from a link sent by the research team (for example from an email or a recruitment
website). That link opens the study's own login page (see 2.6).

## 2.2 Logging in with your email

1. On the home page, type your email address and click **Continue**.
2. The first time, the platform emails you a confirmation link. If you do not see it, check your spam folder.
3. Open the link (on the same device or another one, for example your phone) and click **Confirm and log in**. The
   page where you typed your email then opens your account by itself.
4. The confirmation page tells you which device asked to log in. If you did not ask to log in, do not confirm.

Your browser then stays logged in (for 180 days), so you do not need a new link each time. A link that was already
used or has expired can be replaced by typing your email again.

## 2.3 Creating your account

After your first confirmation, the platform asks for a few details: first and last name (required), year of birth,
gender, country of residence, highest education level and occupation.

- Tick the consent box (you must be 18 or older) and, if you wish, **Email me when new studies are available**.
- Click **Create my account**.

A short notice explains how your information is used: your details are stored separately from your study answers,
which are recorded under an anonymous code.

## 2.4 The tabs of your account

Once logged in, your account has these tabs:

| Tab | What it shows |
| --- | --- |
| **Studies** | The studies you can join now, each with its title, a short description and a button. |
| **My participation** | The studies you took part in, with your first and last visit. |
| **My details** | Your details, which you can change and save (**Save changes**). |
| **Bank details** | Only needed for paid studies (see 2.5). |
| **Account** | Your email address, invitations, notifications, log out, and account deletion. |

On the **Studies** tab, each study has a button:

- **Take part** opens the study; **Continue** goes back into a study you already started.
- Small tags give more information: **Paid**, **Started**, **Not open yet**, **Closed for now**, **Bank details
  needed**.
- Some studies need a particular kind of device (for example a computer). On another device the study is listed but
  its button reads, for example, **Open this on a computer**, and cannot be clicked.

## 2.5 Paid studies and bank details

A study tagged **Paid** pays you by bank transfer. To join it, add your bank details on the **Bank details** tab:
account holder name and IBAN, then **Save bank details**.

- Your IBAN is encrypted and only used to pay you. The page then shows only its last four digits.
- Each bank account can be registered by one participant only.
- **Replace bank details** and **Remove bank details** change or delete them. Without bank details you cannot join
  paid studies.

## 2.6 Taking part in a study

When you open a study (from the **Studies** tab or from a direct link):

1. **Login.** The study's start page logs you in, by your email (as in 2.2) or by an identifier (ID) given by the
   research team, depending on the study.
2. **Waiting.** If the study has not started yet, a countdown shows the time left. Studies played in groups wait until
   enough participants are present, then start a session.
3. **The study's pages.** Instructions, tasks, questionnaires: these are specific to each study. Follow the
   instructions on screen. Keep the page open: if your connection drops, the page says **Connection lost,
   reconnecting... Please keep this page open.** and continues when it is back.
4. **Earnings and end.** At the end, a page shows your earnings (for paid studies) and an end page thanks you.

Messages you may see on the start page:

| Message | What it means |
| --- | --- |
| This study is not open at the moment. | The study has not opened yet, or is closed. |
| Sorry, this study is now closed to new participants. | The study no longer accepts new participants. |
| Sorry, all sessions of this study are full. | Every session has started. |
| Sorry, not enough participants joined in time to start a session. | No group could be formed. You still receive the show-up fee, if the study pays one. |
| This study cannot be done on this device. | Open the study on the kind of device it names. |
| This study is only open to email addresses ending in ... | Use your email address from that domain (for example your school's). |
| This ID is already logged in on another page or device. | Close the other page, then try again. |
| You have already completed the maximum number of sessions of this study. | You cannot take part again. |
| This is a paid study: please add your bank details ... | Add your bank details first (2.5). |

Some pages check that you are still there: if you do nothing for a while, a pop-up asks you to confirm. Answer it,
otherwise you may be excluded from the study.

Depending on the study:

- **Recruited on Prolific**: the link from Prolific logs you in with your Prolific ID, without typing it. At the end,
  the end page sends you back to Prolific with the completion code (a button, and by itself after 10 seconds).
- **Chat**: a box on the page lets you write to the other players of your group (or your pair, or the session). Write
  plain text only (at most 500 characters).
- **Bots**: some of the other players of your group may be computer programs (bots). The study tells you so in its
  consent or instructions, and may show which players are bots.
- **Language**: the texts the platform adds to the pages (login, waiting room, connection messages) are in the study's
  language (English or French).

## 2.9 Trying the platform: the public demo

When the research team opens it, `YOUR-SITE/demo.php` lists a few studies anyone can try, each with a **Play** button,
without an account: a survey, a public goods game, a coordination game, a timed task, and network games (connectors,
brokerage, linking). You play alone; the other players are bots. Nothing you do there is used for research.

## 2.7 Installing the app and notifications

The home page can be installed as an app:

- **Chrome or Edge** (Android, Windows, Mac): click **Install the app** on the home page.
- **iPhone and iPad**: in Safari, tap **Share**, then **Add to Home Screen**.

The installed app opens the home page, already logged in.

On the **Account** tab, **Notify me on this device when a new study I can join opens** turns on notifications for the
device you are using. They also need **Email me when new studies are available** to be ticked. On iPhone and iPad,
notifications only work once the site is added to the home screen.

## 2.8 Your account: email, log out, deletion

On the **Account** tab:

- **Use another email address** sends a confirmation link to the new address. Your account (details, bank details,
  studies) moves to it once you click the link; until then nothing changes. Your previous address is told about the
  change.
- **Log out of this browser** ends the login on this browser; **Log out on all my devices** ends it everywhere.
- **Delete my account** deletes your email address, your details and your bank details. Your anonymous study answers
  are kept, with no link to you. This cannot be undone.

# Part B. Researchers

# 3. Key ideas

| Term | Meaning |
| --- | --- |
| **App** | The code of an experiment: its pages, styles, scripts, images, payoffs and bots. |
| **Study** | A run of an app with its own settings, starting values, participants, data, link, control panel and owner. Its pages and scripts are those of its app (nothing is copied). Every app is also its own default study. |
| **Page** | What participants see, one after the other: a start page to log in, then for example instructions, the main task, a questionnaire, the earnings page and the end page. |
| **Main task** | The interactive part, played in groups. A survey without interaction does not need one. |
| **Round, period** | The main task is made of rounds; each round has one or more periods. Results are shown at the end of each round. |
| **Action** | A decision participants make in the main task (for example `contribution` or `choice`). |
| **Brick** | A documented, reusable piece of a page or script (a question, a button, a heading...). |
| **Shared library** | Files, ready-made pages and bricks shared by every app. |

Changing an app's pages or scripts changes them for all its studies. For a version that must not change, create a
new app from it instead (see 5.1).

# 4. Logging in and the admin panel

## 4.1 Logging in

1. Open `YOUR-SITE/home.php` and choose **Researcher** at the top.
2. Type your admin name (or the email linked to your admin account) and your password, then **Log in**.
3. On your own phone or computer, tick **Keep me logged in on this device**: the app then opens the admin panel
   directly. The login ends after 30 days without use, or when you log out.

If your admin account is linked to your participant email, the participant side of the home page also shows an
**Admin** tab, which opens the admin panel after asking for your admin password.

## 4.2 The admin panel

The admin panel (**Platform administration**) has:

- **Header**: who you are logged in as, **My participant account**, **Change my password**, **Log out**, and the
  participant email linked to this admin account (**change** to link or unlink one).
- **Tiles**:
  - **Admin users** (main admin only): administrator accounts and their rights (section 12).
  - **Registered emails**: participants' accounts and who can join each study (section 11).
  - **My apps**: create, edit and delete apps and studies (section 5).
- **Launch an application**: choose an app and click **Launch** to start it on the server (see 10.1).
- **Running applications**: the apps running now, with a link to each one's **Admin page** (control panel), its
  **Participants' link**, and **Remove**.
- **This device**: install the app, and **Notify me on this device when a session of one of my apps is starting**.

# 5. My apps

**My apps** lists every app and study you have a right on, with its type, what **You can** do, and its actions:

- **Open** (or **View** when you can only read it): the app editor (section 6).
- **Launch**: the app is chosen in **Launch an application** on the admin panel.
- **Create an app from it**: a copy that is yours to change and run.
- **Delete** (owner only). An app that has studies cannot be deleted before them.

A link at the top opens the **Shared library** page (section 9.3), with the number of proposals **to review** for the
main admin.

## 5.1 Creating an app or a study

Click **+ Create new** and choose:

- **New app (its own pages and scripts)**, then in **Create from**:
  - **Blank app (a small two-player game to change)**: a login page, a main task where two players each choose a
    number, an earnings page and an end page. Its pages fit phones.
  - an app you can open: a copy has everything of the app (pages, scripts, bricks, settings, starting values, sample
    IDs), never its participants or data.
- **New study of an existing app**, then **Study of app**: the study uses the app's pages and scripts with its own
  settings, starting values, participants, data and link. Several studies can run at the same time.

Names use letters, digits, `_` or `-`. A study name has at most 40 characters.

## 5.2 Apps that come with the platform

The platform comes with complete, working apps: a **survey** (no main task), a **public goods** game, a
**coordination** game and a **timed task** (an individual task with a timer). Every admin can run them. To change one,
create an app from it. The network games of the lab (**connectors**, **connectors2**, **brokerage**, **linking**) are
also on the platform: participants create links in a network shown on screen, in continuous time, and their main page
is made of bricks (9.1). The **public demo** (2.9) plays some of them with bots.

# 6. The app editor

Opening an app shows the editor, titled **Application** with the app's name. It has five tabs: **Parameters**,
**Payoffs**, **Bots**, **Init** and **Pages**. Without a main task, only **Parameters** and **Pages** are shown.

At the bottom: **Back to my apps**, **Save app**, **Test run**, **History**, **Download** and **Upload**.

## 6.1 Saving

- The line next to **Save app** says **Unsaved changes**, or when the app was last saved. A bar stays at the top while
  there is something to save (**Save now**). **Ctrl+S** saves too. You are asked before leaving with unsaved changes.
- **Save app** first checks the settings and the code, in plain words. Errors block the save (for example a minimum
  group size above the maximum, a closing time before the starting time, action names with spaces or dashes, a
  JavaScript syntax error, a missing `computeRewards`); warnings do not. Each problem is shown next to its field and
  listed at the top with a link to it.
- When the app or one of its studies is running, you are told how many participants are in it and asked to confirm.
- A save that gets no answer from the server within 20 seconds is reported with **Retry**; your changes stay in the
  editor. If the app cannot be loaded, saving stays off (a banner says why), so an app is never replaced by empty
  pages.
- New files you add are stored at once, but pages only use them once the app is saved.

## 6.2 Several admins on the same app

- **Live co-editing**: the code editors (pages, payoffs, bots, updateScreen, init) are shared. What one admin types
  appears in the others' editors as they type, and **Undo** only undoes your own typing. The **Parameters** tab is not
  shared live.
- A bar under the title lists the other admins editing the app and where; the page tabs show who is on them; a warning
  appears when someone else types in the page you are on, and a message says when someone else saved.
- If someone saved since you opened the app, your save is refused and you choose: load their version, **Combine**
  both, or save yours over theirs (theirs stays in **History**). **Combine** keeps every setting, script or page
  changed on one side only, merges a file changed on both sides line by line when the changes touch different lines,
  and asks which version to keep for the rest.
- Admins with read rights follow the typing without changing anything. A study shows its app's code read-only.

## 6.3 History, Download and Upload

- **History** lists the last 20 saved versions (time and author) and restores one.
- **Download** saves the whole app (settings, pages, scripts and page files) as one file on your computer.
- **Upload** replaces the app with a file made with **Download**; you see a summary of what it replaces first.

## 6.4 Test run

**Test run** runs the saved app for real in a private test study (`<app>_test`, open for 4 hours, its data deleted at
each test run). Open a participant page from the links it gives. For a main task, a session starts with you alone and
the other seats of the group are played by bots; open more participant pages to play several seats. Delete the test
study from **My apps** when you no longer need it.

## 6.5 Run bot test

**Run bot test** (next to **Test run**) checks the saved app on the server in a few seconds, without a study and
without saving anything:

- each page is answered by bots with random valid answers, its scripts are checked, and pages never reached (after a
  missing page, a page without a button, a question that cannot be answered) are listed;
- every round and period of the main task is played with your bots (7.3) and payoffs (7.2): the report gives the
  points of each player, the points outside the range you expect, and the **rules** you typed (for example
  `effort=10 -> 15`: when every player chooses 10, each gets 15). **Check the payoffs** (Payoffs tab) has **Keep as a
  rule of the bot test**;
- with bots in the groups (7.3), **Also play the rounds in accelerated time** plays the rounds on a virtual clock (a
  5-minute round in a few seconds) with the bots of your plan and simulated participants who make random moves. The
  report gives, for each round and period, each player's moves and wake-ups, their actions at the end and their
  points, the limits the bots reached and their errors. AI bots play as their fallback type there (no paid calls).

It checks the code; it does not replace a **Test run**, where you see the pages as participants do.

# 7. Editor tabs

## 7.1 Parameters

A short explanation of pages, main task, rounds, periods and actions comes first, then the settings in numbered steps.
Each setting has a line of help under it; rarely used ones are under **Advanced settings**.

1. **What the experiment contains**: **Main task**: *Yes, an interactive task in groups* or *No, pages only (a
   survey, a questionnaire)*.
   - **Language of the platform's texts**: English or French, for the texts the platform adds to the pages (login,
     waiting room, connection lost, inactivity, device page). Your own pages stay as you write them.
   - **Treatments** (optional): one per line, a name, `:` and its values, for example `low: MPCR=0.4` and
     `high: MPCR=0.8, endowment=20`. Each participant (or each group, whose players then share it) gets one, drawn so
     that each is given about as often as the others. The treatment is saved with the participant (it is in the data),
     shown in pages with `{{treatment}}`, and its values replace the values of the same names at the top of
     `payoffs.js` and `bots.js` for that group.
2. **Who can join**:
   - **Participants log in with their email address instead of an ID** (a one-time confirmation link; the same
     browser then logs in directly). Optionally, **Only accept emails from these domains** (a domain also accepts its
     subdomains).
   - **Show this study on the participant portal**, with the **Title shown to participants** and a **Short
     description**.
   - **Paid study**: participants need bank details in their account to log in.
   - **How many sessions one participant may take part in** (usually 1; 0 = no limit).
   - **Recruited on Prolific**: on Prolific, give the study link followed by
     `?PROLIFIC_PID={{%PROLIFIC_PID%}}&STUDY_ID={{%STUDY_ID%}}&SESSION_ID={{%SESSION_ID%}}` (Prolific's option "I'll
     use URL parameters"). Participants are logged in with their Prolific ID. Set the **Completion code** (the end page
     sends participants back to Prolific with it), the **Code for participants released from the waiting room**, and
     the **Fixed reward paid on Prolific** (the control panel's Prolific bonus file gives each participant their
     earnings minus this amount). **Other panels: link back at the end** sends participants to another panel's page.
3. **Devices**: **Desktop**, **Tablet**, **Phone** (all by default). Other devices see the study's description and a
   message saying which device it needs; on the home page the study is shown but cannot be opened. A phone is a touch
   screen whose shorter side is under 600 px, a tablet a touch screen of 600 to 1100 px (or an iPad); everything else
   is a desktop. Set the same restriction on your recruitment website.
4. **Groups and rounds** (**Session size** without a main task):
   - number of groups in a session, minimum and maximum group size, maximum number of sessions (0 = no limit);
   - **Forming sessions from the waiting room**: **Fill** (at the start time, sessions of the maximum size, then a
     session as soon as the minimum number is waiting) or **Balanced** (sessions of balanced sizes, then a session
     with everyone waiting);
   - **Who plays with whom in each round**: fixed groups, random with fixed groups, or random across groups;
   - **Actions**, comma separated (letters, digits and `_` only), and the actions every participant must make before
     the period can end;
   - number of rounds, and for each round the periods, their durations (0 = no timer) and the paid moments, with
     buttons to copy values across periods, rounds and groups, or to draw paid moments and periods at random;
   - **Actions kept from one period or round to the next**.
   - **What players receive of the others' moves during the round**: *Everything* (the default), *Only their own
     moves*, *Only the group's sum, mean, lowest and highest*, or *The actions listed here* (seen by all; the others
     only by their owner). What is hidden is never sent to the other players' browsers, not only hidden on the page;
     the server then computes the payoffs and sends each player theirs. The admin pages and the data keep everything.
     In a network game, keep the network action in the list, or the others' links cannot be drawn.
5. **Timing**: experiment starting and closing times (typed in your own time zone, shown next to the fields), maximum
   time in the waiting room, maximum wait for the other players before a round, pause before a new period, maximum
   time on the results of each round.
6. **Payments**: points per unit of currency, show-up fee (paid to everyone who logs in, also to those who cannot be
   placed in a session), participation fee (paid to those who finish), initial endowment, how several paid moments
   are combined (sum or average), and whether negative final earnings are raised to 0. **Paying account** (also for
   apps without a main task): the account holder, IBAN, BIC, currency and the transfer date proposed, for the SEPA
   transfer file of the Payments page (10.4). The IBAN is kept encrypted on the server, apart from the settings: the
   editor only shows its last 4 characters, and only the main admin and the app's owner can set, replace or remove it.
   Without one, the platform's account is used, if the main admin set one (13.1).
7. **Time per page**: for each page, a time limit and an activity check (a pop-up asking an inactive participant to
   confirm they are still there), the time to answer that pop-up, and the disconnection delay.

**Advanced settings**: who moves timed periods on (server or client), delay before showing the others' actions, where
points are computed, bots for offline participants, what happens to the data when the study is launched again (keep
and archive, or delete), and actions entered as a network.

## 7.2 Payoffs

The **Payoffs** tab edits `js/payoffs.js`:

- The values at the top of the file (`var NAME = number; // what it is`) are shown as fields.
- **The payoff as a formula** writes the payoff function from one line using `mine.ACTION`, `sum.ACTION`,
  `mean.ACTION`, `min.ACTION`, `max.ACTION`, `n` and the values above, checked in plain words.
- **Check the payoffs** computes the points of 2 to 4 players with the actions you type.
- The code editor shows the function `computeRewards(data)`, which receives the actions of the group and returns
  `{ pay: [...] }`, one number per player.

`payoffs.js`, `bots.js` and the settings run on the server in a protected sandbox: they cannot reach the server or its
data, and a call that takes too long (an endless loop) is stopped. When the code fails, players get 0 points for that
call and a bot keeps its actions; the control panel shows the error (**The code of this app has errors**). The
participants' browsers load `payoffs.js` (the page computes the points it shows), never `bots.js` or the settings.

## 7.3 Bots

The **Bots** tab sets three kinds of bots.

**Bots for participants who leave.** When **Bots** is set to *Replace offline subjects with bots* (Parameters,
Advanced), a bot plays for a participant who went offline, at the end of each period. The form sets, for each action,
what a bot chooses: a random value in a range, the same as in the last period, the mean of the other players, or a
fixed value. It writes the function `bot_inactivity` of `js/bots.js`. Code changed by hand is not replaced without
asking.

**AI bots.** **Bots ask a language model** makes those bots ask a model (Anthropic) for their actions at the start of
each period. Set your **API key** (from console.anthropic.com: your account pays the calls; kept encrypted on the
server and shown as "Saved: •••• 1234"; only the main admin and the owner can change it), the **Model**, **Thinking**,
the **Longest wait for an answer**, the **Calls per session, at most**, and what happens **On a refusal**. Write **What
the model is told**: describe the game and its payoffs, with values such as `{{round}}`, `{{me}}`, `{{actions}}`,
`{{group}}`, `{{treatment}}`; save it with **Save the text** (it is kept on the server, never in the files
participants can load). An answer that comes too late, an error or the end of the calls: the bot plays with the form
above.

**Bots in the groups.** Tick **Bots in the groups** to put bots in the free seats of each group, playing during the
round as participants do (set the group size to participants + bots):

- **Bot types**: a name, what it **Plays with**: *Script* (its behaviour written in `bots.js` with
  `bots.define('name', { onPeriodStart, onEvent, onWake, decide })`: it sees each move of the group, can wake itself up
  later, and acts with `ctx.act`, or `ctx.link` / `ctx.unlink` in a network), *Form* (the bots for participants who
  leave, at the end of each period) or *AI* (a language model chooses its moves among the actions of the game; it is
  asked at most every N seconds, and its fallback Script type plays when it cannot answer); and a **Reaction time**
  (a random delay before each move, so that bots do not answer instantly).
- **Bots of each type in each group, round by round**: a table with one row per round.
- **Participants see the bots as**: *ordinary players*, or *bots* (the main page is told which seats are bots and can
  label them).
- Participants must be told that bots may play: the form gives a sentence to add to the consent or the instructions.
  Saving warns when no page mentions bots, when a Script type has no `bots.define`, and when there are more bots than
  free seats.

The bots' moves are checked like a participant's and saved in the data (marked as bots, with their type; they are not
paid); the analysis file has a row per bot. Each call of a bot is logged. Try them with **Run bot test** (6.5).

## 7.4 Init

The **Init** tab sets the values the experiment starts from, saved as CSV files in the app's `init/` folder:

- **Starting values of the actions** (required for a main task), **Signals of the players** and **Outcomes of the
  groups** (optional), and **Allowed or blocked participant IDs** (a white list or black list of IDs, used when
  participants log in with an ID).
- Choose the group and round, then type the values. **Copy round → all rounds**, **Copy group → all groups** and
  **Copy player 1 → all players in group** fill the table quickly.
- **Paste from a spreadsheet** accepts cells copied from Excel or another spreadsheet. **Load existing init file**,
  **Download CSV** and **Delete CSV file** manage the files.
- The checks before saving point out starting values that are text among numbers, and network links outside the
  group.

## 7.5 Pages

The **Pages** tab shows the participants' path as boxes joined by arrows: **Start**, your pages in order, **Main**,
**Earnings**, **End**.

- Click a box to edit the page. Drag a box (or use **Move earlier** / **Move later**) to change the order. Start,
  Main, Earnings and End stay in place, and Earnings always follows Main. **Delete this page** removes a page.
- The email login pages are in a group of their own, shown only when email login is on. Other pages that are not in
  the path are under **Pages not in the path**.
- **+ Add page** opens **Add a Page**:
  - **Ready-made questionnaires**: Demographics, Big Five personality, Risk attitude, Social preferences, Payment
    details. One click adds the page; its answers are stored in a table of their own.
  - **Pages made of bricks**: Consent page, Short questionnaire. Change them in their Design view.
  - Or a page of your own: empty, copied from another app's page, or uploaded from your computer, with its name and
    where to insert it.

Under the header of each page:

- **Show only if**: a condition checked when the participant reaches the page; when it does not hold, the page is
  skipped. A condition compares `treatment`, `round` or an earlier answer (`PAGE.NAME`, for example
  `consent.agree = 1`) with a value, with `=`, `!=`, `<`, `<=`, `>`, `>=`, joined by `and` / `or`.
- **Randomize the order of this page with the other ticked pages**: the ticked pages swap places at random for each
  participant; the order is saved with the participant.

Each page has two views, **Design** and **Code** (sections 7.6 and 7.7), and a live **Preview** on the right (section
8). The editor remembers the view you last chose for each page; a page made of bricks opens in Design.

Pages are plain HTML and never run on the server. They show values with placeholders: `{{my_id}}` (the participant's
identifier), `{{final_earnings}}` and `{{show_up_fee}}` (end page), `{{url}}`, `{{app}}`, `{{session}}`.

## 7.6 The Design view

The Design view shows the page as cards, in order: each brick with its fields, and **Custom HTML** for code outside
bricks (kept as it is).

- **Add a brick** from the list on the left: search it by name or purpose, click **?** to see what it is for, then
  click it to add it after the selected card (or before the button that ends the page), or drag it into the page.
- **Move** cards by dragging their handle (a line shows where they land) or with the arrows; **duplicate** or
  **remove** them.
- **More** has **Show in the code**, **Save this card as a brick** (with its current values as defaults) and
  **Detach from brick** (keeps its HTML as Custom HTML).
- A question added or duplicated gets an answer name of its own (`satisfaction`, `satisfaction_2`...).
- A brick with style options has a collapsible **Style** part on its card: text colour, background, width, alignment,
  text size, space above and below, depending on the brick. An empty field keeps the brick's own look.
- A card whose code was changed by hand shows **changed in the code**; a newer version of a brick shows **Update to
  version X**, with the code before and after.
- The view checks the page: actions the app does not have, two questions saved to one answer name, a missing submit
  button, questions without the button that saves them, a start page without its login form. Under the cards, **What
  this page records** lists its answer names and actions.
- Once the app has been launched, removing or moving the options of a question asks first (the answers saved are the
  numbers of the options).

Every change goes straight into the page's code, so saving, History, Undo and live co-editing work as in the Code
view, and changes made in the code rebuild the cards.

**On the main page** (`main.html`), each brick also has **Shown**: *always*, *while waiting*, *during the decision*,
or *with the results*. The platform shows it at that moment of the round. Texts can include values of the round:
`{{round}}`, `{{points}}`, `{{mine.ACTION}}`, `{{others.ACTION}}`, `{{sum.ACTION}}`, `{{mean.ACTION}}`,
`{{min.ACTION}}`, `{{max.ACTION}}`, and `{{result.NAME}}` for any other value the payoff function returns. The waiting
message has a text for each wait (before round 1, after submitting, when the time is up, after the results).

## 7.7 The Code view

The Code view is a code editor for the page's HTML.

- **Insert a brick...** puts a brick at the cursor with its default values; **Set it in the Design view** then opens
  its card.
- **Save as brick** turns the selected code into a brick of the app: its name, its documentation, the type and label
  of each `[[setting]]` in its code, and, if wanted, the usual style options. If the name is already used, you can
  replace that brick by its next version.
- The code editors complete the platform's functions and values (**Ctrl+Space**, or as you type). Typing
  `updateScreen`, `setup`, `computeRewards`, `updateActions`, `bot_inactivity` or `timer` then **Tab** inserts a
  ready-made piece of code.
- Script editors have **Insert a function...** (the functions of a script brick) and **Save as brick**.

## 7.8 Files of a page

Page files (CSS, JavaScript, images, audio, video) live in the app's `css/`, `js/`, `images/`, `audios/` and `videos/`
folders, and any page can use any of them. Each page's panel lists the files it uses and which other pages use them.

**Add a file to page** offers: **A file of this app**, **From the shared library**, **Upload from my computer**,
**Copy from another app**, or **New empty file**. Removing a file from a page only removes the reference; files no page
uses can then be deleted when you save.

## 7.9 The main page and its optional scripts

The platform shows `main.html` at each moment of the round by itself, so most apps need no script of their own. Two
optional scripts exist for what it does not do:

- **updateScreen.js**: for what the platform does not show (continuous time, a network, colours, feedback of your
  own). It receives `obj` (the state of the round) and `event_flag` (what just happened).
- **init.js**: to build something once when the page opens, in `function setup() { return {...}; }` (its result is
  `obj.setup`).

Each has a tab only when the app has it. **+ Add updateScreen.js** and **+ Add init.js** above `main.html` create it
with a ready-made start. A file left with no code (empty, or comments only) is removed when the app is saved; the save
message says so, and **Undo** there (or **History**) brings it back.

The Main page has a reference under the editor: the `data-*` attributes of `main.html` (`data-moment`,
`data-waiting-for`, `data-rounds`, `data-value`, `data-timer`), the functions a page can call (`updateActions`,
`submit_choice`, `next_round`, `computeRewards`, `timer`), and, under **Advanced**, the values of `event_flag` and the
rest of `obj`.

| Moment (`obj.moment`) | Waiting for | When |
| --- | --- | --- |
| `waiting` | `start` | before round 1 |
| `decision` | | the round is played |
| `waiting` | `choices` | this participant submitted, or the period ended: the others are still choosing |
| `waiting` | `time` | the time of the period is up |
| `results` | | the round is over |
| `waiting` | `continue` | this participant clicked Continue, the others have not yet |

# 8. The previewer

The previewer shows a page as participants see it, on what is in the editor now, saved or not (labelled **Draft, not
saved**). Nothing is saved when it opens.

- **Preview** (right of the Design view): a live preview that follows every change. **Hide** folds it.
- **Open the full preview** (in the header of each page): the previewer in its own tab, with its controls. It follows
  your edits as you make them.
- **Phone / Tablet / Desktop** set the width of the preview (the page's own CSS for small screens applies; touch is
  not simulated), with a note when the app does not accept that device.
- **Try the page** (main page): choose **You are** (your player number) and the **Round**, then click a moment:
  **Before round 1**, **Start of a round**, **Others choose**, **I submit**, **Timer ends**, **Results**, **Continue**.
  **Random choices for the others** gives the other players random actions. Every raw value of `obj`, the server
  simulation and `event_flag` are under **Advanced**.
- **Errors in the page code** lists errors with the file, the line and a hint, for example
  `missingThing is not defined (in js/updateScreen.js line 48)`. **Clear** empties the list.

Opened from a link without the editor, the previewer shows the saved version of the app.

# 9. Bricks and the shared library

## 9.1 Bricks

A brick is a documented piece of a page or of a script. Its card in the Design view shows its fields (texts, answer
names, options, actions...) and, for most bricks, style options. Bricks come from the shared library (for every app)
or from an app (its own bricks).

Bricks of the library, by category:

| Category | Bricks |
| --- | --- |
| Text and media | Heading, Paragraph, Image |
| Questions | Question: one choice, Question: number, Question: scale, Question: slider, Question: text answer, Question: a grid of statements, Question: a drop-down list, Consent box, Save the answers of a page |
| Questionnaires | Lottery choice list (risk attitude: one row drawn and played), Sharing points with another person (social value orientation sliders, one question paid) |
| Buttons | Button: continue (no answers), Button: save the answers and continue |
| Start page | Login form |
| Main task | Decision: one option, Decision: a number, Decision: a slider, Decision: a slider sent at once (continuous time), Button: submit the decision, Record the decisions of the main task, Waiting message, Result of the round, Button: continue after the results, Timer of the round, Table of values, Network (players and their links), Chat |
| Results | Earnings summary (the earnings page) |
| Scripts | Countdown display |

Bricks combine: the question bricks are saved by **Button: save the answers and continue**, which saves every answer of
the page in the page's own table; the decision bricks are recorded by **Button: submit the decision**.

The ready-made questionnaires (Big Five, Demographics, Risk attitude, Social preferences) and the earnings pages are
made of these bricks, so their texts, options, amounts and codes can be changed in the Design view.

When a newer version of a brick used in a page is in the library, the page's header says so, with **Update it here**.

## 9.2 Shared files

Files used by several apps belong in the shared library rather than in each app: in the editor, **Add a file** →
**From the shared library**. A change to a shared file applies to every app that uses it, including running ones.
**Use an app copy** gives an app its own copy of a shared file to change. An app file identical to a shared file shows
**Use the shared file instead**.

## 9.3 The Shared library page

The **Shared library** page (linked from **My apps**) shows one item at a time, chosen in a menu per category: bricks
(grouped by purpose), ready-made pages, CSS, JavaScript, images. For each item: its description, how to use it, its
fields and style options (bricks), its files, the apps using it (files), its history, any change waiting for it, and
the form to change it. Its address names the item, so you can share a link to it.

## 9.4 Proposing changes

Every admin can propose:

- a new file (**Propose for the shared library** on a file of their app, with its documentation);
- a change to a shared file or to its documentation;
- a new brick (**Save as brick**, then **Propose it**), or a new version of a shared brick (**Propose a change**).

Proposals take effect only once the main admin accepts them. The main admin sees **To review (N)** first in the menus,
with each proposal's diff and author, and **Accept** or **Reject**; the main admin's own changes apply at once. The
author can **Withdraw** a proposal. While a change waits, pages keep using the accepted version, and every replaced
version is kept in the item's history.

# 10. Running a study

## 10.1 Launch

On the admin panel, choose the app in **Launch an application** and click **Launch**. The app appears under
**Running applications** with its **Admin page** (control panel) and **Participants' link**
(`YOUR-SITE/Apps/<name>/game.php`).

## 10.2 The control panel

The control panel of a study shows:

- **Open access**: lets participants in. A checklist comes first (pages present, payoffs defined, start and closing
  times, devices, a test run since the last save, email settings, starting values of the actions), each problem with
  a link to the place to fix it in the editor. **Open anyway** opens it despite the problems.
- **Close to new participants**: stops new logins and releases the waiting room, while sessions in progress continue.
  **Reopen to new participants** undoes it.
- **Stop the experiment**: closes the study for everyone, participants in a session included.
- **Reset Experiment**: restarts the study (participants are logged out).
- **Download data**: a zip file of the study's data, every table as it is.
- **Download analysis file**: a zip ready for R, Stata or Excel: one row per participant, round and period (actions at
  the end of the period, payoff, final earnings, and the answers of the pages, one column per answer); the time spent
  on each page; the chat messages; and a dictionary of the columns.
- **Chart of the rounds** (under the session shown): the mean, smallest or largest value of an action in each group
  and round, updated while it is open.
- **Payments**: the payments page of the study (10.4). **Prolific bonus file** (studies recruited on Prolific): the
  bonus of each participant, ready to upload to Prolific.
- **Reset database**: archives the data and starts with empty tables, or deletes it, depending on the study's
  setting. A line shows how many rows the database holds. Download the data first if you need it.
- The main settings (times, rounds, group sizes, fees, periods, time per page), which can be changed here. Restart the
  experiment after a change, and avoid changes while it is running.
- **Show Init Files**: the study's starting-value files, to download or replace.
- The number of connected participants and, for a chosen session, each participant's ID, status, page, group, round,
  period, activity and earnings.

When you click **Open access** on a study shown on the home page, participants who asked for notifications receive
one (once per study). Admins who turned on notifications get one when a session of
their app is starting.

## 10.3 Waiting room and disconnections

- Participants who arrive before the start time wait; sessions are formed as set in **Forming sessions from the
  waiting room** (7.1). A participant who does not join their planned session within 30 seconds is replaced by the
  next one waiting. Participants still waiting when no session can start any more are released with the show-up fee.
- **Maximum wait** starts a round with the players who are ready after that many seconds, if they are enough.
- A participant who disconnects: after the disconnection delay the others stop waiting for them, and they join again
  if they come back. On pages with an activity check, they are excluded instead.

## 10.4 Paying participants: the Payments page

**Payments** (control panel) lists each participant of the study: status (finished, released from the waiting room
with the show-up fee, not finished), earnings (show-up fee included), account holder and IBAN from their account
(masked, except for the main admin and the study's owner), and **Paid**, ticked by an admin (saved with who ticked it
and when). Files, for everyone or **only those not paid yet**:

- **CSV for the accountant**;
- **Prolific bonus file** (studies recruited on Prolific);
- **SEPA transfer file** (main admin and owner only): one transfer per participant with bank details, from the paying
  account of the study (7.1, step 6) or of the platform, on the transfer date you choose. Upload it to your bank.

Making a file ticks nobody: tick **Paid** once the transfer is done.

# 11. Registered emails

The **Registered emails** page manages participants who log in by email. You see the emails used in the apps you can
edit.

- **Registered emails**: emails used in each app, with their status (verified, waiting for confirmation, not
  confirmed), filters, **Download as CSV** and **Delete all listed**.
- **Participant accounts**: the accounts of the home page (name, details, last login, studies), and **Duplicate IBAN
  attempts**.
- **Study access**: rules per study to **allow** or **block** emails or domains (for example `uni.example`). With no
  rule, every verified email can join. Rules only apply to studies with email login.
- **End of data collection**: **End data collection for this app** stops participants from logging in to it. This
  cannot be undone.
- **Contact list for future studies**: participants who asked to be told about new studies.

# 12. Admin users and rights

The main admin manages administrators on **Admin users**:

- **Create a new admin**: an admin name (letters, digits, `. _ @ -`), an optional email (which links their participant
  account) and a first password (at least 8 characters). **Set password** / **Reset password** and **Delete** manage
  existing admins.
- **Rights** on each app:
  - **Read**: open it read-only, see its control panel and data, create an app from it;
  - **Run**: also launch it and use its control panel, without changing it;
  - **Write**: change it and run it.
  The **Owner** has every right; **make owner** and **give back to main admin** change the owner.
- **All admins**: gives a right on an app to every admin, including the ones added later. The control panel of an app
  every admin can run says that its runs and data are shared.

Every admin can change their own password from the admin panel (**Change my password**); this logs out their other
sessions.

# 13. For the main admin: the platform's settings

## 13.1 Settings of the server

Some settings are in the server's `server/settings.js` (see `settings.example.js`), changed by whoever runs the
server, then Node restarted:

- `params.sepa`: the platform's paying account, for the apps that set none.
- `params.ai`: a platform API key for the AI bots of the apps that set none, and the most calls a session may make
  (a ceiling for every app, even with its own key).
- `params.demo`: the public demo (2.9): on or off, its apps, and how often its studies start again.

## 13.2 Docker

The platform can also run in Docker (`docker compose up -d --build`): the web pages, the experiment server and the
database in three containers, with the settings in a `.env` file. It gives the same platform on any computer or server
(a second lab, a new server, a test before an update). See `DOCKER.md` in the software folder.

## 13.3 What the web server sends

Participants' browsers get only what the pages load: never the apps' settings, bots, starting-value files (except
those named `NAME.public.csv`, which a page loads itself), pages not reached yet, notes, logs or participant lists.
The rules come with the software; on a server whose Apache does not read them, copy the platform's rules file once
(`SETUP.md`, "Web access rules"). To check a live site, run `sh server/tools/check_web_exposure.sh YOUR-SITE`: every
line must say PASS.

# 14. Quick reference

| I want to... | Where |
| --- | --- |
| Create an experiment | My apps → + Create new → New app |
| Run the same app with other settings | My apps → + Create new → New study of an existing app |
| Add a questionnaire | Editor → Pages → + Add page |
| Build a page without code | Editor → Pages → a page → Design |
| See a page as participants do | Preview, or Open the full preview |
| Try the app with bots | Editor → Test run, or Run bot test |
| Give participants different treatments | Editor → Parameters → Treatments |
| Skip a page for some participants | Editor → Pages → a page → Show only if |
| Recruit on Prolific | Editor → Parameters → Recruited on Prolific |
| Put bots in the groups | Editor → Bots → Bots in the groups |
| Hide the others' moves | Editor → Parameters → What players receive of the others' moves |
| Let participants in | Admin panel → Launch, then control panel → Open access |
| Get the data | Control panel → Download data, or Download analysis file |
| Pay participants | Control panel → Payments |
| Limit a study to some emails | Registered emails → Study access |
| Share a file or brick with all apps | Propose it for the shared library |

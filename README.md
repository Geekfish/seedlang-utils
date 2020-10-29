# seedlang-utils
⚠️ **Unofficial** ⚠️ scripts for seedlang.com

## Retire Review Bookmarklet

This is a helper bookmarklet to let you easily retire review cards with a single click.

It is meant to be used during [reviews](https://www.seedlang.com/reviews/decks/review) on [seedlang.com](https://www.seedlang.com).

### Usage

With a review card currently visible, click the bookmarklet to immediately retire the card. 

### Installation

#### Firefox

- **Right click** on your bookmarks bar (if it's not visible, [see here](https://support.mozilla.org/en-US/kb/bookmarks-firefox#w_how-to-turn-on-the-bookmarks-toolbar)).
- Select **"New Bookmark..."**
- Give the bookmark a *Name*, like `Retire Review`
- In the *Location* field, paste the code found in [retire_review.js](./bookmarklets/retire_review.js).<br>
  Make sure you select the entire line, and that it's all in one line.
- Click **Add**

#### Chrome

- **Right click** on your bookmarks bar (if it's not visible, [see here](https://support.google.com/chrome/answer/188842)).
- Select **"Add Page..."**
- Give the bookmark a *Name*, like `Retire Review`
- In the *URL* field, paste the code found in [retire_review.js](./bookmarklets/retire_review.js).<br>
  Make sure you select the entire line, and that it's all in one line.
- Click **Save**


## WordReference Translation Lookup

This is a helper bookmarklet to let you easily lookup a word on the WordReference dictionary.
This could be used by translators who need extra references from various dictionaries.

✅ This will also work on other websites, not just Seedlang.

### Usage

1. Highlight the word you want to lookup
2. Click the bookmarklet
3. A new window should open in your browser with a dictionary lookup.

### Select Language

You need to configure the bookmarklet before you can use it:

1. Open [wordref_translation_lookup.js](./wordref_translation_lookup.js)
2. Find the part of the text that says `REPLACE_ME`
3. Replace `REPLACE_ME` with the language combo you need, for example for English to Greek you would set `engr`. <br>
   You can identify the exact language codes by selecting the dictionary you want at https://wordreference.com and looking at the URL.<br>
   Some examples:
    - English -> Greek (`engr`): https://www.wordreference.com/engr/
    - German -> Spanish (`dees`): https://www.wordreference.com/dees/
    - English synonyms: https://www.wordreference.com/synonyms/

### Installation

#### Firefox

- **Right click** on your bookmarks bar (if it's not visible, [see here](https://support.mozilla.org/en-US/kb/bookmarks-firefox#w_how-to-turn-on-the-bookmarks-toolbar)).
- Select **"New Bookmark..."**
- Give the bookmark a *Name*, like `English -> Greek`
- In the *Location* field, paste the code you have configured at the `Select Language` step above.<br>
  Make sure you select the entire line, and that it's all in one line.
- Click **Add**

#### Chrome

- **Right click** on your bookmarks bar (if it's not visible, [see here](https://support.google.com/chrome/answer/188842)).
- Select **"Add Page..."**
- Give the bookmark a *Name*, like `English -> Greek`
- In the *URL* field, paste the code you have configured at the `Select Language` step above.<br>
  Make sure you select the entire line, and that it's all in one line.
- Click **Save**

## Bookmarklets in other browsers

I have not tested other browsers, but the process should be similar to the above.

## Limitations

- This is in no way supported by the official Seedlang app.
- It relies on the Seedlang app not changing its web interface (which it occasionally does). In that case these utils might break, with unexpected results.
- ⚠️ **When you retire a review you do not get any points**. Please take this into account before you go into a retirement spree 🔥

# Contenteditable Code Block

A Google Chrome extension that takes `<pre>` tags loaded in your browser's DOM that
 are often used as code blocks and turns them into editable code blocks/snippets.

You might be thinking: "why do I need this?" or "how is it helpful?". The answer is
 simply it cuts out a lot of unnecessary copy and pasting if you use any of the
 supported sites. For me: I no longer need to copy from the site to my IDE, make my
 changes, copy it _again_, then paste it into my destination (whether that be the
 terminal or my web browser).

## Supported Sites:

* app.getguru.com
* docs.aws.amazon.com
* github.com
* stackoverflow.com
* trello.com
* unix.stackexchange.com
* zendesk.com
* *.atlassian.net (both confluence and JIRA)

## Install:

As of right now, this extension is not available via the Google Chrome Web Store.
 This requires you to install it via Developer mode.

1. `cd` into the directory you want to put the extension
1. Run the following command to pull down the files:

  ```
  git clone git@github.com:philipjewell/contenteditable-code-block.git
  ```

1. Navigate to: `chrome://extensions/`
1. Check the box that say **Developer mode**
1. Select the **Load unpacked extension...** button
1. Select the **contenteditable_code_block** folder that should be located in your
 desired directory from step #1
1. Check the **Enable** box to the extension

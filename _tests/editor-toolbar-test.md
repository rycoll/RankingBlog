---
title: Editor Toolbar Test
layout: test
test_html: >-
  <p>Test: <strong>bold</strong>, <em>italicise</em>, <a
  href="/tests/editor-toolbar-test.html">link</a>.</p><blockquote><p>Quote,
  <strong>bold</strong>, <em>italicise</em>, <a
  href="/tests/editor-toolbar-test.html">link</a>.</p></blockquote>
test_markdown: 'Hello, this is a test for Markdown rich text.'
---

Content editor:

Testing the editor toolbar. Bold **this** word. Italicise *this* word. Bold and italicise ***this*** word.

Visual Editor:

Testing the editor toolbar. Bold **this** word. Italicise *this* word. Bold and italicise ***this*** word.

> Quote indent this.

Link [this](/tests/editor-toolbar-test.html) somewhere.

> Bold, italicise, quote indent, and link [***this***](/tests/editor-toolbar-test.html).

Front matter:{{page.test_html}}{{page.test_markdown}}

From data file:
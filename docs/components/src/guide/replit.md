---
title: Replit
---

Embed Replit demo in Markdown files.

<!-- more -->

## Demo

A replit:

<Replit user="FuckDoctors" repl="Java-Test" />

```md
<Replit user="FuckDoctors" repl="Java-Test" />
```

A replit with opening file:

<Replit user="FuckDoctors" repl="Java-Test" file="Main.java" />

```md
<Replit user="FuckDoctors" repl="Java-Test" file="Main.java" />
```

An autoload replit:

<Replit user="FuckDoctors" repl="Java-Test" auto-load />

```md
<Replit user="FuckDoctors" repl="Java-Test" auto-load />
```

A repl with link:

<Replit link="https://replit.com/@FuckDoctors/Java-Test" />

```md
<Replit link="https://replit.com/@FuckDoctors/Java-Test" />
```

## Props

### link

- Type: `string`
- Required: Yes

Replit link.

### user

- Type: `string`
- Required: Yes

Replit username.

### repl

- Type: `string`
- Required: Yes

Replit repl name.

### title

- Type: `string`
- Required: Yes

Replit title.

### width

- Type: `string | number`
- Default: `100%`

Replit component width.

### height

- Type: `string | number`
- Required: No

Replit component height.

### ratio

- Type: `number`
- Default: `16 / 9`

Replit component ratio, ONLY valid when `height` not set.

### autoLoad

- Type: `boolean`
- Default: `false`

Wether auto-load ReplIt.

### text

- Type: `string`
- Default: `"Load ReplIt"`

Load button text.

### theme

- Type: `string`
- Default: `"light"`

Replit theme.

### file

- Type: `string`
- Required: No

The default file to have open in the editor.

Robust Maliit Keyboard with crash fixes
=======================================

This project is co‑authored by Qwen (mostly) and Gemini as the code reviewer.
However, this is not *vibe coding* in any sense. Here is my workflow with the AIs:

1. AI analyze existing code
2. AI summarize its understanding
3. I verify or correct that understanding
4. I define the requirements or the bug
5. AI implements the solution
6. I get another AI (in this case Gemini) to review the changes, and I repeat this step back and forth several times
7. Finally, I make the final decision

However, if this AI‑assisted workflow isn’t something you’re comfortable with, you’re welcome to skip it.

To install this package on Fedora, run the following commands:

```console
$ sudo dnf copr enable cwt/maliit-keyboard-robust
$ sudo dnf install maliit-keyboard-robust --allowerasing
```

This package will replace the installed maliit-keyboard so `--allowerasing` is required.

---

**Above is the ROBUST fork information. Below is the original README content:**

---

Maliit Keyboard
===============

Maliit Keyboard is a free software virtual keyboard for Linux systems with Wayland and X11 display servers. It supports many different languages and emoji. It is implemented as a plug-in for Maliit Framework.

Maliit Keyboard evolved from the [reference keyboard plug-in](https://github.com/maliit/plugins), [Ubuntu Keyboard](https://launchpad.net/ubuntu-keyboard) and [Lomiri Keyboard](https://github.com/maliit/keyboard/pull/60). Ubuntu Keyboard was a fork of the reference plugin which was taking into account the special UI/UX needs of Ubuntu Phone.

License
-------
The license of the combined work is LGPL-3.0-only.

The majority of individual files in `src` are under a BSD license as written in `COPYING.BSD`.

The majority of individual files in `qml` are under LGPL-3.0-only. New contributions in that directory should be licensed under LGPL-3.0-or-later or aforementioned BSD license.

All new code outside the `qml` directory should be licensed as defined in `COPYING.BSD`.

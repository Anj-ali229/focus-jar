Focus Jar 🏺

A lightweight, single-file Pomodoro focus timer and visual productivity tracker built with plain HTML, CSS, and JavaScript—with zero external dependencies.

Fill your jar with focused time: every completed Focus session drops a marble into your collection jar, helping you track both today's momentum and your all-time progress.

✨ Features

Visual Liquid-Fill Countdown Timer: Large, tabular MM:SS countdown display inside a stylized jar whose liquid level drains smoothly as time elapses.

Focus & Break Modes + Custom Durations: Switch between Focus (default 25 min) and Break (default 5 min), or enter your own custom session lengths (1–180 minutes).

Dynamic Controls: Toggle seamlessly between Start and Pause, or Reset the timer at any time.

Synthesized Audio Chime: Plays a pleasant 4-note ascending major chime (C5 → E5 → G5 → C6) using the browser's native Web Audio API whenever a session ends—no external audio files needed.

Built-In Task List (XSS-Safe): Add tasks, click any task to cross it off, or remove items with the × button. Uses textContent instead of innerHTML to safely render user input without Cross-Site Scripting (XSS) risks.

Animated Marble Collection Jar: Completing a Focus session drops an animated marble into the collection jar (Break sessions do not add marbles).

Today vs. All-Time Tracking: Tracks today's completed marbles separately from your all-time total, highlighting today's marbles in indigo and automatically resetting the daily counter at midnight.

Demo Speed Mode: Check Demo speed (1s = 1min) to run the timer at 60× speed for quick testing.

Automatic Persistence: Saves your tasks, custom durations, and marble counts in localStorage so everything stays intact across page reloads.

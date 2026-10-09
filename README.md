<!--
  YUNUS · PLAYER 1 · pixel profile README
  Type: Silkscreen (SIL OFL 1.1, see assets/Silkscreen-OFL.txt).
-->

<a href="https://yunus.digital"><img src="assets/v2/hero.svg" width="100%" alt="Pixel-art title screen: YUNUS, full-stack and cloud engineer. Useful tools. Playful worlds. A red-hooded hero walks to a campfire, stomps a code bug and collects a coin."></a>

<p align="center">
  <a href="https://yunus.digital"><img src="assets/v2/btn-portfolio.svg" height="52" alt="Portfolio"></a>&nbsp;
  <a href="https://x.com/MohammediYunus_"><img src="assets/v2/btn-x.svg" height="52" alt="Follow on X"></a>&nbsp;
  <a href="https://mohammediyunus.github.io/yunus-os/"><img src="assets/v2/btn-demo.svg" height="52" alt="Try Yunus OS in your browser"></a>
</p>

<img src="assets/v2/player.svg" width="100%" alt="Player 1 character sheet with Yunus's photo. Class: full-stack and cloud engineer. Party: Claude, build partner. Inventory: Yunus OS, dwago, capture-check, and Hushfall in development.">

Hey, I’m Yunus. I build useful tools, games and playful interfaces, and share the code, demos and decisions behind them.

<img src="assets/v2/section-01.svg" width="100%" alt="Open source: things you can use today">

<a href="https://github.com/MohammediYunus/yunus-os"><img src="assets/v2/card-yunus-os.svg" width="100%" alt="Yunus OS card: a pixel desktop with a code graph, a console answering a workspace summary, a task that asks for approval, and a voice assistant."></a>

**[Yunus OS](https://github.com/MohammediYunus/yunus-os)** · my repositories, pull requests and tasks in one place, with a little assistant that can talk back. Try the browser demo without installing anything, then run it locally to connect your own workspace. Voice and model integrations are optional, and supported actions ask for approval.

[Try it in your browser](https://mohammediyunus.github.io/yunus-os/) · [Run locally](https://github.com/MohammediYunus/yunus-os#try-it) · [Watch the demo](https://github.com/MohammediYunus/yunus-os/releases/download/v0.1.0/yunus-os-community-1080p.mp4) · [Report a problem](https://github.com/MohammediYunus/yunus-os/issues)

<details>
<summary><b>See the real interface</b></summary>
<br>

[![Yunus OS showing repository activity, tasks and an interactive code graph](https://raw.githubusercontent.com/MohammediYunus/yunus-os/20a43ef6cbc2ce3692412f2a05d937faa14ec056/docs/media/yunus-os-preview.webp)](https://github.com/MohammediYunus/yunus-os)

</details>

<a href="https://github.com/MohammediYunus/dwago"><img src="assets/v2/card-dwago.svg" width="100%" alt="dwago card: a pixel brain map where files are neurons and imports are wiring. A file is selected and strikes run along its edges to connected files."></a>

**[dwago](https://github.com/MohammediYunus/dwago)** · explore a repository through its symbols, imports and git history. Ask questions, trace the impact of a change, and see how files connect in an interactive brain map. Answers point back to the code. The card shows example queries such as *how do we prevent double charging?*

[Explore the source](https://github.com/MohammediYunus/dwago) · [Read the setup guide](https://github.com/MohammediYunus/dwago#install)

<details>
<summary><b>See the real brain map</b></summary>
<br>

[![dwago brain map: files as neurons, communities as lobes, imports as wiring and gold churn hotspots](https://raw.githubusercontent.com/MohammediYunus/dwago/188155744d8fd46408415788a676ae46e438c0c6/docs/images/brain.jpg)](https://github.com/MohammediYunus/dwago)

</details>

<a href="https://github.com/MohammediYunus/capture-check"><img src="assets/v2/card-capture-check.svg" width="100%" alt="capture-check card: a frame timeline where steady 16.67 ms frames hit a 216.67 ms stall. Status fail, cadence 27.27 fps, median 16.67 ms. Then the steady sample passes at 60 fps."></a>

**[capture-check](https://github.com/MohammediYunus/capture-check)** · a small tool I made while improving my game recordings. It checks source-frame timestamps for slow capture cadence and stalls, with CSV/JSONL input and clear timing reports. In the stall example the median stays at 16.67 ms, which is why the median alone can hide a stall.

[Try the examples](https://github.com/MohammediYunus/capture-check#quick-start) · [Collect timestamps on Mac](https://github.com/MohammediYunus/capture-check/tree/main/examples/macos-screencapturekit) · [Report a problem](https://github.com/MohammediYunus/capture-check/issues)

<img src="assets/v2/section-02.svg" width="100%" alt="Bug hunt: fixes I’m sending upstream, with live status">

I’m also digging into bugs in other open-source tools. Each fix is a boss fight: when a pull request merges, its bug is defeated. Statuses are read from GitHub automatically.

<!-- live:missions:start -->
<a href="https://github.com/chestso/portty/pull/9"><img src="assets/live/mission-portty-9.svg" width="100%" alt="Bug 01, Portty (chestso/portty #9): Fix library paths and signing in macOS ZIPs. Status: merged."></a>
<a href="https://github.com/urfave/cli/pull/2460"><img src="assets/live/mission-urfave-cli-2460.svg" width="100%" alt="Bug 02, urfave/cli (urfave/cli #2460): Fix a GenericFlag panic with payload getters. Status: merged."></a>
<a href="https://github.com/CoplayDev/unity-mcp/pull/1448"><img src="assets/live/mission-unity-mcp-1448.svg" width="100%" alt="Bug 03, Unity MCP (CoplayDev/unity-mcp #1448): Optional MCP log filter, with regression tests. Status: open, awaiting review."></a>
<a href="https://github.com/mermaid-js/mermaid/pull/8400"><img src="assets/live/mission-mermaid-8400.svg" width="100%" alt="Bug 04, Mermaid (mermaid-js/mermaid #8400): Stop temporary diagrams shifting the page. Status: open, in review."></a>
<a href="https://github.com/transloadit/uppy/pull/6688"><img src="assets/live/mission-uppy-6688.svg" width="100%" alt="Bug 05, Uppy (transloadit/uppy #6688): Keep retried uploads from looking done early. Status: open, awaiting review."></a>
<a href="https://github.com/Zulko/moviepy/pull/2598#issuecomment-6039403205"><img src="assets/live/mission-moviepy-2598.svg" width="100%" alt="Bug 06, MoviePy (Zulko/moviepy #2598): Tested the mono audio fix and followed up. Status: reviewed and reproduced (pull request by another author)."></a>
<a href="https://github.com/sharkdp/bat/pull/4018#issuecomment-6063551504"><img src="assets/live/mission-bat-4018.svg" width="100%" alt="Bug 07, Bat (sharkdp/bat #4018): Regression test for Unicode tab alignment. Status: regression test adopted by the author (pull request by another author)."></a>
<a href="https://github.com/charmbracelet/bubbles/pull/1032#issuecomment-6063310809"><img src="assets/live/mission-bubbles-1032.svg" width="100%" alt="Bug 08, Bubbles (charmbracelet/bubbles #1032): Help rendering test, now golden tests. Status: regression test adopted by the author (pull request by another author)."></a>
<a href="https://github.com/dequelabs/axe-core/pull/5457"><img src="assets/live/mission-axe-core-5457.svg" width="100%" alt="Bug 09, axe-core (dequelabs/axe-core #5457): Fix false role warnings on carousel panels. Status: open, awaiting review."></a>

**Live status** (from GitHub, refreshed every 6 hours): [Portty #9](https://github.com/chestso/portty/pull/9) merged · [urfave/cli #2460](https://github.com/urfave/cli/pull/2460) merged · [Unity MCP #1448](https://github.com/CoplayDev/unity-mcp/pull/1448) open, awaiting review · [Mermaid #8400](https://github.com/mermaid-js/mermaid/pull/8400) open, in review · [Uppy #6688](https://github.com/transloadit/uppy/pull/6688) open, awaiting review · [MoviePy #2598](https://github.com/Zulko/moviepy/pull/2598#issuecomment-6039403205) reviewed and reproduced · [Bat #4018](https://github.com/sharkdp/bat/pull/4018#issuecomment-6063551504) regression test adopted by the author · [Bubbles #1032](https://github.com/charmbracelet/bubbles/pull/1032#issuecomment-6063310809) regression test adopted by the author · [axe-core #5457](https://github.com/dequelabs/axe-core/pull/5457) open, awaiting review

<!-- live:missions:end -->

<img src="assets/v2/section-03.svg" width="100%" alt="In the workshop: work in progress">

<a href="https://x.com/MohammediYunus_/status/2107565252305174710"><img src="assets/v2/hushfall.svg" width="100%" alt="Dwago: Journey to Hushfall, in development. A real gameplay capture framed like a game screen, cycling through gold, rose, violet and night lighting moods as flat colour tints."></a>

**Dwago: Journey to Hushfall** · a cozy adventure I’m building with satisfying combat, boss fights and a world full of secrets. I’m sharing gameplay clips as it takes shape.

[![Animated Echo Pool waterfall from Dwago: Journey to Hushfall](assets/dwago-gameplay-preview.webp)](https://x.com/MohammediYunus_/status/2107565252305174710)

[Watch the gameplay trailer](https://x.com/MohammediYunus_/status/2107565252305174710) · [Download the full-quality 1080p60 video](https://github.com/MohammediYunus/MohammediYunus/releases/download/dwago-demo-2026-10-08/dwago-gameplay-1080p60.mp4)

<sub>This is a separate project from the dwago codebase tool above.</sub>

<img src="assets/v2/section-04.svg" width="100%" alt="Loadout: tools I reach for">

<img src="assets/v2/loadout.svg" width="100%" alt="Loadout inventory: Python, JavaScript, TypeScript, Go, Rust, C# and Swift; Node.js, Next.js, Unity, tree-sitter, MCP and GitHub Actions; AWS, Azure, Claude, Ollama and Whisper. A cursor shows where each one appears in my public work.">

<sub>Python (dwago, capture-check) · JavaScript and Node.js (Yunus OS) · TypeScript and Next.js · Go (urfave/cli fix) · Rust (pinray fix) · C# and Unity (my game, Unity MCP fixes) · Swift · tree-sitter · MCP · GitHub Actions · AWS and Azure · Claude (build partner) · Ollama and Whisper (optional Yunus OS providers)</sub>

<img src="assets/v2/section-05.svg" width="100%" alt="Live log: auto-updated from GitHub">

<a href="https://github.com/pulls?q=author%3AMohammediYunus+is%3Apublic+sort%3Aupdated-desc"><img src="assets/live/log.svg" width="100%" alt="Quest log: my latest public pull requests, merges and releases, updated automatically every 6 hours."></a>

<img src="assets/v2/footer.svg" width="100%" alt="Thanks for playing. The hero rests at a campfire save point. Continue? Yes.">

<p align="center">Trying one of these tools? I’d love to hear what works and what gets in your way. <a href="https://x.com/MohammediYunus_">Find me on X</a> or open an issue in the project.</p>

<p align="center">
  <img src="./assets/header.svg" width="100%" alt="William Xu / inbannable — Systems. Signals. Machines. I build software that listens, decides, and moves." />
</p>

<p align="center">
  <a href="#selected-work"><b>Selected work</b></a> &nbsp; / &nbsp;
  <a href="#side-quests"><b>Side quests</b></a> &nbsp; / &nbsp;
  <a href="#under-the-hood"><b>Under the hood</b></a> &nbsp; / &nbsp;
  <a href="https://github.com/inbannable?tab=repositories"><b>All repositories ↗</b></a>
</p>

<br />

**Hey, I'm William.** I connect software to the physical world: real-time audio, robots in motion, and small interfaces with a lot going on underneath.

I care about the signal path, the control loop, and the assumptions between input and action. This is my corner of the internet for turning those ideas into things you can use.

## Selected work

<samp>FOUR WAYS FROM INPUT TO ACTION</samp>

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/inbannable/WristAsk"><img src="./assets/wristask.svg" width="100%" alt="Explore WristAsk — an illustrated watch with a streaming conversation" /></a>
      <p><sub><samp>01 / INTERFACE · WATCHOS</samp></sub></p>
      <h3><a href="https://github.com/inbannable/WristAsk">腕问 · WristAsk ↗</a></h3>
      <p>A small screen. A bigger conversation. An AI assistant built for your wrist.</p>
      <p><code>Swift</code> <code>SwiftUI</code> <code>watchOS</code></p>
      <details>
        <summary><b>Follow the conversation</b></summary>
        <p>Dictation, handwriting, or keyboard input → DeepSeek → streaming responses on your watch.</p>
        <p><a href="https://github.com/inbannable/WristAsk">Explore the app and source →</a></p>
      </details>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/inbannable/EchoRadar"><img src="./assets/echoradar.svg" width="100%" alt="Explore EchoRadar — a directional radar with highlighted audio sectors" /></a>
      <p><sub><samp>02 / SIGNAL · SPATIAL AUDIO</samp></sub></p>
      <h3><a href="https://github.com/inbannable/EchoRadar">EchoRadar v2 ↗</a></h3>
      <p>See where sound comes from. Native multichannel game audio, mapped to a directional radar.</p>
      <p><code>C++20</code> <code>WASAPI</code> <code>STFT</code> <code>DirectX 11</code></p>
      <details>
        <summary><b>Trace the signal</b></summary>
        <p>Native 5.1/7.1 audio → multichannel signal analysis → a 24-sector radar. Direction comes from the channels, without inventing it from stereo.</p>
        <p><a href="https://github.com/inbannable/EchoRadar">Explore the signal path →</a></p>
      </details>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/inbannable/Turret-Lab"><img src="./assets/turret-lab.svg" width="100%" alt="Explore Turret Lab — an illustrative control response converging toward a target" /></a>
      <p><sub><samp>03 / CONTROL · SIMULATION</samp></sub></p>
      <h3><a href="https://github.com/inbannable/Turret-Lab">Turret Lab ↗</a></h3>
      <p>Tune the loop. Watch the response. A browser lab for exploring how control systems behave.</p>
      <p><code>TypeScript</code> <code>React</code> <code>PID</code></p>
      <details>
        <summary><b>Look inside the loop</b></summary>
        <p>Compare direct PID with cascaded control using the same plant, target, and disturbance. Change the controller; inspect the response.</p>
        <p><a href="https://github.com/inbannable/Turret-Lab">Explore the simulation →</a></p>
      </details>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/inbannable/2026Rebuilt-dev"><img src="./assets/orion.svg" width="100%" alt="Explore Orion — a robot following a curved path while aiming at a target" /></a>
      <p><sub><samp>04 / MOTION · ROBOTICS</samp></sub></p>
      <h3><a href="https://github.com/inbannable/2026Rebuilt-dev">Orion · FRC 6940 ↗</a></h3>
      <p>Keep moving. Keep aiming. Robot software that connects sensing, planning, and action.</p>
      <p><code>Java</code> <code>WPILib</code> <code>AdvantageKit</code> <code>PathPlanner</code></p>
      <details>
        <summary><b>Inspect the moving parts</b></summary>
        <p>Aiming on the move, turret control, dual-encoder positioning, vision fusion, and autonomous routines.</p>
        <p><a href="https://github.com/inbannable/2026Rebuilt-dev">Explore the robot code →</a></p>
      </details>
    </td>
  </tr>
</table>

<sub>Project illustrations are conceptual. Open a card to explore its repository, or expand a note for a closer look.</sub>

<br />

## Side quests

<samp>SMALL RULES. UNEXPECTED OUTCOMES.</samp>

| Experiment | What's inside |
| :-- | :-- |
| **[星阵 · 3D Gomoku ↗](https://github.com/inbannable/3d-gomoku)** | Think in three dimensions. Gravity-aware 5×5×5 connect-four with a strategy AI and move coach. |
| **[Director's Cut ↗](https://github.com/inbannable/directors-cut-mc26.2)** | Controlled chaos. A server-authoritative Minecraft story director for events and hints. |
| **[Conway's Game of Life ↗](https://github.com/inbannable/Conway-Life-Game)** | Watch complexity emerge from simple rules, right in the browser. |

<br />

## Under the hood

Pick a channel to explore my toolkit.

<details>
  <summary><b>◉ &nbsp; Signal</b> — from samples to meaning</summary>
  <p><code>C++20</code> <code>Python</code> <code>CMake</code></p>
  <p>Multichannel DSP, spectral analysis, and the path from raw audio to spatial information.</p>
  <p>Start with <a href="https://github.com/inbannable/EchoRadar">EchoRadar →</a></p>
</details>

<details>
  <summary><b>◎ &nbsp; Control</b> — from error to action</summary>
  <p><code>Java</code> <code>WPILib</code> <code>PID</code></p>
  <p>Trajectory planning, sensor fusion, and control loops that have to work in the physical world.</p>
  <p>Start with <a href="https://github.com/inbannable/Turret-Lab">Turret Lab</a> or <a href="https://github.com/inbannable/2026Rebuilt-dev">Orion →</a></p>
</details>

<details>
  <summary><b>⌘ &nbsp; Interface</b> — from intent to interaction</summary>
  <p><code>Swift</code> <code>SwiftUI</code> <code>watchOS</code> <code>TypeScript</code> <code>React</code></p>
  <p>Apple-platform apps and interactive simulations, from a watch screen to a browser canvas.</p>
  <p>Start with <a href="https://github.com/inbannable/WristAsk">WristAsk →</a></p>
</details>

<br /><br />

---

<p align="center">
  <samp>OBSERVE CAREFULLY. MODEL HONESTLY. LEAVE A CLEAN TRACE.</samp>
  <br /><br />
  <a href="https://github.com/inbannable?tab=repositories"><b>Find your next rabbit hole ↗</b></a>
  &nbsp; · &nbsp;
  <a href="#"><samp>Back to top ↑</samp></a>
</p>

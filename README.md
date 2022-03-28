<h1 align="center">Fursuit Detector</h1>

Detects fursuit pictures via PyTorch!

<p align="center">
  <a href="https://youtu.be/hx_wx0s2dUE">
    <img src="https://github.com/OpenFurs/Fursuit-Detector/blob/main/fursuit-detection-demo.gif?raw=true">
  </a>
</p>

- **Full video:** [Fursuit detection AI version 1.0](https://youtu.be/hx_wx0s2dUE)
- **Original video used to test the model:** [Furrydelphia 2019 Fursuit Parade](https://youtu.be/U3ieglNOiQg)

## Technologies used

<img src="https://skillicons.dev/icons?i=nextjs" width="30">&nbsp;<img src="https://skillicons.dev/icons?i=ts" width="30">&nbsp;<img src="https://skillicons.dev/icons?i=py" width="30">&nbsp;<img src="https://upload.wikimedia.org/wikipedia/commons/1/10/PyTorch_logo_icon.svg" width="25">&nbsp;<img src="https://raw.githubusercontent.com/github/explore/main/topics/flask/flask.png" width="30">

Created using Next.js + TypeScript for the front-end -- while Flask for the back-end, and PyTorch for handling the AI.

## Get it up and running

> You'll need an up-to-date version of both Node (at least v16.x) and Python (at least v3.9)
> to properly get it up and running.

Fork and clone the repo and install the required dependencies:

```sh
npm install
```

Next, install Python backend stuff:

```sh
pip install -r requirements.txt
```

Then finally, run both Node and Python dev servers by simply running:

```sh
npm run dev
```

**"But how are you able to run both Python and Node servers?"**, you ask -- fortunately, there's an npm
package called [concurrently](https://github.com/open-cli-tools/concurrently) which has the ability
to run our Next.js dev server and Python Flask server simultaneously. Without opening a second terminal!

----

<smaller><b>© 2021-22, created by thatITfox & skepfusky, MIT license</b></smaller>

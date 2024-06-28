# AI Alibis: Multi-Agent LLM Murder Mystery

### Play online: [AI Alibis](https://ai-alibis.vercel.app)

<div align="center">
  <img alt="AI Alibis Logo" src="https://raw.githubusercontent.com/ironman5366/ai-murder-mystery-hackathon/actually_playable/web/src/assets/screenshot.png" style="max-width:80%;">
</div>

**Authors:** [Paul Scotti](https://paulscotti.github.io/) and [Will Beddow](https://www.willbeddow.com/)

We employ a principles & refinement prompting approach inspired by SynthLab's research paper, [Suppressing Pink Elephants with Direct Principle Feedback](https://arxiv.org/abs/2402.07896)

Special thanks to [Synthlabs](https://www.synthlabs.ai/) for organizing the hackathon that inspired this project.

## Setup
1. Git clone the repo
```
git clone https://github.com/ironman5366/ai-murder-mystery-hackathon.git
cd ai-murder-mystery-hackathon
```
2. Add your Anthropic API (and optionally PostgreSQL DB) to api/.env file
```
nano api/.env
export ANTHROPIC_API_KEY="YOUR_API_KEY_HERE"
(<ctrl+x , y, enter> to save changes and exit nano)
```
3. Install Node dependencies
```
web/npm i
```
3. Start up the api
```
bash api_start.sh
```
4. In separate terminal, start up the web interface
```
bash web_start.sh
```
5. Play the game


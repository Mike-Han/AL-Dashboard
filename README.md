<p align='center'>
  <img src='https://raw.githubusercontent.com/Mike-Han/AL-Dashboard/assets/assets/AL.png' alt='Alrighty Labs' width='200px' />
</p>

<p>
  <h2 align='center'>
    Modern Dashboard powered by
    <img src='https://raw.githubusercontent.com/Mike-Han/AL-Dashboard/assets/assets/painel-dark.png' alt='painel-light' height='50px' align='center'/>
    from Team
    <img src='https://raw.githubusercontent.com/Mike-Han/AL-Dashboard/assets/assets/rdm-dark.png' alt='painel-dark' height='50px' align='center'/>
  </h2>
</p>

<br/>

<p align='center'>
  <a href="https://painel-labs.netlify.app/">Live Demo</a>
</p>

## Installation

### Pre-requisites

1. [Nodejs](https://nodejs.org/en/download/)
1. [Git](https://git-scm.com/downloads)
1. pnpm

   ```bash
   # terminal
   npm install -g pnpm
   ```

### Clone to local

```bash
# terminal
git clone https://github.com/Mike-Han/AL-Dashboard.git AL-Dashboard
cd AL-Dashboard
pnpm i
```

## Usage

### Painel Demo Site - Development

```bash
# terminal
pnpm demo:dev
```

Visit <http://localhost:3031>

### Painel Demo Site - Build

```bash
# terminal
pnpm demo:build
```

Generated files in `apps\painel-demo\dist` is ready to be served.

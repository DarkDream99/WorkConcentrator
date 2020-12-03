# Work Concentrator

Tool that helps you to keep your concentration on the important work

## Requirements

1. Python 3 interpreter;
2. `notify-send` lib for Linux (for notification features) 

## Installation

1. Clone this repository or install from [releases](https://github.com/DarkDream99/WorkConcentrator/releases);
2. Select your python environment (via venv for example);
3. Double check that you use `python3` (you can run: `which python` on Unix)
![Vesion example](./imgs/pyversion.png?raw=true)
4. Run: `python3 <path-to-work_concentrator.py>`
![Files in dir](./imgs/files_in_dir.png)
![Execution example](./imgs/pyexecution.png)

### Additional:
- For Linux users:
    - nothing

- For Windows users:
    - nothing

- For MacOS users:
    - nothing

## User guide

![Demo](./imgs/demo.png)

Working process are divided by short breaks on iterations. 

One iteration is:
- 25 min working
    - 5 min break
- 25 min working
    - 5 min break
- 25 min working
    - 5 min break
- 25 min working
- 20 min break

After last (20 min) break new iteration will be started.

To start timer you should click on the `Start` button.
If the work is finished you can click `Reset` to reset timer state or just close the application.

In the bottom you can see how many stages of the iteration were passed. One stage contains (`work` + `break`) time line.


## Versions

See on [master branch](https://github.com/DarkDream99/WorkConcentrator/) page
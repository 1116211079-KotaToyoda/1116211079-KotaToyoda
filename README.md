## Continuous-Space Learning Environment for Cooperative AI

The following is the procedure to build this environment on your computer.
- Install Unity Hub (version 3.9.1)
- Install Unity Editor (version 2022.3.49f1)
- Clone this repo
- Install Unity ML agents (Version: Release 22) from [ML-Agents Installation Documentation](https://unity-technologies.github.io/ml-agents/Installation/)
- Use `scripts/unity_env_from_jupyter.ipynb` to verify installation

## 1. Install Unity hub

Download Unity from the [Download page](https://unity.com/download)

## 2. Install Unity Editor (version 2022.3.49f1)

Download this Unity Editor from Unity Hub. If same verison is not on the `Official Release`, jump to `archive` and find the same editor. (Other versions will be available soon...)

## 3. Clone this repo

Clone this repo.
Then unzip `unityEssential.zip`. The components are as follows.

- Assests (this folder includes game objects, the C# scripts to handle this environment, etc.)
- Packages
- Usersettings
- Projectsettings

From Unity Hub, press `Add` -> `Add pprojects from disk` and select the `unityEssential` folder.

There will be an error due to the loss of mlagent packages but ignore those and create a project.

## 4. Install ML agents version: release 22
Install Unity ML agents (Version: Release 22) from [ML-Agents Installation Documentation](https://unity-technologies.github.io/ml-agents/Installation/).

Python version is 3.10.12 and we used [Anaconda 2024-10-1](https://repo.anaconda.com/archive/) to manage python verison.

## 5. Install jupyter lab and test play

Install jupyter lab from this command.

```bash
pip install jupyterlab

open scripts folder and use `scripts/unity_env_from_jupyter.ipynb` to verify installation.


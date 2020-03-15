# NodeJS template
NodeJS with VSCode Container

## Development setup with Docker / VSCode
- Create an empty .env.local file
  ```bash
  $ touch .env.local
  ```
- Start VS Code, run the **Remote-Containers: Open Folder in Container...** command from the Command Palette (`F1` or `CMD + P`) or quick actions Status bar item, and select the project folder you'd like to set up the container for.  
  ![quick actions Status bar](https://code.visualstudio.com/assets/docs/remote/common/remote-dev-status-bar.png)
- **Or** just open the folder with VSCode as normal, it will automatically detect the Remote-Containers configuration. At that time, just choose **Reopen in Container**  
  ![reopen promt](https://code.visualstudio.com/assets/docs/remote/containers/dev-container-reopen-prompt.png)
- The VS Code window will reload and start building the dev container. A progress notification provides status updates. Note that you only have to build a dev container the first time you open it; opening the folder after the first successful build will be much quicker.  
  ![progress notification](https://code.visualstudio.com/assets/docs/remote/containers/dev-container-progress.png)
- After the build completes, VS Code will automatically connect to the container.

**Note**: If you don't have VSCode that support the Remote Container yet, please install it by follow the [official guide from Microsoft](https://code.visualstudio.com/docs/remote/containers#_installation):
1. Install [Visual Studio Code](https://code.visualstudio.com/)
2. Install the [Remote Development extension pack](https://aka.ms/vscode-remote/download/extension).


# ScratchHW-desktop
The version of desktop will comming soon, before this you can try the develop version:  [https://github.com/ScratchHW/scratch-gui](https://github.com/ScratchHW/scratch-gui).(Just for developer)

This project is start from [Scratch 3.0 LLK](https://github.com/LLK), it's goal is to complete a program that can build upload code to hardware. Especially for arduino and microbit. At present, this core function has been realized. But still need to improve the detail function for ordinary users. 

This is a fast changing and incomplete program. It's for professional developer.

<img src="docs\1.png" alt="5" style="zoom:25%;" />

<img src="docs\2.png" alt="6" style="zoom:25%;" />

<img src="docs\3.png" alt="7" style="zoom:25%;" />

<img src="docs\4.png" alt="1" style="zoom:25%;" />

<img src="docs\5.png" alt="2" style="zoom:25%;" />

<img src="docs\6.png" alt="3" style="zoom:25%;" />

<img src="docs\7.png" alt="4" style="zoom:25%;" />

<img src="docs\8.png" alt="4" style="zoom:25%;" />

<img src="docs\9.png" alt="4" style="zoom:25%;" />

## Installation

1. Before build scratch-gui. You should clone these link. Run `npm install` and `npm link` in these floders. (If you are in China. You may need to use net proxy to finish the following)

   ```bash
   git clone https://github.com/ScratchHW/saveSvgAsPng
   git clone https://github.com/ScratchHW/scratch-audio
   git clone https://github.com/ScratchHW/scratch-blocks
   git clone https://github.com/ScratchHW/scratch-l10n
   git clone https://github.com/ScratchHW/scratch-render
   git clone https://github.com/ScratchHW/scratch-vm
   cd saveSvgAsPng
   npm install
   npm link
   cd ..
   cd scratch-audio
   npm install
   npm link
   cd ..
   ...Repeat the above steps
   ```

3. Clone and run install in scratch-gui, then link those project.

   ```bash
   git clone https://github.com/ScratchHW/scratch-gui
   cd scratch-gui
   npm install
   npm link save-svg-as-png scratch-audio scratch-blocks scratch-l10n scratch-render scratch-vm
   ```

4. Clone scratch-link then install.

   ```bash
   git clone https://github.com/ScratchHW/scratch-link
   cd scratch-link
   npm install
   ```
   
4. Clone scratch-extension-server then install.

   ```bash
   git clone https://github.com/ScratchHW/scratch-extension-server
   cd scratch-extension-server
   npm install
   ```

## Running

1. First start scratch-link, to provide hardware function link to scratch gui.

   ```bash
   cd scratch-link
   npm start
   ```

2. Start scratch-extension-server.

   ```
   cd scratch-extension-server
   npm start
   ```

3. Start  scratch-gui

   ```bash
   cd scratch-gui
   npm run start-open
   ```

4. After webpack build finish, you should see a browser page pop up. Have fun.

## Project Structure Instruction

...

## Contact me

China QQ group number: 933484739

Email: arthurzheng150@gmail.com

## Bug Report

You can submit the Bug log in Issues of this project.

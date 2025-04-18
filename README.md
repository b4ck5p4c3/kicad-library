# B4CKSP4CE KiCAD Library 🪚

## Installation

1. Install latest version of [KiCAD](https://www.kicad.org/download/).

2. Clone this repository in persistent folder on your machine.
   You'll need it every time you use KiCAD.

3. Open KiCAD. In the main window, go to `Preferences` > `Configure Paths...`.

4. Add a new variable called `KICAD_BKSP_LIB_DIR` and set its value to the full path
   of `library` folder in the cloned repository.

   Example: `/Users/Resident/BKSP/kicad-library/library`.

5. In the same window, go to `Preferences` > `Manage Footprint Libraries...`.
   In the `Global Libraries` tab, click on "+" button. Set **Nickname** to `BKSP` and **Library Path** to `${KICAD_BKSP_LIB_DIR}/BKSP.pretty`
   Click `OK` to add the library.

6. Repeat the previous step, but this time for `Manage Symbol Libraries...`.
   Set **Nickname** to `BKSP` and **Library Path** to `${KICAD_BKSP_LIB_DIR}/BKSP.kicad_sym`

7. Once more for `Manage Design Block Libraries...`.
   Set **Nickname** to `BKSP` and **Library Path** to `${KICAD_BKSP_LIB_DIR}/BKSP.kicad_blocks`

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Note that parts of this repository might be licensed under different licenses.
As B4CKSP4CE don't endorse commercial use of this repository, we consider it safe to use them.
Althrough, we recommend to check the license of each part before using it in your project.

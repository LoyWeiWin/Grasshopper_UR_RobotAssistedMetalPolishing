# Robot-Assisted Metal Polishing using Grasshopper

## Overview
This project explores how Grasshopper can be used to communicate with the Universal Robots UR10 collaborative robot for various metal polishing tasks. These tasks range from standard finishing to handling complex metal pieces mounted at various angles. The system leverages Grasshopper's parametric design capabilities and integrates advanced plugins to achieve precise control and high-quality results.

<img src="https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/Assets/Videos/Vid_RoboticMotion.gif" alt="Alt Text" width="450">

## Project
- [Metal Linishing - Planar approach](https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/GrasshopperFiles/GH_UR_RoboticAssistedMetalLinishing.gh)
- [Metal Polishing - Non-planar approach](https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/GrasshopperFiles/GH_UR_RoboticAssistedMetalPolishing.gh)

## Software Requirement
- Rhino 7 or latest
- [Robot](https://github.com/visose/Robots/) plugin
- [Generation](https://www.food4rhino.com/en/app/generation) plugin

## Key Features
- **Parametric Design Control**: Use Grasshopper to dynamically adjust polishing paths.
- **Compatibility with Universal Robot**: Seamless integration with UR collaborative robots for industrial applications.
- **Flexibility**: Suitable for both standard polishing and complex, angled workpieces.
- **Customizable Workflow**: Modify and adapt Grasshopper scripts to meet your unique needs.

## Repository Structure
- `GrasshopperFiles/`: Grasshopper scripts.
- `RhinoFiles/`: Robot workcell, and end-effectors.
- `Assets/`: Images, thumbnails and videos
- `Docs/`: Documentation for installation, setup instructions, usage, and troubleshooting.

For more details, see the [Wiki](https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/wiki).

## Contributing
Contributions to improve this workflow are welcome! Please follow the contributing guidelines in the [contributing guidelines](https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/wiki/06_Contributing-Guidelines) in wiki.

## Code of Conduct
This project follows the Contributor Covenant Code of Conduct. Please read our [Code of Conduct](https://github.com/LoyWeiWin/Grasshopper_UR_RobotAssistedMetalPolishing/blob/main/CODE_OF_CONDUCT.md) before contributing.

> [!WARNING]  
> If you are unfamiliar with using cobots (collaborative robots), please ensure you have supervision from a qualified advisor or professional. Alternatively, simulate your intended workflow in a Grasshopper environment before working with physical machines.
> The contributor or owner of this repository is not responsible for any physical damage, injury, or harm caused to the immediate environment or individuals due to improper usage of cobots or related tools.

## Acknowledgements
This project was independently developed as part of my personal initiative and commitment to advancing this field.

## References
1. Zhang, Y., & Li, X. (2022). Robotic polishing: A review of recent progress and future perspectives. Robotics and Computer-Integrated Manufacturing, 73, 102234. https://doi.org/10.1016/j.rcim.2021.102234

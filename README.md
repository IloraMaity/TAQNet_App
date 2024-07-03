# TAQNetQCI Executable

## 1. Prerequisites for Deployment

Verify that MATLAB Runtime(R2024a) is installed.
If not, you can run the MATLAB Runtime installer.
To find its location, enter

    >>mcrinstaller

at the MATLAB prompt.

NOTE: You will need administrator rights to run the MATLAB Runtime installer.

Alternatively, download and install the Windows version of the MATLAB Runtime for R2024a
from the following link on the MathWorks website:

    [1](https://bing.com/search?q=)
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see
"Distribute Applications" in the MATLAB Compiler documentation
in the MathWorks Documentation Center.



## 2. Application Overview
TAQNetQCI is a standalone application designed to facilitate the deployment of a quantum communication infrastructure (QCI) using a cost-effective and efficient approach. The application leverages advanced algorithms to address key challenges in quantum key distribution (QKD).

### Key Features
Minimum Steiner Tree Construction: Utilizes a Steiner tree-based approach to construct a minimum spanning tree (MST) that connects all quantum nodes (QNs) with a minimal number of trusted repeater nodes (TRNs), thereby reducing deployment costs.
Genetic Algorithm-based QKD Request Distribution: Implements a genetic algorithm to distribute QKD requests efficiently, ensuring that the key rate demands of multiple QKD requests are met despite limited path availability and key rate capacities.
Optical Bypassing Technique: Supports QKD between non-adjacent QNs, reducing energy consumption and improving the overall efficiency of the QCI.

### System Requirements
Operating System: Windows 10, macOS 11, or later
RAM: Minimum 8 GB
Disk Space: Minimum 500 MB

### Research Background
Quantum key distribution (QKD) provides a secure method to exchange encrypted information between two parties within a QCI. Deploying a QCI cost-effectively involves using optical fibres that multiplex quantum and classical communication. The primary challenge in such deployments is the cost, which our approach mitigates by constructing a minimum spanning tree (MST) with minimal trusted repeater nodes (TRNs).

Addressing the key rate demands of multiple QKD requests is complex due to limited path availability and key rate capacities, which decrease with link distance. This application proposes a minimum Steiner tree combined with a genetic algorithm for QKD request distribution, optimizing the deployment to serve maximum QKD requests. Additionally, it employs an optical bypassing technique for QKD between non-adjacent QNs, reducing energy consumption and enhancing deployment efficiency.

## 3. Installation Instructions
Download the Package
Download the deployment package containing the necessary files.

### Install MATLAB Runtime
Ensure MATLAB Runtime R2024a is installed on your system. Refer to the Prerequisites section for detailed instructions.

### Run the Installer
If the package includes an installer script (e.g., setup.exe), run it to install the application.

### Manual Installation
If no installer script is provided:

Copy TAQNetQCI.exe to your desired installation directory.
Ensure MCRInstaller.exe is in the same directory if the MATLAB Runtime is not already installed.

## 4. Running the Application
To run TAQNetQCI:

Navigate to the directory where TAQNetQCI.exe is located.
Double-click TAQNetQCI.exe to launch the application.

## 5. Definitions

For information on deployment terminology, go to
[2](https://www.mathworks.com/help) and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.

## 6. Troubleshooting
### Common Issues
MATLAB Runtime not found
Ensure that the MATLAB Runtime is correctly installed. Check the installation directory and verify the version.

Application crashes on startup
Verify that your system meets the minimum requirements. Check for any missing dependencies or permissions issues.

### Support
For further assistance, contact ilora.maity@uni.lu.

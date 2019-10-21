
Docker training part I
==================

Start learning Docker intallation on Windows


Requirements
-----------

What you need in order to run and install Docker:

 **About Version:**
* To run Docker, your machine must have a 64-bit operating system running Windows 7 or higher. Additionally, you must make sure that virtualization is enabled on your machine. To verify your machine meets these requirements, do the following:

1.  Right click the windows message and choose  **System**.
    
    If you aren’t using a supported version, you could consider upgrading your operating system.
    
    If you have a newer system, specifically 64bit Windows 10 Pro, with Enterprise and Education (1607 Anniversary update, Build 14393 or later), consider using  [Docker Desktop for Windows](https://docs.docker.com/docker-for-windows)  instead. It runs natively on the Windows, so there is no need for a pre-configured Docker QuickStart shell. It also uses Hyper-V for virtualization, so the instructions below for checking virtualization will be out of date for newer Windows systems. Full install prerequisites are provided in the Docker Desktop for Windows topic in  [What to know before you install](https://docs.docker.com/docker-for-windows/#what-to-know-before-you-install).
    
2.  Make sure your Windows system supports Hardware Virtualization Technology and that virtualization is enabled.


Installation
--------------

1.  Double-click  **Docker Desktop Installer.exe**  to run the installer.
    
    If you haven’t already downloaded the installer (`Docker Desktop Installer.exe`), you can get it from  [**Docker Hub**](https://hub.docker.com/?overlay=onboarding). It typically downloads to your  `Downloads`  folder, or you can run it from the recent downloads bar at the bottom of your web browser.
    
2.  Follow the instructions on the installation wizard to accept the license, authorize the installer, and proceed with the install.
    
    When prompted, authorize the Docker Desktop Installer with your system password during the install process. Privileged access is needed to install networking components, links to the Docker apps, and manage the Hyper-V VMs.
    
3.  Click  **Finish**  on the setup complete dialog and launch the Docker Desktop application.


Starting with Docker
--------------

 1. Run the following command in the Powershell and confirm that docker is alive :).

``````
> docker run hello-world

docker : Unable to find image 'hello-world:latest' locally
...

latest:
Pulling from library/hello-world
ca4f61b1923c:
Pulling fs layer
ca4f61b1923c:
Download complete
ca4f61b1923c:
Pull complete
Digest: sha256:97ce6fa4b6cdc0790cda65fe7290b74cfebd9fa0c9b8c38e979330d547d22ce1
Status: Downloaded newer image for hello-world:latest

Hello from Docker!
This message shows that your installation appears to be working correctly.


[1]: [https://docs.docker.com/docker-for-windows/]
``````

# Mystique Design Web (MDW) Offline Application

## Project Overview

While working at Christie Digital, I developed an offline version of their Mystique Design Web application. This solution was designed for field technicians who needed to run projection mapping simulations in environments with limited or unreliable internet connectivity.

![MDW Offline Application Interface](images/mdw-interface.jpg)
<!-- Replace with your actual screenshot once available -->

## About Christie's Mystique

Christie Digital is a prominent audiovisual company that manufactures and installs displays and projectors for major clients globally, including cinema chains, theme parks, sports arenas, and large-scale events such as the Dubai 2020 Expo and Star Wars premieres.

### Mystique Software Suite

[Mystique](https://www.christiedigital.com/products/warping-blending/mystique/) is Christie's proprietary software solution that addresses complex projection mapping scenarios where content needs to be displayed on non-standard surfaces:
- Curved domes
- Architectural features
- Three-dimensional objects (vehicles, sculptures etc)

The software manages essential functions including image warping and blending, multi-projector calibration, and sophisticated surface mapping calculations.

### Mystique Design Web (MDW)

MDW provides a browser-based virtual simulation environment for projection setups, allowing developers to:
- Design and test projection configurations
- Simulate optimal projector placement
- Share projects with team members
- Plan complex setups without physically deploying equipment

![MDW Offline Application Interface](images/mdw-interface.jpg)
<!-- Replace with your actual screenshot once available -->

## The Challenge

Field technicians frequently operate in environments with poor or non-existent internet connectivity. Despite these conditions, they require access to the MDW toolset to:
- Implement real-time adjustments to projection setups
- Troubleshoot configuration issues
- Access and modify existing project designs

The solution required a standalone, offline-capable version of MDW that could synchronize with users' online accounts when connectivity became available.

![MDW Implementation Challenge](images/mdw-challenge.jpg)
<!-- Replace with a relevant image once available -->

## My Role & Contributions

As a Projection Mapping C++ Developer at Christie, I spearheaded the development of the MDW Offline application with the following focus areas:

### Core Development
I adapted the web-based MDW application to function effectively in offline environments by:
- Modifying JavaScript webpack configurations for local operation
- Creating a user interface consistent with the online version
- Implementing local data storage solutions

### DevOps Implementation
I established a robust development pipeline including:
- Creating GitHub Action workflows for automated build and deployment
- Developing synchronization mechanisms for offline installations
- Packaging the application with all dependencies for streamlined distribution

### Executable Creation
I developed a comprehensive launcher application that:
- Simplified the deployment process
- Performed system requirement verification for Docker and MongoDB
- Implemented installation routines for missing dependencies

![MDW Architecture Diagram](images/mdw-architecture.jpg)
<!-- Replace with your actual diagram once available -->

## Technical Implementation

### Technology Stack
- **Frontend:** JavaScript, HTML, CSS
- **Backend:** Docker containerization
- **Database:** MongoDB
- **CI/CD:** GitHub Actions
- **Distribution:** Custom executable launcher

### Development Process
My approach to developing the offline application included:

1. Starting with the original MDW codebase as a foundation
2. Reconfiguring webpack for offline compatibility
3. Implementing GitHub Actions workflows to:
   - Retrieve updated files from the main MDW repository
   - Package application components and dependencies
   - Generate downloadable deployment packages
4. Creating a custom launcher that would:
   - Verify system requirements
   - Install necessary dependencies when missing
   - Launch the containerized application
   - Manage Docker containers and MongoDB instances

## Challenges & Solutions

### GitHub Actions Workflow Development
**Challenge:** I had no prior experience with GitHub Actions for CI/CD pipelines.  
**Solution:** I researched documentation, utilized AI tools, and consulted with my supervisors to develop functional workflows.

### System Compatibility
**Challenge:** The executable behaved inconsistently across different machines.  
**Solution:** I implemented more robust error handling and system checks to accommodate variations in host environments.

### Authentication Implementation
**Challenge:** Developing secure authentication without internet connectivity.  
**Solution:** I created a simplified authentication system for the prototype, laying groundwork for a more secure implementation in future iterations.

### Dependency Management
**Challenge:** Ensuring Docker and MongoDB were properly configured on various systems.  
**Solution:** I developed a comprehensive system check and installation routine to ensure all prerequisites were properly configured.

![MDW Development Process](images/mdw-development.jpg)
<!-- Replace with your actual process image once available -->

## Results & Achievements

Through this project, I:
- Developed a functional offline GUI prototype
- Implemented container-based architecture for consistent deployment
- Created a foundation for field technicians to utilize MDW without internet connectivity
- Provided comprehensive documentation for future development efforts

## Future Enhancement Opportunities

The initial prototype established a solid foundation for offline functionality. Potential enhancements include:
- Implementing a more robust offline authentication system
- Developing bidirectional data synchronization for offline changes
- Optimizing container performance for field hardware
- Streamlining the installation process

## Skills Demonstrated

This project showcased my capabilities in:
- **Software Development:** JavaScript, HTML, CSS
- **DevOps Engineering:** GitHub Actions, CI/CD pipelines, Docker
- **Database Management:** MongoDB
- **System Integration:** Executable development, dependency management
- **User Interface Design:** Maintaining consistency between web and desktop applications

---

*I completed this project during my tenure as a Projection Mapping C++ Developer at Christie Digital Systems from September to December 2022.*

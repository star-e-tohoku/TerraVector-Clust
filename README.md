# TerraVector-Clust

![License](https://img.shields.io/github/license/username/repository)
![Issues](https://img.shields.io/github/issues/username/repository)
![Stars](https://img.shields.io/github/stars/username/repository)

## Table of Contents
- [About](#about)
- [Paper](#paper)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## About
TerraVector-Clust is a hierarchical clustering methodology for clustering data from a global navigation satellite system (GNSS) that is applicable at local to global scales. 
TerraVector-Clust first adapted the conventional 2D velocity clustering metric for global-scale applications by implementing parallel translation in differential geometry.
TerraVector-Clust then combined it with a Euler-vector-based metric to incorporate the kinematic constraint associated with the rigid motion of plates,
achieving advantages in identifying tectonic structures. 
This hybrid metric approach is assessed through two case studies at different spatial scales to determine whether it can accurately identify tectonic plate and crustal block boundaries: 
one study uses global-scale data from the ITRF2008 and ITRF2020 plate motion models, and the other focuses on a local-scale study in Taiwan. 
Results obtained using the hybrid metric consistently align better with geological data than those from either the 2D or Euler vector-based metrics alone. 
The proposed method is computationally efficient, enabling us to conduct two types of stability assessment: 
examination of the robustness of clusters with synthetic noise contamination and leave-one-out analysis. Both tests are demonstrated to be feasible within practical timeframes.

## Paper

- Title: A GNSS-velocity clustering method applicable at local to global scales
- Authors: Atsushi Takahashi (RIKEN, Center for Advanced Intelligence Project), Keisuke Yano (The Institute of Statistical Mathematics), and Masayuki Kano (Tohoku University)
- Journal: in revision

## Demo
Include a demo or screenshots of the project.  
You can use `![Demo Image](URL)` to insert images or GIFs that showcase the project's appearance.

## Installation
Provide instructions on how to install the project.

```bash
# Clone the repository
git clone https://github.com/username/repository.git

# Navigate to the project directory
cd repository

# Install the necessary packages
npm install

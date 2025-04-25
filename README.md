# Executable Environment for OSF Project [w4gey](https://osf.io/w4gey/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** Legacy media as inhibitors and drivers of public reservations against science: Global survey evidence on the link between media use and anti-science attitudes

**Project Description:**
> This project contains all materials to reproduce the results presented in the main article and the appendix, i.e. the complete survey data, code, outputs, and pre-computed regression models.

**Original OSF Page:** [https://osf.io/w4gey/](https://osf.io/w4gey/)

---

**Important Note:** The contents of the `w4gey_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_w4gey/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_w4gey/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `w4gey_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

**Pull the Docker Image**

```bash
docker pull meet261/repo2docker-w4gey:latest
```

**Launch RStudio Server**

```bash
docker run -e PASSWORD=yourpassword -p 8787:8787 meet261/repo2docker-w4gey
```
Replace `yourpassword` with a secure password of your choice. You will use this to log in to the RStudio web interface.

**Once the container is running, visit `http://localhost:8787` in your browser.**
Use username: `rstudio` and the password you set with `-e PASSWORD=...`.

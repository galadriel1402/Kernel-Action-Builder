# Android Kernel Builder

[![License: Apache-2.0](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)

A fully automated kernel image builder for **Android Custom Kernels** using GitHub Actions.

---

## Getting Started

1. **Fork or clone** this repository.
2. Copy the desired workflow into `.github/workflows/`.
3. In your repository settings, add the following GitHub Secret:
   - `GH_TOKEN` – A **GitHub Personal Access Token (PAT)** with `repo` permissions (required for private kernel repos)
4. Manually trigger the build:
   - Go to **Actions** tab → Select the kernel build workflow → **Run workflow**
   - Fill out required inputs such as kernel repo URL, branch, and Android version (e.g., A15 or A16)

---

## Credits

- [@azwhikaru](https://github.com/azwhikaru) – Workflow ideas & CI inspiration  
- [@carlodandan](https://github.com/carlodandan) – Kernel CI reference  
- [@eidawon](https://github.com/galadriel1402) – Maintainer and builder  
- [AnyKernel3](https://github.com/osm0sis/AnyKernel3) – ZIP packaging framework  
- All open-source maintainers, kernel devs, and testers

---

## Disclaimer

This is a **community-driven project** and is not affiliated with any official kernel team, vendor, or OEM.  
Use at your own risk. Always verify your build outputs before flashing on real devices.

---

## License

Licensed under the [Apache License 2.0](LICENSE).
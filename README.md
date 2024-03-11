[![Build and Test](https://github.com/milliewalky/setup-vulkan/actions/workflows/sample.yml/badge.svg)](https://github.com/milliewalky/setup-vulkan/actions/workflows/sample.yml)

# Setup Vulkan

This action downloads, unpacks, and configures Vulkan for use in GitHub Actions workflows. Vulkan is unpacked under the temporary directory of a runner.

# Usage

<!-- start usage -->
```yaml
- uses: milliewalky/setup-vulkan@v1
```
<!-- end usage -->

This action appends `VULKAN_SDK` to a temporary PATH file, and therefore, programs such as CMake _should not_ have too much trouble finding it.

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)

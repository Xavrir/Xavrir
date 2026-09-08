# Terminal profile generators

Adapted from [navi3582/animated-github-profile](https://github.com/navi3582/animated-github-profile), under the MIT license included in this directory.

The portrait generator fetches the current GitHub avatar and converts it to typing ASCII, preserving its aspect ratio. The information card contains Xavrir's public profile details. The contribution fetcher reads public GitHub counts, accepts thousands separators, and fails when a nonzero day has no count instead of estimating it.

The existing profile image workflow runs these scripts from `dist/` and publishes the SVGs on the `output` branch. No personal token is needed by these generators.

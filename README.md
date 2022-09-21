### ⚠️ Warning ⚠️
This repository has been deprecated in favor of the [Keep3r Web v2 Registry](https://github.com/keep3r-network/web-v2/blob/main/utils/registry.tsx)

# Keep3r Job Registry

Job information will be fetched from [the web](https://thekeep3r.network) reading the `v2.json` file on this repository. To add a job to the Registry, a Pull Request must be created with the following requirements:

- cli-job repo must be created using [keep3r-cli-job-boilerplate](https://github.com/defi-wonderland/keep3r-cli-job-boilerplate) as template
- cli-job must be available as an `npm package`
- job must be a verified address on Etherscan
- job must not be a proxy contract
- job must be added to `v2.json` with:
    - title
    - link to CLI Job repository

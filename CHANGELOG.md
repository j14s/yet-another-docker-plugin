##

## 0.1.0-rc35
- Non-ui image builder/pusher.

## 0.1.0-rc34
- Example of DockerCloud global settings reconfiguration from @samrocketman
- Fix dropdown button for docker templates.
- Throw DockerSimpleBuildWrapper errors.
- Allow setting readTimeouts.

## 0.1.0-rc33
- Docker Simple BuildWrapper for external specific use case.
- Use docker-java 3.0.9

## 0.1.0-rc32 (failed release)

## 0.1.0-rc31
- Bypass strictVerification from JNLPLauncher
- Add cloud-stats-plugin (half worked, plugin missing integration points)

## 0.1.0-rc30
- Possibly fix overprovisioning.

## 0.1.0-rc29
- Support dash?

## 0.1.0-rc28
- Sync durable-task Once retention strategy implementation.
- Fix DockerCloudRetentionStrategy regression (was broken since 0.1.0-rc25).
- Fix logging messages.
- JNLP launcher:
  - No certificate check option.
  - Allow custom settings.
  - Use adduser, gosu (Support stock jdk alpine image).

## 0.1.0-rc27
- [fix #83] Don't exclude Demand strategy. 
- Form validation for Links

## 0.1.0-rc26
 - Add links to create options

## 0.1.0-rc25
 - jucies is optional dep.
 - Fix idle timeout persistence.

## 0.1.0-rc24
 - Update to docker-java 3.0.6. (Support unix socket for JERSEY impl).

## 0.1.0-rc23
 - Don't print NPE warn in system log. On < 2.12 core will show strategies in global settings.

## 0.1.0-rc22
 - Fix provisioning strategy.

## 0.1.0-rc21
 - More logging for ssh launcher.

## 0.1.0-rc20
 - Fix load private key generated with linux openssl.

## 0.1.0-rc19
 - Update docker-java dependency.
 - Don't warn about 1.24 API.

## 0.1.0-rc18
 - Enhance usability: more help files, UI input validations.
 - Added NPE debug code.
 - Codecoverage is back.

## 0.1.0-rc17
 - Inject env vars for workflow-plugin.

## 0.1.0-rc16
 - Fix `Test Connection` in configuration.
 - Allow set connector type `Netty` or `Jersey`.

## 0.1.0-rc15
 - Fix image.getRepoTags() NPE.
 - Fix http -> tcp UI help.

## 0.1.0-rc14
 - Fix UI databinding for tlsVerify

## 0.1.0-rc13
 - change git tag names for releases

## 0.1.0-rc12
 - Prepare release for jitpack.

## 0.1.0-rc11
 - Fix NPE when dockerTlsVerify was undefined.

## 0.1.0-rc10
 -	Added cpusetMems cpusetCpus create options.
 - Added devices container create option.
 - Switch to docker-java-3.0.0 (custom until https://github.com/docker-java/docker-java/pull/596 )
 - Switch to netty implementation (helps to use with docker-beta)

## 0.1.0-rc9
 - Fixed template counting limit.

## 0.1.0-rc8
 - Add network (net) parameter to docker template settings.
 
## ~~0.1.0-rc7~~

## 0.1.0-rc6
 - Faster node provisioning strategy. Exclude delay before provision and allow provisioning multiple slaves for single label in a time.

## 0.1.0-rc5
 - Fix possible null during pull.
 - Update docker-java
 - Fix possible delay in slave clean-up in case of errors.

## 0.1.0-rc4
 - New "pull once" strategy
 - Support credentials for pull operation
 - Fixed some UI settings with a test case.
 - Support NodeProperties (i.e. ToolsInstallation).
 - Support ECDSA keys for docker daemon auth.
 - More integration tests

## 0.1.0-rc3
- Release to main Jenkins Update Center

## 0.1.0-rc2
- Failed maven-release-plugin release

## 0.1.0-alpha7
- Fix UI configuration save.

## 0.1.0-alpha6 
 - Fully fixed shading (excludes conflict with docker-traceability). Verified with IT.
 
## < 0.1.0-alpha5
 - Failed attempts to release plugin.
 - Rewrote everything, some logic that @KostyaSha wrote before kept.

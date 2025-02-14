# Changelog

## [v0.12.0](https://github.com/googleforgames/agones/tree/v0.12.0) (2019-08-06)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.12.0-rc...v0.12.0)

**Closed issues:**

- Release 0.12.0-rc [\#972](https://github.com/googleforgames/agones/issues/972)

**Merged pull requests:**

- Minor Fix 0.8.1 release on agones.dev Blog [\#978](https://github.com/googleforgames/agones/pull/978) ([aLekSer](https://github.com/aLekSer))
- Minor - Fix helm repo command in the governance template [\#977](https://github.com/googleforgames/agones/pull/977) ([aLekSer](https://github.com/aLekSer))
- Documentation updates to apply just prior to cutting the 0.12.0 release. [\#911](https://github.com/googleforgames/agones/pull/911) ([roberthbailey](https://github.com/roberthbailey))

## [v0.12.0-rc](https://github.com/googleforgames/agones/tree/v0.12.0-rc) (2019-08-01)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.11.0...v0.12.0-rc)

**Breaking changes:**

- C++ SDK: Use const-reference in WatchGameServer [\#941](https://github.com/googleforgames/agones/issues/941)
- Proposal: Split up the api group stable.agones.dev [\#703](https://github.com/googleforgames/agones/issues/703)
- Update the supported version of Kubernetes to 1.12. [\#967](https://github.com/googleforgames/agones/pull/967) ([roberthbailey](https://github.com/roberthbailey))
- Update the node affinity key to the new label name. [\#964](https://github.com/googleforgames/agones/pull/964) ([roberthbailey](https://github.com/roberthbailey))
- Implement block on connect with Rust+Node.js SDK [\#953](https://github.com/googleforgames/agones/pull/953) ([markmandel](https://github.com/markmandel))
- C++ SDK: Update the function signature of WatchGameServer to use a const-reference [\#951](https://github.com/googleforgames/agones/pull/951) ([roberthbailey](https://github.com/roberthbailey))
- Update GKE documentation to 1.12 [\#897](https://github.com/googleforgames/agones/pull/897) ([roberthbailey](https://github.com/roberthbailey))
- Move the stable api group and promote it to v1 [\#894](https://github.com/googleforgames/agones/pull/894) ([roberthbailey](https://github.com/roberthbailey))
- Promote allocation to v1 [\#881](https://github.com/googleforgames/agones/pull/881) ([roberthbailey](https://github.com/roberthbailey))
- Promote autoscaling to v1 [\#874](https://github.com/googleforgames/agones/pull/874) ([roberthbailey](https://github.com/roberthbailey))
- Remove / Expire FleetAllocation from documentation. [\#867](https://github.com/googleforgames/agones/pull/867) ([markmandel](https://github.com/markmandel))
- Remove FleetAllocation. [\#856](https://github.com/googleforgames/agones/pull/856) ([markmandel](https://github.com/markmandel))

**Implemented enhancements:**

- Make all yaml files in the examples directory use working configurations / images [\#969](https://github.com/googleforgames/agones/issues/969)
- Move nodejs example to a docker build [\#943](https://github.com/googleforgames/agones/issues/943)
- Upgrade to Kubernetes 1.12 [\#717](https://github.com/googleforgames/agones/issues/717)
- 1st Party / Distributed Matchmaker support [\#660](https://github.com/googleforgames/agones/issues/660)
- SDK Build/test pipeline separation from build-image [\#599](https://github.com/googleforgames/agones/issues/599)
- Move to using CRD Subresources for all Agones CRDs [\#329](https://github.com/googleforgames/agones/issues/329)
- Unity Plugin SDK [\#246](https://github.com/googleforgames/agones/issues/246)
- Add Reserve to Node.js SDK [\#955](https://github.com/googleforgames/agones/pull/955) ([steven-supersolid](https://github.com/steven-supersolid))
- Add the missing functions to the C++ SDK \(Allocated & Reserve\) [\#948](https://github.com/googleforgames/agones/pull/948) ([roberthbailey](https://github.com/roberthbailey))
- Update the nodejs example to build in a docker image [\#945](https://github.com/googleforgames/agones/pull/945) ([roberthbailey](https://github.com/roberthbailey))
- Updates to the C++ SDK along with the simple example that exercises it. [\#934](https://github.com/googleforgames/agones/pull/934) ([roberthbailey](https://github.com/roberthbailey))
- Update GameServer state diagram with Reserved [\#933](https://github.com/googleforgames/agones/pull/933) ([markmandel](https://github.com/markmandel))
- E2E tests for SDK.Reserve\(seconds\) [\#925](https://github.com/googleforgames/agones/pull/925) ([markmandel](https://github.com/markmandel))
- Add new GameServer lifecycle diagrams for Reserved [\#922](https://github.com/googleforgames/agones/pull/922) ([markmandel](https://github.com/markmandel))
- Compliance tests for Reserve\(seconds\). [\#920](https://github.com/googleforgames/agones/pull/920) ([markmandel](https://github.com/markmandel))
- Reserve\(\) SDK implementation [\#891](https://github.com/googleforgames/agones/pull/891) ([markmandel](https://github.com/markmandel))
- Update GKE development tooling to 1.12 [\#887](https://github.com/googleforgames/agones/pull/887) ([markmandel](https://github.com/markmandel))
- Fix Rust SDK, add allocate, add conformance test [\#879](https://github.com/googleforgames/agones/pull/879) ([aLekSer](https://github.com/aLekSer))
- Add instructions about taints and tolerations to the install instructions [\#870](https://github.com/googleforgames/agones/pull/870) ([roberthbailey](https://github.com/roberthbailey))
- Add events to SDK state change operations [\#866](https://github.com/googleforgames/agones/pull/866) ([markmandel](https://github.com/markmandel))
- Add ReserveUntil to GameServer.Status [\#865](https://github.com/googleforgames/agones/pull/865) ([markmandel](https://github.com/markmandel))
- add unity example [\#860](https://github.com/googleforgames/agones/pull/860) ([whisper0077](https://github.com/whisper0077))
- SDK Conformance testing [\#848](https://github.com/googleforgames/agones/pull/848) ([aLekSer](https://github.com/aLekSer))
- Reserve proto definition and generated code [\#820](https://github.com/googleforgames/agones/pull/820) ([markmandel](https://github.com/markmandel))
- Cpp prerequisities cmake [\#803](https://github.com/googleforgames/agones/pull/803) ([dsazonoff](https://github.com/dsazonoff))

**Fixed bugs:**

- Rust SDK does not wait for connection to be ready [\#938](https://github.com/googleforgames/agones/issues/938)
- Unable to build the rust-simple example [\#935](https://github.com/googleforgames/agones/issues/935)
- Building the rust sdk leaves untracked files [\#912](https://github.com/googleforgames/agones/issues/912)
- Fail to pass Health Check on Agones + UE4 plugin [\#861](https://github.com/googleforgames/agones/issues/861)
- Agones Getting Started Guide with Minikube uses wrong IP due to minikube bug  [\#751](https://github.com/googleforgames/agones/issues/751)
- Flaky - e2e cp: cannot stat [\#919](https://github.com/googleforgames/agones/pull/919) ([markmandel](https://github.com/markmandel))
- added affinity and tolerations to gameserver-allocator [\#910](https://github.com/googleforgames/agones/pull/910) ([daplho](https://github.com/daplho))
- fix: Fix gRCP context leaks. [\#904](https://github.com/googleforgames/agones/pull/904) ([devjgm](https://github.com/devjgm))
- Fix minikube developer experience [\#898](https://github.com/googleforgames/agones/pull/898) ([markmandel](https://github.com/markmandel))
- Fix timeout on Terraform Helm install agones step [\#890](https://github.com/googleforgames/agones/pull/890) ([aLekSer](https://github.com/aLekSer))
- Flaky: TestGameServerPassthroughPort [\#863](https://github.com/googleforgames/agones/pull/863) ([markmandel](https://github.com/markmandel))

**Security fixes:**

- Need to Bump js-yaml from 3.12.1 to 3.13.1 in /sdks/nodejs  [\#868](https://github.com/googleforgames/agones/issues/868)
- Update node.js coverage, dependencies and potential issue [\#954](https://github.com/googleforgames/agones/pull/954) ([steven-supersolid](https://github.com/steven-supersolid))

**Closed issues:**

- Approver access for @roberthbailey [\#914](https://github.com/googleforgames/agones/issues/914)
- Release 0.11.0 [\#849](https://github.com/googleforgames/agones/issues/849)
- NodeJS example needs a description in the README [\#728](https://github.com/googleforgames/agones/issues/728)
- C++ SDK should follow Google Style  [\#713](https://github.com/googleforgames/agones/issues/713)
- Write a guide for setting up Agones with taints and tolerations [\#491](https://github.com/googleforgames/agones/issues/491)

**Merged pull requests:**

- Typo in the changelog. [\#974](https://github.com/googleforgames/agones/pull/974) ([markmandel](https://github.com/markmandel))
- Release 0.12.0-rc [\#973](https://github.com/googleforgames/agones/pull/973) ([markmandel](https://github.com/markmandel))
- Fix Reference docs and sync it with Examples dir [\#970](https://github.com/googleforgames/agones/pull/970) ([aLekSer](https://github.com/aLekSer))
- Fix AWS EKS cluster creating docs [\#965](https://github.com/googleforgames/agones/pull/965) ([aLekSer](https://github.com/aLekSer))
- Fix Installation Docs and example GS configuration [\#962](https://github.com/googleforgames/agones/pull/962) ([aLekSer](https://github.com/aLekSer))
- \[Fix Breaking CI\] Site test failure due to 404s [\#961](https://github.com/googleforgames/agones/pull/961) ([markmandel](https://github.com/markmandel))
- Fix the capitalization for 'publishVersion' in the website docs. [\#960](https://github.com/googleforgames/agones/pull/960) ([roberthbailey](https://github.com/roberthbailey))
- Remove GameServer UpdateStatus\(\) since its not being used. [\#959](https://github.com/googleforgames/agones/pull/959) ([markmandel](https://github.com/markmandel))
- Update the container image version for the simple unity sdk. [\#952](https://github.com/googleforgames/agones/pull/952) ([roberthbailey](https://github.com/roberthbailey))
- Update the xonotic wrapper binary to the new Go SDK version. [\#950](https://github.com/googleforgames/agones/pull/950) ([roberthbailey](https://github.com/roberthbailey))
- Fix indentation of two of the build targets. [\#944](https://github.com/googleforgames/agones/pull/944) ([roberthbailey](https://github.com/roberthbailey))
- Updates to the rust simple example. [\#937](https://github.com/googleforgames/agones/pull/937) ([roberthbailey](https://github.com/roberthbailey))
- Update Dockerfile for Rust simple [\#936](https://github.com/googleforgames/agones/pull/936) ([aLekSer](https://github.com/aLekSer))
- With the extra whitespace the rendered output has undesirable new paragraphs. [\#932](https://github.com/googleforgames/agones/pull/932) ([roberthbailey](https://github.com/roberthbailey))
- Updates to the create webhook fleetautoscaler guide. [\#931](https://github.com/googleforgames/agones/pull/931) ([roberthbailey](https://github.com/roberthbailey))
- Updates to the allocator service tutorial. [\#930](https://github.com/googleforgames/agones/pull/930) ([roberthbailey](https://github.com/roberthbailey))
- Update the dev-gameserver example to use the current udp-server container image. [\#929](https://github.com/googleforgames/agones/pull/929) ([roberthbailey](https://github.com/roberthbailey))
- Update K8s Code Generation Tooling to 1.12 [\#928](https://github.com/googleforgames/agones/pull/928) ([markmandel](https://github.com/markmandel))
- Flaky: Make preview --no-promote to avoid promotion race conditions [\#926](https://github.com/googleforgames/agones/pull/926) ([markmandel](https://github.com/markmandel))
- Fix a small typo. [\#923](https://github.com/googleforgames/agones/pull/923) ([roberthbailey](https://github.com/roberthbailey))
- Fixup the formatting on Fleet Getting Started Guide [\#921](https://github.com/googleforgames/agones/pull/921) ([markmandel](https://github.com/markmandel))
- Update client-go to 9.0.0 and k8s api to 1.12.10 [\#918](https://github.com/googleforgames/agones/pull/918) ([heartrobotninja](https://github.com/heartrobotninja))
- Fix the command to teardown the test cluster in the GKE developer instructions. [\#916](https://github.com/googleforgames/agones/pull/916) ([roberthbailey](https://github.com/roberthbailey))
- Newline at the end of go.mod [\#915](https://github.com/googleforgames/agones/pull/915) ([roberthbailey](https://github.com/roberthbailey))
- Fix Rust SDK conformance flakiness, add clean step [\#913](https://github.com/googleforgames/agones/pull/913) ([aLekSer](https://github.com/aLekSer))
- Cmake. Removed unused script. [\#907](https://github.com/googleforgames/agones/pull/907) ([dsazonoff](https://github.com/dsazonoff))
- Changed cmake required version to 3.5 to work on more machines [\#903](https://github.com/googleforgames/agones/pull/903) ([devjgm](https://github.com/devjgm))
- Upgrading Terraform to 0.12.3 [\#899](https://github.com/googleforgames/agones/pull/899) ([aLekSer](https://github.com/aLekSer))
- Update kind dev tooling to 1.12 [\#896](https://github.com/googleforgames/agones/pull/896) ([roberthbailey](https://github.com/roberthbailey))
- Update minikube documentation and dev tooling to 1.12 [\#895](https://github.com/googleforgames/agones/pull/895) ([roberthbailey](https://github.com/roberthbailey))
- Explicitly disable creation of the client certificate on GKE [\#888](https://github.com/googleforgames/agones/pull/888) ([roberthbailey](https://github.com/roberthbailey))
- Document SDK - Allocated-\>Ready\(\) [\#886](https://github.com/googleforgames/agones/pull/886) ([markmandel](https://github.com/markmandel))
- Small improvements to create-fleet quickstart [\#885](https://github.com/googleforgames/agones/pull/885) ([markmandel](https://github.com/markmandel))
- Last touches to the install guide regarding taints and tolerations [\#882](https://github.com/googleforgames/agones/pull/882) ([roberthbailey](https://github.com/roberthbailey))
- Make GameServerAllocation reference document [\#880](https://github.com/googleforgames/agones/pull/880) ([markmandel](https://github.com/markmandel))
- Fix ensure SDK image [\#878](https://github.com/googleforgames/agones/pull/878) ([aLekSer](https://github.com/aLekSer))
- Fix for CRD API docs generator [\#877](https://github.com/googleforgames/agones/pull/877) ([aLekSer](https://github.com/aLekSer))
- Update gen-sdk-grpc make target name. [\#873](https://github.com/googleforgames/agones/pull/873) ([roberthbailey](https://github.com/roberthbailey))
- Add a note about the gameserver IP not being reachable when using minikube [\#871](https://github.com/googleforgames/agones/pull/871) ([roberthbailey](https://github.com/roberthbailey))
- Docs: Centralise udp-server tag [\#869](https://github.com/googleforgames/agones/pull/869) ([markmandel](https://github.com/markmandel))
- Unreal Engine plugin - Health Ping Enabled to true by default [\#864](https://github.com/googleforgames/agones/pull/864) ([edwardchuang](https://github.com/edwardchuang))
- Fix for podtemplatespec link [\#862](https://github.com/googleforgames/agones/pull/862) ([markmandel](https://github.com/markmandel))
- Update gke install instructions [\#857](https://github.com/googleforgames/agones/pull/857) ([roberthbailey](https://github.com/roberthbailey))
- Cpp clang-format [\#855](https://github.com/googleforgames/agones/pull/855) ([dsazonoff](https://github.com/dsazonoff))
- Preparation for 0.12.0 sprint [\#852](https://github.com/googleforgames/agones/pull/852) ([markmandel](https://github.com/markmandel))
- Update CPP Example Readme and yaml files [\#847](https://github.com/googleforgames/agones/pull/847) ([markmandel](https://github.com/markmandel))
- Add Unity to the SDK page. [\#846](https://github.com/googleforgames/agones/pull/846) ([markmandel](https://github.com/markmandel))

## [v0.11.0](https://github.com/googleforgames/agones/tree/v0.11.0) (2019-06-25)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.11.0-rc...v0.11.0)

**Fixed bugs:**

- Set secret namespace to agones-system for allocator service [\#843](https://github.com/googleforgames/agones/pull/843) ([pooneh-m](https://github.com/pooneh-m))

**Closed issues:**

- Release 0.11.0-rc [\#841](https://github.com/googleforgames/agones/issues/841)

**Merged pull requests:**

- Release 0.11.0 [\#850](https://github.com/googleforgames/agones/pull/850) ([markmandel](https://github.com/markmandel))
- Flaky: TestAutoscalerWebhook [\#844](https://github.com/googleforgames/agones/pull/844) ([aLekSer](https://github.com/aLekSer))

## [v0.11.0-rc](https://github.com/googleforgames/agones/tree/v0.11.0-rc) (2019-06-18)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.10.0...v0.11.0-rc)

**Breaking changes:**

- Move FleetAutoscaling to autoscaling.agones.dev group [\#829](https://github.com/googleforgames/agones/pull/829) ([markmandel](https://github.com/markmandel))
- Fixing SDK proto file according to style guide [\#776](https://github.com/googleforgames/agones/pull/776) ([aLekSer](https://github.com/aLekSer))

**Implemented enhancements:**

- Add Events for common errors with Webhook FleetAutoscaler configuration [\#792](https://github.com/googleforgames/agones/issues/792)
- Self allocation in Node.js is not supported [\#773](https://github.com/googleforgames/agones/issues/773)
- In case of dynamic port allocation, offer the option to set the container port to the same value as the host port [\#294](https://github.com/googleforgames/agones/issues/294)
- Implement EnqueueAfter on WorkerQueue [\#835](https://github.com/googleforgames/agones/pull/835) ([markmandel](https://github.com/markmandel))
- Changed AllocationEndpoint to array of endpoints [\#830](https://github.com/googleforgames/agones/pull/830) ([pooneh-m](https://github.com/pooneh-m))
- fix: check if NodeExternalIP is empty to fallback to NodeInternalIP [\#828](https://github.com/googleforgames/agones/pull/828) ([aarnaud](https://github.com/aarnaud))
- Rewrite Agones Overview [\#824](https://github.com/googleforgames/agones/pull/824) ([markmandel](https://github.com/markmandel))
- Add Unity SDK [\#818](https://github.com/googleforgames/agones/pull/818) ([whisper0077](https://github.com/whisper0077))
- PortPolicy of Passthrough - Same Port for Container and Host [\#817](https://github.com/googleforgames/agones/pull/817) ([markmandel](https://github.com/markmandel))
- Add Fleet RollingUpdate strategy params validation [\#808](https://github.com/googleforgames/agones/pull/808) ([aLekSer](https://github.com/aLekSer))
- Batched Packed and Distributed Allocations [\#804](https://github.com/googleforgames/agones/pull/804) ([markmandel](https://github.com/markmandel))
- Add Events on FleetAutoscaler connection errors [\#794](https://github.com/googleforgames/agones/pull/794) ([aLekSer](https://github.com/aLekSer))
- Expose allocate method in node sdk [\#774](https://github.com/googleforgames/agones/pull/774) ([rorygarand](https://github.com/rorygarand))
- Adding an allocator service that acts as a reverse proxy. [\#768](https://github.com/googleforgames/agones/pull/768) ([pooneh-m](https://github.com/pooneh-m))
- Add Reserved GameServer State [\#766](https://github.com/googleforgames/agones/pull/766) ([markmandel](https://github.com/markmandel))
- Add AKS, GKE and Helm terraform modules [\#756](https://github.com/googleforgames/agones/pull/756) ([aLekSer](https://github.com/aLekSer))
- Add close method to node client [\#748](https://github.com/googleforgames/agones/pull/748) ([BradfordMedeiros](https://github.com/BradfordMedeiros))

**Fixed bugs:**

- Allocator service needs to get the namespace from input and not environment. [\#809](https://github.com/googleforgames/agones/issues/809)
- apiserver role binding is referencing an invalid system account [\#805](https://github.com/googleforgames/agones/issues/805)
- Fleet scale down doesn't work after an update [\#800](https://github.com/googleforgames/agones/issues/800)
- Fleet Rolling Update doesn't seem to be rolling [\#799](https://github.com/googleforgames/agones/issues/799)
- Packed Allocation is very not packed [\#783](https://github.com/googleforgames/agones/issues/783)
- If GameServer webhook validation fails, it doesn't raise up to Fleet [\#765](https://github.com/googleforgames/agones/issues/765)
- Some Gameservers stays in Unhealthy state \(instead of being deleted\) [\#736](https://github.com/googleforgames/agones/issues/736)
- GS Shutdown sdk calls sometimes failed/timeout and leave Gameservers behind [\#624](https://github.com/googleforgames/agones/issues/624)
- Adding apiGroup to roleRef for gameservice-allocator [\#825](https://github.com/googleforgames/agones/pull/825) ([pooneh-m](https://github.com/pooneh-m))
- Add ShutdownReplicas count [\#810](https://github.com/googleforgames/agones/pull/810) ([aLekSer](https://github.com/aLekSer))
- Fix Down Scale on RollingUpdate [\#802](https://github.com/googleforgames/agones/pull/802) ([aLekSer](https://github.com/aLekSer))
- Fix publishDate on unreal docs [\#793](https://github.com/googleforgames/agones/pull/793) ([markmandel](https://github.com/markmandel))
- Flaky: TestAllocator [\#789](https://github.com/googleforgames/agones/pull/789) ([markmandel](https://github.com/markmandel))
- Prevent race conditions by syncing node cache on GameServer controller [\#782](https://github.com/googleforgames/agones/pull/782) ([markmandel](https://github.com/markmandel))
- Prevent race conditions by syncing cache on new Allocation elements [\#780](https://github.com/googleforgames/agones/pull/780) ([markmandel](https://github.com/markmandel))
- Fix for front link. Not sure what happened? [\#772](https://github.com/googleforgames/agones/pull/772) ([markmandel](https://github.com/markmandel))
- Add validation of the fleet underlying gameserver [\#771](https://github.com/googleforgames/agones/pull/771) ([aLekSer](https://github.com/aLekSer))

**Closed issues:**

- Request to become an Approver on Agones [\#796](https://github.com/googleforgames/agones/issues/796)
- Approver access for @pooneh-m [\#787](https://github.com/googleforgames/agones/issues/787)
- Release 0.10.0 [\#769](https://github.com/googleforgames/agones/issues/769)
- Use batching in GameServerAllocation controller to improve throughput. [\#536](https://github.com/googleforgames/agones/issues/536)
- Improve fleet scaling performance [\#483](https://github.com/googleforgames/agones/issues/483)
- End to End test [\#37](https://github.com/googleforgames/agones/issues/37)

**Merged pull requests:**

- Release 0.11.0-rc [\#842](https://github.com/googleforgames/agones/pull/842) ([markmandel](https://github.com/markmandel))
- Flaky: TestFleetRecreateGameServers [\#840](https://github.com/googleforgames/agones/pull/840) ([markmandel](https://github.com/markmandel))
- Flaky: TestAllocator [\#839](https://github.com/googleforgames/agones/pull/839) ([markmandel](https://github.com/markmandel))
- Flaky: TestFleetRollingUpdate [\#838](https://github.com/googleforgames/agones/pull/838) ([markmandel](https://github.com/markmandel))
- Flaky: TestSDKSetAnnotation [\#837](https://github.com/googleforgames/agones/pull/837) ([markmandel](https://github.com/markmandel))
- Move all to https://github.com/googleforgames/agones [\#836](https://github.com/googleforgames/agones/pull/836) ([markmandel](https://github.com/markmandel))
- E2E test for Ready-\>Allocated-\>Ready [\#834](https://github.com/googleforgames/agones/pull/834) ([markmandel](https://github.com/markmandel))
- Remove GSA Experimental warnings. [\#833](https://github.com/googleforgames/agones/pull/833) ([markmandel](https://github.com/markmandel))
- More Google Inc. -\> Google LLC Licence changes. [\#832](https://github.com/googleforgames/agones/pull/832) ([markmandel](https://github.com/markmandel))
- Flaky: TestControllerSyncFleetAutoscaler [\#827](https://github.com/googleforgames/agones/pull/827) ([markmandel](https://github.com/markmandel))
- Move lifecycle diagram to use GameServerAllocation [\#823](https://github.com/googleforgames/agones/pull/823) ([markmandel](https://github.com/markmandel))
- Fix instructions for getting pprof information from controller [\#822](https://github.com/googleforgames/agones/pull/822) ([markmandel](https://github.com/markmandel))
- Fix header alignment on Fleet Reference [\#821](https://github.com/googleforgames/agones/pull/821) ([markmandel](https://github.com/markmandel))
- --promote on development site [\#819](https://github.com/googleforgames/agones/pull/819) ([markmandel](https://github.com/markmandel))
- Flaky: TestHealthControllerRun [\#816](https://github.com/googleforgames/agones/pull/816) ([markmandel](https://github.com/markmandel))
- Handle delete events when caching Ready GameServers for Allocation [\#815](https://github.com/googleforgames/agones/pull/815) ([markmandel](https://github.com/markmandel))
- Remove env namespace dependency from allocator service. [\#814](https://github.com/googleforgames/agones/pull/814) ([pooneh-m](https://github.com/pooneh-m))
- Flaky: TestAutoscalerWebhook [\#812](https://github.com/googleforgames/agones/pull/812) ([markmandel](https://github.com/markmandel))
- Update Locust to 0.9 image and set cpu requests/limits [\#807](https://github.com/googleforgames/agones/pull/807) ([markmandel](https://github.com/markmandel))
- Correcting the reference to the service account role binding. \#805 [\#806](https://github.com/googleforgames/agones/pull/806) ([bbf](https://github.com/bbf))
- Add HandleError input parameter check [\#798](https://github.com/googleforgames/agones/pull/798) ([aLekSer](https://github.com/aLekSer))
- Fix locust tests [\#797](https://github.com/googleforgames/agones/pull/797) ([aLekSer](https://github.com/aLekSer))
- Fleetautoscaler: Add check to have minReplicas\>0 when use percents bufferSize [\#795](https://github.com/googleforgames/agones/pull/795) ([aLekSer](https://github.com/aLekSer))
- Add missing validation for GameServerSet, refactor [\#791](https://github.com/googleforgames/agones/pull/791) ([aLekSer](https://github.com/aLekSer))
- Add a link in the minikube install instructions to jump to creating the required cluster role binding [\#790](https://github.com/googleforgames/agones/pull/790) ([roberthbailey](https://github.com/roberthbailey))
- Docs: FleetAllocation example fix [\#788](https://github.com/googleforgames/agones/pull/788) ([rorygarand](https://github.com/rorygarand))
- Fix spelling in docs and comments [\#785](https://github.com/googleforgames/agones/pull/785) ([aLekSer](https://github.com/aLekSer))
- Flakey: TestControllerSyncGameServerDeletionTimestamp [\#781](https://github.com/googleforgames/agones/pull/781) ([markmandel](https://github.com/markmandel))
- Flaky: Race condition in TestControllerSyncGameServerStartingState [\#779](https://github.com/googleforgames/agones/pull/779) ([markmandel](https://github.com/markmandel))
- Update SDK page with full list of current SDKs. [\#778](https://github.com/googleforgames/agones/pull/778) ([markmandel](https://github.com/markmandel))
- Fix spelling mistake in grafana dashboard. [\#777](https://github.com/googleforgames/agones/pull/777) ([markmandel](https://github.com/markmandel))
- Preparation for 0.11.0 release! [\#775](https://github.com/googleforgames/agones/pull/775) ([markmandel](https://github.com/markmandel))
- Revert UnHealthy standalone GameServers to not be deleted [\#763](https://github.com/googleforgames/agones/pull/763) ([markmandel](https://github.com/markmandel))

## [v0.10.0](https://github.com/googleforgames/agones/tree/v0.10.0) (2019-05-16)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.10.0-rc...v0.10.0)

**Fixed bugs:**

- Add secret list and watch permissions to RBAC rules [\#762](https://github.com/googleforgames/agones/pull/762) ([pooneh-m](https://github.com/pooneh-m))

**Closed issues:**

- Release 0.10.0-rc [\#759](https://github.com/googleforgames/agones/issues/759)

**Merged pull requests:**

- Release 0.10.0 [\#770](https://github.com/googleforgames/agones/pull/770) ([markmandel](https://github.com/markmandel))
- Update examples list [\#767](https://github.com/googleforgames/agones/pull/767) ([markmandel](https://github.com/markmandel))
- Update Fleet autoscaling documentation [\#764](https://github.com/googleforgames/agones/pull/764) ([markmandel](https://github.com/markmandel))
- Bad copy paste on 0.10.0 rc release page [\#761](https://github.com/googleforgames/agones/pull/761) ([markmandel](https://github.com/markmandel))

## [v0.10.0-rc](https://github.com/googleforgames/agones/tree/v0.10.0-rc) (2019-05-08)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.9.0...v0.10.0-rc)

**Breaking changes:**

- Add status subresource for FleetAutoscaler [\#730](https://github.com/googleforgames/agones/pull/730) ([aLekSer](https://github.com/aLekSer))
- Implement GameServerAlocation as API Extension  [\#682](https://github.com/googleforgames/agones/pull/682) ([markmandel](https://github.com/markmandel))

**Implemented enhancements:**

- Implementing cross cluster allocation request [\#757](https://github.com/googleforgames/agones/pull/757) ([pooneh-m](https://github.com/pooneh-m))
- Rename APIServerEndpoint to AllocationEndpoint for multi-cluster allocation [\#755](https://github.com/googleforgames/agones/pull/755) ([pooneh-m](https://github.com/pooneh-m))
- Implement multicluster allocation for local cluster allocation. [\#753](https://github.com/googleforgames/agones/pull/753) ([pooneh-m](https://github.com/pooneh-m))
- Implementing cluster selector from multi-cluster allocation policies. [\#733](https://github.com/googleforgames/agones/pull/733) ([pooneh-m](https://github.com/pooneh-m))
- Added Supersolid logo to the homepage [\#727](https://github.com/googleforgames/agones/pull/727) ([KamiMay](https://github.com/KamiMay))
- Implementation of SDK.Allocate\(\) [\#721](https://github.com/googleforgames/agones/pull/721) ([markmandel](https://github.com/markmandel))
- Add allocation policy CRD and schema definition. [\#698](https://github.com/googleforgames/agones/pull/698) ([pooneh-m](https://github.com/pooneh-m))
- Helm support for Terraform [\#696](https://github.com/googleforgames/agones/pull/696) ([aLekSer](https://github.com/aLekSer))
- Implement lacking functions in Rust SDK [\#693](https://github.com/googleforgames/agones/pull/693) ([thara](https://github.com/thara))
- Terraform support to generate test cluster [\#670](https://github.com/googleforgames/agones/pull/670) ([aLekSer](https://github.com/aLekSer))
- Lightweight library for implementing APIServer extensions [\#659](https://github.com/googleforgames/agones/pull/659) ([markmandel](https://github.com/markmandel))
- Unreal Engine 4 Plugin [\#647](https://github.com/googleforgames/agones/pull/647) ([YannickLange](https://github.com/YannickLange))

**Fixed bugs:**

- Ensure memory leak fix in apimachinery wait.go fix does not get overwritten [\#734](https://github.com/googleforgames/agones/issues/734)
- Flaky Test: TestGameServerAllocationMetaDataPatch [\#725](https://github.com/googleforgames/agones/issues/725)
- gen-api-docs make target is not generating API docs for GameServerAllocation [\#705](https://github.com/googleforgames/agones/issues/705)
- Agones controller does not remove deleted pod from game server list [\#678](https://github.com/googleforgames/agones/issues/678)
- Flaky: Fix test for TestGameServerUnhealthyAfterDeletingPod [\#758](https://github.com/googleforgames/agones/pull/758) ([markmandel](https://github.com/markmandel))
- Updated the filtering condition on GameServerShutdown to include the undeleted Unhealthy GSs [\#740](https://github.com/googleforgames/agones/pull/740) ([ilkercelikyilmaz](https://github.com/ilkercelikyilmaz))
- Add back goimports 🔥 [\#714](https://github.com/googleforgames/agones/pull/714) ([markmandel](https://github.com/markmandel))
- Add proto directory and update tooling. [\#709](https://github.com/googleforgames/agones/pull/709) ([heartrobotninja](https://github.com/heartrobotninja))
- Add explicit local version of agones in go.mod [\#706](https://github.com/googleforgames/agones/pull/706) ([aLekSer](https://github.com/aLekSer))
- Move GameServer to Unheathy when Pod Deleted [\#694](https://github.com/googleforgames/agones/pull/694) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- Agones e2e tests are flakey [\#700](https://github.com/googleforgames/agones/issues/700)
- Release 0.9.0 [\#686](https://github.com/googleforgames/agones/issues/686)
- Integration with Unreal Engine [\#138](https://github.com/googleforgames/agones/issues/138)

**Merged pull requests:**

- Release 0.10.0-rc [\#760](https://github.com/googleforgames/agones/pull/760) ([markmandel](https://github.com/markmandel))
- Add tests for gameServerCacheEntry in GameServerAllocation controller [\#754](https://github.com/googleforgames/agones/pull/754) ([markmandel](https://github.com/markmandel))
- Fix instructions to create AKS cluster [\#752](https://github.com/googleforgames/agones/pull/752) ([aLekSer](https://github.com/aLekSer))
- Deprecate Fleet Allocation. [\#750](https://github.com/googleforgames/agones/pull/750) ([markmandel](https://github.com/markmandel))
- Cleanup - no longer need to list Pods for GameServers [\#747](https://github.com/googleforgames/agones/pull/747) ([markmandel](https://github.com/markmandel))
- Convert C++ Example to Docker Build Pattern [\#746](https://github.com/googleforgames/agones/pull/746) ([markmandel](https://github.com/markmandel))
- Switch to parrallel execution of SDK commands [\#742](https://github.com/googleforgames/agones/pull/742) ([aLekSer](https://github.com/aLekSer))
- Move terraform targets into a separate file [\#741](https://github.com/googleforgames/agones/pull/741) ([aLekSer](https://github.com/aLekSer))
- We don't need CMake in the base build image [\#739](https://github.com/googleforgames/agones/pull/739) ([markmandel](https://github.com/markmandel))
- CI Speedup: Cache Build SDK between builds [\#738](https://github.com/googleforgames/agones/pull/738) ([markmandel](https://github.com/markmandel))
- Intial tool vendoring commit. [\#737](https://github.com/googleforgames/agones/pull/737) ([heartrobotninja](https://github.com/heartrobotninja))
- Add vendor\_fixed directory with apimachinery module [\#735](https://github.com/googleforgames/agones/pull/735) ([heartrobotninja](https://github.com/heartrobotninja))
- Option for CMake silent output [\#731](https://github.com/googleforgames/agones/pull/731) ([dsazonoff](https://github.com/dsazonoff))
- Cache htmltest url checks for 2 weeks [\#729](https://github.com/googleforgames/agones/pull/729) ([markmandel](https://github.com/markmandel))
- Fix for flaky TestGameServerAllocationMetaDataPatch [\#726](https://github.com/googleforgames/agones/pull/726) ([markmandel](https://github.com/markmandel))
- Adds a .clang-format file making Google style the default [\#724](https://github.com/googleforgames/agones/pull/724) ([devjgm](https://github.com/devjgm))
- Group make test output in cloudbuild.yaml [\#723](https://github.com/googleforgames/agones/pull/723) ([markmandel](https://github.com/markmandel))
- Upgrade Hugo to 0.55.2 [\#722](https://github.com/googleforgames/agones/pull/722) ([markmandel](https://github.com/markmandel))
- Remove dependency to util/runtime from allocation/v1alpha1/register.go [\#720](https://github.com/googleforgames/agones/pull/720) ([pooneh-m](https://github.com/pooneh-m))
- Clang-formatted the C++ SDK files. [\#716](https://github.com/googleforgames/agones/pull/716) ([devjgm](https://github.com/devjgm))
- Abstract build image ensuring and building [\#715](https://github.com/googleforgames/agones/pull/715) ([markmandel](https://github.com/markmandel))
- Mount go mod cache [\#712](https://github.com/googleforgames/agones/pull/712) ([markmandel](https://github.com/markmandel))
- Move local-includes above others [\#711](https://github.com/googleforgames/agones/pull/711) ([markmandel](https://github.com/markmandel))
- We no longer need gen-grpc-cpp.sh [\#710](https://github.com/googleforgames/agones/pull/710) ([markmandel](https://github.com/markmandel))
- Update issue templates [\#708](https://github.com/googleforgames/agones/pull/708) ([thisisnotapril](https://github.com/thisisnotapril))
- Change  the website theme  and add Ubisoft logo [\#704](https://github.com/googleforgames/agones/pull/704) ([cyriltovena](https://github.com/cyriltovena))
- Fixed typo in URL [\#702](https://github.com/googleforgames/agones/pull/702) ([devjgm](https://github.com/devjgm))
- Fixed a minor typo [\#701](https://github.com/googleforgames/agones/pull/701) ([pooneh-m](https://github.com/pooneh-m))
- Change License from Google Inc. to Google LLC due to branding change in 2015 [\#699](https://github.com/googleforgames/agones/pull/699) ([pooneh-m](https://github.com/pooneh-m))
- Remove dependency to util/runtime from APIS package [\#697](https://github.com/googleforgames/agones/pull/697) ([pooneh-m](https://github.com/pooneh-m))
- Update Linter to 1.16.0 [\#692](https://github.com/googleforgames/agones/pull/692) ([markmandel](https://github.com/markmandel))
- Choose specific release version of gen-crd-api-reference-docs [\#691](https://github.com/googleforgames/agones/pull/691) ([aLekSer](https://github.com/aLekSer))
- Upgrade Testify to 1.3.0 [\#689](https://github.com/googleforgames/agones/pull/689) ([markmandel](https://github.com/markmandel))
- Setup for release 0.10.0 [\#688](https://github.com/googleforgames/agones/pull/688) ([markmandel](https://github.com/markmandel))
- End to end tests for GameServer Pod Deletion [\#684](https://github.com/googleforgames/agones/pull/684) ([markmandel](https://github.com/markmandel))
- Removes the sdk generation tooling from our main build image [\#630](https://github.com/googleforgames/agones/pull/630) ([cyriltovena](https://github.com/cyriltovena))

## [v0.9.0](https://github.com/googleforgames/agones/tree/v0.9.0) (2019-04-03)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.9.0-rc...v0.9.0)

**Fixed bugs:**

- Url pointing to install.yaml pointing to master [\#676](https://github.com/googleforgames/agones/pull/676) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- Release 0.9.0-rc [\#673](https://github.com/googleforgames/agones/issues/673)
- Move to go modules [\#625](https://github.com/googleforgames/agones/issues/625)
- Documentation for the extended Kubernetes API [\#409](https://github.com/googleforgames/agones/issues/409)

**Merged pull requests:**

- Changes for 0.9.0 release! [\#687](https://github.com/googleforgames/agones/pull/687) ([markmandel](https://github.com/markmandel))
- Add the GDC presentation to the website [\#685](https://github.com/googleforgames/agones/pull/685) ([markmandel](https://github.com/markmandel))
- Forgot to highlight the breaking change. [\#680](https://github.com/googleforgames/agones/pull/680) ([markmandel](https://github.com/markmandel))
- Minor tweaks to documentation [\#677](https://github.com/googleforgames/agones/pull/677) ([markmandel](https://github.com/markmandel))
- Update do-release to fully build images [\#675](https://github.com/googleforgames/agones/pull/675) ([markmandel](https://github.com/markmandel))

## [v0.9.0-rc](https://github.com/googleforgames/agones/tree/v0.9.0-rc) (2019-03-26)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.8.1...v0.9.0-rc)

**Breaking changes:**

- Consistency: Portpolicy static=\>Static & dynamic=\>Dynamic [\#617](https://github.com/googleforgames/agones/pull/617) ([markmandel](https://github.com/markmandel))

**Implemented enhancements:**

- Adding a section in the documentation about deploying Agones using GCP Marketplace. [\#664](https://github.com/googleforgames/agones/pull/664) ([bbf](https://github.com/bbf))
- Add Agones Kubernetes API docs generator [\#645](https://github.com/googleforgames/agones/pull/645) ([aLekSer](https://github.com/aLekSer))
- Added support for persisting logs in 'emptyDir' volume attached to agones controller. [\#620](https://github.com/googleforgames/agones/pull/620) ([jkowalski](https://github.com/jkowalski))
- Adding Locust tests - initial changes for \#412 [\#611](https://github.com/googleforgames/agones/pull/611) ([pm7h](https://github.com/pm7h))
- Emit stress test metrics in Fortio format. [\#586](https://github.com/googleforgames/agones/pull/586) ([jkowalski](https://github.com/jkowalski))
- Add Node.js SDK and example - closes \#538 [\#581](https://github.com/googleforgames/agones/pull/581) ([steven-supersolid](https://github.com/steven-supersolid))
- Cpp sdk cmake [\#464](https://github.com/googleforgames/agones/pull/464) ([dsazonoff](https://github.com/dsazonoff))

**Fixed bugs:**

- Feature shortcode does not behave correctly for versions \> "0.10.0" \(2 digit minor version\) [\#650](https://github.com/googleforgames/agones/issues/650)
- Labels referencing resources name can be too long [\#541](https://github.com/googleforgames/agones/issues/541)
- Fix feature shortcode for Hugo [\#655](https://github.com/googleforgames/agones/pull/655) ([aLekSer](https://github.com/aLekSer))
- \[Regression\] Fleet scale down didn't adhere to Packed Scheduling [\#638](https://github.com/googleforgames/agones/pull/638) ([markmandel](https://github.com/markmandel))
- Fixed gameserverset overshooting the number of GameServers [\#621](https://github.com/googleforgames/agones/pull/621) ([jkowalski](https://github.com/jkowalski))
- Update GameServerSet scheduling when Fleet scheduling is changed. [\#582](https://github.com/googleforgames/agones/pull/582) ([pooneh-m](https://github.com/pooneh-m))

**Security fixes:**

- Remove serviceaccount for game server container [\#640](https://github.com/googleforgames/agones/pull/640) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- gcloud-auth-cluster: Create unique name for cluster role binding [\#662](https://github.com/googleforgames/agones/issues/662)
- Hotfix 0.8.1 [\#652](https://github.com/googleforgames/agones/issues/652)
- Slow game servers deletion [\#540](https://github.com/googleforgames/agones/issues/540)

**Merged pull requests:**

- Release 0.9.0-rc [\#674](https://github.com/googleforgames/agones/pull/674) ([markmandel](https://github.com/markmandel))
- Fix typo on metrics documentation [\#671](https://github.com/googleforgames/agones/pull/671) ([princyraza](https://github.com/princyraza))
- Moved Azure link, breaking builds. [\#669](https://github.com/googleforgames/agones/pull/669) ([markmandel](https://github.com/markmandel))
- Add hash of account to clusterrolebinding name to support multiple accounts [\#666](https://github.com/googleforgames/agones/pull/666) ([aLekSer](https://github.com/aLekSer))
- Simplify homepage messaging [\#665](https://github.com/googleforgames/agones/pull/665) ([markmandel](https://github.com/markmandel))
- GKE installation n1-standard-1 -\> n1-standard-2 [\#663](https://github.com/googleforgames/agones/pull/663) ([markmandel](https://github.com/markmandel))
- Switch Agones to Go Modules [\#661](https://github.com/googleforgames/agones/pull/661) ([heartrobotninja](https://github.com/heartrobotninja))
-  Merge hotfix 0.8.1 back into master [\#658](https://github.com/googleforgames/agones/pull/658) ([markmandel](https://github.com/markmandel))
- Cleanup Xonotic image [\#654](https://github.com/googleforgames/agones/pull/654) ([markmandel](https://github.com/markmandel))
- E2E Cleanup: Implement SendGameServerUDP [\#644](https://github.com/googleforgames/agones/pull/644) ([markmandel](https://github.com/markmandel))
- Refactor https server into its own component [\#643](https://github.com/googleforgames/agones/pull/643) ([markmandel](https://github.com/markmandel))
- Add .gocache directory for WSL users [\#642](https://github.com/googleforgames/agones/pull/642) ([heartrobotninja](https://github.com/heartrobotninja))
- E2E test for Disabled Health checks. [\#641](https://github.com/googleforgames/agones/pull/641) ([markmandel](https://github.com/markmandel))
- Refactor AllocationCounter to GameServerCounter [\#639](https://github.com/googleforgames/agones/pull/639) ([markmandel](https://github.com/markmandel))
- Adding Kubernetes API server requests metrics [\#637](https://github.com/googleforgames/agones/pull/637) ([aLekSer](https://github.com/aLekSer))
- Partial revert "Emit stress test metrics in Fortio format." which accidentally overwrote our vendored fixes to wait.go [\#633](https://github.com/googleforgames/agones/pull/633) ([jkowalski](https://github.com/jkowalski))
- Switch to using default gke-cluster oauthScopes settings for clusters [\#632](https://github.com/googleforgames/agones/pull/632) ([aLekSer](https://github.com/aLekSer))
- Update docs Create Gameserver with current state [\#627](https://github.com/googleforgames/agones/pull/627) ([aLekSer](https://github.com/aLekSer))
- Add input parameters check on CRD loggers [\#626](https://github.com/googleforgames/agones/pull/626) ([aLekSer](https://github.com/aLekSer))
- New logo for the website! [\#618](https://github.com/googleforgames/agones/pull/618) ([markmandel](https://github.com/markmandel))
- Unified logging of resource identifiers so that we can reliably get entire history of a resource in stack driver. [\#616](https://github.com/googleforgames/agones/pull/616) ([jkowalski](https://github.com/jkowalski))
- Organising Makefile into includes [\#615](https://github.com/googleforgames/agones/pull/615) ([markmandel](https://github.com/markmandel))
- Upgraed go-lint tooling. [\#612](https://github.com/googleforgames/agones/pull/612) ([markmandel](https://github.com/markmandel))
- Moving to 0.9.0! [\#610](https://github.com/googleforgames/agones/pull/610) ([markmandel](https://github.com/markmandel))
- Adding resources limits for E2E tests gameserver Spec [\#606](https://github.com/googleforgames/agones/pull/606) ([aLekSer](https://github.com/aLekSer))
- Add Fleet and Gameserverset Validation handler [\#598](https://github.com/googleforgames/agones/pull/598) ([aLekSer](https://github.com/aLekSer))
- Improve allocation performance [\#583](https://github.com/googleforgames/agones/pull/583) ([ilkercelikyilmaz](https://github.com/ilkercelikyilmaz))
- Add status subresource to fleet and Gameserverset [\#575](https://github.com/googleforgames/agones/pull/575) ([aLekSer](https://github.com/aLekSer))

## [v0.8.1](https://github.com/googleforgames/agones/tree/v0.8.1) (2019-03-15)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.8.0...v0.8.1)

**Implemented enhancements:**

- Create Node.js library [\#538](https://github.com/googleforgames/agones/issues/538)

**Fixed bugs:**

- CPU/Memory leak issue caused by go routines that never completes [\#636](https://github.com/googleforgames/agones/issues/636)
- Quickstart: Create a Game Server [\#609](https://github.com/googleforgames/agones/issues/609)
- Fleet status completely out-of-sync with GameServerSet status [\#570](https://github.com/googleforgames/agones/issues/570)
- GameServerSet sometimes creates more GameServers than necessary [\#569](https://github.com/googleforgames/agones/issues/569)
- If you modify the `Scheduling` on a Fleet, it does not flow down to the `GameServerSet`. [\#495](https://github.com/googleforgames/agones/issues/495)
- SDK Service Account was Hardcoded [\#629](https://github.com/googleforgames/agones/pull/629) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- GKE scopes in installation and testing are overkill [\#614](https://github.com/googleforgames/agones/issues/614)
- Release 0.8.0 [\#604](https://github.com/googleforgames/agones/issues/604)
- Grafana: add basic API Server graphs [\#546](https://github.com/googleforgames/agones/issues/546)
- Remove all the kubectl custom commands from the quickstarts [\#521](https://github.com/googleforgames/agones/issues/521)

**Merged pull requests:**

- Final release pieces for 0.8.1 hotfix. [\#653](https://github.com/googleforgames/agones/pull/653) ([markmandel](https://github.com/markmandel))
- Tarballing source into the images for dependencies that are required by their licenses. [\#634](https://github.com/googleforgames/agones/pull/634) ([bbf](https://github.com/bbf))
- 2 Hotfixes: Allow Helm to reference image digests and inject licenses [\#631](https://github.com/googleforgames/agones/pull/631) ([bbf](https://github.com/bbf))
- \[Hotfix\] Prep work for hotfix 0.8.1 [\#628](https://github.com/googleforgames/agones/pull/628) ([markmandel](https://github.com/markmandel))

## [v0.8.0](https://github.com/googleforgames/agones/tree/v0.8.0) (2019-02-20)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.8.0-rc...v0.8.0)

**Implemented enhancements:**

- Register GameServers with local IP addresses [\#469](https://github.com/googleforgames/agones/issues/469)

**Fixed bugs:**

- agonessdk-0.8.0-\*-runtime-linux-arch\_64.tar.gz is growing unboundedly [\#589](https://github.com/googleforgames/agones/issues/589)
- Create a boolean to gate the creation of priority classes for controllers. [\#602](https://github.com/googleforgames/agones/pull/602) ([bbf](https://github.com/bbf))
- Exclude tar.gz and zip files from Runtime archive [\#596](https://github.com/googleforgames/agones/pull/596) ([aLekSer](https://github.com/aLekSer))
- Switch to htmltest link checker -- and fix issues [\#594](https://github.com/googleforgames/agones/pull/594) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- Release 0.8.0-rc [\#590](https://github.com/googleforgames/agones/issues/590)
- Help us pick a new project logo!  [\#577](https://github.com/googleforgames/agones/issues/577)

**Merged pull requests:**

- Release 0.8.0 [\#605](https://github.com/googleforgames/agones/pull/605) ([markmandel](https://github.com/markmandel))
- Remove deprecation from FleetAllocation [\#603](https://github.com/googleforgames/agones/pull/603) ([markmandel](https://github.com/markmandel))
- Remove -v from Go testing - becomes too noisy [\#595](https://github.com/googleforgames/agones/pull/595) ([markmandel](https://github.com/markmandel))
- Minor tweaks to release process. [\#592](https://github.com/googleforgames/agones/pull/592) ([markmandel](https://github.com/markmandel))

## [v0.8.0-rc](https://github.com/googleforgames/agones/tree/v0.8.0-rc) (2019-02-14)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.7.0...v0.8.0-rc)

**Implemented enhancements:**

- Allocation on GameServers rather than Fleets [\#436](https://github.com/googleforgames/agones/issues/436)
- Website that contains documentation [\#410](https://github.com/googleforgames/agones/issues/410)
- Node Affinity, Tolerations and Node selector support for helm chart [\#407](https://github.com/googleforgames/agones/issues/407)
- As game server, I want to get the Agones sidecar version [\#310](https://github.com/googleforgames/agones/issues/310)
- fix setAnnotation for simple-udp to use customized key & value [\#576](https://github.com/googleforgames/agones/pull/576) ([Yingxin-Jiang](https://github.com/Yingxin-Jiang))
- Adding GitHub link and version dropdown to the navigation bar [\#566](https://github.com/googleforgames/agones/pull/566) ([markmandel](https://github.com/markmandel))
- simple-udp: added support for customizing labels and annotations by the caller [\#564](https://github.com/googleforgames/agones/pull/564) ([jkowalski](https://github.com/jkowalski))
- Monitoring improvements [\#559](https://github.com/googleforgames/agones/pull/559) ([jkowalski](https://github.com/jkowalski))
- Add support to create a development gameserver. [\#558](https://github.com/googleforgames/agones/pull/558) ([jeremyje](https://github.com/jeremyje))
- Adds gameservers per node count and distribution [\#551](https://github.com/googleforgames/agones/pull/551) ([cyriltovena](https://github.com/cyriltovena))
- Add Scale Subresource into Fleet and Gameserverset CRDs [\#539](https://github.com/googleforgames/agones/pull/539) ([aLekSer](https://github.com/aLekSer))
- Continuous Deployment of Agones.dev [\#527](https://github.com/googleforgames/agones/pull/527) ([markmandel](https://github.com/markmandel))
- Makefile: allowed 'go test' to run without docker and optionally w/o race detector [\#509](https://github.com/googleforgames/agones/pull/509) ([jkowalski](https://github.com/jkowalski))
- add client-go metrics and grafana dashboards [\#505](https://github.com/googleforgames/agones/pull/505) ([cyriltovena](https://github.com/cyriltovena))
- Prometheus and grafana improvements based on load testing experience [\#501](https://github.com/googleforgames/agones/pull/501) ([jkowalski](https://github.com/jkowalski))
- improved isolation of Agones controllers using taints and priority [\#500](https://github.com/googleforgames/agones/pull/500) ([jkowalski](https://github.com/jkowalski))
- Add Agones version into Gameserver Annotation [\#498](https://github.com/googleforgames/agones/pull/498) ([aLekSer](https://github.com/aLekSer))
- controller: made QPS, burst QPS and number of workers externally configurable [\#497](https://github.com/googleforgames/agones/pull/497) ([jkowalski](https://github.com/jkowalski))
- Website for Agones [\#493](https://github.com/googleforgames/agones/pull/493) ([markmandel](https://github.com/markmandel))
- Add Stackdriver Exporter for Opencensus [\#492](https://github.com/googleforgames/agones/pull/492) ([aLekSer](https://github.com/aLekSer))
- Add TLS to Fleetautoscaler webhook service [\#476](https://github.com/googleforgames/agones/pull/476) ([aLekSer](https://github.com/aLekSer))
- Add pod tolerations, nodeSelector and affinity in helm [\#473](https://github.com/googleforgames/agones/pull/473) ([cyriltovena](https://github.com/cyriltovena))
- adding Prometheus+Grafana for metrics and visualizations [\#472](https://github.com/googleforgames/agones/pull/472) ([cyriltovena](https://github.com/cyriltovena))
- GameServerAllocation implementation [\#465](https://github.com/googleforgames/agones/pull/465) ([markmandel](https://github.com/markmandel))

**Fixed bugs:**

- Gameserver's that are not assigned to a node are left behind even after the scale was lowered [\#543](https://github.com/googleforgames/agones/issues/543)
- Investigate why increasing worker count/QPS causes E2E tests to fail [\#499](https://github.com/googleforgames/agones/issues/499)
- Investigate why we sometimes have multiple pods per gameserver [\#490](https://github.com/googleforgames/agones/issues/490)
- Assign higher priority to Agones system pods [\#489](https://github.com/googleforgames/agones/issues/489)
- e2e tests don't cleanup fleetautoscalers [\#471](https://github.com/googleforgames/agones/issues/471)
- Race condition in SDK.SetLabel and SDK.SetAnnotation [\#455](https://github.com/googleforgames/agones/issues/455)
- sdkserver: fix race condition in SDK.SetLabel and SDK.SetAnnotation \(issue \#455\) [\#588](https://github.com/googleforgames/agones/pull/588) ([Yingxin-Jiang](https://github.com/Yingxin-Jiang))
- Changed how GameServer POD names are generated [\#565](https://github.com/googleforgames/agones/pull/565) ([jkowalski](https://github.com/jkowalski))
- Fix stackdriver distribution without bucket bounds [\#554](https://github.com/googleforgames/agones/pull/554) ([aLekSer](https://github.com/aLekSer))
- Fix potential data race in allocation counter [\#525](https://github.com/googleforgames/agones/pull/525) ([markmandel](https://github.com/markmandel))
- Fix concurrency bug in port allocator. [\#514](https://github.com/googleforgames/agones/pull/514) ([markmandel](https://github.com/markmandel))
- Go download link has changed [\#494](https://github.com/googleforgames/agones/pull/494) ([markmandel](https://github.com/markmandel))
- Fix for the controller panic issue on metrics.enabled is false [\#486](https://github.com/googleforgames/agones/pull/486) ([aLekSer](https://github.com/aLekSer))

**Security fixes:**

- \[SECURITY\] Update Go to 1.11.5 [\#528](https://github.com/googleforgames/agones/pull/528) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- Grafana: add graph of nodes in cluster [\#547](https://github.com/googleforgames/agones/issues/547)
- Replace global allocation mutex with fine-grained concurrency controls. [\#535](https://github.com/googleforgames/agones/issues/535)
- Approver access for @jkowalski [\#526](https://github.com/googleforgames/agones/issues/526)
- Docker images layers not optimal [\#481](https://github.com/googleforgames/agones/issues/481)
- Release 0.7.0 [\#477](https://github.com/googleforgames/agones/issues/477)
- Improve build speed by refactoring Makefile [\#453](https://github.com/googleforgames/agones/issues/453)

**Merged pull requests:**

- Release 0.8.0-rc [\#591](https://github.com/googleforgames/agones/pull/591) ([markmandel](https://github.com/markmandel))
- typo [\#587](https://github.com/googleforgames/agones/pull/587) ([jkowalski](https://github.com/jkowalski))
- test: make e2e test logs more readable [\#585](https://github.com/googleforgames/agones/pull/585) ([jkowalski](https://github.com/jkowalski))
- Update godoc command to enable search [\#580](https://github.com/googleforgames/agones/pull/580) ([markmandel](https://github.com/markmandel))
- Removal of allocationMutex from controllers that don't need it. [\#579](https://github.com/googleforgames/agones/pull/579) ([markmandel](https://github.com/markmandel))
- Remove the mutex usage for Delete GS in both GS and GSS controllers [\#572](https://github.com/googleforgames/agones/pull/572) ([ilkercelikyilmaz](https://github.com/ilkercelikyilmaz))
- Added very simple stress test which scales fleets up/down and basic stress test harness [\#571](https://github.com/googleforgames/agones/pull/571) ([jkowalski](https://github.com/jkowalski))
- Fix of TestWorkQueueHealthCheck test [\#568](https://github.com/googleforgames/agones/pull/568) ([aLekSer](https://github.com/aLekSer))
- bump default qps to 400 w/burst to 500 and worker count to 100 [\#563](https://github.com/googleforgames/agones/pull/563) ([jkowalski](https://github.com/jkowalski))
- added fleet-loadtest.yaml for use in load testing [\#562](https://github.com/googleforgames/agones/pull/562) ([jkowalski](https://github.com/jkowalski))
- Fix prometheous installation on minikube [\#561](https://github.com/googleforgames/agones/pull/561) ([markmandel](https://github.com/markmandel))
- CloudBuild for a "development" subdomain [\#560](https://github.com/googleforgames/agones/pull/560) ([markmandel](https://github.com/markmandel))
- Remove the custom kubectl commands from quickstarts [\#556](https://github.com/googleforgames/agones/pull/556) ([hpandeycodeit](https://github.com/hpandeycodeit))
- e2e: fixed test-only race condition in TestAutoscalerBasicFunctions [\#552](https://github.com/googleforgames/agones/pull/552) ([jkowalski](https://github.com/jkowalski))
- e2e: improved logging and simplified waiting for fleet conditions [\#550](https://github.com/googleforgames/agones/pull/550) ([jkowalski](https://github.com/jkowalski))
- Typo: Docsy -\> Agones Blog. [\#549](https://github.com/googleforgames/agones/pull/549) ([markmandel](https://github.com/markmandel))
- GameServer Creation, Allocation and Shutdown Lifecycle [\#548](https://github.com/googleforgames/agones/pull/548) ([markmandel](https://github.com/markmandel))
- Changed kubeInformation to kubeInformer. [\#545](https://github.com/googleforgames/agones/pull/545) ([pooneh-m](https://github.com/pooneh-m))
- Changed kubeInformation to kubeInformer. [\#544](https://github.com/googleforgames/agones/pull/544) ([pooneh-m](https://github.com/pooneh-m))
- Speed up creation/deletion of game servers in a set [\#542](https://github.com/googleforgames/agones/pull/542) ([jkowalski](https://github.com/jkowalski))
- Adding tags to cloudbuilds [\#537](https://github.com/googleforgames/agones/pull/537) ([markmandel](https://github.com/markmandel))
- This is how you write shortcode in hugo [\#534](https://github.com/googleforgames/agones/pull/534) ([markmandel](https://github.com/markmandel))
- Add 2 new flags to control the Helm installation: [\#533](https://github.com/googleforgames/agones/pull/533) ([bbf](https://github.com/bbf))
- PortAllocator.Run\(\) is no longer blocking. [\#531](https://github.com/googleforgames/agones/pull/531) ([markmandel](https://github.com/markmandel))
- Move SDK local tooling into its own section [\#529](https://github.com/googleforgames/agones/pull/529) ([markmandel](https://github.com/markmandel))
- Put CI buiild logs in a public bucket. [\#524](https://github.com/googleforgames/agones/pull/524) ([markmandel](https://github.com/markmandel))
- fixed go\_build\_base\_path for LOCAL\_GO [\#523](https://github.com/googleforgames/agones/pull/523) ([jkowalski](https://github.com/jkowalski))
- Test using gcloud base for e2e works. [\#522](https://github.com/googleforgames/agones/pull/522) ([markmandel](https://github.com/markmandel))
- fixed gcloud-test-cluster setup problem caused by bad merge between \#500 and \#501 [\#520](https://github.com/googleforgames/agones/pull/520) ([jkowalski](https://github.com/jkowalski))
- Remove TOC from metrics page [\#519](https://github.com/googleforgames/agones/pull/519) ([markmandel](https://github.com/markmandel))
- Extend consul -try to 30m [\#518](https://github.com/googleforgames/agones/pull/518) ([markmandel](https://github.com/markmandel))
- fixes kind prometheus installation [\#517](https://github.com/googleforgames/agones/pull/517) ([cyriltovena](https://github.com/cyriltovena))
- Fix for flaky TestSDKSetAnnotation [\#516](https://github.com/googleforgames/agones/pull/516) ([markmandel](https://github.com/markmandel))
- minkube-setup-grafana =\> minikube-setup-grafana [\#515](https://github.com/googleforgames/agones/pull/515) ([markmandel](https://github.com/markmandel))
- Restructure cloudbuild.yaml [\#513](https://github.com/googleforgames/agones/pull/513) ([markmandel](https://github.com/markmandel))
- e2e: run cleanup before tests in addition to after [\#512](https://github.com/googleforgames/agones/pull/512) ([jkowalski](https://github.com/jkowalski))
- Prometheus installation docs tweak. [\#510](https://github.com/googleforgames/agones/pull/510) ([markmandel](https://github.com/markmandel))
- Add e2e test for updating gameserver configurations in fleet [\#508](https://github.com/googleforgames/agones/pull/508) ([Yingxin-Jiang](https://github.com/Yingxin-Jiang))
- Extend e2e lock to 30m [\#507](https://github.com/googleforgames/agones/pull/507) ([markmandel](https://github.com/markmandel))
- Speed up builds by using local go/zip instead of dockerized ones. [\#506](https://github.com/googleforgames/agones/pull/506) ([jkowalski](https://github.com/jkowalski))
- Fixes for flaky e2e tests. [\#504](https://github.com/googleforgames/agones/pull/504) ([markmandel](https://github.com/markmandel))
- Fix for Flaky TestControllerCreationMutationHandler [\#503](https://github.com/googleforgames/agones/pull/503) ([markmandel](https://github.com/markmandel))
- fixed e2e tests by using generated object names [\#502](https://github.com/googleforgames/agones/pull/502) ([jkowalski](https://github.com/jkowalski))
- added resource limits to gameserver.yaml and changed to generateName: [\#496](https://github.com/googleforgames/agones/pull/496) ([jkowalski](https://github.com/jkowalski))
- Remove reflect from controller. [\#488](https://github.com/googleforgames/agones/pull/488) ([markmandel](https://github.com/markmandel))
- specify resource limits on simple-udp/fleet.yaml [\#487](https://github.com/googleforgames/agones/pull/487) ([jkowalski](https://github.com/jkowalski))
- improve docker layers using COPY --chown [\#482](https://github.com/googleforgames/agones/pull/482) ([cyriltovena](https://github.com/cyriltovena))
- Update fleet\_spec.md [\#480](https://github.com/googleforgames/agones/pull/480) ([pm7h](https://github.com/pm7h))
- Post 0.7.0 changes [\#479](https://github.com/googleforgames/agones/pull/479) ([markmandel](https://github.com/markmandel))
- docs: added game server state diagram [\#475](https://github.com/googleforgames/agones/pull/475) ([jkowalski](https://github.com/jkowalski))
- fix autoscaler cleanup on tests failure [\#474](https://github.com/googleforgames/agones/pull/474) ([cyriltovena](https://github.com/cyriltovena))

## [v0.7.0](https://github.com/googleforgames/agones/tree/v0.7.0) (2019-01-08)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.7.0-rc...v0.7.0)

**Closed issues:**

- Release 0.7.0-rc [\#467](https://github.com/googleforgames/agones/issues/467)

**Merged pull requests:**

- Release 0.7.0 [\#478](https://github.com/googleforgames/agones/pull/478) ([markmandel](https://github.com/markmandel))
- Preparation for 0.7.0 [\#470](https://github.com/googleforgames/agones/pull/470) ([markmandel](https://github.com/markmandel))

## [v0.7.0-rc](https://github.com/googleforgames/agones/tree/v0.7.0-rc) (2019-01-02)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.6.0...v0.7.0-rc)

**Breaking changes:**

- Update to Kubernetes 1.11 [\#447](https://github.com/googleforgames/agones/pull/447) ([markmandel](https://github.com/markmandel))
- Remove crd-install hook, as it break CRD updates [\#441](https://github.com/googleforgames/agones/pull/441) ([markmandel](https://github.com/markmandel))

**Implemented enhancements:**

- Delete crds, and fleets, gameservers etc on deletion of Helm chart [\#426](https://github.com/googleforgames/agones/issues/426)
- `GameServers` should have the Fleet name in a label for easy retrieval [\#411](https://github.com/googleforgames/agones/issues/411)
- Horizontal Fleet Autoscaling [\#334](https://github.com/googleforgames/agones/issues/334)
- Add webhook functionality into FleetAutoscaler [\#460](https://github.com/googleforgames/agones/pull/460) ([aLekSer](https://github.com/aLekSer))
- Adds Kind local cluster support with documentation [\#458](https://github.com/googleforgames/agones/pull/458) ([cyriltovena](https://github.com/cyriltovena))
- Adds OpenCensus metrics integration. [\#457](https://github.com/googleforgames/agones/pull/457) ([cyriltovena](https://github.com/cyriltovena))
- added incremental build option to Makefile to speed up rebuilds [\#454](https://github.com/googleforgames/agones/pull/454) ([jkowalski](https://github.com/jkowalski))
- CRD: added additionalPrinterColumns to GameServer for kubectl [\#444](https://github.com/googleforgames/agones/pull/444) ([jkowalski](https://github.com/jkowalski))
- Adding explicit length of git revision in Makefile and E2E Can't Allocate test  [\#440](https://github.com/googleforgames/agones/pull/440) ([aLekSer](https://github.com/aLekSer))
- Pinger service for Multiple Cluster Latency Measurement. [\#434](https://github.com/googleforgames/agones/pull/434) ([markmandel](https://github.com/markmandel))

**Fixed bugs:**

- This should fail e2e in any command fails [\#462](https://github.com/googleforgames/agones/pull/462) ([markmandel](https://github.com/markmandel))
- Apply fix for goroutines leak [\#461](https://github.com/googleforgames/agones/pull/461) ([aLekSer](https://github.com/aLekSer))
- GameServerSets: DeleteFunc could receive a DeletedFinalStateUnknown [\#442](https://github.com/googleforgames/agones/pull/442) ([markmandel](https://github.com/markmandel))

**Security fixes:**

- \[Security\] Upgrade Go to 1.11.4 [\#446](https://github.com/googleforgames/agones/pull/446) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- Controller logging consistency  [\#456](https://github.com/googleforgames/agones/issues/456)
- Add Agones to helm hub [\#450](https://github.com/googleforgames/agones/issues/450)
- Add support for Kind cluster [\#448](https://github.com/googleforgames/agones/issues/448)
- Move SDK server code from pkg/gameservers to a separate package [\#445](https://github.com/googleforgames/agones/issues/445)
- Helm chart for 0.6.0 do not work on Helm v2.9.1 due crd-install hook [\#431](https://github.com/googleforgames/agones/issues/431)
- Release 0.6.0 [\#428](https://github.com/googleforgames/agones/issues/428)

**Merged pull requests:**

- Release 0.7.0-rc [\#468](https://github.com/googleforgames/agones/pull/468) ([markmandel](https://github.com/markmandel))
- Move the README.md into /agones/ so it's in the Helm Chart [\#466](https://github.com/googleforgames/agones/pull/466) ([markmandel](https://github.com/markmandel))
- Convert to using Fluentdformatter [\#463](https://github.com/googleforgames/agones/pull/463) ([markmandel](https://github.com/markmandel))
- Upgrade minikube to K8s 1.11 [\#459](https://github.com/googleforgames/agones/pull/459) ([markmandel](https://github.com/markmandel))
- pkg/sdkserver: added doc.go [\#452](https://github.com/googleforgames/agones/pull/452) ([jkowalski](https://github.com/jkowalski))
- Split pkg/gameservers into two  [\#451](https://github.com/googleforgames/agones/pull/451) ([jkowalski](https://github.com/jkowalski))
- Copy/paste fix [\#449](https://github.com/googleforgames/agones/pull/449) ([joeholley](https://github.com/joeholley))
- Delete crds, and fleets, gameservers etc on deletion of Helm chart [\#437](https://github.com/googleforgames/agones/pull/437) ([EricFortin](https://github.com/EricFortin))
- Update gRPC to v1.16.1 [\#435](https://github.com/googleforgames/agones/pull/435) ([markmandel](https://github.com/markmandel))
- adds minimun tiller version in chart and update doc [\#433](https://github.com/googleforgames/agones/pull/433) ([cyriltovena](https://github.com/cyriltovena))
- README: Autoscaler example link [\#432](https://github.com/googleforgames/agones/pull/432) ([markmandel](https://github.com/markmandel))
- Post 0.6.0 updates [\#430](https://github.com/googleforgames/agones/pull/430) ([markmandel](https://github.com/markmandel))
- add fleet name to gameservers labels [\#427](https://github.com/googleforgames/agones/pull/427) ([cyriltovena](https://github.com/cyriltovena))

## [v0.6.0](https://github.com/googleforgames/agones/tree/v0.6.0) (2018-11-28)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.6.0-rc...v0.6.0)

**Closed issues:**

- Release 0.6.0.rc [\#424](https://github.com/googleforgames/agones/issues/424)

**Merged pull requests:**

- Release 0.6.0 updates. [\#429](https://github.com/googleforgames/agones/pull/429) ([markmandel](https://github.com/markmandel))

## [v0.6.0-rc](https://github.com/googleforgames/agones/tree/v0.6.0-rc) (2018-11-21)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.5.0...v0.6.0-rc)

**Implemented enhancements:**

- Using the Cluster Autoscaler with Agones [\#368](https://github.com/googleforgames/agones/issues/368)
- Agones sdk-server sidecar should have cpu and memory limits [\#344](https://github.com/googleforgames/agones/issues/344)
- As developer, I want to emulate an allocation in local mode [\#314](https://github.com/googleforgames/agones/issues/314)
- Document how to configure maximum number of pods/node that can be allocated [\#295](https://github.com/googleforgames/agones/issues/295)
- Development tools to enable pprof [\#422](https://github.com/googleforgames/agones/pull/422) ([markmandel](https://github.com/markmandel))
- Changes to the GameServer configuration are reflected in the local sdk server [\#413](https://github.com/googleforgames/agones/pull/413) ([markmandel](https://github.com/markmandel))
- Mark GameServer Unhealthy if allocated HostPort isn't available [\#408](https://github.com/googleforgames/agones/pull/408) ([markmandel](https://github.com/markmandel))
- Cluster Autoscaling: safe-to-evict=false annotations for GameServer Pods [\#405](https://github.com/googleforgames/agones/pull/405) ([markmandel](https://github.com/markmandel))
- Packed: Fleet scaled down removes GameServers from least used Nodes [\#401](https://github.com/googleforgames/agones/pull/401) ([markmandel](https://github.com/markmandel))
- Packed: PreferredDuringSchedulingIgnoredDuringExecution PodAffinity with a HostName topology [\#397](https://github.com/googleforgames/agones/pull/397) ([markmandel](https://github.com/markmandel))
- Specify CPU Request for the SDK Server Sidecar [\#390](https://github.com/googleforgames/agones/pull/390) ([markmandel](https://github.com/markmandel))
- Mount point for helm config [\#383](https://github.com/googleforgames/agones/pull/383) ([markmandel](https://github.com/markmandel))
- Add crd-install helm hook to crds templates [\#375](https://github.com/googleforgames/agones/pull/375) ([smoya](https://github.com/smoya))
- Prioritise Allocation from Nodes with Allocated/Ready GameServers [\#370](https://github.com/googleforgames/agones/pull/370) ([markmandel](https://github.com/markmandel))

**Fixed bugs:**

- Admission webhook "mutations.stable.agones.dev" errors with Invalid FleetAutoscaler [\#406](https://github.com/googleforgames/agones/issues/406)
- Ports should always be allocated to a GameServer [\#415](https://github.com/googleforgames/agones/pull/415) ([markmandel](https://github.com/markmandel))
- Apparently patching events is a thing. [\#402](https://github.com/googleforgames/agones/pull/402) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- Release 0.5.0 [\#387](https://github.com/googleforgames/agones/issues/387)

**Merged pull requests:**

- Release 0.6.0-rc [\#425](https://github.com/googleforgames/agones/pull/425) ([markmandel](https://github.com/markmandel))
- More stringent linting rules \(and update linter\) [\#417](https://github.com/googleforgames/agones/pull/417) ([markmandel](https://github.com/markmandel))
- FleetAutoscaler can be targeted at Non Existent Fleets [\#416](https://github.com/googleforgames/agones/pull/416) ([markmandel](https://github.com/markmandel))
- Adding colour to the linter, because colours are pretty. [\#400](https://github.com/googleforgames/agones/pull/400) ([markmandel](https://github.com/markmandel))
- Process to become an reviewer/approver on Agones. [\#399](https://github.com/googleforgames/agones/pull/399) ([markmandel](https://github.com/markmandel))
- Update Helm to 2.11.0 [\#396](https://github.com/googleforgames/agones/pull/396) ([markmandel](https://github.com/markmandel))
- Make sure do-release always uses the release\_registry [\#394](https://github.com/googleforgames/agones/pull/394) ([markmandel](https://github.com/markmandel))
- Adding third part videos and presentations. [\#393](https://github.com/googleforgames/agones/pull/393) ([markmandel](https://github.com/markmandel))
- TOC for the SDK integration and tooling [\#392](https://github.com/googleforgames/agones/pull/392) ([markmandel](https://github.com/markmandel))
- Set test clusters to base version. GKE will work out the rest. [\#391](https://github.com/googleforgames/agones/pull/391) ([markmandel](https://github.com/markmandel))
- Post 0.5.0 Updates [\#389](https://github.com/googleforgames/agones/pull/389) ([markmandel](https://github.com/markmandel))
- Update to Go 1.11.1 [\#385](https://github.com/googleforgames/agones/pull/385) ([markmandel](https://github.com/markmandel))

## [v0.5.0](https://github.com/googleforgames/agones/tree/v0.5.0) (2018-10-16)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.5.0-rc...v0.5.0)

**Fixed bugs:**

- Tutorial fails @ Step 5 due to RBAC issues if you have capital letters in your gcloud account name [\#282](https://github.com/googleforgames/agones/issues/282)

**Closed issues:**

- Release 0.5.0.rc [\#378](https://github.com/googleforgames/agones/issues/378)

**Merged pull requests:**

- Change for the 0.5.0 release. [\#388](https://github.com/googleforgames/agones/pull/388) ([markmandel](https://github.com/markmandel))
- Troubleshooting guide for issues with Agones. [\#384](https://github.com/googleforgames/agones/pull/384) ([markmandel](https://github.com/markmandel))
- Spec docs for FleetAutoscaler [\#381](https://github.com/googleforgames/agones/pull/381) ([markmandel](https://github.com/markmandel))
- Post 0.5.0-rc updates [\#380](https://github.com/googleforgames/agones/pull/380) ([markmandel](https://github.com/markmandel))

## [v0.5.0-rc](https://github.com/googleforgames/agones/tree/v0.5.0-rc) (2018-10-09)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.4.0...v0.5.0-rc)

**Implemented enhancements:**

- Improve support for developing in custom environments [\#348](https://github.com/googleforgames/agones/issues/348)
- Agones helm repo [\#285](https://github.com/googleforgames/agones/issues/285)
- Add Amazon EKS Agones Setup Instructions [\#372](https://github.com/googleforgames/agones/pull/372) ([GabeBigBoxVR](https://github.com/GabeBigBoxVR))
- Agones stable helm repository [\#361](https://github.com/googleforgames/agones/pull/361) ([cyriltovena](https://github.com/cyriltovena))
- Improve support for custom dev environments [\#349](https://github.com/googleforgames/agones/pull/349) ([victor-prodan](https://github.com/victor-prodan))
- FleetAutoScaler v0 [\#340](https://github.com/googleforgames/agones/pull/340) ([victor-prodan](https://github.com/victor-prodan))
- Forces restart when using tls generation. [\#338](https://github.com/googleforgames/agones/pull/338) ([cyriltovena](https://github.com/cyriltovena))

**Fixed bugs:**

- Fix loophole in game server initialization [\#354](https://github.com/googleforgames/agones/issues/354)
- Health messages logged with wrong severity [\#335](https://github.com/googleforgames/agones/issues/335)
- Helm upgrade and SSL certificates [\#309](https://github.com/googleforgames/agones/issues/309)
- Fix for race condition: Allocation of Deleting GameServers Possible [\#367](https://github.com/googleforgames/agones/pull/367) ([markmandel](https://github.com/markmandel))
- Map level to severity for stackdriver [\#363](https://github.com/googleforgames/agones/pull/363) ([cyriltovena](https://github.com/cyriltovena))
- Add ReadTimeout for e2e tests, otherwise this can hang forever. [\#359](https://github.com/googleforgames/agones/pull/359) ([markmandel](https://github.com/markmandel))
- Fixes race condition bug with Pod not being scheduled before Ready\(\) [\#357](https://github.com/googleforgames/agones/pull/357) ([markmandel](https://github.com/markmandel))
- Allocation is broken when using the generated go client [\#347](https://github.com/googleforgames/agones/pull/347) ([markmandel](https://github.com/markmandel))

**Security fixes:**

- \[Vuln\] Update to Alpine 3.8.1 [\#355](https://github.com/googleforgames/agones/issues/355)
- Update Alpine version to 3.8.1 [\#364](https://github.com/googleforgames/agones/pull/364) ([fooock](https://github.com/fooock))

**Closed issues:**

- C++ SDK no destructor body [\#366](https://github.com/googleforgames/agones/issues/366)
- Release 0.4.0 [\#341](https://github.com/googleforgames/agones/issues/341)
- Update "Developing, Testing and Building Agones" tutorial with how to push updates to your test cluster [\#308](https://github.com/googleforgames/agones/issues/308)
- Use revive instead of gometalinter [\#237](https://github.com/googleforgames/agones/issues/237)
- Integrate a spell and/or grammar check into build system [\#187](https://github.com/googleforgames/agones/issues/187)
- Helm package CI [\#153](https://github.com/googleforgames/agones/issues/153)
- Use functional parameters in Controller creation [\#104](https://github.com/googleforgames/agones/issues/104)

**Merged pull requests:**

- Release 0.5.0.rc changes [\#379](https://github.com/googleforgames/agones/pull/379) ([markmandel](https://github.com/markmandel))
- Make WaitForFleetCondition take up to 5 minutes [\#377](https://github.com/googleforgames/agones/pull/377) ([markmandel](https://github.com/markmandel))
- Fix for flaky test TestControllerAddress [\#376](https://github.com/googleforgames/agones/pull/376) ([markmandel](https://github.com/markmandel))
- Fix typo [\#374](https://github.com/googleforgames/agones/pull/374) ([Maxpain177](https://github.com/Maxpain177))
- Update instructions for Minikube 0.29.0 [\#373](https://github.com/googleforgames/agones/pull/373) ([markmandel](https://github.com/markmandel))
- Update README.md [\#371](https://github.com/googleforgames/agones/pull/371) ([iamrare](https://github.com/iamrare))
- Remove c++ sdk destructor causing linker errors [\#369](https://github.com/googleforgames/agones/pull/369) ([nikibobi](https://github.com/nikibobi))
- Update README.md [\#362](https://github.com/googleforgames/agones/pull/362) ([iamrare](https://github.com/iamrare))
- Upgrade GKE version and increase test cluster size [\#360](https://github.com/googleforgames/agones/pull/360) ([markmandel](https://github.com/markmandel))
- Fix typo in sdk readme which said only two sdks [\#356](https://github.com/googleforgames/agones/pull/356) ([ReDucTor](https://github.com/ReDucTor))
- Add allocator service example and documentation [\#353](https://github.com/googleforgames/agones/pull/353) ([slartibaartfast](https://github.com/slartibaartfast))
- Adding goimports back into the build shell. [\#352](https://github.com/googleforgames/agones/pull/352) ([markmandel](https://github.com/markmandel))
- e2e tests for Fleet Scaling and Updates [\#351](https://github.com/googleforgames/agones/pull/351) ([markmandel](https://github.com/markmandel))
- Switch to golangci-lint [\#346](https://github.com/googleforgames/agones/pull/346) ([cyriltovena](https://github.com/cyriltovena))
- Prepare for next release - 0.5.0.rc [\#343](https://github.com/googleforgames/agones/pull/343) ([markmandel](https://github.com/markmandel))

## [v0.4.0](https://github.com/googleforgames/agones/tree/v0.4.0) (2018-09-04)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.4.0.rc...v0.4.0)

**Closed issues:**

- Release 0.4.0.rc [\#330](https://github.com/googleforgames/agones/issues/330)

**Merged pull requests:**

- Release 0.4.0 [\#342](https://github.com/googleforgames/agones/pull/342) ([markmandel](https://github.com/markmandel))
- Fix yaml file paths [\#339](https://github.com/googleforgames/agones/pull/339) ([oskoi](https://github.com/oskoi))
- Add Troubleshooting section to Build doc [\#337](https://github.com/googleforgames/agones/pull/337) ([victor-prodan](https://github.com/victor-prodan))
- Preparing for 0.4.0 release next week. [\#333](https://github.com/googleforgames/agones/pull/333) ([markmandel](https://github.com/markmandel))

## [v0.4.0.rc](https://github.com/googleforgames/agones/tree/v0.4.0.rc) (2018-08-28)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.3.0...v0.4.0.rc)

**Implemented enhancements:**

- When running the SDK sidecar in local mode, be able to specify the backing `GameServer` configuration [\#296](https://github.com/googleforgames/agones/issues/296)
- Move Status \> Address & Status \> Ports population to `Creating` state processing [\#293](https://github.com/googleforgames/agones/issues/293)
- Propagating game server process events to Agones system [\#279](https://github.com/googleforgames/agones/issues/279)
- Session data propagation to dedicated server [\#277](https://github.com/googleforgames/agones/issues/277)
- Ability to pass `GameServer` yaml/json to local sdk server [\#328](https://github.com/googleforgames/agones/pull/328) ([markmandel](https://github.com/markmandel))
- Move Status \> Address & Ports population to `Creating` state processing [\#326](https://github.com/googleforgames/agones/pull/326) ([markmandel](https://github.com/markmandel))
- Implement SDK SetLabel and SetAnnotation functionality [\#323](https://github.com/googleforgames/agones/pull/323) ([markmandel](https://github.com/markmandel))
- Implements SDK callback for GameServer updates [\#316](https://github.com/googleforgames/agones/pull/316) ([markmandel](https://github.com/markmandel))
- Features/e2e [\#315](https://github.com/googleforgames/agones/pull/315) ([cyriltovena](https://github.com/cyriltovena))
- Metadata propagation from fleet allocation to game server [\#312](https://github.com/googleforgames/agones/pull/312) ([victor-prodan](https://github.com/victor-prodan))

**Fixed bugs:**

- Fleet allocation request could not find fleet [\#324](https://github.com/googleforgames/agones/issues/324)
- Hotfix: Ensure multiple Pods don't get created for a GameServer [\#332](https://github.com/googleforgames/agones/pull/332) ([markmandel](https://github.com/markmandel))
- Fleet Allocation via REST was failing [\#325](https://github.com/googleforgames/agones/pull/325) ([markmandel](https://github.com/markmandel))
- Make sure the test-e2e ensures the build image. [\#322](https://github.com/googleforgames/agones/pull/322) ([markmandel](https://github.com/markmandel))
- Update getting started guides with kubectl custom columns [\#319](https://github.com/googleforgames/agones/pull/319) ([markmandel](https://github.com/markmandel))
- Fix bug: Disabled health checking not implemented [\#317](https://github.com/googleforgames/agones/pull/317) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- Release 0.3.0 [\#304](https://github.com/googleforgames/agones/issues/304)
- Change container builder steps to run concurrently [\#186](https://github.com/googleforgames/agones/issues/186)
- Move Deployment in install script out of v1beta1 [\#173](https://github.com/googleforgames/agones/issues/173)
- YAML packaging [\#101](https://github.com/googleforgames/agones/issues/101)

**Merged pull requests:**

- Changelog, and documentation changes for 0.4.0.rc [\#331](https://github.com/googleforgames/agones/pull/331) ([markmandel](https://github.com/markmandel))
- Added github.com/spf13/viper to dep toml [\#327](https://github.com/googleforgames/agones/pull/327) ([markmandel](https://github.com/markmandel))
- Add Minikube instructions [\#321](https://github.com/googleforgames/agones/pull/321) ([slartibaartfast](https://github.com/slartibaartfast))
- Convert Go example into multi-stage Docker build [\#320](https://github.com/googleforgames/agones/pull/320) ([markmandel](https://github.com/markmandel))
- Removal of the legacy port configuration [\#318](https://github.com/googleforgames/agones/pull/318) ([markmandel](https://github.com/markmandel))
- Fix flakiness with TestSidecarHTTPHealthCheck [\#313](https://github.com/googleforgames/agones/pull/313) ([markmandel](https://github.com/markmandel))
- Move linting into it's own serial step [\#311](https://github.com/googleforgames/agones/pull/311) ([markmandel](https://github.com/markmandel))
- Update to move from release to the next version \(0.4.0.rc\) [\#306](https://github.com/googleforgames/agones/pull/306) ([markmandel](https://github.com/markmandel))

## [v0.3.0](https://github.com/googleforgames/agones/tree/v0.3.0) (2018-07-26)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.3.0.rc...v0.3.0)

**Fixed bugs:**

- Missing `watch` permission in rbac for agones-sdk [\#300](https://github.com/googleforgames/agones/pull/300) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- Release 0.3.0.rc [\#290](https://github.com/googleforgames/agones/issues/290)

**Merged pull requests:**

- Changes for release  0.3.0 [\#305](https://github.com/googleforgames/agones/pull/305) ([markmandel](https://github.com/markmandel))
- Move back to 0.3.0 [\#292](https://github.com/googleforgames/agones/pull/292) ([markmandel](https://github.com/markmandel))

## [v0.3.0.rc](https://github.com/googleforgames/agones/tree/v0.3.0.rc) (2018-07-17)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.2.0...v0.3.0.rc)

**Breaking changes:**

- \[Breaking Change\] Multiple port support for `GameServer` [\#283](https://github.com/googleforgames/agones/pull/283) ([markmandel](https://github.com/markmandel))

**Implemented enhancements:**

- Expose SDK Sidecar GRPC Server as HTTP+JSON [\#240](https://github.com/googleforgames/agones/issues/240)
- supporting multiple ports [\#151](https://github.com/googleforgames/agones/issues/151)
- Support Cluster Node addition/deletion [\#60](https://github.com/googleforgames/agones/issues/60)
- SDK `GameServer\(\)` function for retrieving backing GameServer configuration [\#288](https://github.com/googleforgames/agones/pull/288) ([markmandel](https://github.com/markmandel))
- Move cluster node addition/removal out of "experimental" [\#271](https://github.com/googleforgames/agones/pull/271) ([markmandel](https://github.com/markmandel))
- added information about Agones running on Azure Kubernetes Service [\#269](https://github.com/googleforgames/agones/pull/269) ([dgkanatsios](https://github.com/dgkanatsios))
- Expose SDK-Server at HTTP+JSON [\#265](https://github.com/googleforgames/agones/pull/265) ([markmandel](https://github.com/markmandel))
- Support Rust SDK by gRPC-rs [\#230](https://github.com/googleforgames/agones/pull/230) ([thara](https://github.com/thara))

**Fixed bugs:**

- Minikube does not start with 0.26.x [\#192](https://github.com/googleforgames/agones/issues/192)
- Forgot to update the k8s client-go codegen. [\#281](https://github.com/googleforgames/agones/pull/281) ([markmandel](https://github.com/markmandel))
- Fix bug with hung GameServer resource on Kubernetes 1.10 [\#278](https://github.com/googleforgames/agones/pull/278) ([markmandel](https://github.com/markmandel))
- Fix Xonotic example race condition [\#266](https://github.com/googleforgames/agones/pull/266) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- Agones on Azure AKS [\#254](https://github.com/googleforgames/agones/issues/254)
- Release v0.2.0 [\#242](https://github.com/googleforgames/agones/issues/242)
- helm namespace [\#212](https://github.com/googleforgames/agones/issues/212)

**Merged pull requests:**

- Release 0.3.0.rc [\#291](https://github.com/googleforgames/agones/pull/291) ([markmandel](https://github.com/markmandel))
- Update README.md with information about Public IPs on AKS [\#289](https://github.com/googleforgames/agones/pull/289) ([dgkanatsios](https://github.com/dgkanatsios))
- fix yaml install link [\#286](https://github.com/googleforgames/agones/pull/286) ([nikibobi](https://github.com/nikibobi))
- install.yaml now installs by default in agones-system [\#284](https://github.com/googleforgames/agones/pull/284) ([cyriltovena](https://github.com/cyriltovena))
- Update GKE testing cluster to 1.10.5 [\#280](https://github.com/googleforgames/agones/pull/280) ([markmandel](https://github.com/markmandel))
- Update dependencies to support K8s 1.10.x [\#276](https://github.com/googleforgames/agones/pull/276) ([markmandel](https://github.com/markmandel))
- Remove line [\#274](https://github.com/googleforgames/agones/pull/274) ([markmandel](https://github.com/markmandel))
- Update minikube instructions to 0.28.0 [\#273](https://github.com/googleforgames/agones/pull/273) ([markmandel](https://github.com/markmandel))
- Added list of various libs used in code [\#272](https://github.com/googleforgames/agones/pull/272) ([meanmango](https://github.com/meanmango))
- More Docker and Kubernetes Getting Started Resources [\#270](https://github.com/googleforgames/agones/pull/270) ([markmandel](https://github.com/markmandel))
- Fixing Flaky test TestControllerSyncFleet [\#268](https://github.com/googleforgames/agones/pull/268) ([markmandel](https://github.com/markmandel))
- Update Helm App Version [\#267](https://github.com/googleforgames/agones/pull/267) ([markmandel](https://github.com/markmandel))
- Give linter 15 minutes. [\#264](https://github.com/googleforgames/agones/pull/264) ([markmandel](https://github.com/markmandel))
- Upgrade to Go 1.10.3 [\#263](https://github.com/googleforgames/agones/pull/263) ([markmandel](https://github.com/markmandel))
- Upgrade Helm for build tools [\#262](https://github.com/googleforgames/agones/pull/262) ([markmandel](https://github.com/markmandel))
- Fixed some links & typos [\#261](https://github.com/googleforgames/agones/pull/261) ([meanmango](https://github.com/meanmango))
- Flaky test fix: TestWorkQueueHealthCheck [\#260](https://github.com/googleforgames/agones/pull/260) ([markmandel](https://github.com/markmandel))
- Upgrade gRPC to 1.12.0 [\#259](https://github.com/googleforgames/agones/pull/259) ([markmandel](https://github.com/markmandel))
- Flakey test fix: TestControllerUpdateFleetStatus [\#257](https://github.com/googleforgames/agones/pull/257) ([markmandel](https://github.com/markmandel))
- Remove reference to internal console site. [\#256](https://github.com/googleforgames/agones/pull/256) ([dzlier-gcp](https://github.com/dzlier-gcp))
- Add Licences to Rust SDK & Examples [\#253](https://github.com/googleforgames/agones/pull/253) ([markmandel](https://github.com/markmandel))
- Clearer Helm installation instructions [\#252](https://github.com/googleforgames/agones/pull/252) ([markmandel](https://github.com/markmandel))
- Rust SDK Doc additions [\#251](https://github.com/googleforgames/agones/pull/251) ([markmandel](https://github.com/markmandel))
- use the helm --namespace convention  [\#250](https://github.com/googleforgames/agones/pull/250) ([cyriltovena](https://github.com/cyriltovena))
- fix podspec template broken link to documentation [\#247](https://github.com/googleforgames/agones/pull/247) ([cyriltovena](https://github.com/cyriltovena))
- Make Cloud Builder Faster [\#245](https://github.com/googleforgames/agones/pull/245) ([markmandel](https://github.com/markmandel))
- Increment base version [\#244](https://github.com/googleforgames/agones/pull/244) ([markmandel](https://github.com/markmandel))
- Lock protoc-gen-go to 1.0 release [\#241](https://github.com/googleforgames/agones/pull/241) ([markmandel](https://github.com/markmandel))

## [v0.2.0](https://github.com/googleforgames/agones/tree/v0.2.0) (2018-06-06)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.2.0.rc...v0.2.0)

**Closed issues:**

- Release v0.2.0.rc [\#231](https://github.com/googleforgames/agones/issues/231)

**Merged pull requests:**

- Release 0.2.0 [\#243](https://github.com/googleforgames/agones/pull/243) ([markmandel](https://github.com/markmandel))
- Adding my streaming development to contributing [\#239](https://github.com/googleforgames/agones/pull/239) ([markmandel](https://github.com/markmandel))
- Updates to release process [\#235](https://github.com/googleforgames/agones/pull/235) ([markmandel](https://github.com/markmandel))
- Adding a README.md file for the simple-udp to help developer to get start [\#234](https://github.com/googleforgames/agones/pull/234) ([g-ericso](https://github.com/g-ericso))
- Revert install configuration back to 0.2.0 [\#233](https://github.com/googleforgames/agones/pull/233) ([markmandel](https://github.com/markmandel))

## [v0.2.0.rc](https://github.com/googleforgames/agones/tree/v0.2.0.rc) (2018-05-30)

[Full Changelog](https://github.com/googleforgames/agones/compare/v0.1...v0.2.0.rc)

**Implemented enhancements:**

- Generate Certs for Mutation/Validatiion Webhooks [\#169](https://github.com/googleforgames/agones/issues/169)
- Add liveness check to `pkg/gameservers/controller`. [\#116](https://github.com/googleforgames/agones/issues/116)
- GameServer Fleets [\#70](https://github.com/googleforgames/agones/issues/70)
- Release steps of archiving installation resources and documentation [\#226](https://github.com/googleforgames/agones/pull/226) ([markmandel](https://github.com/markmandel))
- Lint timeout increase, and make configurable [\#221](https://github.com/googleforgames/agones/pull/221) ([markmandel](https://github.com/markmandel))
- add the ability to turn off RBAC in helm and customize gcp test-cluster [\#220](https://github.com/googleforgames/agones/pull/220) ([cyriltovena](https://github.com/cyriltovena))
- Target for generating a CHANGELOG from GitHub Milestones. [\#217](https://github.com/googleforgames/agones/pull/217) ([markmandel](https://github.com/markmandel))
- Generate Certs for Mutation/Validatiion Webhooks [\#214](https://github.com/googleforgames/agones/pull/214) ([cyriltovena](https://github.com/cyriltovena))
- Rolling updates for Fleets [\#213](https://github.com/googleforgames/agones/pull/213) ([markmandel](https://github.com/markmandel))
- helm namespaces [\#210](https://github.com/googleforgames/agones/pull/210) ([cyriltovena](https://github.com/cyriltovena))
- Fleet update strategy: Replace [\#199](https://github.com/googleforgames/agones/pull/199) ([markmandel](https://github.com/markmandel))
- Status \> AllocatedReplicas on Fleets & GameServers [\#196](https://github.com/googleforgames/agones/pull/196) ([markmandel](https://github.com/markmandel))
- Creating a FleetAllocation allocated a GameServer from a Fleet [\#193](https://github.com/googleforgames/agones/pull/193) ([markmandel](https://github.com/markmandel))
- Add nano as editor to the build image [\#179](https://github.com/googleforgames/agones/pull/179) ([markmandel](https://github.com/markmandel))
- Feature/gometalinter [\#176](https://github.com/googleforgames/agones/pull/176) ([EricFortin](https://github.com/EricFortin))
- Creating a Fleet creates a GameServerSet [\#174](https://github.com/googleforgames/agones/pull/174) ([markmandel](https://github.com/markmandel))
- Register liveness check in gameservers.Controller [\#160](https://github.com/googleforgames/agones/pull/160) ([enocom](https://github.com/enocom))
- GameServerSet Implementation [\#156](https://github.com/googleforgames/agones/pull/156) ([markmandel](https://github.com/markmandel))

**Fixed bugs:**

- gometalinter fails [\#181](https://github.com/googleforgames/agones/issues/181)
- Line endings in Windows make the project can't be compiled [\#180](https://github.com/googleforgames/agones/issues/180)
- Missing links in documentation [\#165](https://github.com/googleforgames/agones/issues/165)
- Cannot run GameServer in non-default namespace [\#146](https://github.com/googleforgames/agones/issues/146)
- Don't allow allocation of Deleted GameServers [\#198](https://github.com/googleforgames/agones/pull/198) ([markmandel](https://github.com/markmandel))
- Fixes for GKE issues with install/quickstart [\#197](https://github.com/googleforgames/agones/pull/197) ([markmandel](https://github.com/markmandel))
- `minikube-test-cluster` needed the `ensure-build-image` dependency [\#194](https://github.com/googleforgames/agones/pull/194) ([markmandel](https://github.com/markmandel))
- Update initialClusterVersion to 1.9.6.gke.1 [\#190](https://github.com/googleforgames/agones/pull/190) ([markmandel](https://github.com/markmandel))
- Point the install.yaml to the release-0.1 branch [\#189](https://github.com/googleforgames/agones/pull/189) ([markmandel](https://github.com/markmandel))
- Fixed missing links in documentation. [\#166](https://github.com/googleforgames/agones/pull/166) ([fooock](https://github.com/fooock))

**Security fixes:**

- RBAC: controller doesn't need fleet create [\#202](https://github.com/googleforgames/agones/pull/202) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- helm RBAC on/off [\#211](https://github.com/googleforgames/agones/issues/211)
- Release cycle [\#203](https://github.com/googleforgames/agones/issues/203)
- Fix cyclomatic complexity in examples/simple-udp/server/main.go [\#178](https://github.com/googleforgames/agones/issues/178)
- Fix cyclomatic complexity in cmd/controller/main.go [\#177](https://github.com/googleforgames/agones/issues/177)
- Add .helmignore to Helm chart [\#168](https://github.com/googleforgames/agones/issues/168)
- Add gometalinter to build [\#163](https://github.com/googleforgames/agones/issues/163)
- Google Bot is double posting [\#155](https://github.com/googleforgames/agones/issues/155)
- Add .editorconfig to ensure common formatting [\#97](https://github.com/googleforgames/agones/issues/97)

**Merged pull requests:**

- Release v0.2.0.rc [\#232](https://github.com/googleforgames/agones/pull/232) ([markmandel](https://github.com/markmandel))
- do-release release registry and upstream push [\#228](https://github.com/googleforgames/agones/pull/228) ([markmandel](https://github.com/markmandel))
- Archive C++ src on build and release [\#227](https://github.com/googleforgames/agones/pull/227) ([markmandel](https://github.com/markmandel))
- Update installing\_agones.md [\#225](https://github.com/googleforgames/agones/pull/225) ([g-ericso](https://github.com/g-ericso))
- Some missing tasks in the release [\#224](https://github.com/googleforgames/agones/pull/224) ([markmandel](https://github.com/markmandel))
- Move to proper semver [\#223](https://github.com/googleforgames/agones/pull/223) ([markmandel](https://github.com/markmandel))
- Update tools - vetshadow is more aggressive [\#222](https://github.com/googleforgames/agones/pull/222) ([markmandel](https://github.com/markmandel))
- add helm ignore file [\#219](https://github.com/googleforgames/agones/pull/219) ([cyriltovena](https://github.com/cyriltovena))
- Intercept Xonotic stdout for SDK Integration [\#218](https://github.com/googleforgames/agones/pull/218) ([markmandel](https://github.com/markmandel))
- Some more Extending Kubernetes resources [\#216](https://github.com/googleforgames/agones/pull/216) ([markmandel](https://github.com/markmandel))
- Release process documentation [\#215](https://github.com/googleforgames/agones/pull/215) ([markmandel](https://github.com/markmandel))
- Fix cyclomatic complexity in cmd/controller/main.go [\#209](https://github.com/googleforgames/agones/pull/209) ([enocom](https://github.com/enocom))
- Testing functions for resource events [\#208](https://github.com/googleforgames/agones/pull/208) ([markmandel](https://github.com/markmandel))
- Shrink main func to resolve gocyclo warning [\#207](https://github.com/googleforgames/agones/pull/207) ([enocom](https://github.com/enocom))
- Clearer docs on developing and building from source [\#206](https://github.com/googleforgames/agones/pull/206) ([markmandel](https://github.com/markmandel))
- Add formatting guidelines to CONTRIBUTING.md [\#205](https://github.com/googleforgames/agones/pull/205) ([enocom](https://github.com/enocom))
- Fleet docs: Some missing pieces. [\#204](https://github.com/googleforgames/agones/pull/204) ([markmandel](https://github.com/markmandel))
- Release version, and twitter badges. [\#201](https://github.com/googleforgames/agones/pull/201) ([markmandel](https://github.com/markmandel))
- Typo in GameServer json [\#200](https://github.com/googleforgames/agones/pull/200) ([markmandel](https://github.com/markmandel))
- Install docs: minikube 0.25.2 and k8s 1.9.4 [\#195](https://github.com/googleforgames/agones/pull/195) ([markmandel](https://github.com/markmandel))
- Update temporary auth against Google Container Registry [\#191](https://github.com/googleforgames/agones/pull/191) ([markmandel](https://github.com/markmandel))
- Make the development release warning more visible. [\#188](https://github.com/googleforgames/agones/pull/188) ([markmandel](https://github.com/markmandel))
- Solve rare flakiness on TestWorkerQueueHealthy [\#185](https://github.com/googleforgames/agones/pull/185) ([markmandel](https://github.com/markmandel))
- Adding additional resources for CRDs and Controllers [\#184](https://github.com/googleforgames/agones/pull/184) ([markmandel](https://github.com/markmandel))
- Reworked some Dockerfiles to improve cache usage. [\#183](https://github.com/googleforgames/agones/pull/183) ([EricFortin](https://github.com/EricFortin))
- Windows eol [\#182](https://github.com/googleforgames/agones/pull/182) ([fooock](https://github.com/fooock))
- Missed a couple of small things in last PR [\#175](https://github.com/googleforgames/agones/pull/175) ([markmandel](https://github.com/markmandel))
- Centralise utilities for testing controllers [\#172](https://github.com/googleforgames/agones/pull/172) ([markmandel](https://github.com/markmandel))
- Generate the install.yaml from `helm template` [\#171](https://github.com/googleforgames/agones/pull/171) ([markmandel](https://github.com/markmandel))
- Integrated Helm into the `build` and development system [\#170](https://github.com/googleforgames/agones/pull/170) ([markmandel](https://github.com/markmandel))
- Refactor of workerqueue health testing [\#164](https://github.com/googleforgames/agones/pull/164) ([markmandel](https://github.com/markmandel))
- Fix some Go Report Card warnings [\#162](https://github.com/googleforgames/agones/pull/162) ([dvrkps](https://github.com/dvrkps))
- fix typo found by report card [\#161](https://github.com/googleforgames/agones/pull/161) ([cyriltovena](https://github.com/cyriltovena))
- Why does this project exist? [\#159](https://github.com/googleforgames/agones/pull/159) ([markmandel](https://github.com/markmandel))
- Add GKE Comic to explain Kubernetes to newcomers [\#158](https://github.com/googleforgames/agones/pull/158) ([markmandel](https://github.com/markmandel))
- Adding a Go Report Card [\#157](https://github.com/googleforgames/agones/pull/157) ([markmandel](https://github.com/markmandel))
- Documentation on the CI build system. [\#152](https://github.com/googleforgames/agones/pull/152) ([markmandel](https://github.com/markmandel))
- Helm integration [\#149](https://github.com/googleforgames/agones/pull/149) ([fooock](https://github.com/fooock))
- Minor rewording [\#148](https://github.com/googleforgames/agones/pull/148) ([bransorem](https://github.com/bransorem))
- Move GameServer validation to a ValidatingAdmissionWebhook [\#147](https://github.com/googleforgames/agones/pull/147) ([markmandel](https://github.com/markmandel))
- Update create\_gameserver.md [\#143](https://github.com/googleforgames/agones/pull/143) ([royingantaginting](https://github.com/royingantaginting))
- Fixed spelling issues in gameserver\_spec.md [\#141](https://github.com/googleforgames/agones/pull/141) ([mattva01](https://github.com/mattva01))
- Handle stop signal in the SDK Server [\#140](https://github.com/googleforgames/agones/pull/140) ([markmandel](https://github.com/markmandel))
- go vet: 3 warnings, 2 of them are easy. [\#139](https://github.com/googleforgames/agones/pull/139) ([Deleplace](https://github.com/Deleplace))
- Update Go version to 1.10 [\#137](https://github.com/googleforgames/agones/pull/137) ([markmandel](https://github.com/markmandel))
- Cleanup of grpc go generation code [\#136](https://github.com/googleforgames/agones/pull/136) ([markmandel](https://github.com/markmandel))
- Update base version to 0.2 [\#133](https://github.com/googleforgames/agones/pull/133) ([markmandel](https://github.com/markmandel))
- Centralise the canonical import paths and more package docs [\#130](https://github.com/googleforgames/agones/pull/130) ([markmandel](https://github.com/markmandel))

## [v0.1](https://github.com/googleforgames/agones/tree/v0.1) (2018-03-06)

[Full Changelog](https://github.com/googleforgames/agones/compare/20f6ab798a49e3629d5f6651201504ff49ea251a...v0.1)

**Implemented enhancements:**

- The local mode of the agon sidecar listen to localhost only [\#62](https://github.com/googleforgames/agones/issues/62)
- Record Events for GameServer State Changes [\#32](https://github.com/googleforgames/agones/issues/32)
- Use a single install.yaml to install Agon [\#17](https://github.com/googleforgames/agones/issues/17)
- SDK + Sidecar implementation [\#16](https://github.com/googleforgames/agones/issues/16)
- Game Server health checking [\#15](https://github.com/googleforgames/agones/issues/15)
- Dynamic Port Allocation on Game Servers [\#14](https://github.com/googleforgames/agones/issues/14)
- Sidecar needs a healthcheck [\#12](https://github.com/googleforgames/agones/issues/12)
- Health Check for the Controller [\#11](https://github.com/googleforgames/agones/issues/11)
- GameServer definition validation [\#10](https://github.com/googleforgames/agones/issues/10)
- Default RestartPolicy should be Never on the GameServer container [\#9](https://github.com/googleforgames/agones/issues/9)
- Mac & Windows binaries for local development [\#8](https://github.com/googleforgames/agones/issues/8)
- `gcloud docker --authorize` make target and push targets [\#5](https://github.com/googleforgames/agones/issues/5)
- Do-release target to automate releases [\#121](https://github.com/googleforgames/agones/pull/121) ([markmandel](https://github.com/markmandel))
- Zip archive of sdk server server binaries for release [\#118](https://github.com/googleforgames/agones/pull/118) ([markmandel](https://github.com/markmandel))
- add hostPort and container validations to webhook [\#106](https://github.com/googleforgames/agones/pull/106) ([cyriltovena](https://github.com/cyriltovena))
- MutatingWebHookConfiguration for GameServer creation & Validation. [\#95](https://github.com/googleforgames/agones/pull/95) ([markmandel](https://github.com/markmandel))
- Address flag for the sidecar [\#73](https://github.com/googleforgames/agones/pull/73) ([markmandel](https://github.com/markmandel))
- Allow extra args to be passed into minikube-shell [\#71](https://github.com/googleforgames/agones/pull/71) ([markmandel](https://github.com/markmandel))
- Implementation of Health Checking [\#69](https://github.com/googleforgames/agones/pull/69) ([markmandel](https://github.com/markmandel))
- Develop and Build on Windows \(WSL\) with Minikube [\#59](https://github.com/googleforgames/agones/pull/59) ([markmandel](https://github.com/markmandel))
- Recording GameServers Kubernetes Events [\#56](https://github.com/googleforgames/agones/pull/56) ([markmandel](https://github.com/markmandel))
- Add health check for gameserver-sidecar. [\#44](https://github.com/googleforgames/agones/pull/44) ([dzlier-gcp](https://github.com/dzlier-gcp))
- Dynamic Port Allocation for GameServers [\#41](https://github.com/googleforgames/agones/pull/41) ([markmandel](https://github.com/markmandel))
- Finalizer for GameServer until backing Pods are Terminated [\#40](https://github.com/googleforgames/agones/pull/40) ([markmandel](https://github.com/markmandel))
- Continuous Integration with Container Builder [\#38](https://github.com/googleforgames/agones/pull/38) ([markmandel](https://github.com/markmandel))
- Windows and OSX builds of the sidecar [\#36](https://github.com/googleforgames/agones/pull/36) ([markmandel](https://github.com/markmandel))
- C++ SDK implementation, example and doc [\#35](https://github.com/googleforgames/agones/pull/35) ([markmandel](https://github.com/markmandel))
- Use a sha256 of Dockerfile for build-image [\#25](https://github.com/googleforgames/agones/pull/25) ([markmandel](https://github.com/markmandel))
- Utilises Xonotic.org to build and run an actual game on Agon. [\#23](https://github.com/googleforgames/agones/pull/23) ([markmandel](https://github.com/markmandel))
- Go SDK for integration with Game Servers. [\#20](https://github.com/googleforgames/agones/pull/20) ([markmandel](https://github.com/markmandel))

**Fixed bugs:**

- `make gcloud-auth-docker` fails on Windows [\#49](https://github.com/googleforgames/agones/issues/49)
- Convert `ENTRYPOINT foo` to `ENTRYPOINT \["/path/foo"\]` [\#39](https://github.com/googleforgames/agones/issues/39)
- Handle SIGTERM in Controller [\#33](https://github.com/googleforgames/agones/issues/33)
- Gopkg.toml should use tags not branches for k8s.io dependencies [\#1](https://github.com/googleforgames/agones/issues/1)
- fix liveness probe in the install.yaml [\#119](https://github.com/googleforgames/agones/pull/119) ([cyriltovena](https://github.com/cyriltovena))
- Make Port Allocator idempotent for GameServers and Node events [\#117](https://github.com/googleforgames/agones/pull/117) ([markmandel](https://github.com/markmandel))
- DeleteFunc could recieve a DeletedFinalStateUnknown [\#113](https://github.com/googleforgames/agones/pull/113) ([markmandel](https://github.com/markmandel))
- Goimports wasn't running on CRD generation [\#99](https://github.com/googleforgames/agones/pull/99) ([markmandel](https://github.com/markmandel))
- Fix a bug in HandleError [\#67](https://github.com/googleforgames/agones/pull/67) ([markmandel](https://github.com/markmandel))
- Minikube targts: make sure they are on the agon minikube profile [\#66](https://github.com/googleforgames/agones/pull/66) ([markmandel](https://github.com/markmandel))
- Header insert on gRPC code gen touched too many files [\#58](https://github.com/googleforgames/agones/pull/58) ([markmandel](https://github.com/markmandel))
- Fix for health check stability issues [\#55](https://github.com/googleforgames/agones/pull/55) ([markmandel](https://github.com/markmandel))
- `make gcloud-auth-docker` works on Windows [\#50](https://github.com/googleforgames/agones/pull/50) ([markmandel](https://github.com/markmandel))
- Use the preferred ENTRYPOINT format [\#43](https://github.com/googleforgames/agones/pull/43) ([markmandel](https://github.com/markmandel))
- Update Kubernetes dependencies to release branch [\#24](https://github.com/googleforgames/agones/pull/24) ([markmandel](https://github.com/markmandel))

**Security fixes:**

- Switch to RBAC [\#57](https://github.com/googleforgames/agones/issues/57)
- Upgrade to Go 1.9.4 [\#81](https://github.com/googleforgames/agones/pull/81) ([markmandel](https://github.com/markmandel))

**Closed issues:**

- `make do-release` target [\#115](https://github.com/googleforgames/agones/issues/115)
- Creating a Kubernetes Cluster quickstart [\#93](https://github.com/googleforgames/agones/issues/93)
- Namespace for Agones infrastructure [\#89](https://github.com/googleforgames/agones/issues/89)
- Health check should be moved out of `gameservers/controller.go` [\#88](https://github.com/googleforgames/agones/issues/88)
- Add archiving the sdk-server binaries into gcs into the cloudbuild.yaml [\#87](https://github.com/googleforgames/agones/issues/87)
- Upgrade to Go 1.9.3 [\#63](https://github.com/googleforgames/agones/issues/63)
- Building Agon on Windows [\#47](https://github.com/googleforgames/agones/issues/47)
- Building Agones on macOS [\#46](https://github.com/googleforgames/agones/issues/46)
- Write documentation for creating a GameServer [\#45](https://github.com/googleforgames/agones/issues/45)
- Agon should work on Minikube [\#30](https://github.com/googleforgames/agones/issues/30)
- Remove the entrypoint from the build-image [\#28](https://github.com/googleforgames/agones/issues/28)
- Base Go Version and Docker image tag on Git commit sha [\#21](https://github.com/googleforgames/agones/issues/21)
- Tag agon-build with hash of the Dockerfile [\#19](https://github.com/googleforgames/agones/issues/19)
- Example using Xonotic [\#18](https://github.com/googleforgames/agones/issues/18)
- Continuous Integration [\#13](https://github.com/googleforgames/agones/issues/13)
- C++ SDK [\#7](https://github.com/googleforgames/agones/issues/7)
- Upgrade to alpine 3.7 [\#4](https://github.com/googleforgames/agones/issues/4)
- Make controller SchemeGroupVersion a var [\#3](https://github.com/googleforgames/agones/issues/3)
- Consolidate `Version` into a single constant [\#2](https://github.com/googleforgames/agones/issues/2)

**Merged pull requests:**

- Godoc badge! [\#131](https://github.com/googleforgames/agones/pull/131) ([markmandel](https://github.com/markmandel))
- add missing link to git message documentation [\#129](https://github.com/googleforgames/agones/pull/129) ([cyriltovena](https://github.com/cyriltovena))
- Minor tweak to top line description of Agones. [\#127](https://github.com/googleforgames/agones/pull/127) ([markmandel](https://github.com/markmandel))
- Documentation for programmatically working with Agones. [\#126](https://github.com/googleforgames/agones/pull/126) ([markmandel](https://github.com/markmandel))
- Extend documentation for SDKs [\#125](https://github.com/googleforgames/agones/pull/125) ([markmandel](https://github.com/markmandel))
- Documentation quickstart and specification gameserver [\#124](https://github.com/googleforgames/agones/pull/124) ([cyriltovena](https://github.com/cyriltovena))
- Add MutatingAdmissionWebhook requirements to README [\#123](https://github.com/googleforgames/agones/pull/123) ([markmandel](https://github.com/markmandel))
- Add cluster creation Quickstart. [\#122](https://github.com/googleforgames/agones/pull/122) ([dzlier-gcp](https://github.com/dzlier-gcp))
- Fix typo introduced by refactor [\#120](https://github.com/googleforgames/agones/pull/120) ([markmandel](https://github.com/markmandel))
- Cleanup on GameServer Controller [\#114](https://github.com/googleforgames/agones/pull/114) ([markmandel](https://github.com/markmandel))
- Fixed some typos. [\#112](https://github.com/googleforgames/agones/pull/112) ([EricFortin](https://github.com/EricFortin))
- Added the source of the name to the Readme. [\#111](https://github.com/googleforgames/agones/pull/111) ([markmandel](https://github.com/markmandel))
- Add 'make' to minikube target commands [\#109](https://github.com/googleforgames/agones/pull/109) ([joeholley](https://github.com/joeholley))
- Move WaitForEstablishedCRD into central `crd` package [\#108](https://github.com/googleforgames/agones/pull/108) ([markmandel](https://github.com/markmandel))
- Centralise Controller Queue and Worker processing [\#107](https://github.com/googleforgames/agones/pull/107) ([markmandel](https://github.com/markmandel))
- Slack community! [\#105](https://github.com/googleforgames/agones/pull/105) ([markmandel](https://github.com/markmandel))
- Add an `source` to all log statements [\#103](https://github.com/googleforgames/agones/pull/103) ([markmandel](https://github.com/markmandel))
- Putting the code of conduct front of page. [\#102](https://github.com/googleforgames/agones/pull/102) ([markmandel](https://github.com/markmandel))
- Add CRD validation via OpenAPIv3 Schema [\#100](https://github.com/googleforgames/agones/pull/100) ([cyriltovena](https://github.com/cyriltovena))
- Use github.com/heptio/healthcheck [\#98](https://github.com/googleforgames/agones/pull/98) ([enocom](https://github.com/enocom))
- Adding CoC and Discuss mailing lists. [\#96](https://github.com/googleforgames/agones/pull/96) ([markmandel](https://github.com/markmandel))
- Standardize on LF line endings [\#92](https://github.com/googleforgames/agones/pull/92) ([enocom](https://github.com/enocom))
- Move Agones resources into a `agones-system` namespace. [\#91](https://github.com/googleforgames/agones/pull/91) ([markmandel](https://github.com/markmandel))
- Support builds on macOS [\#90](https://github.com/googleforgames/agones/pull/90) ([enocom](https://github.com/enocom))
- Enable RBAC [\#86](https://github.com/googleforgames/agones/pull/86) ([dzlier-gcp](https://github.com/dzlier-gcp))
- Update everything to be Kubernetes 1.9+ [\#85](https://github.com/googleforgames/agones/pull/85) ([markmandel](https://github.com/markmandel))
- Expand on contributing documentation. [\#84](https://github.com/googleforgames/agones/pull/84) ([markmandel](https://github.com/markmandel))
- Remove entrypoints in makefile. [\#82](https://github.com/googleforgames/agones/pull/82) ([cyriltovena](https://github.com/cyriltovena))
- Update to client-go release 1.6 [\#80](https://github.com/googleforgames/agones/pull/80) ([markmandel](https://github.com/markmandel))
- Setup for social/get involved section. [\#79](https://github.com/googleforgames/agones/pull/79) ([markmandel](https://github.com/markmandel))
- Changing name from Agon =\> Agones. [\#78](https://github.com/googleforgames/agones/pull/78) ([markmandel](https://github.com/markmandel))
- Refactor to centralise controller [\#77](https://github.com/googleforgames/agones/pull/77) ([markmandel](https://github.com/markmandel))
- Missing link to healthchecking. [\#76](https://github.com/googleforgames/agones/pull/76) ([markmandel](https://github.com/markmandel))
- Upgrade to Alpine 3.7 [\#75](https://github.com/googleforgames/agones/pull/75) ([markmandel](https://github.com/markmandel))
- Update to Go 1.9.3 [\#74](https://github.com/googleforgames/agones/pull/74) ([markmandel](https://github.com/markmandel))
- Update Xonotic demo to use dynamic ports [\#72](https://github.com/googleforgames/agones/pull/72) ([markmandel](https://github.com/markmandel))
- Basic structure for better documentation [\#68](https://github.com/googleforgames/agones/pull/68) ([markmandel](https://github.com/markmandel))
- Update gke-test-cluster admin password to new minimum length 16 chars. [\#65](https://github.com/googleforgames/agones/pull/65) ([dzlier-gcp](https://github.com/dzlier-gcp))
- Output the stack error as an actual array [\#61](https://github.com/googleforgames/agones/pull/61) ([markmandel](https://github.com/markmandel))
- Update documentation [\#53](https://github.com/googleforgames/agones/pull/53) ([cyriltovena](https://github.com/cyriltovena))
- Correct maximum parameter typo [\#52](https://github.com/googleforgames/agones/pull/52) ([cyriltovena](https://github.com/cyriltovena))
- Document building Agon on different platforms [\#51](https://github.com/googleforgames/agones/pull/51) ([markmandel](https://github.com/markmandel))
- Development and Deployment to Minikube [\#48](https://github.com/googleforgames/agones/pull/48) ([markmandel](https://github.com/markmandel))
- Fix typo for logrus gameserver field [\#42](https://github.com/googleforgames/agones/pull/42) ([alexandrem](https://github.com/alexandrem))
- Add health check. [\#34](https://github.com/googleforgames/agones/pull/34) ([dzlier-gcp](https://github.com/dzlier-gcp))
- Guide for developing and building Agon. [\#31](https://github.com/googleforgames/agones/pull/31) ([markmandel](https://github.com/markmandel))
- Implement Versioning for dev and release [\#29](https://github.com/googleforgames/agones/pull/29) ([markmandel](https://github.com/markmandel))
- Consolidate the Version constant [\#27](https://github.com/googleforgames/agones/pull/27) ([markmandel](https://github.com/markmandel))
- Make targets `gcloud docker --authorize-only` and `push` [\#26](https://github.com/googleforgames/agones/pull/26) ([markmandel](https://github.com/markmandel))
- zinstall.yaml to install Agon. [\#22](https://github.com/googleforgames/agones/pull/22) ([markmandel](https://github.com/markmandel))
- Disclaimer that Agon is alpha software. [\#6](https://github.com/googleforgames/agones/pull/6) ([markmandel](https://github.com/markmandel))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*

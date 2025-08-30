# Changelog

## [41.2.0](https://github.com/leaf-BA7JCM/vercel-action/compare/v41.1.4...v41.2.0) (2025-08-30)


### Features

* add auto comment logic ([98a62eb](https://github.com/leaf-BA7JCM/vercel-action/commit/98a62eb54746335084d2e9123e5a7eb86c5e846b))
* add logic to update comment ([f2babe1](https://github.com/leaf-BA7JCM/vercel-action/commit/f2babe1b14f8ba569cd432da849936f765a2113b))
* add support to pull_request_target event ([#47](https://github.com/leaf-BA7JCM/vercel-action/issues/47)) ([fa3de6c](https://github.com/leaf-BA7JCM/vercel-action/commit/fa3de6c67ebd1d3b523afa9769673c789ff16224))
* add vercel-version option ([#183](https://github.com/leaf-BA7JCM/vercel-action/issues/183)) ([ee3a438](https://github.com/leaf-BA7JCM/vercel-action/commit/ee3a4382aaf5e15d203aa2fa316819506890430f))
* add working dir input ([#17](https://github.com/leaf-BA7JCM/vercel-action/issues/17)) ([c334a92](https://github.com/leaf-BA7JCM/vercel-action/commit/c334a921c000b578c710d3d83ca696a37a1488bb))
* alias domain to deployment ([#18](https://github.com/leaf-BA7JCM/vercel-action/issues/18)) ([1dbb4cf](https://github.com/leaf-BA7JCM/vercel-action/commit/1dbb4cf552aeaccc8c0c3fbd79be291f06a5faa6)), closes [#7](https://github.com/leaf-BA7JCM/vercel-action/issues/7)
* allow spaces in vercel-args ([#237](https://github.com/leaf-BA7JCM/vercel-action/issues/237)) ([f790839](https://github.com/leaf-BA7JCM/vercel-action/commit/f7908391bab341861b94223ae47cdff688e2551c))
* commit comment ([e9eb2d1](https://github.com/leaf-BA7JCM/vercel-action/commit/e9eb2d18624ca8888b546b4f95631e0c35999160))
* commit comment ([b89568d](https://github.com/leaf-BA7JCM/vercel-action/commit/b89568d6f614a13968fc6d016aca17253f0985c4))
* commit comment on push event ([6c50b33](https://github.com/leaf-BA7JCM/vercel-action/commit/6c50b33f1272262ae1ab14a4e703e5b1b46cb46c))
* enable users to customize github comment ([#56](https://github.com/leaf-BA7JCM/vercel-action/issues/56)) ([737bc95](https://github.com/leaf-BA7JCM/vercel-action/commit/737bc95a6dfb2d31e723bb2f513184c42ef5df26))
* fallback to 41.1.4 instead of 25.1.0 ([#267](https://github.com/leaf-BA7JCM/vercel-action/issues/267)) ([90ffb6b](https://github.com/leaf-BA7JCM/vercel-action/commit/90ffb6bfde6fd08a9722c49fafe8f0efc2f2d7bd))
* get deployment url for commit ([2242707](https://github.com/leaf-BA7JCM/vercel-action/commit/224270736de93e2478a65fbcaf806cfef2da687a))
* github comment optional ([#20](https://github.com/leaf-BA7JCM/vercel-action/issues/20)) ([0fd9718](https://github.com/leaf-BA7JCM/vercel-action/commit/0fd9718f157ce3c96317d385a3c8ebd92b32909e))
* improve slugify ([#34](https://github.com/leaf-BA7JCM/vercel-action/issues/34)) ([f79b066](https://github.com/leaf-BA7JCM/vercel-action/commit/f79b066724a2ac14b8944244a625146e5d6006c3))
* list comments ([29e3c47](https://github.com/leaf-BA7JCM/vercel-action/commit/29e3c4754109ef6908296d99b3eeb820160363c5))
* now cli v17 ([9903655](https://github.com/leaf-BA7JCM/vercel-action/commit/9903655ed61218059e6d81d3b8b94ea8ec4bb909))
* now cli v17, add `NOW_PROJECT_ID` and `NOW_ORG_ID` env variable ([#26](https://github.com/leaf-BA7JCM/vercel-action/issues/26)) ([a16650e](https://github.com/leaf-BA7JCM/vercel-action/commit/a16650e1582eb1433f71c42962a2dcdee5ebef59))
* now deployment ([48174da](https://github.com/leaf-BA7JCM/vercel-action/commit/48174daa09867a2771a906957482ff626d3418c2))
* rename to vercel ([#1](https://github.com/leaf-BA7JCM/vercel-action/issues/1)) ([7af3dee](https://github.com/leaf-BA7JCM/vercel-action/commit/7af3dee125047cf60a30beea92ea3e275f43ea47))
* retry on alias creation error ([#215](https://github.com/leaf-BA7JCM/vercel-action/issues/215)) ([225d234](https://github.com/leaf-BA7JCM/vercel-action/commit/225d234cfe5340ca1f9a6cd158338126b5b6845f))
* use node 20 ([#255](https://github.com/leaf-BA7JCM/vercel-action/issues/255)) ([16e87c0](https://github.com/leaf-BA7JCM/vercel-action/commit/16e87c0a08142b0d0d33b76aeaf20823c381b9b9))
* use now official metadata ([25e3422](https://github.com/leaf-BA7JCM/vercel-action/commit/25e3422b5aa4f238398991584b0abbe05c586bf5))
* Vercel Metadata Override ([#118](https://github.com/leaf-BA7JCM/vercel-action/issues/118)) ([e871873](https://github.com/leaf-BA7JCM/vercel-action/commit/e871873e41e2b50131f708b653f0fd05d174ae1b))


### Bug Fixes

* `id` -&gt; `comment_id` param ([2d160b1](https://github.com/leaf-BA7JCM/vercel-action/commit/2d160b100516148a6f745d6097fc52324a95342a))
* add `actions/checkout@v1` before all ([dbb4a84](https://github.com/leaf-BA7JCM/vercel-action/commit/dbb4a84b8a5642156015d9829543e4a653e2ecaa))
* add quotes around commit message ([#141](https://github.com/leaf-BA7JCM/vercel-action/issues/141)) ([dd9db49](https://github.com/leaf-BA7JCM/vercel-action/commit/dd9db4939281edb057f663e490ca254376e55863))
* add token args ([37e58ab](https://github.com/leaf-BA7JCM/vercel-action/commit/37e58ab893d5313e4e0cd8dc484c288b44a21a0f))
* branch is undefined ([#33](https://github.com/leaf-BA7JCM/vercel-action/issues/33)) ([740d8b5](https://github.com/leaf-BA7JCM/vercel-action/commit/740d8b5d8da5d7fb17d898d64c4787e72e8286b1))
* built with commit undefined ([7758a86](https://github.com/leaf-BA7JCM/vercel-action/commit/7758a86df87900464d1c9e3851e9bd08b863ed9b))
* built with commit undefined ([1506158](https://github.com/leaf-BA7JCM/vercel-action/commit/1506158235ae8c568641a07ab38fbcec51f206c4)), closes [#9](https://github.com/leaf-BA7JCM/vercel-action/issues/9)
* Cannot use both a `vercel.json` and `now.json` file. ([c25ae58](https://github.com/leaf-BA7JCM/vercel-action/commit/c25ae5833e82414e37b0abdc792a99cd57ce942a))
* Cannot use both a `vercel.json` and `now.json` file. ([e416ce3](https://github.com/leaf-BA7JCM/vercel-action/commit/e416ce3f7be196854131aa7f585e832f322f27c1))
* changel log level ([6f7d0e7](https://github.com/leaf-BA7JCM/vercel-action/commit/6f7d0e7be28dae048e4338c1fe82525026797c81))
* ci ([671b323](https://github.com/leaf-BA7JCM/vercel-action/commit/671b32338b738ef2388f533bbd5e22ec06b6bf4a))
* commit author ([a79c74a](https://github.com/leaf-BA7JCM/vercel-action/commit/a79c74a724817c5ac0230523cb54f74c4613ff6e))
* commit author ([81c1952](https://github.com/leaf-BA7JCM/vercel-action/commit/81c1952571643e66ac3ae6dc55e7c999becc6a7e))
* deprecating set-env and add-path commands ([#43](https://github.com/leaf-BA7JCM/vercel-action/issues/43)) ([16ea833](https://github.com/leaf-BA7JCM/vercel-action/commit/16ea833d503f952b234bf37548d26c357c351c59)), closes [#42](https://github.com/leaf-BA7JCM/vercel-action/issues/42)
* don't require the deprecated zeit-token action input ([#210](https://github.com/leaf-BA7JCM/vercel-action/issues/210)) ([2b2891b](https://github.com/leaf-BA7JCM/vercel-action/commit/2b2891b2a25aacf731bced4cff6feb84007b1458))
* don't send new comment for every pushed commit and just edit exi… ([#17](https://github.com/leaf-BA7JCM/vercel-action/issues/17)) ([24e4f90](https://github.com/leaf-BA7JCM/vercel-action/commit/24e4f9073714ca844ed1607c5a415aef823ba78a)), closes [#15](https://github.com/leaf-BA7JCM/vercel-action/issues/15)
* double https:// ([#3](https://github.com/leaf-BA7JCM/vercel-action/issues/3)) ([15e80cf](https://github.com/leaf-BA7JCM/vercel-action/commit/15e80cfd0e44163126addfe4bc49863168164d6a))
* empty output object ([#38](https://github.com/leaf-BA7JCM/vercel-action/issues/38)) ([22abc96](https://github.com/leaf-BA7JCM/vercel-action/commit/22abc967dd6d51ba88a0cb7a978aedbbc7fd4607))
* fallback to last deployment ([dfa7051](https://github.com/leaf-BA7JCM/vercel-action/commit/dfa7051b90a7920b544c4688b9a9aca29df7c55f))
* fallback to last deployment if no deployments for commit found ([571c8f7](https://github.com/leaf-BA7JCM/vercel-action/commit/571c8f72aae3454829c88a60a1ec177cde7a83dc))
* github ref randomly empty for release triggers ([#277](https://github.com/leaf-BA7JCM/vercel-action/issues/277)) ([9ef1deb](https://github.com/leaf-BA7JCM/vercel-action/commit/9ef1deba160a11eaa7bb9a256eadde16513c7d46))
* github-deployment typo ([68ccfe2](https://github.com/leaf-BA7JCM/vercel-action/commit/68ccfe27ba7cf10bcc5cf5c6b4c4fd3f31d05d1b))
* handle inaccessible PR head repository gracefully ([f9aadd3](https://github.com/leaf-BA7JCM/vercel-action/commit/f9aadd3303aeb96f7003366b164cb06a2b54d69e))
* if event is push, failed ([a26e9dc](https://github.com/leaf-BA7JCM/vercel-action/commit/a26e9dcdb71d27ae9f43d97913bdc5d67fdb387c))
* if event is push, failed ([1e6f244](https://github.com/leaf-BA7JCM/vercel-action/commit/1e6f244022a6ffa562a445367630296778c8c583))
* node_modules ([9f6532e](https://github.com/leaf-BA7JCM/vercel-action/commit/9f6532e10e2fa883d2ec778b320b8cc2b60c02d6))
* now-args bug ([d5c8672](https://github.com/leaf-BA7JCM/vercel-action/commit/d5c8672a5487aee7d9496ee89cf9b636f62bd1d7))
* octokit.repos.commentId is not a function ([5972282](https://github.com/leaf-BA7JCM/vercel-action/commit/597228245179fdb266befe3c4a5d8ab1f6d468b7))
* outputs object is always empty ([#29](https://github.com/leaf-BA7JCM/vercel-action/issues/29)) ([f943bcf](https://github.com/leaf-BA7JCM/vercel-action/commit/f943bcfed35f89c9ff32df2ea9f9974fae9cbc06))
* pass GITHUB_TOKEN to action ([3041327](https://github.com/leaf-BA7JCM/vercel-action/commit/304132751e452c18920f892587fb95e5a8d36932))
* remove hard-coded commit for testing ([06f262a](https://github.com/leaf-BA7JCM/vercel-action/commit/06f262a8e48721578f316aa40d84be993c5598bb))
* typo ([7d5454b](https://github.com/leaf-BA7JCM/vercel-action/commit/7d5454b10d43ea2613da61e75308fd6dd75d4bf3))
* typo in argument ([feeb57c](https://github.com/leaf-BA7JCM/vercel-action/commit/feeb57c4cc4c40fbf6b9fdc403dbf11dbfd3bf5c))
* typo in argument ([0996748](https://github.com/leaf-BA7JCM/vercel-action/commit/099674872ee4d9a0addd734929f9ef5f880da5cf))
* use `issues.createComment()` ([7074387](https://github.com/leaf-BA7JCM/vercel-action/commit/7074387d77360ca4715f3e74c103da06620ef113))
* use `yarn` to install dependencies ([bc48fc7](https://github.com/leaf-BA7JCM/vercel-action/commit/bc48fc77961ea60d9209afecac966b434ebda1b3))
* use correct commit SHA ([#278](https://github.com/leaf-BA7JCM/vercel-action/issues/278)) ([9f07672](https://github.com/leaf-BA7JCM/vercel-action/commit/9f07672661f866626bf48680190c656d3dd1cded))
* use first alias as preview url ([f12f593](https://github.com/leaf-BA7JCM/vercel-action/commit/f12f5937db4274e1afa4522ff2b3611393183bc1))
* use scope everywhere npx is used ([4ed2945](https://github.com/leaf-BA7JCM/vercel-action/commit/4ed2945de0cd28e55bdb3013e81f0eeaa491ff26))
* vercel inspect fails in team scope ([#5](https://github.com/leaf-BA7JCM/vercel-action/issues/5)) ([b0d780b](https://github.com/leaf-BA7JCM/vercel-action/commit/b0d780b932a54b155d51d6be01dc9f514f01d5f0))
* workflow examples with deprecated commands ([#189](https://github.com/leaf-BA7JCM/vercel-action/issues/189)) ([3500841](https://github.com/leaf-BA7JCM/vercel-action/commit/350084192dd04458921db86a29ff3550b7b8d39f))
* wrong object key ([5ce38e9](https://github.com/leaf-BA7JCM/vercel-action/commit/5ce38e970386a089b0d13d8a2803ad188bd6d819))
* wrong variable after rename ([341a40a](https://github.com/leaf-BA7JCM/vercel-action/commit/341a40ac484b57829b7b4554f77833eb6564fdeb))

## [v25.0.0](https://github.com/amondnet/vercel-action/tree/v25.0.0) (2022-06-08)

[Full Changelog](https://github.com/amondnet/vercel-action/compare/v20.0.2...v25.0.0)

## [v20.0.2](https://github.com/amondnet/vercel-action/tree/v20.0.2) (2022-06-08)

[Full Changelog](https://github.com/amondnet/vercel-action/compare/v20.0.1...v20.0.2)

**Closed issues:**

- Create previews for branches, not per commit [\#150](https://github.com/amondnet/vercel-action/issues/150)
- Error: Resource not accessible by integration [\#148](https://github.com/amondnet/vercel-action/issues/148)
- How to re-authenticate [\#138](https://github.com/amondnet/vercel-action/issues/138)
- Unclear how the build command and the build directory are inferred [\#122](https://github.com/amondnet/vercel-action/issues/122)

**Merged pull requests:**

- fix: add quotes around commit message [\#141](https://github.com/amondnet/vercel-action/pull/141) ([Regaddi](https://github.com/Regaddi))
- docs: how to skip build step [\#136](https://github.com/amondnet/vercel-action/pull/136) ([amondnet](https://github.com/amondnet))
- docs: use `@vercel/static-build` instead of `@now/static` [\#135](https://github.com/amondnet/vercel-action/pull/135) ([amondnet](https://github.com/amondnet))
- Revert "docs: remove builds from vercel.json" [\#134](https://github.com/amondnet/vercel-action/pull/134) ([amondnet](https://github.com/amondnet))
- docs: remove builds from vercel.json [\#133](https://github.com/amondnet/vercel-action/pull/133) ([amondnet](https://github.com/amondnet))

## [v20.0.1](https://github.com/amondnet/vercel-action/tree/v20.0.1) (2022-03-09)

[Full Changelog](https://github.com/amondnet/vercel-action/compare/v20.0.0...v20.0.1)

**Implemented enhancements:**

- Enable users to use "preview-url" in the "github-comment" [\#75](https://github.com/amondnet/vercel-action/issues/75)
- Feature request: enable users to customize github comment [\#52](https://github.com/amondnet/vercel-action/issues/52)
- feat: enable users to customize github comment [\#56](https://github.com/amondnet/vercel-action/pull/56) ([sundoufu](https://github.com/sundoufu))

**Closed issues:**

- Vercel Deployment fails due to "missing input" [\#105](https://github.com/amondnet/vercel-action/issues/105)
- Action doesn't set vercel-org-id [\#96](https://github.com/amondnet/vercel-action/issues/96)
- promote deployment to production if commited branch equals master or main [\#81](https://github.com/amondnet/vercel-action/issues/81)
- Action Failing at vercel inspect [\#80](https://github.com/amondnet/vercel-action/issues/80)
- Use branch name from ref? [\#78](https://github.com/amondnet/vercel-action/issues/78)
- Error when trying to fetch deployment [\#67](https://github.com/amondnet/vercel-action/issues/67)
- Deployment is on the correct branch, but it always use source code on main branch [\#65](https://github.com/amondnet/vercel-action/issues/65)
- Remove depracated package @now/node-server [\#61](https://github.com/amondnet/vercel-action/issues/61)

**Merged pull requests:**

- Use vercel-compatible ref naming [\#108](https://github.com/amondnet/vercel-action/pull/108) ([andyrichardson](https://github.com/andyrichardson))
- reformated checkbox [\#92](https://github.com/amondnet/vercel-action/pull/92) ([claranceliberi](https://github.com/claranceliberi))
- chore: Fix typo in README.md [\#73](https://github.com/amondnet/vercel-action/pull/73) ([caoer](https://github.com/caoer))
- ci: pull\_request\_target [\#59](https://github.com/amondnet/vercel-action/pull/59) ([amondnet](https://github.com/amondnet))
- Parse deployment details in Github comments [\#124](https://github.com/amondnet/vercel-action/pull/124) ([abstractalgo](https://github.com/abstractalgo))
- feat: Vercel Metadata Override [\#118](https://github.com/amondnet/vercel-action/pull/118) ([cgosiak](https://github.com/cgosiak))
- ci: use pull request target [\#63](https://github.com/amondnet/vercel-action/pull/63) ([amondnet](https://github.com/amondnet))
- docs: remove deprecated package now/node-server [\#62](https://github.com/amondnet/vercel-action/pull/62) ([amondnet](https://github.com/amondnet))
- build\(deps\): bump node-fetch from 2.6.0 to 2.6.1 [\#44](https://github.com/amondnet/vercel-action/pull/44) ([dependabot[bot]](https://github.com/apps/dependabot))
- build\(deps\): bump lodash from 4.17.15 to 4.17.20 [\#36](https://github.com/amondnet/vercel-action/pull/36) ([dependabot[bot]](https://github.com/apps/dependabot))
- build\(deps\): bump http-proxy from 1.18.0 to 1.18.1 in /example/angular [\#35](https://github.com/amondnet/vercel-action/pull/35) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v20.0.0](https://github.com/amondnet/vercel-action/tree/v20.0.0) (2020-11-30)

[Full Changelog](https://github.com/amondnet/vercel-action/compare/v19.0.1+4...v20.0.0)

**Implemented enhancements:**

- add support to pull\_request\_target event [\#47](https://github.com/amondnet/vercel-action/pull/47) ([nionis](https://github.com/nionis))

**Closed issues:**

- Error: ENOENT [\#51](https://github.com/amondnet/vercel-action/issues/51)
- Deployment is always done on the same branch refs/heads/develop [\#48](https://github.com/amondnet/vercel-action/issues/48)

**Merged pull requests:**

- chore\(README\): Update deployment script path [\#49](https://github.com/amondnet/vercel-action/pull/49) ([richardtapendium](https://github.com/richardtapendium))
- chore\(deps\): vercel cli v20.1.1 [\#41](https://github.com/amondnet/vercel-action/pull/41) ([amondnet](https://github.com/amondnet))

## [v19.0.1+4](https://github.com/amondnet/vercel-action/tree/v19.0.1+4) (2020-10-13)

[Full Changelog](https://github.com/amondnet/vercel-action/compare/v19.0.1+3...v19.0.1+4)

**Fixed bugs:**

- Getting errors after upgrading to vercel-action [\#4](https://github.com/amondnet/vercel-action/issues/4)

**Closed issues:**

- `set-env` command is deprecated and will be disabled soon [\#42](https://github.com/amondnet/vercel-action/issues/42)
- Unable to find version [\#39](https://github.com/amondnet/vercel-action/issues/39)
- Difficulty adding multiple environment variables in vercel-args [\#38](https://github.com/amondnet/vercel-action/issues/38)
- Deployment never finish [\#32](https://github.com/amondnet/vercel-action/issues/32)
- Input required and not supplied: `${name}` [\#26](https://github.com/amondnet/vercel-action/issues/26)

**Merged pull requests:**

- fix: deprecating set-env and add-path commands [\#43](https://github.com/amondnet/vercel-action/pull/43) ([amondnet](https://github.com/amondnet))
- Fix prod\_or\_not in example-static [\#37](https://github.com/amondnet/vercel-action/pull/37) ([olivercoad](https://github.com/olivercoad))
- feat: improve slugify [\#34](https://github.com/amondnet/vercel-action/pull/34) ([ocavue](https://github.com/ocavue))
- Update README.md [\#33](https://github.com/amondnet/vercel-action/pull/33) ([zdhz](https://github.com/zdhz))

## [v19.0.1+3](https://github.com/amondnet/vercel-action/tree/v19.0.1+3) (2020-08-12)

[Full Changelog](https://github.com/amondnet/vercel-action/compare/v19.0.1+2...v19.0.1+3)

**Fixed bugs:**

- Deployment succeeds but action log says it failed [\#27](https://github.com/amondnet/vercel-action/issues/27)
- fix: use scope everywhere npx is used [\#24](https://github.com/amondnet/vercel-action/pull/24) ([aulneau](https://github.com/aulneau))

**Closed issues:**

- Deploy is failing [\#28](https://github.com/amondnet/vercel-action/issues/28)
- Not deploying to production [\#22](https://github.com/amondnet/vercel-action/issues/22)
- Alias does not incorporate scope [\#23](https://github.com/amondnet/vercel-action/issues/23)

**Merged pull requests:**

- build\(deps\): bump elliptic from 6.5.2 to 6.5.3 in /example/angular [\#25](https://github.com/amondnet/vercel-action/pull/25) ([dependabot[bot]](https://github.com/apps/dependabot))
- build\(deps\): bump lodash from 4.17.15 to 4.17.19 in /example/angular [\#20](https://github.com/amondnet/vercel-action/pull/20) ([dependabot[bot]](https://github.com/apps/dependabot))
- Fix latest "inspect" bug by adding manual Vercel Project Name option [\#29](https://github.com/amondnet/vercel-action/pull/29) ([EvanLovely](https://github.com/EvanLovely))

## [v19.0.1+2](https://github.com/amondnet/vercel-action/tree/v19.0.1+2) (2020-07-24)

[Full Changelog](https://github.com/amondnet/vercel-action/compare/v19.0.1+1...v19.0.1+2)

**Implemented enhancements:**

- feat: alias domain to deployment [\#7](https://github.com/amondnet/vercel-action/issues/7)
- feat: alias domain to deployment [\#18](https://github.com/amondnet/vercel-action/pull/18) ([amondnet](https://github.com/amondnet))

**Fixed bugs:**

- Don't send new comment for every pushed commit and just edit existed one [\#15](https://github.com/amondnet/vercel-action/issues/15)

**Closed issues:**

- There was an error when attempting to execute the process [\#16](https://github.com/amondnet/vercel-action/issues/16)
- Custom env in action [\#13](https://github.com/amondnet/vercel-action/issues/13)
- Action fails even when build succeeds [\#11](https://github.com/amondnet/vercel-action/issues/11)
- Failed to find deployment \(url\) in \(user\) [\#10](https://github.com/amondnet/vercel-action/issues/10)
- Error! Project not found [\#9](https://github.com/amondnet/vercel-action/issues/9)
- New release [\#19](https://github.com/amondnet/vercel-action/issues/19)

**Merged pull requests:**

- build\(deps\): bump @actions/http-client from 1.0.6 to 1.0.8 [\#6](https://github.com/amondnet/vercel-action/pull/6) ([dependabot[bot]](https://github.com/apps/dependabot))
- fix: don't send new comment for every pushed commit and just edit exi… [\#17](https://github.com/amondnet/vercel-action/pull/17) ([amondnet](https://github.com/amondnet))
- chore: fix broken workflow\(s\) link [\#14](https://github.com/amondnet/vercel-action/pull/14) ([shunkakinoki](https://github.com/shunkakinoki))
- build\(deps\): bump websocket-extensions from 0.1.3 to 0.1.4 in /example/angular [\#12](https://github.com/amondnet/vercel-action/pull/12) ([dependabot[bot]](https://github.com/apps/dependabot))

## [v19.0.1+1](https://github.com/amondnet/vercel-action/tree/v19.0.1+1) (2020-05-18)

[Full Changelog](https://github.com/amondnet/vercel-action/compare/v19.0.1...v19.0.1+1)

**Fixed bugs:**

- fix: vercel inspect fails in team scope [\#5](https://github.com/amondnet/vercel-action/pull/5) ([amondnet](https://github.com/amondnet))

## [v19.0.1](https://github.com/amondnet/vercel-action/tree/v19.0.1) (2020-05-18)

[Full Changelog](https://github.com/amondnet/vercel-action/compare/v2.0.3...v19.0.1)

**Fixed bugs:**

- Remove double https:// [\#3](https://github.com/amondnet/vercel-action/pull/3) ([sunderipranata](https://github.com/sunderipranata))

**Merged pull requests:**

- refactor: eslint [\#2](https://github.com/amondnet/vercel-action/pull/2) ([amondnet](https://github.com/amondnet))
- feat: rename to vercel [\#1](https://github.com/amondnet/vercel-action/pull/1) ([amondnet](https://github.com/amondnet))


---

# ZEIT Now Deplyoment Changelog

## [v2.0.3](https://github.com/amondnet/now-deployment/tree/v2.0.3) (2020-05-06)

[Full Changelog](https://github.com/amondnet/now-deployment/compare/v2.0.2...v2.0.3)

**Implemented enhancements:**

- Show project name in Github comment [\#44](https://github.com/amondnet/now-deployment/pull/44) ([rodrigorm](https://github.com/rodrigorm))

**Closed issues:**

- Update now version to v18 [\#41](https://github.com/amondnet/now-deployment/issues/41)

**Merged pull requests:**

- docs: basic auth example [\#46](https://github.com/amondnet/now-deployment/pull/46) ([amondnet](https://github.com/amondnet))
- build: now@18.0.0 [\#45](https://github.com/amondnet/now-deployment/pull/45) ([amondnet](https://github.com/amondnet))

## [v2.0.2](https://github.com/amondnet/now-deployment/tree/v2.0.2) (2020-04-04)

[Full Changelog](https://github.com/amondnet/now-deployment/compare/v2.0.1...v2.0.2)

**Implemented enhancements:**

- team\_id seems to be not working [\#19](https://github.com/amondnet/now-deployment/issues/19)

**Fixed bugs:**

- undefined url on pull request comment [\#37](https://github.com/amondnet/now-deployment/issues/37)
- Branch is undefined [\#31](https://github.com/amondnet/now-deployment/issues/31)
- Outputs object is always empty [\#25](https://github.com/amondnet/now-deployment/issues/25)
- Fix empty output object [\#38](https://github.com/amondnet/now-deployment/pull/38) ([hakonkrogh](https://github.com/hakonkrogh))
- fix: branch is undefined [\#33](https://github.com/amondnet/now-deployment/pull/33) ([amondnet](https://github.com/amondnet))

**Closed issues:**

- Validation failed: commit\_id has been locked when deploying multiple projects [\#21](https://github.com/amondnet/now-deployment/issues/21)

**Merged pull requests:**

- chore\(release\): 2.0.2  [\#39](https://github.com/amondnet/now-deployment/pull/39) ([amondnet](https://github.com/amondnet))
- docs\(README\): Update documentation regarding github secrets [\#35](https://github.com/amondnet/now-deployment/pull/35) ([amalv](https://github.com/amalv))

## [v2.0.1](https://github.com/amondnet/now-deployment/tree/v2.0.1) (2020-02-25)

[Full Changelog](https://github.com/amondnet/now-deployment/compare/v2.0.0...v2.0.1)

**Fixed bugs:**

- fix: outputs object is always empty [\#29](https://github.com/amondnet/now-deployment/pull/29) ([amondnet](https://github.com/amondnet))

**Closed issues:**

- How can I deploy with an assigned domain? [\#30](https://github.com/amondnet/now-deployment/issues/30)
- Add instruction on getting `project\_id` and `org\_id` [\#27](https://github.com/amondnet/now-deployment/issues/27)

**Merged pull requests:**

- docs: how to get organization and project id of project [\#28](https://github.com/amondnet/now-deployment/pull/28) ([amondnet](https://github.com/amondnet))

## [v2.0.0](https://github.com/amondnet/now-deployment/tree/v2.0.0) (2020-02-18)

[Full Changelog](https://github.com/amondnet/now-deployment/compare/v1.2.0...v2.0.0)

**Implemented enhancements:**

- Do not want to receive comments from action [\#14](https://github.com/amondnet/now-deployment/issues/14)
- Support for Vercel CLI v17 [\#24](https://github.com/amondnet/now-deployment/issues/24)
- feat: now cli v17, add `NOW\_PROJECT\_ID` and `NOW\_ORG\_ID` env variable [\#26](https://github.com/amondnet/now-deployment/pull/26) ([amondnet](https://github.com/amondnet))

**Fixed bugs:**

- Deploy stalled [\#23](https://github.com/amondnet/now-deployment/issues/23)

**Closed issues:**

- Can I upload the contents of a folder with pre-built assets? [\#22](https://github.com/amondnet/now-deployment/issues/22)
- getting 403 error every time it tries to comment [\#18](https://github.com/amondnet/now-deployment/issues/18)
- Feature: Ability to specify path for --local-config flag [\#16](https://github.com/amondnet/now-deployment/issues/16)

## [v1.2.0](https://github.com/amondnet/now-deployment/tree/v1.2.0) (2020-01-28)

[Full Changelog](https://github.com/amondnet/now-deployment/compare/v1...v1.2.0)

**Implemented enhancements:**

- feat: github comment optional [\#20](https://github.com/amondnet/now-deployment/pull/20) ([amondnet](https://github.com/amondnet))

## [v1.1.0](https://github.com/amondnet/now-deployment/tree/v1.1.0) (2020-01-17)

[Full Changelog](https://github.com/amondnet/now-deployment/compare/v1.0.1...v1.1.0)

**Implemented enhancements:**

- feature: add working dir input [\#17](https://github.com/amondnet/now-deployment/pull/17) ([foxundermoon](https://github.com/foxundermoon))

**Fixed bugs:**

- Built with commit undefined [\#9](https://github.com/amondnet/now-deployment/issues/9)
- Add  prod args have an error invalidTagName [\#6](https://github.com/amondnet/now-deployment/issues/6)
- fix: built with commit undefined [\#10](https://github.com/amondnet/now-deployment/pull/10) ([amondnet](https://github.com/amondnet))
- fix now-args bug [\#8](https://github.com/amondnet/now-deployment/pull/8) ([foxundermoon](https://github.com/foxundermoon))
- Update action.yml [\#7](https://github.com/amondnet/now-deployment/pull/7) ([foxundermoon](https://github.com/foxundermoon))
- fix: commit author [\#4](https://github.com/amondnet/now-deployment/pull/4) ([amondnet](https://github.com/amondnet))
- fix: typo in argument  [\#3](https://github.com/amondnet/now-deployment/pull/3) ([amalv](https://github.com/amalv))

**Closed issues:**

- Can't unlink a previous Org connection if I no longer have access to org [\#15](https://github.com/amondnet/now-deployment/issues/15)
- How to deploy from other folders such as build [\#13](https://github.com/amondnet/now-deployment/issues/13)
- Deployment succeeds but workflow reports failure [\#12](https://github.com/amondnet/now-deployment/issues/12)

**Merged pull requests:**

- release: v1 [\#1](https://github.com/amondnet/now-deployment/pull/1) ([amondnet](https://github.com/amondnet))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*

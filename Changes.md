# faktory\_worker\_go

## 1.3.0

- Add new job context APIs for Faktory Enterprise features
- Misc API refactoring to improve test coverage
- Remove `faktory_worker_go` Pool interface in favor of the Pool now in `faktory/client`

## 1.0.1

- FWG will now dump all thread backtraces upon `kill -TTIN <pid>`,
  useful for debugging stuck job processing.
- Send current state back to Faktory so process state changes are visible on Busy page.
- Tweak log output formatting

## 1.0.0

- Allow process labels (visible in Web UI) to be set [#32]
- Add APIs to manage [Batches](https://github.com/contribsys/faktory/wiki/Ent-Batches).

## 0.7.0

- Implement weighted queue fetch [#20, nickpoorman]
- Initial version.

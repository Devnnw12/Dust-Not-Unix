# Dust Not Unix

Dust not unix atau DNU adalah kernel buatan saya yang menggabungkan ketiga model kernel yang terkenal dengan efisiensi dan kecepatannya seperti NT kernel dari kernel windows, linux kernel, xnu atau x not unix dari kernel milik apple. pada project kernel ini saya hanya dapat membuatnya jalan pada architecture x86_64 atau desktop, mungkin kedepannya bisa menjalankan pada architecture arm64, amd64, x86_64 .

## Project Structure

```
DNU.img
  +-- base/
  |    +--shell/
  |
  +-- boot/
  |     +-- uefi/
  |     +-- bootdata/
  |
  +-- Dnu_oskernl/
  |     +-- corpses/
  |     +-- ipc/
  |     +-- kernel/
  |     +-- kextd/
  |     +-- libsa/
  |     +-- ob/
  |     +-- default_pager/
  |
  +-- driver/
  |     +-- bsddev/
  |     |    +--skywalk
  |     +-- IOKit/
  |     |    +-- conf/
  |     |    +-- Driverkit/
  |     |    +-- Exclaves/
  |     |    +-- IOKitUser/
  |     |    +-- kernel/
  |     |    +-- system/
  |
  +-- include/
  |     |    +-- libkdd/
  |     |    +-- libkern/
  |     |    +-- libsa/
  |     |    +-- libsyscall
  |
  +-- hal/
  |     |    +--halx86_64/
  |
  +-- config.cpp/
```
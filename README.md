parking_lot real-time
=====================

A fork of the well-known [parking_lot](https://crates.io/crates/parking_lot)
crate with real-time-safe patches.

* Threads are parked immediately if a lock is not available.

* Spin-free [`Once`], [`Mutex`] and [`RwLock`] implementations.

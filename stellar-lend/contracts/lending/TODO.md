# Borrow-Withdraw Exploit Attempts - Implementation TODO

## Plan Summary
Add adversarial tests that attempt to borrow and immediately withdraw collateral in ways that might exploit rounding, timing, or view inconsistencies. Ensure the contract rejects any path that would leave positions undercollateralized.

## Steps

- [x] Research codebase (borrow.rs, withdraw.rs, views.rs, existing tests)
- [x] Develop comprehensive plan
- [x] Create `borrow_withdraw_adversarial_test.rs` with exploit scenarios
- [x] Update `lib.rs` to include new test module
- [x] Update `SECURITY_NOTES.md` with security note about borrow-withdraw invariants
- [ ] Run tests and verify all pass
- [ ] Include test output in commit


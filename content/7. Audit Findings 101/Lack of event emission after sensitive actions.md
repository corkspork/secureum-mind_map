
# 77 - [Lack of event emission after sensitive actions](./Lack%20of%20event%20emission%20after%20sensitive%20actions.md)

Lack of event emission after sensitive actions The `_getLatestFundingRate` function of the `FundingRateApplier` contract does not emit relevant events after executing the sensitive actions of setting the `fundingRate`, `updateTime` and `proposalTime`, and transferring the rewards.


1. Recommendation: Consider emitting events after sensitive changes take place, to facilitate tracking and notify off-chain clients following the contract’s activity.
2. Medium Risk severity finding from [OpenZeppelin’s Audit of UMA Phase 4](https://blog.openzeppelin.com/uma-audit-phase-4/)


___
## Slide Screenshot
![077.png](../../images/7.%20Audit%20Findings%20101/077.png)
___
## Slide Text
- 
___
## References
- Youtube Reference
___
## Tags
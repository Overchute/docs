# Protocol Specification

The logic of the Blind Crowdsale Protocol, in generic terms (not just for intellectual property)

---

- A seller offers to provide a public good if a certain amount of money is raised from the public. The seller specifies the offer price and the end date of the crowdsale.
- Members of the public make contributions to the crowdsale.
- The offer price, individual contributions, and total contribution are not disclosed.
- The crowdsale runs until the end date, regardless of the total contributed amount. On this date:
  - If the total contributed amount is less than the offer price,
    - The crowdsale has failed.
    - Each contribution is refunded to its contributor.
    - The seller does not provide the public good.
  - If the total contributed amount is greater than or equal to the offer price:
    - The crowdsale has succeeded.
    - The price is paid to the seller.
    - The seller provides the public good.
  - The overshoot, which is the amount by which the total contributed amount exceeds the offer price is distributed as follows:
    - 10% of the total contributed amount (limited by the available overshoot) is reserved by the platform.\*
    - The remainder of the overshoot is shared equally between the seller and the contributors, with the contributors' share distributed in proportion to each individual contribution.

!!! Note: The amount reserved by the platform serves multiple purposes:

- To fund platform operating costs and profit.
- To fund shared platform ownership by sellers.
- To disincentivise sellers from inflating the true offer price paired with a corresponding shill contribution. This shilling tactic would normally capture some of the contributors' share of the overshoot for the seller. However, with a platform reserve of 10% of the total contributed amount, a shilling would probably decrease a seller's net gain (depending on the total contributed amount, which they can't know in advance). At a platform reserve of 50%, a shilling would always be detrimental to the seller.
  !!!

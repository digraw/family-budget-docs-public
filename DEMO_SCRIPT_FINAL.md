# Family Budget Tracker Demo Capture Script

Objective: capture public screenshots and walkthroughs using synthetic data
only. This script is for media production and does not describe a Google Play
Production release.

## Safety checklist

- Use a dedicated synthetic demo account such as `sarah_demo`.
- Use synthetic statements and transactions only.
- Do not show administrator controls, email addresses, credentials, tokens,
  notification text, real account identifiers, or real balances.
- Capture from the build and distribution channel being described.
- Do not show SMS controls in media described as the Google Play build.
- Review every frame before publishing.

## Preparation

- Record at 1920 by 1080 or another consistent high-resolution size.
- Store source fixtures outside this public repository.
- Save approved output under `assets/web_media/` or `assets/mobile_media/`.
- Start from a clean synthetic household with GBP, USD, and EUR examples.

## Primary workflow

### 1. Create a savings goal

1. Open **Savings Goals**.
2. Create a Physical goal named **Emergency Fund**.
3. Link it to a synthetic savings account.
4. Set a synthetic target and pay-cycle allocation.
5. Pin the goal to the Dashboard.

Suggested narration: "Create a goal and link it to the account that holds the
reserved money."

### 2. Upload a synthetic statement

1. Open **AI Upload**.
2. Select a synthetic budgeting account.
3. Upload a supported synthetic PDF or image.
4. Show indeterminate activity or measured processing stages. Do not invent a
   progress percentage.
5. Review the extracted rows and reconciliation result.
6. Confirm only after the rows have been checked.

Suggested narration: "Upload a statement, review the extracted rows, and
confirm them before they enter the ledger."

### 3. Show the resulting budget views

1. Open the Dashboard and show the selected member filter.
2. Open Savings Goals and show the synthetic goal history.
3. Open Transactions and show stable ordering and category filters.
4. Open Budget and show Ready to Assign and envelope activity.

## Supporting captures

- Dashboard with Safe to Spend and a visible family filter.
- Statement review with synthetic data and no personal identifiers.
- Goal progress and cycle history.
- Combined family view and one synthetic member view.
- Reports with income and expense trends.
- Investments with synthetic holdings and a clearly labelled price refresh.
- Android Settings with optional notification access disclosure.
- Pricing copied from the live application at capture time.

## Final review

- [ ] All data is synthetic.
- [ ] No credentials or private paths are visible.
- [ ] Distribution wording matches the captured build.
- [ ] Google Play is described only as closed testing.
- [ ] No unreleased bank-connection feature appears.
- [ ] Screenshots and narration avoid guarantees or unsupported accuracy claims.

# ShopSphere – Manual Testing Project

Manual functional testing of the e-commerce practice application
**https://practicesoftwaretesting.com**, covering five modules.

## Modules Tested
1. Login & Registration
2. Product Search
3. Shopping Cart
4. Coupon Application
5. Checkout & Payment

## Project Structure
```
ShopSphere-Manual-Testing/
├── README.md
├── Test-Scenarios.xlsx
├── Test-Cases.xlsx
├── Bug-Reports.xlsx
├── Screenshots/
└── Test-Execution-Report.md
```

| File | Description |
|------|-------------|
| `Test-Scenarios.xlsx` | [25] high-level test scenarios mapped to modules and business rules |
| `Test-Cases.xlsx` | [33] detailed test cases with actual results and status, plus a Summary sheet |
| `Bug-Reports.xlsx` | [4] genuine defects with steps, severity, priority and evidence |
| `Screenshots/` | Evidence for defects and key test cases |
| `Test-Execution-Report.md` | Final test summary and conclusions |

## Business Rules Verified
- Email addresses must be unique
- Password must contain at least 8 characters
- Product quantity cannot exceed available stock
- Cart quantity cannot be zero or negative
- Only one coupon per order, and minimum purchase conditions apply
- Final order amount must include the correct discount
- Failed payments must not create successful orders
- Repeated payment submission must not create duplicate orders

## Test Environment
| Item | Details |
|------|---------|
| Application | https://practicesoftwaretesting.com |
| Browser | [Firefox, version] |
| Operating System | [Ubuntu] |
| Test Dates | [25-11-2026] |
| Tester | [Md Khalid Khan] |

## Testing Approach
- Test scenarios were derived from the assignment requirements and business rules.
- Test cases cover positive, negative and boundary conditions.
- All test cases were executed manually and results recorded.
- Defects were logged only when genuinely found and reproducible.
- [Coupon feature was not available on the site, so those cases were marked Blocked.] *(Delete if not applicable.)*

## Results Summary
| Metric | Count |
|--------|-------|
| Total test cases | 33 |
| Passed | 22 |
| Failed | 4 |
| Blocked | 7 |

Key findings: [one or two sentences, e.g. core purchase flow works; defects relate to weak input validation on the registration form.]

See `Test-Execution-Report.md` for the full report.

## Tools Used
Firefox, browser DevTools, Onlyoffice

# Basics of Financial Statements

___

## I. Introduction

___

In this section, I’m going to learn the building blocks of trading by covering the basics of financial accounting and
investment finance.

First, I’ll focus on how to read and understand the three key financial statements: the *balance sheet*, *income
statement*, and *statement of cash flows*. I’ll also learn the difference between *accrual accounting* and *cash-basis
accounting*. Using these statements, I’ll define, calculate, and interpret common financial ratios, including
*liquidity, solvency, activity, profitability, and market price ratios*.

Then I’ll move into investment finance topics, especially the *risk–return relationship and diversification*. I’ll learn
what kinds of risk are actually priced and review major asset pricing models like the *Capital Asset Pricing Model
(CAPM)*, *Arbitrage Pricing Theory (APT)*, and an *empirical asset pricing model*.

After that, I’ll study market mechanics: the types of orders I can place, how the order book works, how orders execute,
and how to measure transaction costs.

Finally, I’ll learn what *hedge funds* are and explore *common trading strategies*. By the end, I should be able to
confidently interpret a company’s financial statements, understand how risk and return connect to asset pricing, and
explain how markets function—including how I can measure my trading costs as an investor.

## II. Introduction to Accounting

___

Accounting is the formal collection, aggregation, analysis, and reporting of a company’s financial and non-financial
information to different end users, with some reporting required regularly (often quarterly). There are three types of
accounting:

- **Financial accounting:** provides information to people outside the company. Its primary purpose is to help outsiders
  assess the company’s performance and financial health for decisions like *valuation* (investors, investment banks) and
  *credit risk* (banks, suppliers). A secondary purpose is to help monitor and evaluate managers and ensure responsible
  use of resources. Financial accounting is communicated through audited financial statements and disclosures in
  quarterly and annual reports.
- **Managerial accounting:** provides information to people inside the company for internal decision-making—like product
  costing, profitability and pricing, product mix decisions, adding or discontinuing products, capacity planning, and
  production volume decisions. It also supports performance evaluation and cost control. These reports aren’t
  standardized and aren’t audited.
- **Tax accounting:** focuses on estimating taxes owed and complying with tax reporting requirements. It’s legal for tax
  reporting to differ from financial reporting because the rules can be different.

In this section, I’m focusing on financial accounting, and a key concept is **accrual accounting**. Instead of recording
transactions when cash moves, accrual accounting records them when the underlying economic event happens. This approach
helps measure earnings and the company’s financial position during a period, and it drives the creation of major
statements like the **income statement** (profit and loss) and the **balance sheet**.

Accrual accounting works mainly through:

- **Revenue recognition:** record revenue when it’s earned (through delivering a product or service), when it can be
  measured, and when its collection is reasonably assured.
- **Matching:** record expenses in the same period as the revenues they help generate, and for other costs, recognize
  them over the period when benefits are received.

The main advantage is that accrual accounting produces timelier and more decision-relevant financial statements. The
main downside is that it relies on judgments and estimates, making it less objectively reliable than cash flows; hence
the idea that cash flow is a fact, while earnings involve opinion. Because of this discretion, financial statements
follow formal rules and are audited by external auditors.

## III. The Balance Sheet

___

The balance sheet presents a company’s financial position at a specific point in time, typically at the end of a quarter
or year. It is made up of three sections: assets, liabilities, and shareholders’ equity, which together show what the
company owns, what it owes, and how much money shareholders have invested in the business.

- **Assets** are resources the company owns that are expected to generate future economic benefits (either higher cash
  inflows or lower cash outflows). Examples include cash and equivalents, inventory, property, plant and equipment, and
  intangible assets such as patents and trademarks. Assets are classified as **current** (expected to be converted to
  cash, sold, or consumed within one year) or **non-current** (expected to be realized after one year).
- **Liabilities** are the company’s economic obligations to outsiders who have claims on the company’s assets. Examples
  include accounts payable, short-term borrowing, and long-term debt. Liabilities are also divided into **current** (due
  within one year) and **non-current** (due after one year).
- **Shareholders’ equity** represents the owners’ claim on the company’s total assets. It includes owners’ invested
  capital and accumulated undistributed profits, known as **retained earnings**.

The balance sheet is called a "balance" sheet because it must always satisfy the fundamental accounting equation:
`Assets = Liabilities + Shareholders’ Equity`. Assets reflect how the company uses resources, while liabilities and
equity reflect where those resources come from, and the two sides must always match. One thing to note is that balance
sheet items are recorded at historical cost, meaning they generally are not updated to current market values.

![Amazon Balance Sheet, end of 2015](assets/images/Amazon%20Balance%20Sheet%202015.jpg)

### Assets

Assets show how a company uses its resources. They are split into:

1. **Current assets** (Amazon, end of 2015)

   Assets are expected to be sold, converted to cash, or consumed within one year. Amazon's current assets are broken
   into investment-related items and operating-related items:

    - **Cash and cash equivalents:** includes currency and bank balances plus highly liquid short-term investments
      (generally with maturities of three months or less when purchased). Amazon reported \\$15.89B.
    - **Marketable securities:** investments such as stocks and bonds that are less liquid than cash but can be
      converted to cash relatively easily. Amazon reported \$3.92B.

   Together, cash/equivalents and marketable securities represent the investment portion of current assets.

    - **Inventories:** includes raw materials, work in progress, and finished goods (though the mix depends on the
      business; service firms may have little finished goods inventory). For Amazon, this likely includes products like
      books and consumer electronics. Amazon reported \$10.24B.
    - **Accounts receivable:** money customers (and other counterparties) owe the company from credit sales; recorded
      when goods/services are delivered but payment hasn’t yet been received. Amazon reported \$6.42B, mostly due from
      customers, vendors, and sellers.

   Adding these components gives Amazon’s total current assets: \$36.47B at the end of 2015, representing cash and
   assets
   expected to become cash within a year.

2. **Non-current assets** (Amazon, end of 2015)

   They represent everything else (held for longer than one year). The largest components are:
    - **Property, plant, and equipment (PP&E):** physical assets used to operate the business—land, buildings,
      machinery, vehicles, office equipment, furniture/fixtures, etc. Amazon reported \$21.84B in PP&E. This includes
      owned buildings/land, assets acquired through build-to-suit financing and capital leases, and equipment such as
      servers, networking equipment, and internal-use software/website development.
    - **Intangible assets:** nonphysical assets such as patents, trademarks, copyrights, goodwill, and brand-related
      value. Amazon reported \$3.76B in goodwill.
    - **Other assets:** additional miscellaneous non-current items totaled \$3.37B.

   These Amazon’s non-current assets totaled \$28.97B at the end of 2015.

With current assets of \$36.47B and non-current assets of \$28.97B, Amazon’s total assets were \$65.44B at the end
of 2015.

### Liabilities

Assets describe how a company uses resources while liabilities describe where a company gets part of its resources
from. Using Amazon’s December 2015 balance sheet, it explains that liabilities are split into current and non-current
based on timing:

1. **Current liabilities** (Amazon, end of 2015)

   Current liabilities are obligations due within one year.
    - **Accounts payable:** amounts owed to vendors and suppliers for goods and services already received; essentially
      purchases made on credit that are expected to be paid within the year. Amazon reported \$20.40B.
    - **Accrued expenses:** expenses incurred but not yet invoiced (or not yet processed), such as wages, interest, and
      utilities. Amazon reported \$10.38B. The annual report notes these are primarily related to items such as
      unredeemed gift cards, leases, asset retirement obligations, current debt, acquired digital media content, and
      other operating expenses.
    - **Unearned revenue:** customer payments received in advance for products or services that have not yet been
      delivered; it remains a liability until the company fulfills its obligation. Amazon reported \$3.12B, mainly tied
      to Amazon Prime membership prepayments and Amazon Web Services.

   Together, these total Amazon’s current liabilities: \$33.90B at the end of 2015.

2. **Non-current liabilities** (Amazon, end of 2015)

   Non-current liabilities are obligations due after one year.
    - **Long-term debt:** loans and bonds due after one year. Amazon reported \$8.23B.
    - **Other long-term liabilities:** Amazon reported \$9.93B, which the annual report describes as primarily long-term
      lease obligations, tax contingencies, and long-term deferred tax liabilities.

   These sum to Amazon’s non-current liabilities: \$18.16B.

   Adding current liabilities (\$33.90B) and non-current liabilities (\$18.16B) gives Amazon’s total liabilities:
   \$52.06B
   at the end of 2015.

Since Amazon’s total assets were previously identified as \$65.44B, liabilities account for \$52.06B of the resources
used. The remaining \$13.37B comes from shareholders’ equity.

### Shareholders’ Equity

Shareholders’ equity (also called net worth) represents the residual ownership interest of shareholders in the company.

Key parts of shareholders’ equity are:

- **Common equity (most important form of equity):** Common shareholders have voting rights and therefore control
  ownership decisions, including electing the board of directors, which appoints senior executives who oversee
  day-to-day operations. Amazon had close to 500 million common shares outstanding at the end of 2015 with a par value
  of \$0.01 each, giving a par-value total of about \$5 million (`500M x 0.01`).
- **Additional paid-in capital (APIC):** Since shares are typically issued at above par value, the premium received is
  recorded as additional paid-in capital. Amazon reported \$13.39B in APIC at the end of 2015.
- **Treasury stock:** Treasury stock is common stock repurchased by the company (or authorized but not sold) and is
  recorded at cost. It is deducted from equity because it has no voting rights and pays no dividends, and it should not
  be counted as shares outstanding. Amazon reported \$1.84B in treasury stock.
- **Preferred stock (preferred equity):** Preferred shareholders have priority over common shareholders for dividends,
  but typically do not have voting rights. Amazon was authorized to issue preferred shares but had issued none by the
  end of 2015, so preferred equity is \$0 on the balance sheet.
- **Retained earnings:** Retained earnings are the cumulative total of undistributed profits over time. Management
  decides how much profit (if any) is paid out as dividends; what is not distributed is added to retained earnings.
  Amazon reported \$2.55B in retained earnings at the end of 2015.
- **Accumulated other comprehensive loss (AOCI):** Amazon also reported \$0.72B of accumulated other comprehensive loss,
  described as unrealized gains and losses on investments in cash, cash equivalents, and marketable securities.

Putting it together: the balance sheet balances. Summing the equity items, Amazon’s total shareholders’ equity is stated
as about \$13.3B. When combined with total liabilities of \$52.06B, the total equals \$65.44B, matching total assets;
demonstrating the balance sheet identity: `Assets = Liabilities + Shareholders’ Equity`.

## IV. The Income Statement

___

The income statement reports a company’s operating results over a period, mainly its revenues and costs. Amazon labels
this statement the "consolidated statements of operations." It is especially important to analysts and investors because
it indicates profitability. In basic terms, `net income (profit or loss) = revenues − expenses`.

**Expensing vs. capitalizing**

Assets and expenses as two ways of describing the use of company resources:

- **Expensing** occurs when the benefits from using resources are realized in the same period. In that case, the full amount
  is recorded as an expense on that period’s income statement.
- **Capitalizing** occurs when the benefits are expected to be realized in future periods. Then the cost is recorded as an
  asset on the balance sheet (rather than fully expensed immediately). Examples include PP&E and purchased
  patents/trademarks.

Capitalized items eventually become expenses through:

- **Amortization:** spreading the asset’s cost over its useful life (e.g., a 5-year life means expensing 1/5 each year).
  The most common form is **depreciation**, which applies to PP&E. 
- **Impairment:** a one-time write-down when the asset’s value is substantially reduced (e.g., due to market forces or
  damage). The write-down amount is recorded as an expense in the period the loss occurs. The key contrast is that
  amortization is systematic and recurring, while impairment is event-driven and non-recurring.

![Amazon Income Statement 2015](assets/images/Amazon%20Income%20Statement%202015.jpg)

### Revenue (the "top line")

The first item on the income statement is revenue/sales, often called the top line. Revenue includes income from the
company’s primary operations, excluding income from things like investments (which appear later in the statement).

For Amazon in 2015:
- **Net product sales:** \$76.27B (sales from Amazon’s own inventory)
- **Net service sales:** \$27.74B (largely Amazon’s share of revenue from third-party seller activity)
- **Total net sales:** \$107.01B

"Net" indicates sales after returns and customer discounts.
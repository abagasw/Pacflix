# PacFlix

PacFlix is a video streaming platform service with various features to help users choose and manage their subscription plans.

## Features

- `check_benefit()`: Display all benefits of each available plan.
- `check_plan(username)`: Display the benefits received and the duration of the subscription for a specific user.
- `upgrade_plan(username, current_plan, new_plan)`: Calculate the final price for upgrading a plan, including a 5% discount if the subscription duration is more than 12 months.
- `pick_plan(new_plan, referral_code)`: For new users, calculate the final price if using a referral code with a 4% discount.

## Table Subscription Plans

The following subscription plans are available:

| Plan           | Price   | Can Stream | Can Download | Has SD | Has HD | Has UHD | Num of Devices | Content                                      |
|----------------|---------|------------|--------------|--------|--------|---------|----------------|----------------------------------------------|
| Basic Plan     | 120000  | Yes        | Yes          | Yes    | No     | No      | 1              | 3rd party movie only                        |
| Standard Plan  | 160000  | Yes        | Yes          | Yes    | Yes    | No      | 2              | Basic Plan Content + Sports (F1, Football, Basketball) |
| Premium Plan   | 200000  | Yes        | Yes          | Yes    | Yes    | Yes     | 4              | Basic Plan + Standard Plan + PacFlix Original Series or Movie |

## User Data

The following users are available:

| Username | Plan           | Duration (months) | Referral Code |
|----------|----------------|-------------------|---------------|
| Shandy   | Basic Plan     | 12                | shandy-2134   |
| Cahya    | Standard Plan  | 24                | cahya-abcd    |
| Ana      | Premium Plan   | 5                 | ana-2f9g      |
| Bagus    | Basic Plan     | 11                | bagus-9f92    |


## Installation

Make sure you have Python installed on your system. You also need to install the `tabulate` library:

```bash
pip install tabulate

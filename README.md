# PacFlix

PacFlix is a video streaming platform service with various features to help users choose and manage their subscription plans.

## Features

- `check_benefit()`: Display all benefits of each available plan.
- `check_plan(username)`: Display the benefits received and the duration of the subscription for a specific user.
- `upgrade_plan(username, current_plan, new_plan)`: Calculate the final price for upgrading a plan, including a 5% discount if the subscription duration is more than 12 months.
- `pick_plan(new_plan, referral_code)`: For new users, calculate the final price if using a referral code with a 4% discount.

## Installation

Make sure you have Python installed on your system. You also need to install the `tabulate` library:

```bash
pip install tabulate

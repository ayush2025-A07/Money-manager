Weekly Budget Planner

A simple, modern, and privacy-focused personal finance planner for
managing weekly budgets, money in, money out, categories, and
checklists.

Overview

Weekly Budget Planner is designed to make everyday money management
simple.

The app helps you quickly answer:

How much money came in this week?

How much did I spend?

How much money is remaining?

Which categories am I spending the most on?

Am I staying within my weekly budget?

What financial tasks do I need to complete?

The application is designed to work 100% locally, without requiring
a bank connection, account, cloud database, or external financial
service.

Features

💰 Money In

Track income such as:

Salary

Allowance

Freelance income

Gifts

Refunds

Other income

Each transaction can contain:

Amount

Description

Category

Date

Optional notes

💸 Money Out

Track everyday expenses such as:

Food

Transport

Bills

Shopping

Entertainment

Education

Health

Savings

Other

Expenses can be edited or deleted at any time.

📊 Weekly Budget

Set spending limits for individual categories.

Example:

Category          Weekly Budget

Food                     ₹1,500
Transport                  ₹800
Entertainment              ₹500
Shopping                 ₹1,000

The app shows:

Budget amount

Amount spent

Remaining amount

Percentage used

Progress toward the budget

If spending exceeds the limit, the app clearly indicates the over-budget
amount.

🏷️ Custom Categories

Create your own categories instead of being restricted to predefined
ones.

You can:

Add categories

Rename categories

Delete categories

Use different categories for different types of transactions

This makes the planner adaptable to different lifestyles and budgets.

✅ Weekly Checklist

Use the built-in checklist for financial and personal tasks.

Examples:

Pay electricity bill

Pay rent

Transfer money to savings

Buy groceries

Review expenses

Cancel unused subscription

Checklist items can be:

Added

Completed

Uncompleted

Edited

Deleted

📅 Weekly Organization

The planner is organized around individual weeks.

The intended week structure is:

Monday → Sunday

Previous weeks can remain available for reviewing historical spending
rather than being automatically deleted.

📈 Financial Summary

The dashboard provides a quick overview of:

Total Money In

Total Money Out

Remaining Balance

Weekly Budget

Budget Usage

Category spending

The goal is to make the most important information visible immediately.

Core Calculations

Remaining Balance

Remaining = Total Money In - Total Money Out

Budget Usage

Budget Used % = Total Spending / Total Budget × 100

Category Remaining

Category Remaining = Category Budget - Category Spending

The application should handle invalid or empty values safely and should
never display values such as NaN, Infinity, or undefined.

Privacy

Privacy is a core part of the application.

The planner is intended to keep financial information local to the
user's device.

The app does not require:

Bank accounts

Payment accounts

Cloud accounts

Financial APIs

Analytics

Advertising

Tracking

Local Data

Persistent application data can be stored using browser/device local
storage technology such as IndexedDB.

Data may include:

Transactions

Categories

Budgets

Checklist items

Weekly records

Application settings

Refreshing or restarting the application should not remove saved data.

Backup & Export

For additional safety, the application can support local:

JSON backup

JSON import

CSV transaction export

These operations should happen directly on the user's device without
sending financial information to an external server.

User Interface

The application follows a simple navigation structure:

Dashboard

Money In

Money Out

Budgets

Checklist

Categories

History

Settings

The interface is designed to be:

Clean

Responsive

Beginner-friendly

Mobile-friendly

Accessible

Fast

Easy to understand

Suggested Dashboard Layout

The main dashboard should prioritize the following information:

┌─────────────────────────────────────────┐
│          WEEKLY BUDGET PLANNER          │
│             Current Week                │
├──────────────┬──────────────┬───────────┤
│   Money In   │  Money Out   │ Remaining │
│    ₹10,000   │    ₹6,250    │  ₹3,750   │
├──────────────┴──────────────┴───────────┤
│          Category Budgets               │
│                                         │
│ Food        ₹1,200 / ₹1,500  ████████   │
│ Transport     ₹600 / ₹800    ███████    │
│ Shopping      ₹900 / ₹1,000  █████████  │
├───────────────────────┬─────────────────┤
│ Recent Transactions   │ Checklist       │
│                       │                 │
│ + Salary     ₹10,000  │ ✓ Pay bill      │
│ - Food          ₹250  │ ✓ Buy groceries │
│ - Bus            ₹80  │ □ Review budget │
└───────────────────────┴─────────────────┘

Technology

The application should be built using modern web technologies.

Recommended stack:

HTML

CSS

JavaScript

IndexedDB for persistent local data

A framework may be used if needed, but the application should remain
lightweight and easy to maintain.

Local-Only Requirement

The following are intentionally excluded:

Bank synchronization

Online account system

Cloud database

Remote financial APIs

Advertising networks

Tracking scripts

Unnecessary third-party services

The application should remain usable without an internet connection
after it has been installed/loaded locally.

Validation & Safety

The application should validate user input before saving it.

Examples:

Amount must be a valid number.

Amount should not be negative where inappropriate.

Transaction descriptions should not be empty.

Category names should not be empty.

Duplicate categories should be prevented where appropriate.

Destructive actions should require confirmation.

Responsive Design

The interface should work comfortably on:

Desktop computers

Laptops

Tablets

Android phones

iPhones

Mobile layouts should avoid unnecessary horizontal scrolling and keep
important actions easy to reach.

Recommended User Workflow

At the beginning of the week

Open the planner.

Check the expected money coming in.

Set category budgets.

Add important checklist tasks.

During the week

Record income.

Record expenses.

Keep categories accurate.

Check budget progress.

Complete checklist tasks.

At the end of the week

Review total income.

Review total spending.

Check remaining money.

Identify categories that exceeded their budgets.

Complete any remaining checklist tasks.

Use the previous week's data to plan the next week.

Project Goals

The project focuses on five principles:

Simple --- Anyone should understand it quickly.

Local --- Financial data stays on the user's device.

Flexible --- Users can create their own categories and budgets.

Useful --- The dashboard should provide actionable information.

Private --- No unnecessary collection or transmission of
financial data.

Future Improvements

Possible future features include:

Monthly overview

Savings goals

Recurring transactions

Recurring bills

Multiple wallets/accounts

Spending trends

Custom dashboard widgets

Advanced charts

Budget templates

Automatic weekly rollover

PWA installation

Offline app caching

Dark mode

Multiple currency support

Local encrypted backups

These features should preserve the application's local-first and
privacy-focused design.

License

Choose a license appropriate for the project before public distribution.

Example:

MIT License

If the project is not intended to be open source, replace this section
with the appropriate proprietary license or usage terms.

Project Status

Status: Active Development

Project: Weekly Budget Planner

Purpose: Simple local personal finance and weekly budget management.

Storage Model: Local-first

Primary Currency: INR (₹)

Data Privacy: No external financial service required

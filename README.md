📱 Nudge — Authentication Prototype (SwiftUI + Xcode)

Nudge is an early-stage prototype for a financial wellness app designed to help college students set financial goals and receive personalized AI-generated budgets.

This repository focuses on the passkey-style authentication system, providing:

Email + password onboarding

Legal name collection

Phone number collection + SMS verification

Local account storage

Animated SwiftUI experience

Real Firebase integrations (SMS 2FA + email verification) are currently in development.

✨ Features
🔐 Passkey-Style Authentication Flow

Sign up with email + password

Enter legal first/last name

Add phone number with auto-formatting

Receive and enter 6-digit verification code

Smooth animated transitions between all steps

Local account persistence using UserDefaults

📱 SMS 2FA (Prototype)

Auto-generated 6-digit verification codes

Simulated SMS delivery printed to Xcode console

“Resend Code” functionality

Full verification logic with error handling

🎨 Modern SwiftUI Interface

Fully animated onboarding sequence

Clean custom components:

FloatingTextField

CodeBox

ScaleButtonStyle

Light/Dark Mode using @AppStorage

Polished UI with gradients, transitions, and tab navigation

🗄 Local Account System (Temporary)

Stores user email, password, name, and phone

Automatically logs in returning users

Supports sign-in, sign-out, and basic account states

🧭 Dashboard & Tabs (UI Prototype)

After authentication, users land on a multi-tab interface:

Home — welcome header, savings actions

Stats — placeholder analytic cards

Goals — placeholder goal tracking

Settings — dark mode toggle, profile display, logout

These views are ready to integrate with the future AI budgeting engine.

🚧 Coming Soon
🔥 Firebase Integration

Real SMS authentication

Real email verification

Secure user storage

Password resets

Cloud user profiles

🤖 AI Budgeting Engine

College students input financial goals

AI generates budgets with spending flexibility

Weekly nudges to improve habits

🏦 Financial Integrations

(Future) Deposit linking

Automated savings

Secure financial data connections (Plaid/Stripe)

🛠 Tech Stack
Technology	Purpose
Swift + SwiftUI	Core app UI + animation
Xcode	iOS development environment
UserDefaults	Temporary storage for prototype
Firebase Authentication (coming soon)	SMS 2FA + email auth
📂 File Structure (Main Components)
NudgeApp.swift

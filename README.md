# SpendSmart

**Topic:** Expense tracker (Flutter group project, KHIT Guntur)

## Description
SpendSmart is an Android app to record and review personal spending. Users
create an account, log in, add expenses through a validated form, search and
filter them, open one for full details, edit or delete it, see totals per
category, and track a monthly budget. Each user has a profile with an editable
details page and a profile picture. Four colour themes (Violet, Green, Black & Orange, Black & White) and light/dark
mode can be chosen from the Appearance screen and are remembered. The currency symbol follows the country
chosen on the profile (symbol only, amounts are not converted). Each expense is
marked Essential, Worth it or Not needed, and weekly and monthly review notes
show what was spent, what was not needed, what was saved, and value for money.

## Screenshots
(Add at least 3: disclaimer, login, list, form with an error, detail, summary, profile)

## Data source
All data is entered by the user and saved on the device with
`shared_preferences`. No API or key is used. Passwords are stored as a hash.

## Run the project
1. Install Flutter 3.35+ (stable), Android Studio and JDK 17.
2. `git clone <repo-url>`
3. `cd spendsmart`
4. `flutter pub get`
5. `flutter run`
6. Tests: `flutter test`
7. Release APK: `flutter build apk --release`

## Team
| Member | Parts built |
|---|---|
| NAME 1 | Models, storage, auth and expense Provider stores, theme, widget test, release APK |
| NAME 2 | Disclaimer, login, sign-up, profile and edit profile screens |
| NAME 3 | Expense list, detail, form and summary screens, README, defect log |

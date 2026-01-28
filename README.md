# MSoC-2025 Internship Report

### Project Overview

**Project:** Migration of Android Client to Kotlin Multiplatform (KMP) <br>
**Project Proposal:** [GSoC Proposal 2025](https://github.com/itsPronay/MSoC-2025/blob/main/google-summer-of-code-proposal-2025.pdf) <br>
**Organization:** Mifos Initiative  
**Official MSoC Duration:** June 2025 - September 2025  

---

## Pre-MSoC Work (March - May 2025)

### Android Client

- [feat: Core/common to KMP #2351](https://github.com/openMF/android-client/pull/2351)
- [feat: Migrate [core/database] to KMP #2354](https://github.com/openMF/android-client/pull/2354)
- [feat - Migrate hilt to koin #2337](https://github.com/openMF/android-client/pull/2337) 
- [Feat - CMP migration of feature/groups #2369](https://github.com/openMF/android-client/pull/2369)
- [Migrate [feature/splash] to cmp #2370](https://github.com/openMF/android-client/pull/2370)
- [feat : Migrate Datatable to cmp #2382](https://github.com/openMF/android-client/pull/2382)
- [Integrate Fastlane and update CI workflows #2484](https://github.com/openMF/android-client/pull/2484)
- [fixed App build issue + network calls #2383](https://github.com/openMF/android-client/pull/2383)
- [fix: Fixed build failure #2329](https://github.com/openMF/android-client/pull/2329)
- [fixed CMP plugin naming convention #2332](https://github.com/openMF/android-client/pull/2332)
- [Removed testing module #2371](https://github.com/openMF/android-client/pull/2371)
- [fix: Login was successful even it is not authenticated #2322](https://github.com/openMF/android-client/pull/2322)
- [fix - Failed to fetch staffs in createNewClient screen #2357](https://github.com/openMF/android-client/pull/2357)
- [fix: Can't create new client #2358](https://github.com/openMF/android-client/pull/2358)
- [Fix: App crash on disburse loan Click #2336](https://github.com/openMF/android-client/pull/2336)
- [[kmp branch] Fixed app crash on loan disbursement screen #2336](https://github.com/openMF/android-client/pull/2336)
- [fix: Replaced hardcoded package name with context.packageName for FileProvider #2335](https://github.com/openMF/android-client/pull/2335)
- [Updated zoom link #2326](https://github.com/openMF/android-client/pull/2326)

### Mifos Mobile

- [refactor: migrate feature/update-password to CMP #2802](https://github.com/openMF/mifos-mobile/pull/2802)
- [refactor: [feature/guarantor] migrate to CMP #2808](https://github.com/openMF/mifos-mobile/pull/2808)
- [feat: [feature/recent_transactions] to CMP #2810](https://github.com/openMF/mifos-mobile/pull/2810)

### Pre-MSoC Impact
- **Key Focus:** Core KMP migration work (database, common modules, features)
- **Foundation Work:** Hilt to Koin migration, build system fixes, CI/CD improvements
- **Impact:** Established groundwork for the full KMP migration during MSoC period

---

## Progress Summary

### June 2025

**Focus:** Initial repository familiarization and CMP migration of feature modules

#### Android Client - Authored PRs

1. **Jun 5** - [feat : Collection sheet migrated to cmp](https://github.com/openMF/android-client/pull/2398)
2. **Jun 8** - [refactor(feature:path-tracking): migrate to CMP](https://github.com/openMF/android-client/pull/2398)
3. **Jun 9** - [savings migration to CMP #2398](https://github.com/openMF/android-client/pull/2398)
4. **Jun 14** - [errorFix: Parameter not null defined as null in savingsDepositScreen #2405](https://github.com/openMF/android-client/pull/2405)
5. **Jun 24** - [fix: failed to create savings account #2412](https://github.com/openMF/android-client/pull/2412)
6. **Jun 27** - [Fix: Failed to activate centers/groups/clients #2419](https://github.com/openMF/android-client/pull/2419)
7. **Jun 27** - [Fix auto-login delay and snackbar message not showing while there is ... #2418](https://github.com/openMF/android-client/pull/2418)

#### Android Client - Reviewed PRs

1. **Jun 10** - [Feat - CMP migration of feature/groups](https://github.com/openMF/android-client/pull/2398)
2. **Jun 11** - [fix: Settings Module Enhancements (Theme Change and Clean Up)](https://github.com/openMF/android-client/pull/2398)
3. **Jun 12** - [feat : Offline Migrate to CMP](https://github.com/openMF/android-client/pull/2398)
4. **Jun 13** - [feat : Migrate Datatable to cmp](https://github.com/openMF/android-client/pull/2398)
5. **Jun 13** - [feat : Document Migrated to CMP](https://github.com/openMF/android-client/pull/2398)
6. **Jun 22** - [refactor(feature:client): migrate to CMP](https://github.com/openMF/android-client/pull/2398)
7. **Jun 22** - [Report migrate to cmp](https://github.com/openMF/android-client/pull/2398)
8. **Jun 25** - [fix: failed to create savings account](https://github.com/openMF/android-client/pull/2412)
9. **Jun 26** - [fix : Group Module (api), added Navigations in Feature Nav Host](https://github.com/openMF/android-client/pull/2398)
10. **Jun 27** - [fix(feature:client): resolve early empty state and dialog layout in identifiers](https://github.com/openMF/android-client/pull/2398)
11. **Jun 27** - [fix(feature:client): fix signature reset issue and enforce white canvas background](https://github.com/openMF/android-client/pull/2398)
12. **Jun 27** - [fix : UpdateServerConfig (navigation,ui)](https://github.com/openMF/android-client/pull/2398)
13. **Jun 28** - [fix : Create Client](https://github.com/openMF/android-client/pull/2398)
14. **Jun 29** - [fix : SavingsAccount With Drawl and Saving Account Deposit screens not loading Serializable error](https://github.com/openMF/android-client/pull/2398)

#### Mifos Mobile - Reviewed PRs

1. **Jun 25** - [refactor: radio button component](https://github.com/openMF/mifos-mobile/pull/2867)
2. **Jun 29** - [feat: onboarding language screen ui and viewModel](https://github.com/openMF/mifos-mobile/pull/2867)

#### Mobile Wallet - Reviewed PRs

1. **Jun 17** - [[MW-225] feat(auth): Implement full Sign In & Sign Up flow with validation](https://github.com/openMF/mobile-wallet/pull/1925)
2. **Jun 28** - [Refactor MakeTransferScreen to improve account selection using BottomSheetScaffold](https://github.com/openMF/mobile-wallet/pull/1925)

---

### July 2025

**Focus:** Desktop build fixes, KMP implementation cleanup, and UI migration

#### Android Client - Authored PRs

1. **Jul 2** - [fix: cmp-desktop does not build #2427](https://github.com/openMF/android-client/pull/2427)
2. **Jul 7** - [Final cleanup of kmp-impl branch #2431](https://github.com/openMF/android-client/pull/2431)
3. **Jul 7** - [removed todo in clients/centers to prevent app crash #2432](https://github.com/openMF/android-client/pull/2432)
4. **Jul 8** - [Fix : Can't Load savings Account summary because of typeError #2434](https://github.com/openMF/android-client/pull/2434)
5. **Jul 28** - [Fix: FOREIGN KEY constraint failure when saving ChargesEntity to DB #2442](https://github.com/openMF/android-client/pull/2442)

#### Android Client - Reviewed PRs

1. **Jul 3** - [feat: Refactor SignatureScreen to CommonMain using Compose-Signature Library](https://github.com/openMF/android-client/pull/2431)
2. **Jul 9** - [fix(feature:client): fix stuck loading & empty state for charges UI](https://github.com/openMF/android-client/pull/2434)
3. **Jul 12** - [refactor(feature:client): merge ViewModels, add charge validation, fix empty chargeOptions crash](https://github.com/openMF/android-client/pull/2434)
4. **Jul 16** - [fix: Update server config not working](https://github.com/openMF/android-client/pull/2434)

#### Mifos Mobile - Reviewed PRs

1. **Jul 2** - [Sign in ui and view model](https://github.com/openMF/mifos-mobile/pull/2867)
2. **Jul 7** - [feat: otp authentication ui and viewModel](https://github.com/openMF/mifos-mobile/pull/2867)
3. **Jul 8** - [feat: recover password ui and viewModel](https://github.com/openMF/mifos-mobile/pull/2867)
4. **Jul 9** - [feat: set new password ui and viewModel](https://github.com/openMF/mifos-mobile/pull/2867)
5. **Jul 21** - [feat: savings account ui & viewModel](https://github.com/openMF/mifos-mobile/pull/2867)
6. **Jul 25** - [Indefinite snackBar fix #2867](https://github.com/openMF/mifos-mobile/pull/2867)
7. **Jul 30** - [refactor: bound dashboard services with respective screens](https://github.com/openMF/mifos-mobile/pull/2867)

---

### August 2025

**Focus:** KMP merge to development, UI enhancements, and feature implementations

#### Android Client - Authored PRs

1. **Aug 4** - [Fixed Client DataTable More Info view #2444](https://github.com/openMF/android-client/pull/2444)
2. **Aug 5** - [Ktorfit Cleanup: Remove Duplicates and Align DI Configuration #2446](https://github.com/openMF/android-client/pull/2446)
3. **Aug 6** - [Merge kmp-impl into development #2447](https://github.com/openMF/android-client/pull/2447)
4. **Aug 13** - [fix scrolling in landscape mode #2451](https://github.com/openMF/android-client/pull/2451)
5. **Aug 26** - [feat: Client savings accounts UI #2472](https://github.com/openMF/android-client/pull/2472)
6. **Aug 28** - [Client Loan accounts UI #2477](https://github.com/openMF/android-client/pull/2477)
7. **Aug 31** - [feat: Client identities list screen with new UI #2483](https://github.com/openMF/android-client/pull/2483)

#### Android Client - Reviewed PRs

1. **Aug 3** - [fix(feature:path-tracking, core:network): fix bugs in path tracker fe...](https://github.com/openMF/android-client/pull/2441)
2. **Aug 4** - [498. Remove the visible DialogBox after Identifier creation submission #2445](https://github.com/openMF/android-client/pull/2445)
3. **Aug 8** - [fix(feat:client-identifiers): fix dialogue visibility issues for creating client identifiers #2449](https://github.com/openMF/android-client/pull/2449)
4. **Aug 27** - [Client Profile Notes #2471](https://github.com/openMF/android-client/pull/2471)

---

### September 2025

**Focus:** New UI implementations, feature enhancements, and code reviews

#### Android Client - Authored PRs

1. **Sep 2** - [feat: Client upcoming charges UI #2488](https://github.com/openMF/android-client/pull/2488)
2. **Sep 4** - [feat: Share accounts UI #2495](https://github.com/openMF/android-client/pull/2495)

#### Mobile Wallet - Authored PRs

1. **Sep 6** - [Feat: Update Accounts order by Active state – Show active accounts at top in ascending order #1922](https://github.com/openMF/mobile-wallet/pull/1922)
2. **Sep 8** - [Disable Continue button until Amount & Description is not empty #1925](https://github.com/openMF/mobile-wallet/pull/1925)

#### Android Client - Reviewed PRs

1. **Sep 1** - [feat: Client identities list screen with new UI #2483](https://github.com/openMF/android-client/pull/2483)
2. **Sep 1** - [MIFOSAC-573 Client Recurring Deposit Accounts #2486](https://github.com/openMF/android-client/pull/2486)
3. **Sep 1** - [Client Loan accounts UI #2477](https://github.com/openMF/android-client/pull/2477)
4. **Sep 2** - [MIFOSAC-572 Fixed deposit account #2489](https://github.com/openMF/android-client/pull/2489)
5. **Sep 3** - [fix notes screen issue #2485](https://github.com/openMF/android-client/pull/2485)
6. **Sep 3** - [MIFOSAC-589 Fix: Client Identity status is showing not found always. #2492](https://github.com/openMF/android-client/pull/2492)
7. **Sep 5** - [feat: Share accounts UI #2495](https://github.com/openMF/android-client/pull/2495)
8. **Sep 5** - [feat: Client upcoming charges UI #2488](https://github.com/openMF/android-client/pull/2488)
9. **Sep 10** - [Client – Upload & Manage Signature #2498](https://github.com/openMF/android-client/pull/2498)
10. **Sep 10** - [feat : New Loan Account – Charges Step Implementation #2497](https://github.com/openMF/android-client/pull/2497)
11. **Sep 10** - [feature(savings): new savings account, details step impl #2500](https://github.com/openMF/android-client/pull/2500)

## Technical Skills Demonstrated

- Kotlin Multiplatform (KMP/CMP) architecture
- Jetpack Compose for UI development
- Dependency Injection (Koin migration from Hilt)
- Network layer (Ktorfit)
- Database management (Room)
- Cross-platform mobile development
- Git workflow and collaborative code review practices
- Bug diagnosis and resolution

---

## Impact

After my migration of the Android client project, this project enables
- **Code Sharing:** Shared business logic across Android, iOS, web and Desktop platforms
- **Maintainability:** Single codebase for core features reduces maintenance overhead
- **Scalability:** Easier to add new platforms in the future
- **Performance:** Improved app stability through bug fixes and refactoring

---

## Conclusion

My journey with the Mifos Initiative began in March 2024, even before the official MSoC period. Since then, I have been a regular contributor to the Mifos Field Officer application, with over 80 commits, making me one of the top three contributors to the project. Through this early and consistent involvement, I gained deep insights into cross-platform mobile development, modern Android architecture, and large-scale codebase migration, along with a strong understanding of collaborative development in open-source environments.

I had a great experience throughout this four-month-long program. I received tremendous support from the community as well as my mentor, Rajan Maurya, during this three-month journey. I would also like to thank Ed Cable for his outstanding support. The weekly check-ins were excellent. I had a great opportunity to bond with the community, as well as solve some problems that I encountered in the interim. I learned and grew a great deal as a result of this experience. It would be my pleasure to contribute to this organization in the future, as well as to assist new contributors to get started in this community.


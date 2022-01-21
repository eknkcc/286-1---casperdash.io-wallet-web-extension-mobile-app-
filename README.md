Grant Proposal | 286-1---casperdash.io-wallet-web-extension-mobile-app
------------ | -------------
Milestone Title | Web Wallet
Reviewer | Ekin Keçeci <ekin@ekonteknoloji.com>

# Milestone Details

## Details & Acceptance Criteria

**Details of what will be delivered in milestone:**

- Control of Integration with Casper Singer
- Control of Dashboard
  - View CSPR balance
  - Send/Receive CRPR
  - CRPS price chart
- Control of Tokens
  - View token info/balance
  - Send/Receive tokens
  - Add custom token by contract hash
- Control of History
  - View transfer transactions history
- Control of Keys Manager
  - Deploy keys manager contract
  - Edit account weight
  - Edit Deployment/ Key management threshold
  - Add new associated key
  - Edit associated account weight
- Control of Stacking (Stacking CSPR)  
   
**Acceptance criteria:**

- Release a stable version working on mainnet with feature 

## Milestone Submission

The following milestone assets/artifacts were submitted for review:

Repository | Revision Reviewed
------------ | -------------
https://github.com/CasperDash/casperdash-client/tree/v1.0.0 | ade2cbf

# Install & Usage Testing Procedure and Findings

Pages on the website are working properly :

## Overall Impression of usage testing

The reviewer was unable to build and run the project following the instructions provided due to a target error in the lib file.
But apart from this error the documentation also provides adequate installation/execution instructions for different scenarios.
The reviewer thinks that the project functionality will meet the acceptance criteria once the bugs are fixed.

Requirement | Finding
------------ | -------------
Project builds without errors | FAIL
Documentation provides sufficient installation/execution instructions | PASS
Project functionality meets/exceeds acceptance criteria and operates without error | FAIL

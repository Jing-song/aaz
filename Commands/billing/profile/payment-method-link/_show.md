# [Command] _billing profile payment-method-link show_

Show a payment method linked with a billing profile.

## Versions

### [2023-04-01](/Resources/mgmt-plane/L3Byb3ZpZGVycy9taWNyb3NvZnQuYmlsbGluZy9iaWxsaW5nYWNjb3VudHMve30vYmlsbGluZ3Byb2ZpbGVzL3t9L3BheW1lbnRtZXRob2RsaW5rcy97fQ==/2023-04-01.xml) **Stable**

<!-- mgmt-plane /providers/microsoft.billing/billingaccounts/{}/billingprofiles/{}/paymentmethodlinks/{} 2023-04-01 -->

#### examples

- Show profile payment method link
    ```bash
        billing profile payment-method-link show --billing-account-name name --billing-profile-name name --payment-method-name name
    ```

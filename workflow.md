# DMANDATE Workflow

## Program Information
- **Program ID**: 8kHcaQxyxKFAK6t8KRKDUmn9FaHGZi8kwomBaSDVc4X1
- **Network**: Solana Devnet
- **Wallet**: 7C2NKxuBV84JTRHonk64iCR6PV2ryKSNyE178x5GSYit

## Commands

### Register User
```bash
yarn dev register-user DEEPANSHU -s
```

### Create Mandate
```bash
yarn dev create-mandate <TARGET_ACCOUNT> <SPL_TOKEN> <AMOUNT> <FREQUENCY> "Name" "Description"

# Example:
yarn dev create-mandate <TARGET_ACCOUNT> <SPL_TOKEN> 1 10 "Netflix" "Monthly subscription"
```

### Get Mandate
```bash
yarn dev get-mandate <MANDATE>
```

### Get User Subscriptions
```bash
yarn dev get-user-subscriptions
```

### Cancel Mandate
```bash
yarn dev cancel-mandate <MANDATE>

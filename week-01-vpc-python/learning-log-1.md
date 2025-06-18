## ✅ June 18, 2025 — AWS CLI Setup on WSL

Today I successfully installed and configured the AWS Command Line Interface (CLI) inside my WSL Linux environment. This was an important step for managing AWS resources directly from my terminal and scripting future workflows.

### 🔧 What I Did
- Downloaded the AWS CLI v2 installer using `curl`
- Installed `unzip` and extracted the CLI package
- Ran the installation script using `sudo ./aws/install`
- Verified the installation with:
  ```bash
  aws --version
  ```
  
Output confirmed AWS CLI v2 was installed correctly.

#### Configured AWS CLI using:

```bash

aws configure
```

I entered my IAM user credentials, set a default region, and chose JSON as the default output format.

#### Tested my setup with:

```bash
aws s3 ls
```

Command returned my current S3 buckets (or confirmed none existed).

### 📚 Skills Practiced
- Installing and managing CLI tools in WSL (Linux)

- Understanding the difference between Windows CLI and WSL environments

- Using secure credentials for AWS CLI configuration

- Verifying setup with real AWS service commands
  

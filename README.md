# post-install-config

# osTicket Post-Install Configuration Guide (Windows)

This guide provides comprehensive post-install configuration instructions for osTicket on a Windows system. Follow these steps to ensure your system is secure and operational.

---

## Step 1: Secure Your Installation

1. **Remove the Setup Directory**:
   After installation, remove the `setup` folder to prevent unauthorized access.

   ### Command (Windows Command Prompt):
   ```cmd
   del C:\xampp\htdocs\osTicket\upload\setup

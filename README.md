# OneDriveQuotaManager

This PowerShell script allows administrators to efficiently manage storage quotas for OneDrive sites in a SharePoint environment. It simplifies the process of connecting to the SharePoint admin center, retrieving OneDrive URLs, and updating storage quotas.

## Features

- Connects to the SharePoint admin center.
- Retrieves all OneDrive URLs associated with users.
- Prompts for storage quota and warning levels.
- Updates the storage settings for each OneDrive site.

## Prerequisites

- PowerShell installed on your machine.
- SharePoint Online Management Shell module.
- Appropriate permissions to manage SharePoint Online sites.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/RapidScripter/OneDriveQuotaManager.git
   cd OneDriveQuotaManager

2. Open PowerShell and run the script:
   ```powershell
   .\OneDriveQuotaManager.ps1

3. Follow the prompts:
- Enter the SharePoint admin center URL (e.g., https://example.sharepoint.com).
- Enter the desired OneDrive storage quota in MB.
- Enter the OneDrive storage quota warning level in MB.

4. The script will update the specified settings for all OneDrive sites and display confirmation messages in the console.

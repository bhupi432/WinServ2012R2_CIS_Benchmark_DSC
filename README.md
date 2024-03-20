Host-Based Assessment Automation Script

Purpose:
This script automates the enforcement of security configurations based on the CIS Benchmark for Windows Server 2012 R2 version 1.0.0. Leveraging PowerShell Desired State Configuration (DSC), it ensures consistent application of security policies across systems, enhancing system security and reducing manual effort.

How to Run:

    Ensure PowerShell script execution is allowed. You can do this by running: Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process -Force.
    Execute the script: .\CIS_Benchmark_WindowsServer2012_R2_v1_0_0.ps1. This will generate Managed Object Format (MOF) files in the current directory.

Regulations for the Script:

    Ensure proper permissions are set for executing PowerShell scripts.
    Run the script with appropriate privileges (preferably as an administrator) to apply system configurations.
    Review the output carefully to address any identified security concerns.
    Customize script functionalities as per specific security requirements or environment configurations.

Do's:

    Execute the script on Windows Server 2012 R2 systems.
    Regularly update and maintain the script according to evolving security standards and system changes.
    Ensure necessary backups are taken before applying any configuration changes suggested by the script.

Don'ts:

    Do not execute the script on unsupported Windows Server versions.
    Avoid making blind changes without understanding the implications of suggested configurations.
    Do not share sensitive output or system information from the script output publicly.

Benefits of the Script:

    Time Efficiency: Reduces the time required for manual security configuration by automating various checks.
    Consistency: Ensures consistent application of security configurations across Windows Server systems.
    Accuracy: Minimizes human errors associated with manual configuration enforcement.
    Enhanced Security: Helps identify and address potential security vulnerabilities promptly.

Additional Notes:

    The script requires PowerShell version 5.1 or later.
    Ensure DSC modules (AuditPolicyDsc, SecurityPolicyDsc, NetworkingDsc, PSDesiredStateConfiguration) are installed. You can check and install them using PowerShell commands.
    Exercise caution while implementing changes suggested by the script, especially in production environments.


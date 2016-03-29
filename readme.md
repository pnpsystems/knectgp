Read Me

To be established;

Contents
COMPUTER CONFIGURATION
    JAVA
        DISABLE AUTOUPDATE FOR JAVA (32-BIT WINDOWS)
        DISABLE AUTOUPDATE FOR JAVA (64-BIT WINDOWS)
USER CONFIGURATION
    WINDOWS 10
        SETTINGS – PERSONALISATION – COLOURS
            Specify control of automatic accent colour picking
            Enable Show Colour on Start, Taskbar and Action Center
            Enable Show Colour on Title Bar

Group Policy Reference
    Computer Configuration
        Java
            Disable AutoUpdate for Java (32-bit Windows)
                Requirement: 32-bit Windows
                This setting disables Auto Update for Java.

                Not Configured stops enforcing the policy.
                Enabled: disables Java Auto Update.
                Disabled: enables Java Auto Update.

                Please note, this policy only affects 32-bit Windows.
                
            Disable AutoUpdate for Java (64-bit Windows)
                Requirement: 64-bit Windows
                This setting disables Auto Update for Java.

                Not Configured stops enforcing the policy.
                Enabled: disables Java Auto Update.
                Disabled: enables Java Auto Update.

                Please note, this policy only affects 64-bit Windows.
                
    User Configuration
        Windows 10
            Settings – Personalisation – Colours
                Specify control of automatic accent colour picking
                    Requirement: Windows 10 TH2/Server 2016 TP4
                    Not configured will not remove the policy. 
                        It simply stops enforcing.

                    Enabled turns on the setting in Settings>Personalisation>Colours.
                    Disabled turns it off.
                    
                Enable Show Colour on Start, Taskbar and Action Center
                    Requirement: Windows 10 TH2/Server 2016 TP4
                    Not configured will to remove the policy.
                        It simply stops enforcing.

                    Enabled turns on the setting to Show Colours on Start, Taskbar and Action Center, but it doesn't affect the Title Bars.
                    Disabled turns it off.
                    
                Enable Show Colour on Title Bar
                    Requirement: Windows 10 TH2/Server 2016 TP4
                    Not configured will not remove the policy.
                        It simply stops enforcing.

                    Enabled turns on the setting to Show Colours on the Title Bars.
                    Disabled turns it off.

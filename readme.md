#Group Policy Reference

1. ##COMPUTER CONFIGURATION

    1.1 Java

        1.1.1 DISABLE AUTOUPDATE FOR JAVA (32-BIT WINDOWS)
    
        1.1.2 DISABLE AUTOUPDATE FOR JAVA (64-BIT WINDOWS)

2. ##USER CONFIGURATION
    
    2.1 WINDOWS 10

        2.1.1 SETTINGS – PERSONALISATION – COLOURS
        
            2.1.1.1 Specify control of automatic accent colour picking
            
            2.1.1.2 Enable Show Colour on Start, Taskbar and Action Center
            
            2.1.1.3 Enable Show Colour on Title Bar


##Computer Configuration

    1.1 ##Java
    
        1.1.1 Disable AutoUpdate for Java (32-bit Windows)
        
            Requirement: 32-bit Windows
            
            This setting disables Auto Update for Java.
            Not Configured stops enforcing the policy.
            Enabled: disables Java Auto Update.
            Disabled: enables Java Auto Update.
        
            Please note, this policy only affects 32-bit Windows.
            
        1.1.2 Disable AutoUpdate for Java (64-bit Windows)
        
            Requirement: 64-bit Windows
            
            This setting disables Auto Update for Java.
            Not Configured stops enforcing the policy.
            Enabled: disables Java Auto Update.
            Disabled: enables Java Auto Update.
            
            Please note, this policy only affects 64-bit Windows.
            
##User Configuration

    2.1 Windows 10
    
        2.1.1 Settings – Personalisation – 
        
            2.1.1.1 Specify control of automatic accent colour picking
            
                Requirement: Windows 10 TH2/Server 2016 TP4
                
                Not configured will not remove the policy. 
                    It simply stops enforcing.
                Enabled turns on the setting in Settings>Personalisation>Colours.
                Disabled turns it off.
                    
            2.1.1.2 Enable Show Colour on Start, Taskbar and Action Center
            
                Requirement: Windows 10 TH2/Server 2016 TP4
                
                Not configured will to remove the policy.
                    It simply stops enforcing.
                Enabled turns on the setting to Show Colours on Start, Taskbar and Action Center, but it doesn't affect the Title Bars.
                Disabled turns it off.
                
            2.1.1.3 Enable Show Colour on Title Bar
            
                Requirement: Windows 10 TH2/Server 2016 
                
                Not configured will not remove the policy.
                        It simply stops enforcing.
                Enabled turns on the setting to Show Colours on the Title Bars.
                Disabled turns it off.

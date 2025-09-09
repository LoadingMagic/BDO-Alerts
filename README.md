# BDO-Alerts
BLACK DESERT ONLINE DISCORD BOT

https://bdoalerts.xyz

🌍 Multi-Region Support  
Full support for NA, EU, Console NA, and Console EU servers with region-specific boss timers and alerts.  

💥 Custom Role Management  
Create custom roles with emoji reactions, descriptions, and individual messages per role for organized server management.  

🎮 Live Boss Tracking  
Real-time world boss spawns, guild boss scheduling, and comprehensive timer system for all game resets.  

🎟️ Coupon System  
Automated coupon tracking with expiry dates, redeem links, and auto-refresh functionality.  

🌟 Welcome Customization  
Fully customizable welcome messages with titles, descriptions, banners (WEBP, PNG, JPEG), and footers.  

🔧 Easy Setup  
Guided server setup that automatically creates channels, roles, alerts, and default messages with backup/restore functionality.  

📋 Complete Command List  

🔧 Setup & Configuration (ADMINISTRATOR-ONLY)  
!setup - Initial server setup with channels, roles, default messages, alerts, and more.  
!config - View/Modify bot settings.  
!status - Show bot status, statistics and configuration health.  
!restore - Restore server configuration to the latest backup.  
!migratedb - Update database save so restore point is up to date. (NOT REQUIRED!)  

🌍 Multi-Region Support (NEW!)  
!region - View or change the BDO server region (NA, EU, Console NA, Console EU).  
!testregion <region> - Test boss data fetching for a specific region.  

💥 Role Management (ADMINISTRATOR-ONLY, INDIVIDUAL MESSAGES PER ROLE!)  
!addrole - Create custom roles with emoji reactions and descriptions.  
!removerole - Remove a custom role and its message.  
!refreshroles - Update all role messages & member counts in the role selection channel.  
!listroles - List all custom roles in the channel. (MAX 10 PER SERVER)  

🌟 Welcome Customization (ADMINISTRATOR-ONLY)  
!welcome - View welcome settings and preview your custom title and footer.  
!welcome title <text> - Change welcome title text.  
!welcome description <text> - Update description text.  
!welcome banner <url> - Set custom banner image (WEBP, PNG, JPEG).  
!welcome footer <text> - Change footer text.  
!welcome reset - Restore to default settings.  
!welcome preview - Preview current saved settings.  
!welcome update - Recreate welcome message and banner.  

🎮 Game Information (ADMINISTRATOR & USER)  
!gboss - Guild boss countdown timer with alerts.  
!gbossconfig - Configure guild boss Day/Time.  
!bosses - Current world boss spawns & timers.  
!timers - Game reset timers (Day/Night cycle, Imperial delivery reset, Bartering reset, etc.).  
!stopguildboss - Stop active guild boss event.  

🎟️ Coupon System (ADMINISTRATOR & USER)  
!coupons - Lists all coupon commands with redeem links.  
!couponlist - Detailed list of all codes with expiry dates.  
!refreshcoupons - Force refresh coupon channel.  

🧹 Cleanup & Maintenance (ADMINISTRATOR)  
!cleanup - Clean old messages (ALL TYPES).  
!cleancoupons - Clean ONLY coupon messages in the coupons channel.  
!cleanbossalerts - Clean old boss alerts if duplicated.  

🔥 Slash Command Management (ADMINISTRATOR-ONLY)  
!syncslash - Sync slash commands to this server (instant).  
!listslash - List all registered slash commands.  
!syncglobal - Sync commands globally (1 hour).  
!clearslash - Clear slash commands for this server.  

ℹ️ General  
Use !help for details.  
Use /ping for admin test.  

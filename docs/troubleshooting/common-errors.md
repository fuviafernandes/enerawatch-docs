# Troubleshooting: Common Errors in EneraWatch

**Content:** Frequent platform and sensor issues  
**Task:** Identify and resolve asset-related problems  
**Role:** Field technician, maintenance engineer  
**Tool:** EneraWatch Web Dashboard + IoT Gateway

---

##  Error: Asset shows as “Offline”

**Possible Causes:**
- IoT gateway is disconnected or powered off
- Sensor device ID is incorrectly registered
- Internet/network issues at the plant site

**Resolution:**
1. Check physical connection and power supply of the gateway
2. Confirm that the Device ID matches the installed hardware
3. Restart the gateway and wait for auto-sync (2–5 min)
4. Refresh the dashboard or check status logs

---

##  Error: “No Data” or “Zero Output”

**Possible Causes:**
- Sensor is misaligned or malfunctioning
- The asset is in downtime or under maintenance
- Time range filter is incorrect

**Resolution:**
1. Inspect the asset physically if safe to do so
2. Adjust the time range to “Last 24h” and refresh
3. Check logs in the **Monitoring > Asset Logs** section

---

##  Error: “Access Denied” when viewing site

**Possible Causes:**
- User lacks permission to access the selected plant
- Asset group is restricted to administrators

**Resolution:**
1. Go to **Settings > User Management**
2. Request admin to assign the correct access level
3. Logout and log back in to refresh permissions

---

 **Next guide:** [FAQs – Common User Questions](../faq/general-questions.md)


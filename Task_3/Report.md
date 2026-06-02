Task 3 – Basic Vulnerability Scan on My PC

Objective:
To perform a basic vulnerability assessment using Nessus Essentials and identify security issues on the local system.

Tool Used:
Nessus Essentials

Target:

* 127.0.0.1 (Localhost)

Scan Summary:
The vulnerability scan was successfully performed on the local machine using Nessus Essentials. The scanner detected several informational findings related to service detection, web server information, and host configuration.

What were my Findings:

* Total Findings: 13
* Severity Levels:

  * Critical: 0
  * High: 0
  * Medium: 0
  * Low: 0
  * Informational: 13

Sample Findings:

1. Service Detection

   * Description: Nessus identified running network services on the target system.
   * Risk: Informational
   * Recommendation: Review exposed services and disable unnecessary services.

2. Web Server Information

   * Description: Web server details were detected.
   * Risk: Informational
   * Recommendation: Minimize information disclosure and keep services updated.

3. Port Scanner Detection

   * Description: Open ports and accessible services were identified.
   * Risk: Informational
   * Recommendation: Restrict access to unnecessary ports using firewall rules.

What are my remediation recommendations:

* Keep the operating system updated.
* Remove unused services.
* Close unnecessary open ports.
* Regularly perform vulnerability assessments.
* Apply security patches promptly.

Conclusion:
The Nessus vulnerability scan was successfully completed on the local machine. The scan identified multiple informational findings that provide visibility into running services and exposed resources. Regular vulnerability assessments help improve overall system security and reduce potential attack surfaces.

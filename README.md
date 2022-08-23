# Security-Scanning
## Test scenario  
`Environment:` Test Lab (VM)  
`Scan tool:` OpenVAS/GVM  
`Report tool:` OpenVAS Reporting  
`PenTest VM:` Kali Linux  
`Target VM:` Metasploitable2 Linux  
## Scanning Method
### Vulnerability Scanning method  
For this scenario, the automated test scans were used to assess internal systems of the targeted host which generated a vulnerability scanning report that includes information about the severity of the vulnerability and how it can be exploited.
## OpenVAS/GVM configs
### Target host config
![GVM_target_host_config](https://user-images.githubusercontent.com/95695894/186097103-7300223f-dd2d-49ce-862d-d9c00e9ff480.PNG)  
### Scanning config
![GVM_scan_configs](https://user-images.githubusercontent.com/95695894/186097241-ae5469f9-4826-4a65-80cf-51f755af0812.PNG)  
### Scan task status
![GVM_security_scan_task](https://user-images.githubusercontent.com/95695894/186097313-03e84635-f434-4535-bf6f-c2d277437d2a.PNG)

## Results
Scan results on OpenVAS/GVM tool  

![GVM_results_13_aug_2022](https://user-images.githubusercontent.com/95695894/186097553-4cbf8c96-a622-43f5-884e-bc28ba5a8959.PNG)
## Reports & Summary  
Additional OpenVAS Reporting tool was installed to convert OpenVAS XML into a readable and presentable report as shown below. 

![image](https://user-images.githubusercontent.com/95695894/186098681-ce8fcd52-88c0-482f-bc4e-4241a9e05fad.png)  
![image](https://user-images.githubusercontent.com/95695894/186099650-44271709-0473-476d-9e35-93d26860a350.png)

`RAW report link:` https://github.com/GopiNJ/ACE-Security-Scanning/blob/main/reports/report-a701f3ec-3055-4353-8b58-faee764ab6bf.xml  
`Formated report link:` https://github.com/GopiNJ/ACE-Security-Scanning/blob/main/reports/openvas_report.xlsx

## Sample findings and remediations
5 common types of vulnerabilities stating type, severity and remediation steps required to fix listed below for reference purpose.  

`Sample 1`
![image](https://user-images.githubusercontent.com/95695894/186101919-6c692033-20ba-42e4-a064-68fb11adfb7d.png)
`Sample 2`
![image](https://user-images.githubusercontent.com/95695894/186102048-b92a896d-7934-4b73-8929-e3aabe745de8.png)
`Sample 3`
![image](https://user-images.githubusercontent.com/95695894/186102171-cdfbe719-c777-486a-8c03-7d55ecfc8a05.png)
`Sample 4`
![image](https://user-images.githubusercontent.com/95695894/186107645-7c7704b2-a24d-468f-83ac-6a8a62fdec41.png)
`Sample 5`
![image](https://user-images.githubusercontent.com/95695894/186107800-e61e75d5-e787-4452-99ed-596f5e537fb3.png)

## References
https://www.ceos3c.com/security/install-openvas-kali-linux/  
https://cve.mitre.org/  
https://docs.rapid7.com/metasploit/metasploitable-2-exploitability-guide/  
https://www.openvas.org/  


# Vulnerability Scanning with Nikto

## Objective
To perform vulnerability scanning on a web server using Nikto.

## Tool Used
- Nikto
- XAMPP
- Strawberry Perl

## Target
http://127.0.0.1

## Commands Used

```cmd
perl nikto.pl -h http://127.0.0.1
```

```cmd
perl nikto.pl -h http://127.0.0.1 -output nikto_scan_results.txt
```

## Findings
- Missing security headers
- Apache version disclosure
- Directory indexing detected

## Conclusion
Nikto successfully scanned the localhost web server and identified possible security weaknesses.
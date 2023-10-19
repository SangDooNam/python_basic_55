[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/B7yRh0bR)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12469002&assignment_repo_type=AssignmentRepo)
**Title:** *Pytech's Data Dilemma*

*The Birth of Pytech*

In the heart of Silicon City, a company known as Pytech emerged as a pioneer in data-driven solutions. Founded by a team of dedicated engineers, Pytech revolutionized the way businesses managed and analyzed their data. Their flagship product, "DataWiz," was renowned worldwide for its cutting-edge capabilities.

*The Mysterious Data Leak*

One fateful day, Pytech's chief data scientist, Emily, received an urgent message. It seemed that a massive data leak had occurred, and sensitive client information was at risk. The challenge ahead was to identify the culprit and minimize the damage.

**Task 1:**

Create a function `check_time` that will take an argument `breach_time` and print if the data breach occurred outside or during the business hours.

- Your result should look like this:

```python
check_time(14)
check_time(19)

Breach time: 14 - Data breach occurred during business hours.

Breach time: 19 - Data breach occurred outside business hours.
```

*Data Anomalies*

To identify the data thief, Pytech's security team decided to scrutinize access logs for unusual patterns. They discovered a series of anomalous login attempts.

**Task 2:**

Create a function `check_login` that will take a list as argument `login_attempts` and check if there are more than three failed login attempts in a row.

- Your result should look like this:

```python

login_attempts_1 = [False, False, False, False, True, True, False, False]

login_attempts_2 = [False, False, True, False, True, True, False, False]

check_login(login_attempts_1)
check_login(login_attempts_2)

More than three consecutive failed login attempts.

No more than three consecutive failed login attempts.
```

*Suspicious User Activity*

Further investigation revealed that a user, Alex, had accessed the system during the breach. The security team needed to confirm if Alex's access was legitimate.

**Task 3**

Create a function `check_access` that will take two `boolean` arguments `is_admin` and `is_loggedin` to check if Alex is an administrator or if the breach happened while he was logged in.

- Your result should look like this:

```python

check_access(True, False)
check_access(False, False)


Alex's access is legitimate.

Alex's access is suspicious.
```

*Analyzing the Breach*

Pytech's data analysts gathered a massive dataset to reconstruct the breach. They needed to determine if the breach originated from a specific IP address.

**Task 4**

Create a function `check_ip` that will take a list argument `ip_list` and string argument `ip` and check if the breach IP matches a known malicious IP address.

- Your result should look like this:

```python

known_malicious_ips = ["192.168.1.100", "10.0.0.3", "172.16.0.5"]
breach_ip_1 = "10.0.0.3" 
breach_ip_2 = "192.23.0.4" 

check_ip(known_malicious_ips, breach_ip_1)
check_ip(known_malicious_ips, breach_ip_2)


The breach IP matches a known malicious IP.

The breach IP is not a known malicious IP.
```

*A Code Breakthrough*

Emily, the chief data scientist, made a breakthrough. She analyzed the breach logs and realized that a specific keyword was used to gain unauthorized access.

**Task 5**

Create a function `check_key` that will take an argument `pswd` as string and check if the keyword "p@ssw0rd" was used in the breach.

- Your result should look like this:

```python

breach_keyword_1 = "p@ssw0rd"
breach_keyword_2 = "alex1234"

check_key(breach_keyword_1)
check_key(breach_keyword_2)


The keyword 'p@ssw0rd' was used in the breach.

The keyword 'alex1234' was not used in the breach.
```

*Resolution and Redemption*

Pytech's diligent efforts paid off. They identified the security breach's origin, addressed vulnerabilities, and protected their clients' data. Pytech's commitment to logical thinking, diligent analysis, and precise code saved the day, reinforcing their reputation as a data-driven industry leader.

In the end, Pytech emerged stronger than ever, having turned a potential crisis into an opportunity for growth and innovation.
# Continuous stress-dynamics certificate across covariance durations

OU parameters use consecutive within-day observations. Acceptance requires a strictly positive bootstrap interval for theta, lower out-of-sample loss than the random-walk benchmark in both expanding splits, and agreement between OU and transfer-operator relaxation times within the predeclared tolerance.

| Duration (s) | OU theta [95% interval] | OU half-life (windows / min) | mu | sigma | Transfer time (windows / min) | Transfer lambda_1 | Acceptance (theta>0 / OU>RW / convergence) |
|---:|---|---|---:|---:|---|---:|---|
| 30 | 0.0639 [0.0586, 0.0723] | 10.84 / 5.42 | -0.0697 | 2.0322 | 8.60 / 4.30 | 1.0000 | Yes / Yes / Yes |
| 45 | 0.0512 [0.0472, 0.0576] | 13.55 / 10.16 | -0.1366 | 1.8449 | 10.50 / 7.87 | 1.0000 | Yes / Yes / Yes |
| 60 | 0.0456 [0.0421, 0.0510] | 15.19 / 15.19 | -0.2060 | 1.7532 | 11.72 / 11.72 | 1.0000 | Yes / Yes / Yes |
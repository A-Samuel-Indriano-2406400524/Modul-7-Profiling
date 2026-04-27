## JMeter Results
### `/all-student-name`
![JMeter GUI Summary - all-student-name (Before)](images/jmeter-gui-summary-all-student-name-before.png)
![JMeter CLI - all-student-name (Before)](images/jmeter-cli-all-student-name-before.png)
![JMeter GUI Summary - all-student-name (After)](images/jmeter-gui-summary-all-student-name-after.png)
![JMeter CLI - all-student-name (After)](images/jmeter-cli-all-student-name-after.png)

### `/highest-gpa`
![JMeter GUI Summary - highest-gpa (Before)](images/jmeter-gui-summary-highest-gpa-before.png)
![JMeter CLI - highest-gpa (Before)](images/jmeter-cli-highest-gpa-before.png)
![JMeter GUI Summary - highest-gpa (After)](images/jmeter-gui-summary-highest-gpa-after.png)
![JMeter CLI - highest-gpa (After)](images/jmeter-cli-highest-gpa-after.png)

### Conclusion from JMeter after optimizing
Setelah melakukan profiling dan optimasi, saya melakukan performance test ulang dengan Jmeter untuk endpoint /all-student-name dan /highest-gpa, yang kemudian saya bandingkan lagi dengan hasil test Jmeter di awal sebelum optimasi.

Untuk endpoint /all-student-name, rata-rata response time sebelum optimasi adalah 1817 ms. Setelah dioptimasi, rata-rata response time turun menjadi 352 ms. Selain itu, throughput meningkat dari 4.0/sec menjadi 11.0/sec. Dari hasil ini, endpoint /all-student-name mengalami peningkatan performa yang jelas setelah optimasi.

Untuk endpoint /highest-gpa, rata-rata response time sebelum optimasi adalah 168 ms. Setelah optimasi, rata-rata response time turun menjadi 14 ms. Throughput juga meningkat dari 9.4/sec menjadi 10.9/sec. Dari hasil ini, endpoint /highest-gpa juga mengalami peningkatan performa yang jelas setelah optimasi.

Dari hasil tersebut, dapat disimpulkan bahwa optimasi yang dilakukan sangat meningkatkan performa dari kedua endpoint tersebut. Response time jadi jauh lebih rendah dan throughput meningkat.

## Reflection
1. 
2. 
3. 
4. 
5. 
6. 
7. 
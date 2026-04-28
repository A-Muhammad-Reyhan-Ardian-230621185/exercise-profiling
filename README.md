## **Tutorial 7 Reflection**

### JMeter GUI

1. all-student

![all-student](images/img_1.png)

2. highest-gpa

![highest-gpa](images/img_2.png)

3. all-student-name

![all-student-name](images/img_3.png)

### JMeter Script

1. all-student

![all-student](images/img_4.png)

2. highest-gpa

![highest-gpa](images/img_5.png)

3. all-student-name

![all-student-name](images/img_6.png)

### Reflection

**1. What is the difference between the approach of performance testing with JMeter and
profiling with IntelliJ Profiler in the context of optimizing application performance?**

JMeter melakukan performance testing dengan mensimulasikan user request, terutama jika ada banyak user, dan memberikan data seperti latency, error, dsb. IntelliJ Profiler melakukan performance testing dengan memonitor bagaimana aplikasi bekerja didalam sistem, dan mengukur berrbagai process seperti method call, memory allocation, threads, CPU cycle, dsb

**2. How does the profiling process help you in identifying and understanding the weak points
in your application?**

Profiling mampu membantu melihat apa penyebab dari lambatnya suatu proses, misalnya bagimana aplikasi menggunakan CPU, pembuatan objek di memori serta garbage collection, atau apakah ada proses kecil yang berjalan sangat lama, seperti mengaksess database atau memanggil API

**3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify
bottlenecks in your application code?**

Saya bilang lumayan efektif, karena sudah didalam IDE. Tidak seperti third party profiler, saya bisa mengakses source code dari proses yang menyebabkan suatu isu atau kelambatan

**4. What are the main challenges you face when conducting performance testing and
profiling, and how do you overcome these challenges?**

Kesulitan yang saya temukan yaitu masih banyak proses dan informasi yang tidak saya mengerti

**5. What are the main benefits you gain from using IntelliJ Profiler for profiling your
application code?**

Dari yang saya temukan, yaitu real-time analysis, mampu melihat langsung source code dari suatu isu, ease of usage, karena sudah terdapat di IDE dan tidak perlu setup tambahan, dan terdapat berbagai macam fitur terutama flame graph

**6. How do you handle situations where the results from profiling with IntelliJ Profiler are not
entirely consistent with findings from performance testing using JMeter?**

**7. What strategies do you implement in optimizing application code after analyzing results
from performance testing and profiling? How do you ensure the changes you make do
not affect the application's functionality?**

Optimisasi yang saya terapkan yaitu, saya mengganti perolehan data dari service menjadi SQL query yang diletakkan pada bagian repostiory



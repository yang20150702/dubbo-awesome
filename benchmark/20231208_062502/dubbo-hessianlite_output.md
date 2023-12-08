# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.134 ops/ms
Iteration   1: 5.874 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.874 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.688 ops/ms
Iteration   1: 13.340 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.340 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ops/ms
Iteration   1: 8.846 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.846 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.136 ops/ms
Iteration   1: 3.644 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.644 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.604 ±(99.9%) 0.108 ms/op
Iteration   1: 3.175 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.175 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.130 ±(99.9%) 0.035 ms/op
Iteration   1: 2.040 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.040 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.338 ±(99.9%) 0.050 ms/op
Iteration   1: 2.923 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.923 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.834 ±(99.9%) 0.435 ms/op
Iteration   1: 8.224 ±(99.9%) 0.077 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.224 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.820 ±(99.9%) 0.100 ms/op
Iteration   1: 2.903 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   2.732 ms/op
                 createUser·p0.90:   3.240 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  25.265 ms/op
                 createUser·p0.9999: 25.972 ms/op
                 createUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10980
  mean =      2.903 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2876 
    [ 2.500,  5.000) = 7930 
    [ 5.000,  7.500) = 68 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      2.732 ms/op
     p(90.0000) =      3.240 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     25.265 ms/op
     p(99.9900) =     25.972 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.218 ±(99.9%) 0.076 ms/op
Iteration   1: 1.987 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   1.884 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.834 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.209 ms/op
                 existUser·p0.9999: 11.047 ms/op
                 existUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16063
  mean =      1.987 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 14294 
    [ 2.500,  3.750) = 1339 
    [ 3.750,  5.000) = 155 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.209 ms/op
     p(99.9900) =     11.047 ms/op
     p(99.9990) =     11.583 ms/op
     p(99.9999) =     11.583 ms/op
    p(100.0000) =     11.583 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.411 ±(99.9%) 0.094 ms/op
Iteration   1: 3.380 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.202 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.163 ms/op
                 getUser·p0.999:  16.548 ms/op
                 getUser·p0.9999: 18.022 ms/op
                 getUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9464
  mean =      3.380 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1308 
    [ 2.500,  3.750) = 5729 
    [ 3.750,  5.000) = 2166 
    [ 5.000,  6.250) = 174 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.163 ms/op
     p(99.9000) =     16.548 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.238 ±(99.9%) 0.394 ms/op
Iteration   1: 8.531 ±(99.9%) 0.148 ms/op
                 listUser·p0.00:   3.518 ms/op
                 listUser·p0.50:   7.963 ms/op
                 listUser·p0.90:   11.764 ms/op
                 listUser·p0.95:   13.025 ms/op
                 listUser·p0.99:   21.889 ms/op
                 listUser·p0.999:  27.359 ms/op
                 listUser·p0.9999: 27.984 ms/op
                 listUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3767
  mean =      8.531 ±(99.9%) 0.148 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 66 
    [ 5.000,  7.500) = 1388 
    [ 7.500, 10.000) = 1642 
    [10.000, 12.500) = 383 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      3.518 ms/op
     p(50.0000) =      7.963 ms/op
     p(90.0000) =     11.764 ms/op
     p(95.0000) =     13.025 ms/op
     p(99.0000) =     21.889 ms/op
     p(99.9000) =     27.359 ms/op
     p(99.9900) =     27.984 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.874          ops/ms
Client.existUser                       thrpt         13.340          ops/ms
Client.getUser                         thrpt          8.846          ops/ms
Client.listUser                        thrpt          3.644          ops/ms
Client.createUser                       avgt          3.175           ms/op
Client.existUser                        avgt          2.040           ms/op
Client.getUser                          avgt          2.923           ms/op
Client.listUser                         avgt          8.224           ms/op
Client.createUser                     sample  10980   2.903 ± 0.050   ms/op
Client.createUser:createUser·p0.00    sample          0.937           ms/op
Client.createUser:createUser·p0.50    sample          2.732           ms/op
Client.createUser:createUser·p0.90    sample          3.240           ms/op
Client.createUser:createUser·p0.95    sample          3.920           ms/op
Client.createUser:createUser·p0.99    sample          6.922           ms/op
Client.createUser:createUser·p0.999   sample         25.265           ms/op
Client.createUser:createUser·p0.9999  sample         25.972           ms/op
Client.createUser:createUser·p1.00    sample         25.985           ms/op
Client.existUser                      sample  16063   1.987 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.656           ms/op
Client.existUser:existUser·p0.50      sample          1.884           ms/op
Client.existUser:existUser·p0.90      sample          2.494           ms/op
Client.existUser:existUser·p0.95      sample          2.834           ms/op
Client.existUser:existUser·p0.99      sample          4.301           ms/op
Client.existUser:existUser·p0.999     sample          7.209           ms/op
Client.existUser:existUser·p0.9999    sample         11.047           ms/op
Client.existUser:existUser·p1.00      sample         11.583           ms/op
Client.getUser                        sample   9464   3.380 ± 0.038   ms/op
Client.getUser:getUser·p0.00          sample          0.646           ms/op
Client.getUser:getUser·p0.50          sample          3.346           ms/op
Client.getUser:getUser·p0.90          sample          4.202           ms/op
Client.getUser:getUser·p0.95          sample          4.481           ms/op
Client.getUser:getUser·p0.99          sample          6.163           ms/op
Client.getUser:getUser·p0.999         sample         16.548           ms/op
Client.getUser:getUser·p0.9999        sample         18.022           ms/op
Client.getUser:getUser·p1.00          sample         18.022           ms/op
Client.listUser                       sample   3767   8.531 ± 0.148   ms/op
Client.listUser:listUser·p0.00        sample          3.518           ms/op
Client.listUser:listUser·p0.50        sample          7.963           ms/op
Client.listUser:listUser·p0.90        sample         11.764           ms/op
Client.listUser:listUser·p0.95        sample         13.025           ms/op
Client.listUser:listUser·p0.99        sample         21.889           ms/op
Client.listUser:listUser·p0.999       sample         27.359           ms/op
Client.listUser:listUser·p0.9999      sample         27.984           ms/op
Client.listUser:listUser·p1.00        sample         27.984           ms/op

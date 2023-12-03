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
# Warmup Iteration   1: 2.225 ops/ms
Iteration   1: 5.685 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.685 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.285 ops/ms
Iteration   1: 11.730 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.730 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.265 ops/ms
Iteration   1: 8.740 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.740 ops/ms


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
# Warmup Iteration   1: 1.980 ops/ms
Iteration   1: 3.643 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.643 ops/ms


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
# Warmup Iteration   1: 5.119 ±(99.9%) 0.065 ms/op
Iteration   1: 3.008 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.008 ms/op


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
# Warmup Iteration   1: 3.476 ±(99.9%) 0.039 ms/op
Iteration   1: 1.818 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.818 ms/op


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
# Warmup Iteration   1: 4.728 ±(99.9%) 0.065 ms/op
Iteration   1: 2.815 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.815 ms/op


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
# Warmup Iteration   1: 11.571 ±(99.9%) 0.217 ms/op
Iteration   1: 8.553 ±(99.9%) 0.100 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.553 ms/op


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
# Warmup Iteration   1: 5.311 ±(99.9%) 0.130 ms/op
Iteration   1: 3.018 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.298 ms/op
                 createUser·p0.50:   2.777 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   8.520 ms/op
                 createUser·p0.999:  13.294 ms/op
                 createUser·p0.9999: 24.231 ms/op
                 createUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10799
  mean =      3.018 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2370 
    [ 2.500,  5.000) = 8095 
    [ 5.000,  7.500) = 217 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      2.777 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     13.294 ms/op
     p(99.9900) =     24.231 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 3.282 ±(99.9%) 0.068 ms/op
Iteration   1: 1.916 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   3.367 ms/op
                 existUser·p0.999:  17.498 ms/op
                 existUser·p0.9999: 18.055 ms/op
                 existUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16679
  mean =      1.916 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 823 
    [ 1.250,  2.500) = 14549 
    [ 2.500,  3.750) = 1204 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.367 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.096 ms/op
Iteration   1: 2.764 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   2.679 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.697 ms/op
                 getUser·p0.999:  5.729 ms/op
                 getUser·p0.9999: 9.956 ms/op
                 getUser·p1.00:   10.502 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11567
  mean =      2.764 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 815 
    [ 2.000,  3.000) = 6904 
    [ 3.000,  4.000) = 3410 
    [ 4.000,  5.000) = 379 
    [ 5.000,  6.000) = 53 
    [ 6.000,  7.000) = 4 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      2.679 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.697 ms/op
     p(99.9000) =      5.729 ms/op
     p(99.9900) =      9.956 ms/op
     p(99.9990) =     10.502 ms/op
     p(99.9999) =     10.502 ms/op
    p(100.0000) =     10.502 ms/op


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
# Warmup Iteration   1: 12.139 ±(99.9%) 0.413 ms/op
Iteration   1: 7.376 ±(99.9%) 0.092 ms/op
                 listUser·p0.00:   2.978 ms/op
                 listUser·p0.50:   7.201 ms/op
                 listUser·p0.90:   9.388 ms/op
                 listUser·p0.95:   10.240 ms/op
                 listUser·p0.99:   13.477 ms/op
                 listUser·p0.999:  21.102 ms/op
                 listUser·p0.9999: 22.249 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4334
  mean =      7.376 ±(99.9%) 0.092 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 228 
    [ 5.000,  7.500) = 2270 
    [ 7.500, 10.000) = 1573 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.978 ms/op
     p(50.0000) =      7.201 ms/op
     p(90.0000) =      9.388 ms/op
     p(95.0000) =     10.240 ms/op
     p(99.0000) =     13.477 ms/op
     p(99.9000) =     21.102 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.685          ops/ms
Client.existUser                       thrpt         11.730          ops/ms
Client.getUser                         thrpt          8.740          ops/ms
Client.listUser                        thrpt          3.643          ops/ms
Client.createUser                       avgt          3.008           ms/op
Client.existUser                        avgt          1.818           ms/op
Client.getUser                          avgt          2.815           ms/op
Client.listUser                         avgt          8.553           ms/op
Client.createUser                     sample  10799   3.018 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.298           ms/op
Client.createUser:createUser·p0.50    sample          2.777           ms/op
Client.createUser:createUser·p0.90    sample          3.690           ms/op
Client.createUser:createUser·p0.95    sample          4.350           ms/op
Client.createUser:createUser·p0.99    sample          8.520           ms/op
Client.createUser:createUser·p0.999   sample         13.294           ms/op
Client.createUser:createUser·p0.9999  sample         24.231           ms/op
Client.createUser:createUser·p1.00    sample         25.035           ms/op
Client.existUser                      sample  16679   1.916 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.727           ms/op
Client.existUser:existUser·p0.50      sample          1.821           ms/op
Client.existUser:existUser·p0.90      sample          2.425           ms/op
Client.existUser:existUser·p0.95      sample          2.609           ms/op
Client.existUser:existUser·p0.99      sample          3.367           ms/op
Client.existUser:existUser·p0.999     sample         17.498           ms/op
Client.existUser:existUser·p0.9999    sample         18.055           ms/op
Client.existUser:existUser·p1.00      sample         18.055           ms/op
Client.getUser                        sample  11567   2.764 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          1.061           ms/op
Client.getUser:getUser·p0.50          sample          2.679           ms/op
Client.getUser:getUser·p0.90          sample          3.527           ms/op
Client.getUser:getUser·p0.95          sample          3.813           ms/op
Client.getUser:getUser·p0.99          sample          4.697           ms/op
Client.getUser:getUser·p0.999         sample          5.729           ms/op
Client.getUser:getUser·p0.9999        sample          9.956           ms/op
Client.getUser:getUser·p1.00          sample         10.502           ms/op
Client.listUser                       sample   4334   7.376 ± 0.092   ms/op
Client.listUser:listUser·p0.00        sample          2.978           ms/op
Client.listUser:listUser·p0.50        sample          7.201           ms/op
Client.listUser:listUser·p0.90        sample          9.388           ms/op
Client.listUser:listUser·p0.95        sample         10.240           ms/op
Client.listUser:listUser·p0.99        sample         13.477           ms/op
Client.listUser:listUser·p0.999       sample         21.102           ms/op
Client.listUser:listUser·p0.9999      sample         22.249           ms/op
Client.listUser:listUser·p1.00        sample         22.249           ms/op
